# hello-world-flask-application
Simple Flask application

# Docker Hub link
[https://hub.docker.com/r/jmmfcoutinho/hello-world-flask-application](https://hub.docker.com/r/jmmfcoutinho/hello-world-flask-application)

# Instructions (local deployment):
1. Clone repo:

`$ git clone https://github.com/jmmfcoutinho/hello-world-flask-application.git`
2. Go to repo root folder.
3. Run the image:

`$ docker run -p 127.0.0.1:3000:3000 jmmfcoutinho/hello-world-flask-application`
4. Open browser and check if app is working:

Link: [http://localhost:3000/](http://localhost:3000/)

A message saying `{"message":"Hello world"}` should appear if everything was done correctly.

# Clould deployed app:

This app is deployed on [fly.io](fly.io). It can be accessed using the following link:

Link: [https://hello-world-flask-application.fly.dev/](https://hello-world-flask-application.fly.dev/)
