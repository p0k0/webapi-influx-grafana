docker build . --no-cache
docker run -d -p 8086:8086 -p 8083:8083 -e INFLUXDB_ADMIN_ENABLED=true influxdb:1.1

docker exec -it <id> bash

RUN ["apt-get", "install", "-y", "vim"]