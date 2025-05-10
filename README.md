# My Simple Web App

This is a basic web application created for demonstration purposes.  It includes a simple HTML page, CSS styling, and JavaScript interactivity.  This application has been containerized using both Docker and Podman.

## Files

* `public/index.html`: The main HTML file.
* `public/styles.css`: The stylesheet for the web page.
* `public/script.js`: The JavaScript file for interactivity.
* `Dockerfile`: The Dockerfile for containerizing the application with Docker.
* `podmanfile`: The Podmanfile for containerizing the application with Podman.
* `README.md`: This file.

## Instructions

To run this application, you can use a web server or containerize it using Docker or Podman.

### Running with Docker

1.  **Install Docker:**

2.  **Build the Docker image:**
    ```
    docker build -t myapp .
    ```
   
3.  **Run the Docker container:**
    ```
    docker run -d -p 8080:80 myapp
    ```

4.  **Access the application:**
    * Open your web browser and go to `http://localhost:8080`.


### Running with Podman

1.  **Install Podman:**

2.  **Build the Podman image:**
    ```
    podman build -t myapp
    ```

3.  **Run the Podman container:**
    ```
    podman run -d -p 8080:80 myapp
    ```

4.  **Access the application:**
    * Open your web browser and go to `http://localhost:8080`.

**Note:** The application should look the same when accessed via Docker or Podman.

## Directory Structure
