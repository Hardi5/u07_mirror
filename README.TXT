Access Prometheus:
http://172.232.148.114:9091/

Access Grafana:
http://172.232.148.114:3001

Prometheus Metrics:
http://172.232.148.114:6612/metrics

Integrtated Docker Registry and Backend docker reg:
http://172.232.148.114:5000/

frontend:
http://172.232.148.114:8080
Images are pushed to: http://172.232.148.114:8080/repository/registry

Integration between backend and frontend, eg: 
docker push 172.232.148.114:5000/registry:v3
docker pull 172.232.148.114:5000/registry:v3

Github Mirroring upon branch updates:
https://github.com/Hardi5/u07_mirror
