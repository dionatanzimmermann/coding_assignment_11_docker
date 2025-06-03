# Cloning the GitHUB repository
git clone https://github.com/dionatanzimmermann/coding_assignment_11_docker.git

# Building the docker container image
docker build -t zimmermann_dionatan_coding_assignment11 .

# Running the container on port 7775, in dev environment
docker run -p 7775:3000 --name zimmermann_dionatan_coding_assignment11 zimmermann_dionatan_coding_assignment11
