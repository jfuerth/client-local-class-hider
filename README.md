client-local-class-hider
========================

A Java agent that hides the true definition of classes whose names match an
arbitrary regular expression.

To use this agent in JBoss AS7, add the following to the end of standalone.conf:

    JAVA_OPTS="$JAVA_OPTS -javaagent:/path/to/client-local-class-hider-1.0-SNAPSHOT.jar"

There are some options available; see the source code for details.
