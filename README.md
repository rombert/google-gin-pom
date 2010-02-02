Google-Gin Maven deployment
==========================

This project contains

* a pom.xml file to be deployed with the jar files;
* a build.xml used to deploy the jar files;

To deploy the artifacts:

1. Build the gin jar and gin javadoc jar;
1. Adjust the version (if needed) in the pom.xml file;
1. Run <code>ant -Dgin.jar.file=../gin/gin.jar -Dgin.javadoc.file=../gin/javadoc.jar</code>

Please note that this pom.xml file is intended only for deployment, it is not
able to describe the gin compilation process.
