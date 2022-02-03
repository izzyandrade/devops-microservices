[![CircleCI](https://circleci.com/gh/izzyandrade/devops-microservices/tree/main.svg?style=svg)](https://circleci.com/gh/izzyandrade/devops-microservices/tree/main)

## Project Overview

In this project, you I have applied the skills I have acquired in this course to operationalize a Machine Learning Microservice API.

### Project Tasks

- Test the project code using linting
- Complete a Dockerfile to containerize this application
- Deploy the containerized application using Docker and make a prediction
- Improve the log statements in the source code for this application
- Configure Kubernetes and create a Kubernetes cluster
- Deploy a container using Kubernetes and make a prediction
- Upload a complete Github repo with CircleCI to indicate that the code has been tested

---

## Setup the Environment

- Create a virtualenv with Python 3.7 and activate it. Refer to this link for help on specifying the Python version in the virtualenv.

```bash
python3 -m pip install --user virtualenv
# You should have Python 3.7 available in your host.
# Check the Python path using `which python3`
# Use a command similar to this one:
python3 -m virtualenv --python=<path-to-Python3.7> .devops
source .devops/bin/activate
```

- Run `make install` to install the necessary dependencies

### Running `app.py`

1. Standalone: `python app.py`
2. Run in Docker: `./run_docker.sh`
3. Run in Kubernetes: `./run_kubernetes.sh`
4. Upload docker: `./upload_docker.sh`
5. You can also make a test prediction (once the project is running) in another terminal window with `./make_prediction.sh`
