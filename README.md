
# Standard CI/CD Pipelines

## Usage

 1. Download a template from the template directory & unpack it to the root of your repository
 2. Add the files to the repository `git add --all; git commit -am "adding standard-cicd-pipelines template"`
 3. Make the execute file executable `git update-index --chmod=+x execute`
 4. Push the files to the remove `git push origin main`

## Stages

 - Package - Install dependencies and run unit tests
 - Deploy - Deploy to infrastructure and run integration tests

## Directories

 - templates/ - Generated templates that can be copied into the root of a new repository for use
 - components/ - Individual parts of a template that we use to compile templates
