FROM ros:jazzy

RUN apt update && apt install -y \
    python3-pip \
    python3-colcon-common-extensions \
    git \
    nano \
    vim \
    wget \
    ros-jazzy-turtlesim \
    && rm -rf /var/lib/apt/lists/*

WORKDIR /workspace

CMD ["bash"]
