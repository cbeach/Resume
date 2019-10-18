
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
