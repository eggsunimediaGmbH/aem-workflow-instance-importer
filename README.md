# aem-workflow-instance-importer

This tool can be installed to AEM to import running workflow instances from one AEM instance to another. Currently it works only with "scheduled_activation" and "scheduled_deactivation" but can easily be extended for other workflows.
You only need to create a packe with the path "/var/workflow/instances" and upload it in the tool and the workflow instances will be re-created. 

Internally it uses the Sling Servlet-Helpers framework to call the AEM default workflow creation servlet. 
