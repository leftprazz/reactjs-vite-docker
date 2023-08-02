# ReactJS Vite Dockerized

This repository contains a ReactJS project using Vite that has been dockerized for easy deployment and distribution.

## Clone the Repository

To get started, clone this repository to your local machine using the following command:

```
git clone https://github.com/leftprazz/reactjs-vite-docker.git
```

## Build the Docker Image

Once you have cloned the repository, navigate to the project directory and build the Docker image using the following command:

```
docker build -t reactjs/convert-suhu:1.0.0 .
```

## Run the Docker Container

After successfully building the Docker image, you can run the container with the following command:

```
docker run -d -p 5000:5000 reactjs/convert-suhu:1.0.0
```

The application will now be running in a Docker container and accessible at `http://localhost:5000`.

## Additional Notes

- If you encounter any issues or have questions about the project, please feel free to open an issue on this repository.

- Happy coding! 😄