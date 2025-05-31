FROM us-central1-docker.pkg.dev/cloud-workstations-images/predefined/base:latest
SHELL ["/bin/bash", "-l", "-c"]

RUN sudo apt update && \
    sudo apt install python3-full -y
RUN python -m venv .venv
RUN source .venv/bin/activate && pip install google-adk jsonschema
