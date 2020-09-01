# FOSSASAT-2 -  sketch modified by N6RFM

The sketches for Fossast-1b and 2 appear to have been deprecated in favor of a Qt based control panel. This panel contains a interpreter that processes serial messages sent to and from the ground station.  https://github.com/FOSSASystems/FOSSA-GroundStationControlPanel

For those who desire to use the simpler terminal based approach, this repo contains an updated sketch for Fossasat-2. Included are the ability to use newer public commands to interface with the satellite.  Commands not enabled are password protected for use by the FS-2 team only. See https://github.com/FOSSASystems/FOSSASAT-2/blob/master/docs/Communication%20Protocol.md the command list.  

[![Build Status](https://Github.com/FOSSASystems/FOSSASAT-2/workflows/CI/badge.svg)](https://github.com/FOSSASystems/FOSSASAT-2/actions)

[Doxygen Documentation](https://fossasystems.github.io/FOSSASAT-2)


First generation 2P Satellite dedicated to demonstrating new miniaturized technology for picosatellites developed by FOSSA. To be launched in Q1 2020 aboard a Firefly Alpha launch vehicle. 

## Payload
The main payload of FossaSat-2 is an OV2640 low-resolution CMOS camera. GSD is >50m/pixel. A Skytraq GNSS reciever is being used to test active TLE generation for PocketQubes. GPS Payload Supported by the Galileo Science office.

## ADCS
Active pointing is carried out by using integrated solar panel magnetorquers, 2 16-bit sun sensors and an IMU sensor.

## Comms
An SX1268T Chip is used to establish a Morse, 9k6 GFSK and LoRa Downlink and a LoRa and 9k6 GFSK uplink.

