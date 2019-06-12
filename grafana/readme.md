docker run -d -p 3000:3000 --name grafana grafana/grafana:5.1.0

docker inspect -f '{{range .NetworkSettings.Networks}}{{.IPAddress}}{{end}}'  161ddc6c6478