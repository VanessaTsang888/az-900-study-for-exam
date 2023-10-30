# Describe Infrastructure as a Service

https://learn.microsoft.com/en-gb/training/modules/describe-cloud-service-types/2-describe-infrastructure-service

Infrastructure as a service (IaaS) is the **_most flexible category_** of cloud services, as it provides you the **_maximum amount of control for your cloud resources_**. In an IaaS model, the cloud provider is responsible for maintaining the hardware, network connectivity (to the internet), and physical security. You’re responsible for everything else: operating system installation, configuration, and maintenance; network configuration; database and storage configuration; and so on. With IaaS, you’re essentially renting the hardware in a cloud datacenter, but what you do with that hardware is up to you.

## Shared responsibility model

The shared responsibility model applies to all the cloud service types. **_IaaS places the largest share of responsibility with you_**. The cloud provider is responsible for maintaining the physical infrastructure and its access to the internet. You’re responsible for installation and configuration, patching and updates, and security. I think this is what most large organisation would opt for as they would need this kind of flexibility and control?

**_Diagram:_**
A cart to demonstrate the above.

## Scenarios

Some common scenarios where IaaS might make sense include:

- Lift-and-shift migration: You’re standing up cloud resources similar to your on-prem datacenter, and then simply moving the things running on-prem to running on the IaaS infrastructure.
- Testing and development: You have established configurations for development and test environments that you need to rapidly replicate. You can stand up or shut down the different environments rapidly with an IaaS structure, while maintaining complete control.

## Next up

[Describe Platform as a Service](https://learn.microsoft.com/en-gb/training/modules/describe-cloud-service-types/2-describe-infrastructure-service)
