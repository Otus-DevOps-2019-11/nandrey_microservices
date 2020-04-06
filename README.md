# nandrey_microservices
nandrey microservices repository

HW#15

1. Docker installed with docker_machine
2. hello-world container tested
3. bunch of Docker commands run and examined
4. new GCP project created also Google SDK installed
5. new docker image created
6. new image uploaded to Docker hub
7. container from new image started

-===-===-

HW#16

1. Downloaded code for 3 services
2. Configured and started our application as 3 containers in bridge network

-===-===-

HW#17

1. By default docker-compose uses base directory name as project name
    it can be changed with option:
    -p, --project-name NAME
2. tested various docker host network modes
3. containers starter in bridge network mode with aliases
4. containers started in bridge network mode in two networks with aliases
5. containers started with docker-compose with var file

-===-===-

HW#19

1. Docker Gitlab VM in GCP created
2. project in Gitlab created
3. pipeline with environments defined and tested
4. dynamic environment added to a job

-===-===-

HW#20

My repositories https://hub.docker.com/u/anikolav

1. Created Prometheus monitoring microservice
2. Add project microservices monitoring to Prometheus
3. Images are pushed to Docker hub

-===-===-

HW#21

1. Microservices and monitoring microservices are now in different compose files
2. Added monitoring of Docker containers with cAdvisor
3. Added visualisation with Grafana
4. Added alerting and tested alert via Slack channel
5. All Docker images are pushed in DockerHub

-===-===-

HW#23
1. EFK added like sender, aggregator and convertor for log messages
2. Post microservice configured to send logs to fluentd
3. UI microservice configured to send logs to fluentd
4. Zipkin tracer added like log parser

-===-===-
