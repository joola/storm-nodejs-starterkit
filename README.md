Storm-Node.js Starter Kit
=========================

Starter Kit for Storm and Node.js projects. Tested with

# Prerequisites

1. Maven 3. On Ubuntu install it with:

    ```
    $ sudo apt-get install maven
    ```

2. Node.js

3. If you want to submit your topologies to real Storm cluster, you need to deploy Storm and add `bin` folder of Storm to
your PATH variable.

# Project structure

| Folder                | Description                   |
| --------------------- |-------------------------------|
| multilang/resources   | JavaScript files (Node.js)    |
| src/main/java         | Java files                    |


# Run topology locally

    $ cd storm-nodejs-starterkit
    $ bin/run-test-topology.sh

# Submit topology to the cluster

    $ cd storm-nodejs-starterkit
    $ bin/submit-test-topology.sh

# Open project with Intellij IDEA

"File" -> "Open Project" and browse to "pom.xml" file.

# Run topology withing Intellij IDEA

Open topology java file (i.e. src/main/java/**/TestTopology.java), right-click in the editor and select
"Run TestTopology.main()" (Ctrl-Shift-F10)
