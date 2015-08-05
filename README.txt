CONTENTS OF THIS FILE
---------------------

 * Introduction
 * Installation 
 * Configuration
 * Link references


INTRODUCTION
------------

Implementing Statuscake push monitoring services.

Push monitoring is a service where Drupal is pinging statuscake. If statuscake is not gettting pings for a timeframe, you will get alerted.

To set the service up you need an account at stauscake.com. 

You have to insert this URL in the Statuscake module setting page.


NSTALLATION
------------
 * Install as you would normally install a contributed Drupal module. See:
   https://drupal.org/documentation/install/modules-themes/modules-7
   for further information.


CONFIGURATION
-------------
 * Customize settings in Administration » Configuration »
   Web services » Statuscake. 

 * Insert the URL you get from statuscake.com after you have created your new push test. 

 * Insert the whole URL you received from statuscake.com, including both http:// and time=0.


LINK REFERENCES
---------------
https://www.statuscake.com/