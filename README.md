# fastapi_docker_example

docker build --tag fastapi_image .

docker run -d --name fastapicontainer -p 3002:80 fastapi_image
