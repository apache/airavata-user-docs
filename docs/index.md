# Django Portal General User Documentation

###Airavata Middleware
- A distributed framework that supports execution and management of computational scientific applications and workflows in grid based systems, remote clusters and cloud based systems.
- Primarily focused on submitting and managing application executions and workflows in grid based systems.
- Architecturally extensible to support other underlying resources.<!-- Used by scientific gateway developers as their middleware layer. They can directly call Airavata API in order to communicate with grid based system.-->
- Provides a desktop tools and browser-based web interface components for managing applications, workflows and generated data.
- Contains sophisticated server-side tools for registering and managing scientific applications on computational resources.

### Django Portal
- The Django portal, the 'Science Gateway' provides tools and methods to easily integrate with post processing applications and application centric interfaces.
- Django portal is the users interface to use services available through Apache Airavata Middleware. 
- Django portal mainly has 3 user groups; General User, Read-only- admin user and Admin user
- This documentation provides step by step instructions on functionality available for general users.



More information on <a href="https://airavata.apache.org/" target="_blank">Apache Airavata</a><br>
More information on <a href="https://apache-airavata-django-portal.readthedocs.io/en/latest/" target="_blank">Django Portal</a>
<br>
<br>

<button type="button" style="color:#f2f2f2;text-align:center;font-weight:lighter;background-color:#2481b9;width:220px;border: 2px solid #2481b9;border-radius:4px"><a style="color:white" href="user-documentation/quick-start" target="_blank" ><br/><br/><b>General User Quick Start</b><br/></br></br></a></button>&nbsp; &nbsp; &nbsp;
<button type="button" style="color:#f2f2f2;text-align:center;font-weight:lighter;background-color:#2481b9;width:220px;border: 2px solid #2481b9;border-radius:4px"><a style="color:white" href="user-documentation/account-creation" target="_blank" ><br/><br/><b>Portal Account Creation</b><br/></br></br></a></button>&nbsp; &nbsp; &nbsp;
<button type="button" style="color:#f2f2f2;text-align:center;font-weight:lighter;background-color:#2481b9;width:220px;border: 2px solid #2481b9;border-radius:4px"><a style="color:white" href="installation/EMC-Instructions" target="_blank"><br/><br/><b>Launch Jobs on HPCs</b><br/></br><br/></a></button>&nbsp; &nbsp; &nbsp;
<button type="button" style="color:#f2f2f2;text-align:center;font-weight:lighter;background-color:#2481b9;width:220px;border: 2px solid #2481b9;border-radius:4px"><a style="color:white" href="user-documentation/Custos-Instructions" target="_blank" ><br/><br/><b>Other Features</b><br/><br></br></a></button>&nbsp; &nbsp;

<!--<button type="button" style="color:#f2f2f2;text-align:center;font-weight:lighter;background-color:#2481b9;width:220px;border: 2px solid #2481b9;border-radius:4px"><a style="color:white" href="http://airavata.readthedocs.io/en/latest/ target="_blank"><b>User Guide</b></br><br>In-detail documentation on how to install, configure and do upgrades for gateway admins.</br>Step by step guide for gateway users as well.</br></a></button>-->
<br></br>

<!--The Installation section of the documentation applies to on-premise installation of Apache Airavata. -->

###Django Releases
####2023
#####<h5 id="#February">February</h5>
1. The central 'Shared' data directory for the gateway

More [Details](user-documentation/other-features/#centraldata)
