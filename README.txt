    Instruction to build project via Maven tool:

1. Open directory  tools -> copy files to same directories of project (
for example: copy file pom.xml from builders_maven to builders of project(root directory),
    copy file pom.xml from builders_maven/admin to builders/admin)

2. Open Windows command line -> select directory with project -> mvn package


    Instruction to build project via Gradle tool:

1. Open directory  tools -> copy files to same directories of project (
for example: copy files build.gradle, settings.gradle  from builders_gradle to builders of project(root directory),
    copy file build.gradle from builders_gradle/admin to builders/admin)

2. Open project builders in IIDEA.

3. Open terminal of IIDEA -> ./gradlew tasks build


    How to run tests:
Maven -> mvn test
Gradle -> ./gradlew test


