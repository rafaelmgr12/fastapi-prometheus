# FastAPI with Prometheus Monitoring
This repository contains a FastAPI application that is set up with Prometheus for monitoring. The application, Prometheus, and Grafana are all containerized using Docker.

## Features
* FastAPI application with a simple "Hello World" endpoint.
* Prometheus for monitoring with a job set up to scrape metrics from the FastAPI application.
* Grafana for data visualization.
* Dockerized setup with a Dockerfile for the application and a docker-compose file to run the application, Prometheus, and Grafana in separate containers.

  ## Getting Started
  ### Prerequisites
  * Docker
  * Docker Compose
  * Python 3.6+
 
### Running the application
1. Clone the repository:
  ```bash
  git clone https://github.com/rafaelmgr12/fastapi-prometheus.git

  ```
2. Navigate into the cloned repository:
  ```bash
  cd fastapi-prometheus
  ```
3. Build and start the Docker containers
```bash
  docker-compose up --build
```
The FastAPI application will be running at **http://localhost:8000**, Prometheus at **http://localhost:9090**, and Grafana at **http://localhost:3000**``.

## Application Structure
* `Dockerfile`: Defines the Docker image for the FastAPI application.
* `docker-compose.yml`: Defines the services for the FastAPI application, Prometheus, and Grafana.
* `main.py` The main FastAPI application file.
* `prometheus_data/prometheus.yml`: The configuration file for Prometheus.
* `requirements.txt`: The Python dependencies for the FastAPI application.
## Contributing
Contributions are welcome! Please feel free to submit a Pull Request.

---
## Author

Made with ♥ by Rafael 👋🏻


[![Linkedin Badge](https://img.shields.io/badge/-Rafael-blue?style=flat-square&logo=Linkedin&logoColor=white&link=https://www.linkedin.com/in/tgmarinho/)](https://www.linkedin.com/in/rafael-mgr/)
[![Gmail Badge](https://img.shields.io/badge/-Gmail-red?style=flat-square&link=mailto:nelsonsantosaraujo@hotmail.com)](mailto:ribeirorafaelmatehus@gmail.com)
