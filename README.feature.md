# Release Schedule & Feature Planning
This document is created for EC product-related reference. The team will maintain this information based on the requirement specified in the issue list until the project is fully organised in the github.

## Phase:
Design-> Prototype/Bootsrap-> Development-> QA

## Plan Est/Unit:
in Day

```text
DTEC-71: VLAN Plug-in for windows
>>> An agreeable approach has been identified. (Design)
|
|- SPIKE: VLAN Windows Development. (8 days)


DTEC-77: MAC Filtering 
>>> Available in Watcher release (v1.1beta. QA)
|
|- Add the MAC filtering in gateways config.yml (3 days)

DTEC-76: Track user info 
>>> xcalr persist the subscription info in the request form; user info is available via the certificate. (Development)
|
|- Client/Server Network Profiling (7 days)
|- UI implementing Client/Server Connection Information (24 days)


DTEC-75 EC Cert process fix
Streamline CERT process
>>> Define the maintenance email notification. (Design)
|
|- Watcher: Oversea Cert update/Upgrade Process (15 days)


DTEC-68: EC SmartWatcher: Alert when specific agent/gateway is down
>>> The alert format is configurable in the Watcher grpc interface. (Development)
|
|- UI Alert Implementation (12 days)
|- External **Notification API** Interface Design (6 days)
|- Internal Interface Design for Alert *Watcher Notification* (8 days)
|- DC CLI Alert Implementation (6 days)
|- Implementing/Orchestrate the Alerts in xcalr (6 days)


DTEC-55: BUG: Loop back - Cache needs to be reset - Issue is IP address is getting cached even after restart
>>> An agreeable approach has been identified. (Design)
|
|- Persist/Restore Network Interfaces (Re-defined)


DTEC-63: EC CTL for remote management
>>> Authentication/login package WIP. (Prototype/Bootsrap)
|
|- SPIKE: CLI Opensource Package Usage/Implementation (18 days)


DTEC-69: As an Ops, need EC Admin Console Features
>>> UI/UX functional interview. (Est Days N/A; Design)


DTEC-73: EC Service and UAA run on AWS natively 
>>> xcalr: watcher deployment in userdata (EC2). Add config API. (Development)
>>> AWS: define rules, target groups. TLS cert/DNS update. (Development)
|
|- KT Need: Externalise Nurego Integration (1 days;)
|- Visualising the Gateway Deployment via the WebUI (Re-defined needed.)


DTEC-72: Need data usage report in AWS VPC and broken down by Gateway, group, etc in a more granular way
>>> Available in Watcher release. (v1.1beta. Development)
|
|- Design&Implement: Protobuf for Watcher GRPC interfaces (8 days)
|- Display the Connectivity Usage/Info by DCTL (3 days)
|- Display the Connectivity Usage/Info by WebUI (12 days)
|- Implement the GRPC interface for watcher details in xcalr (6 days)

```
