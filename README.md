# JAVA Academy: DevOps (Developers Operations)

## Introduction

This course teaches us about DevOps, where operators connect with developers, since goals must be aligned, there must be fluid communication, along with speed and high results. It is a change of culture and the desire of both teams to collaborate.

## Dependencies

1. [Docker](https://www.docker.com/)
2. [Jenkins](https://www.jenkins.io/)

## Notes

**Continuous Integration theory**

With Git we make our changes in the code remain in a story that we can test before passing it to the master branch, knowing that our tests are passing successfully without breaking what we have in master.

Jenkins is our test automation, it downloads the latest version of our branch where a change was made and performs the tests we have and if they fail, it prevents us from breaking our main branch and tells us which tests failed to correct it.

We can also do a code analysis, we can have something very complex or a style that the team does not like and it can be changed in this part of the cycle and we keep the style guide good and code clean while we develop.

Artifacts is our unit that will pass to all environments, it must be something immutable. It's something we can store for a certain amount of time, maybe a year in case we need to rollback.

Integration tests are more productive, have more scope and have more value.

![Alt text](http://i.imgur.com/VchG9Ga.png?raw=true "Continuous Integration")


**Continuous Integration, Delivery and Deployment**

*Continuous Integration*
It is a workflow that is used in teams of programmers and facilitates the addition of functionalities to the products.

![Alt text](http://i.imgur.com/jB0SLHh.png?raw=true "Continuous Integration")

*Continuous Delivery*
It is a CI extension that automates the entire process of adding code to the main branch, so that you can deploy to production at any time manually and safely.

![Alt text](http://i.imgur.com/jJFxXqU.png?raw=true "Continuous Delivery")

*Continuous Depoyment*
It goes one step further and the deployment is also automatic, Changes are seen in minutes and you receive feedback from customers to iterate quickly.

![Alt text](http://i.imgur.com/Xfh6tLN.png?raw=true "Delivery vs Depoyment")



