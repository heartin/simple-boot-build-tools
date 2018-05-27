# Simple Starter Build Tools

This project will contain all resources primarily required for build (e.g. checkstyle xml). 

This project needs to be extracted to a folder (buildtools) within the project build folder of the project that is being built. This is currently done by the parent project pom (cloud-heartin-parent-java). 

This project was created using the idea outlined at: http://maven.apache.org/plugins/maven-checkstyle-plugin/examples/multi-module-config.html

## Usage and setup (Local machine)

1. Install and configue Maven in local machine.
1. Configure to extract cloud-heartin-build-tools resources to a folder. Currently done by the parent project pom (cloud-heartin-parent-java). So no need to do anything if you are using that parent project.
1. Clone  cloud-heartin-build-tools into local machine.
1. Run 'mvn clean install'