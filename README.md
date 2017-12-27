# Bobnet Sensors Role

Ansible role for configuring sensor nodes.
This is used as part of [bobnet](https://github.com/robyoung/bobnet)
and configures nodes so that they are ready to use [bobnet-sensors](https://github.com/robyoung/bobnet-sensors).

## What it does

- Enable required hardware features such as I2C and SPI
- Install bobnet-sensors docker image
- Configure bobnet-sensors and Google IoT Core keys
- Install, start and enable systemd service
