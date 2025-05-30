This setup demonstrates how to create a Docker image for a Python app, installing dependencies from requirements.txt and running a Flask server.
The two images attached depicts when it was first run on the therminal, VScode. Port was then copied to run on the local host-web browser to see the contents of the python-app in a pictorial view.


**Certainly! Here are 5 simple steps to create a Docker image for a Python Flask app:**

Create app.py – Write your Flask application code.

Create requirements.txt – List required Python packages (e.g., flask).

Write a Dockerfile – Use a base Python image, copy app files, install dependencies, and set the run command.

Build the Docker image – Run docker build -t flask-app .

Run the container – Use docker run -p 5000:5000 flask-app to start the app and access it via http://localhost:5000.




Feel free to clone and try your hands on.., remember to amend the docker file before use.
