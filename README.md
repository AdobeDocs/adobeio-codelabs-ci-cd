# Setup CI/CD in a Firefly App

Project Firefly allows you to manage multiple environments called workspaces. Each workspace has its own setup: 

* List of Adobe services to integrate via user or technical user accounts
* Runtime namespace
* Cloud storage for the SPA static files
* CDN delegation and sub-domain provisioned on adobeio-static.net
* Related credentials and secrets (API Key, access token, Runtime namespace credentials...)

We recommend to go through the [Firefly CI/CD documentation](https://github.com/AdobeDocs/project-firefly/blob/master/guides/ci_cd_for_firefly_apps.md) to learn more about the architectural details.

This codelab will show you how to create a CI/CD worflow for a stage and production environment using [Github actions](https://github.com/features/actions) within a [Project Firefly](https://github.com/AdobeDocs/project-firefly) App.   

For that, we'll use the default bootstrapped Firefly project provided via the [CLI](https://github.com/adobe/aio-cli) which provides a sample CI/CD workflow out-of-the-box.  

Next: [Requirements](/lessons/requirements.md).  



  
