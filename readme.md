# Commands
## Build the Image
### command line
- docker build -t fireship/demoapp:1.0 .
### Run the Container
This maps the local port 5000 to the docker port 8080. You should be able to view the app on your local system at https://localhost:5000. You can choose any port you want.

### command line
- docker run -p 5000:8080 <image-id>