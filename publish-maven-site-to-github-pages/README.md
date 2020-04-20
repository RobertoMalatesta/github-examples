# Publish Maven Site to GitHub pages

This example demonstrates how you can use publish your Maven site to GitHub pages.

To enable this as a GitHub action you will have to do the following:

1. Copy the contents of the publish.yml into a new or existing workflow
2. Adjust the user in the git push command
3. Adjust the repository in the git push command
4. Adjust the email address in the git config command
5. Add the PUBLISH_USERNAME secret as a secret to your GitHub account / organization
6. Add the PUBLISH_PASSWORD secret as a secret to your GitHub account / organization
