salesforce-ci
=============

CloudAnswers standard build script for our projects

Assumptions:

- your salesforce source code is in ./src

Includes:

- static analysis code scanning via pmd

Todo:

- lightning component
- dx deploys with different org shapes
- test deploy
- apex unit testing

Usage:

Add this line to your CI setup:

    curl https://raw.githubusercontent.com/cloudanswers/salesforce-ci/master/run | bash
