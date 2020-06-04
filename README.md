1. Follow on https://github.com/streamsets/datacollector/blob/master/BUILD.md to setup the environment
This includes: 

git clone http://github.com/streamsets/datacollector
mvn clean install -DskipTests
This is not mandatory (git clone http://github.com/streamsets/datacollector-api)
This is not mandatory (git clone http://github.com/streamsets/datacollector-plugin-api)


2. Import a new project from source into IntelliJ from datacollector/kinesis-lib
3. Replace in destination.kinesis KinesisTarget.java
4. Replace in lib/kinesis KinesisUtil.java
5. Build package 'mvn package' and this will create the jar in target/
