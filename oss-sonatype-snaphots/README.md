# Build and push your artifacts to the OSS Sonatype SNAPSHOTs repository

This example demonstrates how you can use Maven to build and push SNAPSHOTS to
oss.sonatype.org

To enable this as a GitHub action you will have to do the following:

1. Copy the contents of the oss-sonatype-snapshots.yml into a new or existing workflow
2. Make sure your POM file contains the following snippet

```
<distributionManagement>      
    <snapshotRepository>
        <id>ossrh</id>
        <url>https://oss.sonatype.org/content/repositories/snapshots</url>
    </snapshotRepository>
</distributionManagement>

```

3. Add the OSSRH_USERNAME secret as a secret to your GitHub account, which is 
   your username for the OSS Sonatype repository
4. Add the OSSRH_TOKEN secret as a secret to your GitHub account, which is your
   password for the OSS Sonatype repository
