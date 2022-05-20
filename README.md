# Google Summer of Code 2022 @ CNCF - KubeArmor Observability and Policy Discovery Helper Tool

This is a project tracker Google Summer of Code 2022 @ CNCF

## Abstract
> Running Kubernetes should be done with the utmost security in mind. KubeArmor provides a policy based system to increase the quality of security in a Kubernetes cluster. Users need to define their own policy when implementing KubeArmor. Most users might find it challenging to define the most appropriate and effective security policy based on their use case. Currently there are limited ways for users to actually get observability data that can be used to assist them and provide better reasoning when creating an optimal security policy. The solution to this problem is by providing visibility telemetry events to show pod or container observability data. Observability data can consist of processes executions, file system accesses, and network accesses. This information is expected to assist users to create an optimal security policy. This solution is implemented by developing and deploying a Kubernetes service that will connect to the KubeArmor relay and get the events from the daemonsets. These events will then be aggregated and stored in the database for future use. Users can get the data by using the KubeArmor CLI program which will be extended to accommodate this solution.

