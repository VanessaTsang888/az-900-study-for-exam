# Describe Azure functions

Azure Functions is an event-driven, serverless compute option that doesn’t require maintaining virtual machines or containers. If you build an app using VMs or containers, those resources have to be “running” in order for your app to function. With Azure Functions, an event wakes the function, alleviating the need to keep resources provisioned when there are no events.

## Serverless computing in Azure

What is serverless computing?
Video:

As a dev, we want to spend time building our apps and getting that to our customers. We don't want to focus on server managment tasks.

Serverless computting is missleading as there are servers being used. It really means is that the responsibility of managing servers is already handled for you. Therefore, we can take our minds off infrasture concerns and focus on dev concerns. Its an abstration.

## Benefits of using serverless approach

1. No infrastructure management: so dev's only need to deploy our code and it automatically runs with high availability.
2. Scalability: as our app grows in popularity, our app will continue to work under any workload.
3. Only pay for what you use: serverless computing is event driven, resources are only allocated from a direct action. Therefore, we are only charged for the time it takes to run our code.

Therefore, we just upload our code and auto get the benefits of infrastructure management and scalability. Plus, a payment model that will only charge us for what we use.

## Benefits of Azure Functions

Using Azure Functions is ideal when you're only concerned about the code running your service and not about the underlying platform or infrastructure. Functions are commonly used when you need to perform work in response to an event (often via a REST request), timer, or message from another Azure service, and when that work can be completed quickly, within seconds or less.

Functions scale automatically based on demand, so they may be a good choice when demand is variable.

Azure Functions runs your code when it's triggered and automatically deallocates resources when the function is finished. In this model, you're only charged for the CPU time used while your function runs.

Functions can be either stateless or stateful. When they're stateless (the default), they behave as if they're restarted every time they respond to an event. When they're stateful (called Durable Functions), a context is passed through the function to track prior activity.

Functions are a key component of serverless computing. They're also a general compute platform for running any type of code. If the needs of the developer's app change, you can deploy the project in an environment that isn't serverless. This flexibility allows you to manage scaling, run on virtual networks, and even completely isolate the functions.

### Next unit: Describe application hosting options

https://learn.microsoft.com/en-us/training/modules/describe-azure-compute-networking-services/7-describe-application-hosting-options
