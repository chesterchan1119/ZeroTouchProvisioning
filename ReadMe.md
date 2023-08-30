# Zero Touch Provisioning
The application is to allows users to search, reserve and apply new network switch to Data Centers.

## Background
A switch connects devices in a computer network together. Data cables are plugged into a switch to enable communication between different networked devices. 

### - Top-Of-Rack Architecture in Networking
<img width="632" alt="image" src="https://github.com/chesterchan1119/ZeroTouchProvisioning/assets/110362704/603dff31-62a2-407b-9da8-feba39456902">

In Top of Rack (TOR) architecture, each rack of servers has its own network switch placed at the top of the rack. These switches typically have a high port density to accommodate the large number of servers within the rack. The switches connect the servers within the rack to the data center network.

ToR switches in each rack are then connected to aggregation layer switches, which we named Core Switches in this project. These switches aggregate the network traffic from multiple racks and provide connectivity to the core network or distribution layer switches. Aggregation layer switches offer higher bandwidth and additional features for network management and control.

## Existing Organizational approach
<img width="844" alt="image" src="https://github.com/chesterchan1119/ZeroTouchProvisioning/assets/110362704/f3d5b784-57df-49ee-82f5-ed1e06aa9c37">

## Our New Solution - ZTP
<img width="846" alt="image" src="https://github.com/chesterchan1119/ZeroTouchProvisioning/assets/110362704/2dcb79f5-3693-4afb-96b9-eb195a66ba41">

## Overview
<img width="901" alt="image" src="https://github.com/chesterchan1119/ZeroTouchProvisioning/assets/110362704/9e7749e8-86d1-4467-8274-3a28a41cee6e">

