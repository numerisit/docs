# Local Environment Setup

## Install Java

### Download JDK 1.8 from http://www.oracle.com/technetwork/java/javase/downloads/jdk8-downloads-2133151.html
You will see a list of below distributions, choose Accept license Agreement and click the windows X64 version

### Run the jdk-8U151-windows-X64.exe to install the jdk

### Open system variable environments to add JAVA_HOME if it’s not already there. The typical value is C:\Program Files\Java\jdk1.8.0_151. For my local, I copied the C:\Program Files\Java\jdk1.8.0_151 folder to the c:\ jdk1.8.0_151, so below is the screen shot from my local

## Install IntelliJ

### Go to https://www.jetbrains.com/idea/download/#section=windows download the .exe version

### Open IntelliJ, go to File=> Settings, click the Install JetBrains plugin

### From the pop-up window, type scala, you will see a screen like below, click the highlighted “Install” button(my screen is “update” because I installed it already)

### Dowload https://downloads.lightbend.com/scala/2.12.4/scala-2.12.4.msi and install it.

### Make sure the system environment has been set

#### SCALA_HOME

#### PATH

### Install Winutils

#### Download winutils https://github.com/steveloughran/winutils

#### Upzip the file, and locate the local folder for Hadoop-2.7.1 as highlighted above

#### Add  HADOOP_HOME system environment variable, the result should look like      below except it’s Hadoop-2.7.1 for you instead of Hadoop-2.7.4 on this screen shot

#### Modify Path to include %HADOOP_HOME%/bin

## Install Spark

### Go to https://spark.apache.org/downloads.html select pre-built for hadoop 2.7, and download

### Unzip the file with 7Zip

### Modify Path to include Spark\bin folder

### Install Git  from https://git-scm.com/downloads, choose windows

## Get Source Code.
