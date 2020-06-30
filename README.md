
# EFS-Parent

This artifact in the EFS project is the maven parent artifact, that all other artifacts derive from. It provides version information about the particular dependencies that are used by its child artifacts.

It also provides configuration for spring-boot-maven-plugin that should be common for all EFS-services.

To use efs-parent in your EFS-project replace the "parent" block in pom.xml of the project with the following block. Always make sure you are using the correct version of efs-parent. The initial version of efs-parent is `0.0.1-SNAPSHOT`.

**pom.xml parent block:**

```xml
<parent>
  <groupId>de.fraunhofer.iao.efs</groupId>
  <artifactId>efs-parent</artifactId>
  <version>0.0.1-SNAPSHOT</version>
  <relativePath/> <!-- lookup parent from repository -->
</parent>
```
