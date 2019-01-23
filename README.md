## Building Custom image for Python-Flask Application

Goal: The purpose of this image is to Create Flask Application

### Steps to building your own image

Be in the directory pyton-flask-sample-app
- `cd pyton-flask-sample-app`
- `docker build -t ravi2krishna/flask-app .`
- `docker run -p 8000:5000 -d <user-name>/<image-name>`
- `docker run -p 8000:5000 -d ravi2krishna/flask-app`

### Saving the image to docker hub
- `Register for an account on hub.docker.com`
- `In server machine`
- `# docker login`
- `# docker images`      
- `# docker push docker-user_id/image-name`
- `# docker push ravi2krishna/flask-app`

        
        
        

        
