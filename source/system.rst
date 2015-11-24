System
======
System Login
------------
To access the application the user  has to login to DHIS2. Copy the link `JPRP <http://41.89.93.242:8080>`_ into the browser URL and click go; the following log in screen appears where the user feeds in their provided username and password. The landing page of the application is the Dashboard.

.. _is_sweaty:
.. figure::  images/sweat.jpg
   :align:   center

   DHIS2 Login

Accessing the JPRP attribution portal app
+++++++++++++++++++++++++++++++++++++++++
Once logged into DHIS2, Click in the main menu Icon and select the attribution portal. This depends on the DHIS2 role allocated to the user .The attribution app inherits the DHIS2 user login and allocated privileges. 

.. note:: One cannot access the app without logging in to the DHIS2

JPRP Functionalities
--------------------
What the user can do on the attribution portal app
++++++++++++++++++++++++++++++++++++++++++++++++++
* Create/delete/update/view  programs. 
* Create/update/view Support  programs  e.g. PEPFAR.
* Create/update/view support agencies.
* Import the Partner IPSL.
* Data pull from the national DHIS2 instance.
* Perform data sharing/attribution.

What the user cannot do using the attribution portal app
++++++++++++++++++++++++++++++++++++++++++++++++++++++++
* Create system users – this is done using the DHIS2 application.
* Create analysis Dimensions – done using DHIS2 application.
* Update users in user groups – done using the DHIS2 application.


User Roles
----------
MOH(Ministry of Health)-Top Level
++++++++++++++++++++++++++++++++++
* Create, Edit and Remove Programs.
* Create, Edit and Remove Development Partners e.g PEPFAR.
* Assign Programs to a Development Partner.
* View a list of the development partners.
* View details of each development partner such as the programs assigned and the agencies supported by the development partner.
* Uploads the IPSL.
* Attributes the data either by mechanism, IPSL or mechanism.

Development Partner Level
+++++++++++++++++++++++++
* Create, Edit and Remove agencies.
* Assign programs to the agencies. (Programs assigned to the development partner).
* View a list of the agencies.
* View details of each agency: the programs assigned to the agency and the Implementing mechanisms the agency is supporting.

Agency Level
+++++++++++++
* Create, Edit and Remove Implementing Mechanism.
* Assign programs to an Implementing mechanism.
* View the list of the Implementing mechanisms.
* View details of each IM: the programs supported and the facilities under the Implementing Mechanism.



