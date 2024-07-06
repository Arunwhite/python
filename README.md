# python

Build the Docker image: Open a terminal and navigate to the directory containing app.py and the Dockerfile. Run the following command to build the Docker image:

docker build -t python-hello-app .

Run the Docker container: Run the following command to start a container from the image you just built:

docker run -itd -p 5000:5000 -v /data/python:/app --name python python

