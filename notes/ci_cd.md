# Continuous Integration/Deployment - An Introduction

_Sarah Gibson_

## What is Continuous Integration?

Continuous Integration (CI) is the process of automating the integration of code changes from multiple contributors into a single software project.
This process is often comprised of a range of automatic tooling to assert the new code's correctness before integration.
A version control system is the crucial element of CI processes and is often supplemented with other checks such as code quality, syntax style reviews, and more.

## What is Continuous Deployment?

Continuous Deployment (CD) is a software release process that uses automated testing to validate if changes to a code base are correct and stable before immediate deployment to a production environment.
This is beneficial as bugfixes and new features can often be in the hands of users as soon as they are pushed.

## CI/CD Vendors

There are many different platforms that provide CI/CD services.
These services can be thought of as "someone else's computer" where the testing and deployment phases of your software release process can be executed.
The commands you would usually run on the command line to test and build your code can be put into a script that the CI vendor will automatically run on a given trigger, for example, when new code is pushed.

## GitHub Actions

For the purposes of this tutorial, we are going to focus on GitHub Actions.
But all we do here can also be achieved with any other CI vendor.

### What is GitHub Actions?

GitHub Actions is a CI service provided by GitHub.
I (Sarah) like it for a few reasons:

- Results of CI runs are fully integrated with the GitHub repository where I keep my code
- Actions can be triggered by a wide range of events, such as issue comments or label assignments
- Actions can do much more than just test and build your code too, such as comment on issues and assign labels!

But these are my opinions, this is not an advert for GitHub Actions!

I think it's useful to clear up some vocabularly when working with GitHub Actions.

- **GitHub Actions.**
  This is the name of the product/service developed by GitHub.
- **Workflows.**
  This is the task you want to run automatically when triggered.
  A workflow is defined in a YAML file and contains all the steps that need to be run along with other information, such as the OS to run the job on and any dependencies that need installing.
  Another advantage of GitHub Actions over other CI vendors is that you can define as many workflow files as your project requires. Instead of one file that does lots of things, you can have a workflow file per task with it's own specific triggers.
- **Action.** An "action" is some code for a particular step that has been packaged up in such a way that it can be imported into your workflow.
  An example of an action is ["Build and Push" from Docker](https://github.com/marketplace/actions/build-and-push-docker-images).
  If you need to build a Docker image and push it to a registry during deployment, you can import this action to manage that process for you instead of installing docker and executing the build and push commands separately.
  Actions are available on [GitHub Marketplace](https://github.com/marketplace?type=actions) and are provided by official sources and third party developers.
  Creating your own action is also a possibility if you can't find one to suit your needs.
