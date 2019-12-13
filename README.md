# guest-user-access
Project used for guest user access demos. 
This project contains the application, process, organization and guest user profile.

----
Import your archive.bos in Bonita Studio. 
Before deploying the application, you have to modify the configuration file authenticationManager-config.properties (as indicated in guest user access documentation page) with the help of the setup tool:
auth.tenant.guest.active=true
auth.tenant.guest.username=guest
auth.tenant.guest.password=guest
auth.tenant.guest.apps=[public,guest]
