Google-Gin Maven deployment
==========================

This project contains

* a pom.xml.in template to be deployed with the jar files;
* a build.xml used to deploy the jar files;

The current version works with Gin 1.5 and deploys both
pre-2.2 and post-2.2 artifacts with javadoc and source as
two different gin versions, 1.5-pre-2.2 and 1.5-post-2.2.

To deploy the artifacts run ant deploy. This will retrieve
the 1.5 version of gin, and deploy them to the sonatype
staging repository.

To perform deployment, please make sure to follow the instructions
at [Staging artifacts with Ant](https://docs.sonatype.org/display/Repository/Sonatype+OSS+Maven+Repository+Usage+Guide#SonatypeOSSMavenRepositoryUsageGuide-7c.StageArtifactswithAnt) and to have a GPG key configured.
