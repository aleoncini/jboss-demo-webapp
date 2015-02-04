This project lets you build a war file with dynamic version and context without changing source code.

What you need
==

* A jdk 1.7+

* mavevn 3+ 

Get the source
==

`git clone git@github.com:eljeko/jboss-demo-webapp.git`

How to build
==

When you build the app you can change the *appversion* and *contextname* eg:

`mvn clean package -Dappversion=1.2.3 -Dcontextname=mycontextapp`
 
The resulting war file can be deployed into an eap6/jboss7
 
