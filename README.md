# Practice App: Python Flask And Docker

Courtesy & Followed this tutorial: https://www.docker.com/blog/containerized-python-development-part-1/

## Prerequisites

- Install Docker
- Keep the Docker demon running in the background
- Build image:

    ```bash
        $ docker build -t myimage .
    ```

- Run the app

    ```bash
        $ docker run -it -d -p 5005:5005 myimage
    ```

- Test the setup
    ```bash
        $ curl http://0.0.0.0:5005
        Hello World
    ```
