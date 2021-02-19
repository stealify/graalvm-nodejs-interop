# graalvm-nodejs-interop
Examples and Methods to Demonstrate ways to use ECMAScript in a GraalVM Project as Also ways to use GraalVM inside NodeJS Projects.
we will refer NodeJS as nodejs-v8 and node-graal to make sure which NodeJS we are talking about 

## List of Methods
- from graalvm (Java)
  - JNI Call libnode.so
  - graalvm ECMAScript Context with NodeJS Pollyfils like @stealify/graalvm-nodejs-context
  - use es4x which is a bit like graalvm-nodejs-context but at present more complet
- from NodeJS-graal
  - Write a ECMAScript app and Run it Inside node-graal with --jvm option
- from NodeJS-v8
  - call GraalVM
    - https://github.com/joeferner/node-java
    - https://github.com/stealify/node-java
    - https://github.com/joeferner/node-java-maven used to manage maven dependencys with NodeJS-v8



## TODO Archive and consolidate
- https://github.com/direktspeed/jnjs
- https://github.com/stealify/nodejs-jvm
- https://github.com/direktspeed/jnjs/issues/3 
  - graalvm-node
  - node-graalvm
  - graaljs*
  - node-java (done?!)
  - java-node
