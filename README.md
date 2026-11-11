
# VMware ESXi Host Management

## Overview

This repository covers basic VMware ESXi host administration and monitoring through vCenter.

## Host Management

Common tasks include:

- Checking ESXi host connection status
- Monitoring CPU and memory usage
- Reviewing host hardware health
- Checking virtual machines running on a host
- Reviewing host alerts and events
- Checking datastore and network connectivity

## Maintenance Mode

Maintenance mode is used when an ESXi host needs planned maintenance.

Before entering maintenance mode, running virtual machines and their availability must be checked. Depending on the environment, VMs may need to be migrated or powered off.

## Basic Troubleshooting

| Issue | What to Check |
|---|---|
| Host disconnected | Network connectivity and management services |
| High CPU or memory | Host resource usage and running VMs |
| Storage warning | Datastore connectivity and capacity |
| Hardware alert | Host hardware health and logs |
| VM not responding | VM status and host events |

## Tools

- VMware ESXi
- VMware vCenter
- VMware vSphere Client

## Note

This is general technical documentation. No company infrastructure details are included.
