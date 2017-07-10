# 401 backend project week

## Setup
* the team leader should create a repo on thier own account
* add a package.js, .gitiginroe, .travis.yml, test/dummy-test.js
* setup a github repo and add team mates as colaborators
* enable travis 
* In the repo settings, make the master branch a **protected** branch
 * Require pull request reviews before merging
 * Require review from Code Owners
 * Require status checks to pass before merging
 * Require branches to be up to date before merging
 * Include administrators
* Setup Heroku with automated deploys

## Requirements
* build a rest api 
* must have thurow documentation of the routes in the README.md
* must include a user model with auth
* must have two other models
* must have one model that has a file that gets uploaded to AWS s3
* must have 90% code coverage
* must have travis ci setup 
* must have continuous deploment with heroku

## How to add a feature
* checkout master
* pull the lastet updates
* checkout a new branch **NAMED AFTER YOUR FETURE**
* add your changes, and commit as often as possible
* open a pull request
* have a team mate do a **review** of the PR
* If all checks pass and they have done the review THEY can merge it

## Each time a branch is merged
> DELAYING THIS STEP OR DISREGARDING THIS STEP WILL MAKE YOUR CODE UNMERGABLE.  
* everyone immediatly commit thier current changes
* everyone run `git pull origin master` in their current branch
* everyone handles their own merge conflicts immediatly
* everyone continues working on their feature

