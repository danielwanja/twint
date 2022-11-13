FROM mcr.microsoft.com/devcontainers/python:3.10-bullseye

WORKDIR /workspaces/twint
ADD ../requirements.txt .

RUN  pip3 install . -r requirements.txt --user

# CMD /bin/bash
