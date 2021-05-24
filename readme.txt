Step 1 -- This will build the file with name Dockerfile
docker build -t myimage:2.0 .
Here myimage2.0 is name

Step 2 -- Check docker images
docker images

Step 3 -- Run Current image got from step 2 in detached mode so that we can use terminal for other command 
docker run -d myimage:2.0

Step 4 -- Check if image is running
docker ps

Step 5 -- Execute the RUNNING specified conatiner in interactive mode found from step 4
docker exec -it 48f53202bd86 ./bin/bash
 
Step 6 -- Check if file present
do a ls