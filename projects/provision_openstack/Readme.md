This playbook is to provision OpenStack.


main.yml 
Is the Wrapper that connect the various tasks together.

source.yml
Similiar to sourcing an RC file for a tenant. This playbook does the setup of an given system to work on a tenant. It then installs the various OpenStack Clients. 

provision.yml
Similiar to Nova Boot. Actually perform