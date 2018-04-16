---

 ### CI / Envs
 ### (@_aalvz)

 <span style="color:gray">aalvz</span>

---

 ### Content

 - Requirements
 - Proposed solution
 - Architecture & Flow
 - Techs

+++

 ### Content
 
 - Covered Area
 - Demo & OnBoarding
 - Future Work
 - Q/A

---

 ### Requirements
  - Define CI/CD Pipeline
  - DevOps to the test

+++

 ### Proposed Soultion

 - Infrastructure as Code. 
 - Disposable/Inmutable Infrastructure

+++

 ### The Architecture (add image)

 Ansible -> Automatic Provision -> Envs (Dev/QA/Prod) -> Debian 8.0 -> Security (users/paths) -> Install packages (node,mongo....) -> Run App

+++

 ### Workflow

 DevEnv (Server or Vagrant) -> Every Dev w/ fork -> Branches on features -> Push -> Triggers tests with CircleCI -> Triggers tests in disposable QA env -> if passed push to production with git server -> hooks to update services and log changes. 

Only one master repo which is modified via pull request from the forks

+++

 ![Git branches](https://buddy.works/data/blog/_images/gitflow.png)

+++
 
### Techs

  - Emacs
  - Node
  - Mongo
  - CircleCi
  - Mocha
  - Ansible
  - Nginx
  - Vagrant
  - Monit
  - Passenger
  - SSH
  - Bash
  - Git

+++

  ### Covered Area

Everything ready to grow

  - Automated Running app to any environment (clone, express, endpoints, dependencies, test, start)
  - CI/CD Pipeline -> Ansible + CircleCI + Mocha + Git(Server/Branches/Hooks) + Bash (Dev-QA-Prod)
  - No downtime under labor. First version stable.
  - Tests (Infra/Unit/Functional)
  - Monitoring services.
  - Automated Prod env based on Envs
  - Automated Security (Users/Paths/SSH Keys)
  - Nginx routes
  - Automated Database creation and config depending on the env

+++

Future

 - More tests. Lint and stuff
 - Automated full tests beginning with full infrastructure. 

+++

Demo On boarding

+++ 

Some mantras

 - Branch early, and branch often
 - Error DB
 - One step build and daily
 - fix before new
 - Test it all
 - 
---
