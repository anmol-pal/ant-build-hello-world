# ant-build-hello-world

>ant clean-build
```                              

Buildfile: /Users/anmolpal/projects/ant-build-hello-world/build.xml

clean:

compile:
    [mkdir] Created dir: /Users/anmolpal/projects/ant-build-hello-world/build/classes
    [javac] /Users/anmolpal/projects/ant-build-hello-world/build.xml:19: warning: 'includeantruntime' was not set, defaulting to build.sysclasspath=last; set to false for repeatable builds
    [javac] Compiling 1 source file to /Users/anmolpal/projects/ant-build-hello-world/build/classes

jar:
    [mkdir] Created dir: /Users/anmolpal/projects/ant-build-hello-world/build/jar
      [jar] Building jar: /Users/anmolpal/projects/ant-build-hello-world/build/jar/HelloWorld.jar

clean-build:

BUILD SUCCESSFUL
Total time: 0 seconds
```

>ant run
```     
Buildfile: /Users/anmolpal/projects/ant-build-hello-world/build.xml

compile:
    [javac] /Users/anmolpal/projects/ant-build-hello-world/build.xml:19: warning: 'includeantruntime' was not set, defaulting to build.sysclasspath=last; set to false for repeatable builds

jar:

run:
     [java] Hello World

BUILD SUCCESSFUL
Total time: 0 seconds
```

References:

[1] https://github.com/Silverpop/sample-helloworld-ant

[2] https://ant.apache.org/manual/tutorial-HelloWorldWithAnt.html
