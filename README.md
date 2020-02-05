# blogDockerWebsiteSample
This repository contains the working sample for my blog article:

Docker – Run Your Applications Everywhere
https://www.iotcloudarchitect.com/2020/02/05/docker-run-your-applications-everywhere/

# Build container
docker build -t iotarchitecture/blogdockerwebsitesample:v0.1 .

# Run container locally
docker run -it -p 80:80 iotarchitecture/blogdockerwebsitesample:v0.1

# Docker Login
docker login

# Push image to Docker Hub
docker push iotarchitecture/blogdockerwebsitesample:v0.1
