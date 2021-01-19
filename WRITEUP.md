# Write-up Template

### Analyze, choose, and justify the appropriate resource option for deploying the app.

*For **both** a VM or App Service solution for the CMS app:*
- *Analyze costs, scalability, availability, and workflow*
- *Choose the appropriate solution (VM or App Service) for deploying the app*
App Service

- *Justify your choice*
For now the hardware limitations of an app service don't need to be taken into account. We are deploying a lightweight
web application so app service is the right choice as we don't need full control of the underlying VM.

### Assess app changes that would change your decision.

*Detail how the app and any other needs would have to change for you to change your decision in the last section.* 

I would change my decision if I would need to have more control over the underlying VM. Additionally I would change
from App Service to VM if more and more users are using my web application so that the threshold of 
14GB of memory and 4 vCPU cores per instance are not sufficient any more.
