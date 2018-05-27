# Simple Starter Build Tools

This project will contain all resources primarily required for build (e.g. checkstyle xml). 

This project needs to be extracted to a folder (buildtools) within the project build folder of the project that is being built. This is currently done by the parent project pom (cloud-heartin-parent-java). 

This project was created using the idea outlined at: http://maven.apache.org/plugins/maven-checkstyle-plugin/examples/multi-module-config.html

## Usage and setup (Local machine)

1. Clone simple-starter-build-tools: <br>
git clone https://github.com/heartin/simple-starter-build-tools.git
1. Run './mvnw clean install' or 'mvn clean install'