## Lesson 3: Custom CI/CD workflow 

The default implementation of the CI/CD workflow for Project Firefly Applications relies on GitHub capabilities. 
Unfortunately, GitHub actions are not supported on GitHub Enterprise yet.
 
In the case you can't use the GitHub Actions, we recommend implementing a custom CI/CD workflow with focus on two main aspects:

* The [CLI](https://github.com/adobe/aio-cli) is the official tool to manage the Project Firefly Application development lifecycle from bootstrapping to deployment, and can be used within a CI/CD workflow for automation purpose.
* Security is a key requirement, and any alternative CI/CD workflow should propose a solid secret management solution to store the credentials required to deploy a Project Firefly Application against a specific **Workspace**.

Next: [Well done](welldone.md) 