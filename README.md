## Hello World Java

This is a demo hello world with development environment setup instructions!  

To run the code, first it needs to be compiled with the java development kit, and finally the end user needs to execute the code with the java runtime environment.  

## Development

### Writing Code

The src/hello/HelloWorld.java file contains the source code.  You can edit it with any text editor with nice highlighting.  Eclipse is popular in the java development world, but so is jet brain and netbean.  Java is a type heavy language, so vim isn't as handy with java as it is in other areas without installing plugins to automate some of the verbosity needed. As such, this repo is text editor agnostic.  

### Compiling Code

To compile the code, you should install and use the [apache ant](http://www.tutorialspoint.com/ant/ant_environment.htm) build tool.  And you also need the [java development kit](http://ubuntuhandbook.org/index.php/2015/01/install-openjdk-8-ubuntu-14-04-12-04-lts/) version 8 at least (for javaFX which is the new java I guess).  
For Ubuntu/ Linux Mint, that's easily done as...
```
$  sudo add-apt-repository ppa:openjdk-r/ppa
$  sudo apt-get update
$  sudo apt-get install ant openjdk-8-jdk

$  sudo update-alternatives --config java
$  sudo update-alternatives --config javac
```

For ant to be able to build your project, you need to tweak the build.xml file so everything is pointing to the right thing.  

When you have a satisfactory build.xml file, you can invoke the complete build process with the command

    $  ant build-jar

### Decompiling Analysing Code

Because java is a compiled language, it's compiled output needs to be investigating.  To do this run the below command:

```
$ TODO
```
