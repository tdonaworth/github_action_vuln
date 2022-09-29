# GitHub Actions Vulns
Example repository that contains various GitHub Action vulnerabilities, or things NOT to do.

## What is GitHub Actions?

GitHub Actions is a CI/CD platform allowing GitHub developers to automate development workflows easily.
Any repository on GitHub can add YAML files (called workflows) in the .github/workflows path, and once certain events occur, it will run your jobs.
Like every continuous integration system, its usages may vary. Sample workflows could be:

* Building the code into a container and uploading it to the chosen registry.
* Scheduled tasks that scan vulnerabilities in code.
* Running tests for forked pull requests.
* Automatic labeling for issues.
* Sending issues to ticket handling system (Jira/Monday/Asana/etc.).
* Supporting automatic merges for PR created by external bots.
* And more.

## GitHub workflow: 
![Alt text](https://github.com/actions/runner/blob/main/docs/res/workflow-run.png "GitHub Workflow")



# Credit
Some of the content for this was pulled from various articles, repositories, or other research across the web.
Thank you and credit goes to them:
* [Cycode - GitHub Actions Vulnerabilities](https://cycode.com/blog/github-actions-vulnerabilities/)
