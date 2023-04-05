# Write-up Template

### Analyze, choose, and justify the appropriate resource option for deploying the app.

Analyzing and Explaining Your Choice Between a VM or App Service
When deploying a web application, one of the first decisions you'll need to make is whether to use a virtual machine (VM) or an app service. Both options have their advantages and disadvantages depending on the needs of your project. In this writeup, we'll analyze and explain the differences between a VM and an app service to help you make an informed decision.

Virtual Machine (VM)
A virtual machine provides a fully customizable environment where you can install and configure any software you need. This flexibility makes it a great choice for complex applications that require specific configurations or dependencies. VMs also allow you to maintain full control over the operating system, allowing you to customize resource allocation, security settings, and more.

However, because VMs require more resources to maintain than app services, they can be more expensive and time-consuming to manage. You'll need to monitor and maintain the virtual machine itself along with your application, which can lead to increased operational costs.

App Service
An app service operates as a platform-as-a-service (PaaS) offering that abstracts away most of the underlying infrastructure management. With an app service, you simply deploy your application and let the platform take care of the rest. This makes app services a great option for small to medium-sized projects with fewer dependencies, since they require less maintenance compared to VMs.

App services also have the added benefit of being highly scalable. You can easily increase or decrease resources as needed to meet traffic demands. Additionally, app services typically offer built-in features like continuous deployment, automatic scaling, and easy integration with other Azure services.

However, the downside is that app services provide less control over the underlying OS and infrastructure. You'll need to conform to the limits and configurations provided by the platform, which may not work for all use cases.

In conclusion, I have explored the differences between a virtual machine (VM) and an app service. I have discussed that while both options have their advantages and disadvantages, choosing between them comes down to the specific needs of your application. In this case, I have decided that an app service is the better choice due to its built-in scalability and simplified deployment process. That being said, it's important to remember to weigh the pros and cons of each option carefully before making your final decision as every situation is unique.

### Assess app changes that would change your decision.

*Detail how the app and any other needs would have to change for you to change your decision in the last section.* 

To begin with, it's important to note that the specific needs and requirements of your application should always guide your decision-making process. That being said, in order for you to consider changing your decision from an app service to a virtual machine, certain factors would need to come into play.

One of the main reasons why an organization might shift from using an app service to a virtual machine would be if they require more control over the underlying infrastructure. With an app service, the platform abstracts away most of the underlying functionality and provides a simplified interface for developers to deploy their application quickly. However, this abstraction comes at the price of reduced control over the underlying infrastructure. If your application has dependencies or requirements that aren't easily met by the app service architecture, then shifting to a virtual machine may offer more flexibility in terms of customization.

Another reason why an organization might choose to switch to a virtual machine could be because of performance and cost considerations. Virtual machines typically have more resources available to them and can handle higher levels of traffic compared to app services. If your application is experiencing bottlenecks or slowdowns due to high demand, moving to a virtual machine could improve its performance. Additionally, depending on your usage patterns and requirements, a virtual machine could be a more cost-effective option than an app service.

In terms of how the app and other requirements would have to change to support this switch, there are several adjustments that would need to be made. For example, if you were running a containerized application on an app service, you would need to repackage it and run it on the virtual machine. Additionally, you would need to set up the necessary infrastructure to enable traffic to reach the virtual machine, such as configuring load balancers and network security groups. Finally, you would need to make sure that your team has the necessary expertise to manage and maintain the virtual machine, as it requires more hands-on work compared to an app service.

In summary, while an app service is often a simpler and more streamlined option for deploying applications, there may be situations in which a virtual machine is a better choice. If this were to be the case, adjusting your application and infrastructure to support the switch would require significant resources and expertise.