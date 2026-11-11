
# ESXi Host Troubleshooting

This is a basic checklist for checking ESXi host issues through VMware vCenter.

## Host Disconnected

- Check the host connection status in vCenter.
- Review recent alerts and events.
- Check management network connectivity.
- Verify whether the host is accessible.

## High CPU or Memory Usage

- Check host CPU and memory usage.
- Review virtual machines running on the host.
- Identify VMs using high resources.
- Check for performance warnings.

## Datastore Issues

- Check datastore availability.
- Review free storage capacity.
- Verify that the datastore is accessible to the host.
- Check related storage alerts.

## Hardware Alerts

- Review hardware health in vCenter.
- Check available sensor information.
- Review hardware-related warnings.
- Use the server management interface for further checks if available.

## Maintenance Mode

Before placing a host in maintenance mode:

- Check running virtual machines.
- Confirm that workloads can be migrated or safely stopped.
- Follow the approved maintenance procedure.
- Verify host status after maintenance.

## Note

These are general troubleshooting checks. Actual steps depend on the environment and available permissions.
