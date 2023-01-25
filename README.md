# Python Dockerized Development Environment Template

Use this repo as a template for python development. Add the project python code to the source directory and adjust dockerfile based on python impage required.

## Setup

1. Upload code to `src` directory
2. Modify `Dockerfile` to have correct image
3. Ensure requirements.txt is in the root of the `src` directory
4. From the root of this project run `docker-compose up` to build and run the image
5. From a new terminal, enter into the container using `docker exec -it <container-id> //bin/bash`

