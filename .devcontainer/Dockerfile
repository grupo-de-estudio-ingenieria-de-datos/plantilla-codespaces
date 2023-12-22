FROM mcr.microsoft.com/devcontainers/base:ubuntu

ARG USERNAME=vscode

# Everything runs as root during build time, so we want
# to make sure the vscode user can edit these paths too:
RUN chmod 777 -R /home/${USERNAME}/.config
