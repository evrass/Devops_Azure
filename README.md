
# DevSecOps for Azure


**End-to-end supply chain security for GitHub, Azure DevOps, and the Azure cloud**

## What is this project about?
From secure development environments to continuous security and compliance integration, this comprehensive guide equips you with the skills to implement a robust code-to-cloud process tailored for Azure environments.

This project covers the following exciting features:
* Understand the relationship between Agile, DevOps, and the cloud
* Secure the use of containers in a CI/CD workflow
* Implement a continuous and automated threat modeling process
* Secure development toolchains such as GitHub Codespaces, Microsoft Dev Box, and GitHub
* Integrate continuous security throughout the code development workflow, pre-source and post-source control contribution
* Integrate SCA, SAST, and secret scanning into the build process to ensure code safety
* Implement security in release and deploy phases for artifact and environment compliance

## Instructions and Navigations
All of the code is organized into folders. For example, chapter-3.

The code will look like the following:
```
apiVersion: v1
kind: Pod
metadata:
  name: non-root-pod
spec:
  containers:
  - name: mycontainer
    image: myimage
    securityContext:
      runAsUser: 1000
      runAsGroup: 3000
```


With the following software and hardware list you can run all code files present in the book.
### Software and Hardware List
*  A PC with an internet connection
*  An active Azure subscription
*  An Azure DevOps organization
*  A GitHub Enterprise organization

