# blogDockerWebsiteSample


# Build container
docker build -t iotarchitecture/blogdockerwebsitesample:v0.1 .

# Run container locally
docker run -it -p 80:80 iotarchitecture/blogdockerwebsitesample:v0.1

# Docker Login
docker login

# Push image to Docker Hub
docker push iotarchitecture/blogdockerwebsitesample:v0.1
