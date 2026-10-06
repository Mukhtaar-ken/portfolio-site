# portfolio-site

My personal site, hosted on Azure Static Web Apps.
  - https://kind-sea-0a70ac210.4.azurestaticapps.net
  - I deploy it by pushing to main then that push triggers github actions which deploys the azure static web apps
  - one of the things that broke was the push was rejected because my GitHub CLI login didn't have the workflow permission. I fixed it with gh auth refresh -s workflow.
  - Next: a custom domain, and adding each portfolio project here as I finish it.

