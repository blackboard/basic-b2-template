basic-b2-template
=================

This project provides the framework for starting a new Building Block (B2) project for Blackboard Learn.  Fork this project and make changes as necessary for your project.

How To Use This Project
====

Clone this repository into a directory: 
`git clone https://github.com/blackboard/basic-b2-template.git -o template <project name>`

Note that the clone command has assigned the `template` remote identifier to keep it separated from your real origin remote.

Next, add an origin remote for your own git repository: 
`git remote add origin <URL to your git repo>`

Add your code and push to your origin remote: 
`git push origin`

Deploying Your B2
===
To deploy your B2 for testing, run `gradlew deployB2`.
