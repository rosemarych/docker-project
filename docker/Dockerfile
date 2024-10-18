FROM ubuntu:20.04
RUN apt update
EXPOSE 80
WORKDIR /s9rosemary
VOLUME /rosemary/VOLUME
ENV session=s9
COPY . .
RUN useradd rose
USER 1010
