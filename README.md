# aws-budget-tender

This application aims to help manage AWS account spend by:

* Checking for under-utilized resources.
* Highlighting cost changes
* Creating simple reports to help track down costs.

## Utilization Monitoring

This feature check for EC2, ECS, Nat Gateway, and other service that may be operating under 30% utilization and firing off an event to either notify or to take action on the resource.
