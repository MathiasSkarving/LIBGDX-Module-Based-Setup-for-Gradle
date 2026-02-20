# GDXModuleSetup

This is a LIBGDX setup project, made to build modules ending with "-mod" directly into a distribution file with all required jar files.

This makes it possible to utilize a URLClassLoader to dynamically custom modules.

## To make it work
1. Make a new module ending with "-mod" ( An example module is already included )
2. Then run the command: ./gradlew lwjgl3:build
3. And look inside the lwjgl3/build/distributions folder. Here you can see the bin folder that contains a .bat file to run your game, and a lib folder that contains all your modules and dependencies.

Easy!!!
