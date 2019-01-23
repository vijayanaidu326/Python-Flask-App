## Building Custom image for Python-Flask Application

Goal: The purpose of this image is to Create Flask Application

### Setup Python & pip

Install python & pip
- `sudo yum -y update`
- `sudo yum -y install python-pip`
- `sudo pip install --upgrade pip`      

### Steps to run application

Be in the directory Python-Flask-App
- `cd Python-Flask-App`
- `sudo pip install -r requirements.txt`
- `python app.py`

By default the application runs on port 5000, Browse the application http://loclahost:5000

### Steps to building your own image

Be in the directory pyton-flask-sample-app
- `cd Python-Flask-App`
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

        
        
        

        
