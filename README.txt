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

Statuscake allows to submit a time, which is shown in the detailed test information charts. The module automatically measures the cron run time, and sends this to statuscake.


NSTALLATION
------------
 * Install as you would normally install a contributed Drupal module. See:
   https://drupal.org/documentation/install/modules-themes/modules-7
   for further information.


CONFIGURATION
-------------
 * Customize user permissions to edit the URL in Administration » People »
   Permissions.

 * Customize settings in Administration » Configuration »
   Web services » Statuscake. 

 * Create a new push test at statuscake.com

 * Insert the whole URL you received from statuscake.com, including both http:// and time=0.


LINK REFERENCES
---------------
https://www.statuscake.com/