![Community Board](profile/logo-150-150.png)

Kubediscovery lince is a free project for you to monitor the ecosystem of Kubernetes, and the cloud, moreover the proposal organizes the labels, products, and components in your ecosystem and shows them in diagram format.

Kubediscovery lince is organized with 6 components.
- Job-k8s: to read he manifests and mapping the some critical points
- job-azure: to read manifests from Azure
- webserver: is structure to organize your ecosystem
- processing: the component that will read manifests from job-k8s and job-azure and format to show in dashboard
- dashboard: management interface
- hub: deployment of postgres, mongodb and rabbitmq
