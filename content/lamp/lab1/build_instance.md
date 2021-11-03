+++
title = "1.1 - Build the LAMP instance"
weight = 10
+++

The first step in deploying the sample application is creating a LAMP stack instance in Lightsail. 

* From the <a href="https://lightsail.aws.amazon.com/ls/webapp/home/" target="_blank">Lightsail console home page</a> click ***Create Instance***

    ![](../../images/1-1-1.jpg?classes=border)

* Choose the region for your instance. Under ***Instance Location*** click ***Change AWS Region and Availability Zone*** and select the appropriate region. 

    ![](../../images/region.jpg?classes=border)

{{% notice tip %}}
Be sure to create all the resources for this workshop in the same region
{{% /notice %}}

* Make sure that ***Linux/Unix*** is selected under ***Select a platform***, and then under ***Blueprint*** choose ***LAMP (PHP5)***
    
    ![](../../images/lamp-blueprint.jpg?classes=border)


* Name the instance ***PHP-fe-1***

    ![](../../images/lamp-name.jpg?classes=border)

* Click ***Create instance***

    ![](../../images/lamp-create.jpg?classes=border)

* Once the instance shows a state of running in the Lightsail console, SSH into it either using the built in SSH client or using your own (username: ***bitnami***). If you are unfamiliar with SSH please review <a href="../../prerequisites.html" target="_blank">the SSH primer</a>. 

     ![](../../images/lamp-running.jpg?classes=border)

{{% notice tip %}} 
Even though the instance shows a state of running, it may still be executing the startup script, and you won't be able to connect. If this is the case, give it a couple of minutes and try again.
{{% /notice %}}
