FROM mcr.microsoft.com/devcontainers/python:3.12-bookworm
RUN apt update -y
RUN apt install tmux -y

USER vscode
RUN pip install --user poetry
ENV PATH="${PATH}:/home/vscode/.local/bin"

CMD ["tail", "-f", "/dev/null"]