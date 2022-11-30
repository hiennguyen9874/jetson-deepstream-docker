# Jetson deepstreeam opencv

[hub.docker.com/repository/docker/hiennguyen9874/jetson-deepstream](https://hub.docker.com/repository/docker/hiennguyen9874/jetson-deepstream)

## deepstream-l4t:6.0.1-iot

- Build: `docker build -t hiennguyen9874/jetson-deepstream:deepstream-6.0.1-iot-opencv --build-arg BASE_CONTAINER=nvcr.io/nvidia/deepstream-l4t:6.0.1-iot -f Dockerfile.deepstream-6.0.1 .`

- Push: `docker push hiennguyen9874/jetson-deepstream:deepstream-6.0.1-iot-opencv`

## deepstream-l4t:6.0.1-samples

- Build: `docker build -t hiennguyen9874/jetson-deepstream:deepstream-6.0.1-samples-opencv --build-arg BASE_CONTAINER=nvcr.io/nvidia/deepstream-l4t:6.0.1-samples -f Dockerfile.deepstream-6.0.1 .`

- Push: `docker push hiennguyen9874/jetson-deepstream:deepstream-6.0.1-samples-opencv`

## deepstream-l4t:6.1.1-iot

- Build: `docker build -t hiennguyen9874/jetson-deepstream:deepstream-6.1.1-iot-opencv --build-arg BASE_CONTAINER=nvcr.io/nvidia/deepstream-l4t:6.1.1-iot -f Dockerfile.deepstream-6.1.1 .`

- Push: `docker push hiennguyen9874/jetson-deepstream:deepstream-6.1.1-iot-opencv`

## deepstream-l4t:6.1.1-samples

- Build: `docker build -t hiennguyen9874/jetson-deepstream:deepstream-6.1.1-samples-opencv --build-arg BASE_CONTAINER=nvcr.io/nvidia/deepstream-l4t:6.1.1-samples -f Dockerfile.deepstream-6.1.1 .`

- Push: `docker push hiennguyen9874/jetson-deepstream:deepstream-6.1.1-samples-opencv`
