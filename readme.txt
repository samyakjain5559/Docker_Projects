Step 1 -- This will build the file with name Dockerfile
docker build .

Step 2 -- Check docker images
docker images

Step 3 -- Run Current image got from step 2
docker run cfe57e1c332e

Step 4 -- Run the Docker image
docker run 3cb475728ba6

Step 5 -- Check if image is running
docker ps

Step 6 -- Execute the RUNNING specified image in interactive mode
docker exec -it 48f53202bd86 ./bin/bash
 
Step7 -- Check if file present
do a ls