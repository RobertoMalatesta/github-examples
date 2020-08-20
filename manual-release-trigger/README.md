# Manual release trigger

This example demonstrates how you can utilize a manual workflow to trigger a
release pipeline.

To enable this as a GitHub action you will have to do the following:

1. Copy the contents of the manual-release-trigger.yml into a new or existing
   workflow
2. Adjust the username in the git config command
3. Adjust the email address in the git config command
4. Add the GIT_PASSWORD secret as a secret to your GitHub account (note this 
should be a personal access token that can push to your GitHub repository)

And then you can trigger a release pipeline by going to the GitHub UI and
executing the manual workflow with the entered values for the branch and the
version you want to release.
