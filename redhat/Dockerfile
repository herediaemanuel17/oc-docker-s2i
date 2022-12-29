# simple dockerfile to test OCP s2i using Dockerfile 

FROM registry.access.redhat.com/ubi7:latest

#Cambio de parametro del Dockerfile para generar una nueva salida en el pod de OCP
# CMD ["/bin/bash", "-c", "sleep infinity"]
CMD ["/bin/bash", "-c", "--", "while true; do sleep 30; done;"]
