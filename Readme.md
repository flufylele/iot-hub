# IoT Hub

A docker swarm-ed Hub for recieving, storing and showing IoT data.
It uses a Mosquitto broker for recieving the messages, InfluxDB for storage and Grafana for showing it. 

All of them are complicent to the SPRC 3rd homework assignment.

## Run
The first run uses
```bash
make
```
or
```bash
./run.sh
```
.

Otherwise, use 
```bash
make deploy
```
.