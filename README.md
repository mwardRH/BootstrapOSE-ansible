# OpenShift Enterprise Prep Playbook
WORKING: This playbook is used to prep a system making it ready for the install of Red Hat OpenShift Enterprise Edition.

## REQUIREMENTS
You must be using Red Hat Enterprise Linux and Red Hat OpenShift Enterprise.
I recommend having Ansible configured and tested before using this playbook.
You must set the RHUSERNAME and RHPASSWORD environment variable. This will be used for subscribing the system to Red Hat Subscription Manager.
I recommend you have your own hosts file configured.

## To Do for this playbook
1. Add more information to Readme
2. Create update hosts file
3. Add repo logic so it won't remove and add repos every time the playbook is ran.
4. Enhance the Subscription Manager section to search for OpenShift repos
5. Deploy OpenShift master and nodes

## CONTACT
Matthew Ward
