# IoT Data Pipeline Using Apache NiFi, MQTT, and InfluxDB

## Overview
This project sets up an IoT data pipeline using Apache NiFi, MQTT, and InfluxDB, all containerized with Docker. It is designed to manage and automate the flow of data from IoT devices, through MQTT messaging, to be processed and stored in InfluxDB.

## Prerequisites
- Docker
- Docker Compose

## Installation and Setup
1. **Clone the Repository**: `git clone https://github.com/vadymurupa/IoT-data-pipeline.git`
2. **Start the Docker Containers**: Navigate to the project directory and run `docker-compose up`.

## Services Configuration
### Apache NiFi
- Access the NiFi web interface at `http://localhost:8080/nifi`.
- Instructions on setting up data processors for MQTT and InfluxDB.

### MQTT Broker (Mosquitto)
- MQTT broker configuration details.
- Example on how to publish/subscribe to a topic.

### InfluxDB
- Access InfluxDB at `http://localhost:8086`.
- Guidance on creating databases, users, and managing permissions.

## Usage
Detailed instructions on how to use the pipeline, including:
- Sending data to MQTT topics.
- Processing data in NiFi.
- Storing and accessing data in InfluxDB.

## Customization


## Security Considerations


## Troubleshooting


## Contributing


## License


## Acknowledgements


