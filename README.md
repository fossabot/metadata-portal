# Docker Scout demo service
[![FOSSA Status](https://app.fossa.com/api/projects/git%2Bgithub.com%2Falialobidm%2Fmetadata-portal.svg?type=shield)](https://app.fossa.com/projects/git%2Bgithub.com%2Falialobidm%2Fmetadata-portal?ref=badge_shield)


A repository containing an application and Dockerfile to demonstrate the use of Docker Scout to analyze and remediate CVEs in a container image.

Read the [Docker Scout Quickstart](https://docs.docker.com/scout/quickstart) for a full walkthrough. You can build and run the image with the following command:

```shell
docker build -t scout-demo:v1 .
docker run scout-demo:v1
```

The application consists of a basic ExpressJS server and uses an intentionally old version of Express and Alpine base image.
 
 


## License
[![FOSSA Status](https://app.fossa.com/api/projects/git%2Bgithub.com%2Falialobidm%2Fmetadata-portal.svg?type=large)](https://app.fossa.com/projects/git%2Bgithub.com%2Falialobidm%2Fmetadata-portal?ref=badge_large)