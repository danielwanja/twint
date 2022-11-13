FROM mcr.microsoft.com/devcontainers/python:3.10-bullseye

WORKDIR /workspaces/twint
COPY . /workspaces/twint
RUN pwd
RUN ls

RUN  pip3 install . -r requirements.txt --user

# CMD /bin/bash
