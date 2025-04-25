# Use a Maven image with JDK 21
FROM maven:3.9.8-eclipse-temurin-21

LABEL maintainer="taqniat.ae"
WORKDIR /workspace

# Optional: Install extra tools (like git, curl, zip)
RUN apt update && apt install -y git curl zip unzip nano

# Set a default command (interactive shell)
CMD ["/bin/bash"]
