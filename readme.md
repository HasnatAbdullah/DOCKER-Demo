# Commands
## Build the Image
### command line
- docker build -t hasnat1abdullah/demoapp:1.0 .
### Run the Container
This maps the local port 5000 to the docker port 8080. You should be able to view the app on your local system at https://localhost:5000. You can choose any port you want.
### Command to see the image-id
- docker images
### command line to run a new container of image-id
- docker run -p 5000:8080 image-id