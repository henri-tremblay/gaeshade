Spring with Objenesis shading for GAE
===================================================

This application showcase how to shadow `SpringObjenesis` in Spring with a custom implementation using latest `Objenesis`. It can be used
to deploy your application on Google App Engine Java 8 platform if you haven't migrate to Spring 
 
**Important:** This is not a permanent solution. It is an ugly workaround. Spring will be [fixed](https://jira.spring.io/browse/SPR-15600) 
in version 4.3.10.

Interesting code is `src/java/org/springframework/objenesis/SpringObjenesis.java`.

Try locally
----------

`mvn appengine:run`
