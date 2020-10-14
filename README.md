# minimal-flask-docker

docker build -t minimal_flask_docker_img .

docker run -it --name minimal_flask_docker_cont --rm -p 5000:80 minimal_flask_docker_img

then run
`python post.py`