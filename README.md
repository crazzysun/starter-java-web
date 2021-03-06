starter-java-web
================

This Starter Kit provides the basic building blocks for deploying, updating and scaling Java-based applications on Qubell Platform, and can be used as a starting point for your own automation project.

Version 1.1-37p
-------------

[![Install](https://raw.github.com/qubell-bazaar/component-skeleton/master/img/install.png)](http://localhost:9000/applications/upload?metadataUrl=https://raw.githubusercontent.com/crazzysun/starter-java-web/master/meta.yml)


2-Hierarhical app
-----------------

[![Install](https://raw.github.com/qubell-bazaar/component-skeleton/master/img/install.png)](http://localhost:9000/applications/upload?metadataUrl=https://raw.githubusercontent.com/crazzysun/starter-java-web/master/meta_for_parent_childs.yml)

3-Hierarhical app
-----------------

[![Install](https://raw.github.com/qubell-bazaar/component-skeleton/master/img/install.png)](http://localhost:9000/applications/upload?metadataUrl=https://raw.githubusercontent.com/crazzysun/starter-java-web/master/meta_for_parent_parent_child.yml)

Features
--------

 - Launching a new sandbox instance of a web application
 - Updating an existing live application to a new version of the source code and/or database schema
 - Scaling the web tier up and down

Configurations
--------------
 - [Tomcat 5](https://github.com/qubell-bazaar/component-tomcat-dev), [MySQL 5](https://github.com/qubell-bazaar/component-mysql-dev), [HAProxy 1.4](https://github.com/qubell-bazaar/component-haproxy), CentOS 6.4 (us-east-1/ami-eb6b0182), AWS EC2 m1.small, root

Pre-requisites only for Version 1.1-37p
---------------------------------------
 - Configured Cloud Account a in chosen environment
 - Either installed Chef on target compute OR launch under root
 - All pre-requisites from the components above
