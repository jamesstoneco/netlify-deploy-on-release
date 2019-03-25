# Netlify deploy on versions

On Docs Thursday I came across several open source projects that had issues open to deploy to Netlify based on git tags / releases / versions rather than master branch changes. This makes sense since you have the most up to date work in the master branch and you don't want to push documentation changes between releases. So I set out to try and solve that problem with Zapier and it won't work. I still don't have access to GitHub Workflows and that isn't commonly avalaible. So instead I decided to try to put together a python backend based solution that could be easily deployed to a Heroku free tier and become and interum solution.

This project is still a WIP and doesn't support the full functionality. I will be updating it during my SpiceHours or Docs Thursday to support the workflow change end-to-end. Updates will appear here in the change log as I go.

# Changelog

Added basic hook for all and tested with postman on local dev

Based on the project [python-github-webhooks](https://github.com/carlos-jenkins/python-github-webhooks) by carlos jenkins.
