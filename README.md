# DevSecOps pipeline for Python project

A Jenkins end-to-end DevSecOps pipeline for Python web application, hosted on AWS Ubuntu 18.04


<img alt="psparchitecture" src="https://user-images.githubusercontent.com/11514346/71579758-effe5c80-2af5-11ea-97ae-dd6c91b02312.PNG">



> **Checkout project** - check out python application project repository with XSS vulnerability

> **git secret check** - check there is no password/token/keys/secrets accidently commited to project github

> **SCA** - check external dependencies/libraries used by the project have no known vulnerabilities

> **SAST** - static analysis of the application source code for exploits, bugs, vulnerabilites

> **Container audit** - audit the container that is used to deploy the python application

> **DAST** - deploy the application, register, login, attack & analyse it from the frontend as authenticated user

> **System security audit** - analyse at the security posture of the system hosting the application

> **WAF** - deploy application with WAF which will filter malicious requests according to OWASP core ruleset




