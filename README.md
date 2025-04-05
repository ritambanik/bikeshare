# bikeshare

# Build the docker image for the bike_share_api

``docker build -t bikespare_api:0.0.1 .``

# Tag an image to include dockerhub user name
``docker tag bikespare_api:0.0.1 ritambanik/bikespare_api:0.0.1``

# Run the docker container locally

``docker run -p 8000:8000 --rm --name bike_share_api -d bikespare_api:0.0.1``

# Pushing an image into dockerhub

``docker push ritambanik/bikespare_api:0.0.1``

# Test


# Updated the workflow