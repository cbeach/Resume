
Juno is a new aws account/environment with better amenities and more "handrails" to help developers deploy their code. 
A lot of work is required to migrate our tools and services to the new environment. I was chosen to be my team's lead 
lead in this effort and have been deprecating old, incompatible services in preparation for this effort.
Accomplishments to date:
 - Drove the effort to containerize our entire offering of services
 - Deprecated 73 very old and incompatible AWS instances and related infrastructure
   - The instances alone save Cambia \$20,000 per month

Ongoin work:
 - Creating a k8s cluster in EKS to host our services as we transition to our new environment
 - Integrating into our service mest Envoy to make use of cutting edge service mesh technology
 - Integrating a cutting edge service mesh based on envoy into our existing service catalog



This project aims to provide enough horsepower for my other ML projects. The list of hardware and service inventory that I've assembled follows.
 - A 40 core Dell r810 with 256 GB of RAM
 - A home built Intel i9 with 48 GB of RAM and a GTX 1080 TI
 - A 8 core Dell r410 intended for use as a virtual router/gateway.
 - A Synology DS718+ 8TB NAS
 - A bare metal depoyment of Kubernetes with the helm package manager.
