# BEMO


## Docker Images

We have looked at images before, but in this section we'll dive deeper into what Docker images are and build our own image! Lastly, we'll also use that image to run our application locally and finally deploy on AWS to share it with our friends! Excited? Great! Let's get started.

Docker images are the basis of containers. In the previous example, we pulled the Busybox image from the registry and asked the Docker client to run a container based on that image. To see the list of images that are available locally, use the docker images command.

`docker images`

Let's create an webapp image with the followig `Make` commands:


1. To reset Docker images:

   ```
   make clean
   ```

1. Build the image, type:

   ```
   make build
   ```

1. Run the container, type:

   ```
   make run
   ```

4. To stop the docker container, type:

   ```
   make stop
   ```

1. View the application in a browser at `XX.XXX.XXX.XXX:PORT`

where `XX.XXX.XXX.XXX` is the IP we used in the login step above and `PORT` is the port number provided in the `.env` file earlier.


## License

This sample code is licensed under the [MIT License](https://opensource.org/licenses/MIT).

## Open Source @ IBM

Find more open source projects on the [IBM Github Page](http://ibm.github.io/)
