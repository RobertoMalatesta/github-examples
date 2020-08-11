# Release trigger

This example demonstrates how you can run SonarCloud in a pipeline.

To enable this as a GitHub action you will have to do the following:

1. Copy the contents of the trigger.yml into a new or existing workflow
1. Add the SONAR_PROJECT_KEY secret as a secret to your GitHub project
1. Add the SONAR_LOGIN secret as a secret to your GitHub project
