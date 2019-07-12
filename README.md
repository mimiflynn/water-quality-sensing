# Project Name: Residential Water Quality Sensor Project (temptative)

## Motivation (i.e. problem we are trying to solve)

(to frame better)
Lead affectime residential homes 

## Idea (i.e. our solution to the problem)
Place a sensor on water tanks (for example on toilet tanks)
Use a cheap distribution network

## Our Approach

Monitor for lead content in water sources at the point of use. By placing a sensor in a toilet tank, the sensor will have a fresh tank of water to sample with every flush.
Sensor data will be sent via long-range radio network (LoRaWAN) where the data can be monitored by various applications through MQTT subscriptions.

These applications can trigger notifications (for example emails, text messages, etc), store in a DB and analyze the data.

Our proposal is superior to existing solutions because:
> It minimises the human intervention 
> It uploads the information automatically to a centralized database, therefore it can be used to advocate for residents.



## Requirements

### Technology requirements

-Lead Sensors
- cheap network connection

### Human Resorces
Resources to distribute the sensors and distribute educational material to raise awareness on the problem





Initial use case - lead sensing in residences

Continuous testing

Low power

Wireless

cheap






# Passive Lead Sensing

## Purpose

No safe level of lead content in water.

Monitor for lead content in water sources at the point of use. By placing a sensor in a toilet tank, the sensor will have a fresh tank of water to sample with every flush.




## Architecture

Sensor -> LoRaWAN -> TTN -> Node-red, grafana, mapbox

Generate power from movement of water.

https://github.com/mcci-catena/docker-ttn-dashboard


## Sensor Research

UMich developed a $20 sensor

https://news.umich.edu/affordable-lead-sensor-for-home-city-water-lines/

https://pubs.acs.org/doi/abs/10.1021/acs.analchem.7b00843

https://pubs.acs.org/doi/suppl/10.1021/acs.analchem.7b00843/suppl_file/ac7b00843_si_001.pdf

