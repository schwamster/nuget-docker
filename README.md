# nuget-docker
nuget for linux in a docker image

This image is used to use nuget in a docker image. I use it to push nuget packages to nuget.org.

Example:

docker run --rm -v ${pwd}/package:/data/package schwamster/nuget-docker push /data/package/*.nupkg <your nuget api key> -Source nuget.org
