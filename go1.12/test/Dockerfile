FROM golang:1.12

LABEL name="Golang Pipeline"
LABEL maintainer="Shoukoo"
LABEL version="0.2.0"
LABEL repository="https://github.com/shoukoo/golang-pipeline"

LABEL com.github.actions.name="Golang Pipeline"
LABEL com.github.actions.description="Run Golang commands"
LABEL com.github.actions.icon="box"
LABEL com.github.actions.color="blue"

COPY entrypoint.sh /entrypoint.sh
COPY gp-setup.sh /gp-setup.sh

ENTRYPOINT ["/entrypoint.sh"]
