- Links:
A CloudOps guide of Change Manegement, with further links to more support: https://confluence.sage.com/display/CLOUDOPS/Change+Management

The Change Management is only applied in the production environment, when the change is already been tested in lower enviroments (like QA, PP, DEVX). 

Environments:

-- DEV : When developers deploy to prove our the changes. CloudDevops and QA testers don't touch this environment, is only for devs. Devs can do all the deployments that wanted. 
-- QA : This environment is to ensure that the tests runs as expected. Devs can do all the deployments that wanted. Devs can deploy freely, but it's suggested to warn the QA team before the deployment. 
-- PP : A replication from Production Environment, is mandatory to runs tests here. You need approval of CloudDevOps to deploy in PP. 
-- PROD: Only when QA, Developer and Team Leader signed the release and CloudOps is ok with the CAB, we realize. CAB document is needed to be verified with a CloudDevOps, normally a team will have assigned someone from the team. For example, for Team Orange is Robert. The access is restristed. 

In Service Fabric STX we have different policies adapted to our environment, but in the meeting we see that CloudOps follows the same process. See the Release Policy: 

https://confluence.sage.com/display/EINV/Release+Policy

To make a change management request, you have to open a ticket selecting the correct options from your product. In SN, exists a template for each product, that fills the required fields and creates a prepopulated Description to be modified. 

The Changes are maded in a window consecuated with the different parties, like owner of the release or devs and QA. 

All Service Fabric follows the same change management that is guided and owned by Cloud DevOps. 

All the environments are isolated, separated and diferenciated from each other. Only CloudDevops have privilege access to production environment. 

Approvers => Team Leader, Manager or Director. part of the leardship team. 

HW:

-- They will provide us a form to fill up with specific information. Maybe only to DevOps. 
-- We need to provide a list of the person that has access to the pipelines?? => Part of this is to CloudDevOps, but maybe we have to provide screenshots from our pipelines. 
-- They will require a list of the person that has acess to repositories, who manages the access, what happens when someone leaves the team, the approval of changes, the management of branches, organization of them. => We have to provide evidence for each team. 

