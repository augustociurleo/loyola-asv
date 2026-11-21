Instalacion
git clone https://https://github.com/robotica-asv/loyola-asv.git
cd loyola-asv/docker

docker compose build
docker compose up -d


docker exec -it asv-dev bash

source /opt/ros/jazzy/setup.bash
ros2 --version
