epotek/meteor-docker Docker Image
===

Forked from zoder/meteor-docker 

Docker image to run Meteor apps.

# Build instructions
```bash
cd image
docker buildx build --platform=linux/amd64 -t epotek/meteor-docker .
docker login
docker push epotek/meteor-docker
```
