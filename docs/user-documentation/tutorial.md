## Tutorial Hands on: run a Gaussian16 computational experiment in the Django portal


1. Log into <a href="https://testdrive.airavata.org/" target="_blank">TestDrive Portal</a>
<br></br>
2. First, you'll need a user account. <a href="https://testdrive.airavata.org/auth/login" target="_blank">Create an account</a> using your existing institutional login through CILogon. 
<br></br>
3. After you've logged in, an administrator can grant you access to run the Gaussian16 application. 
<br></br>
4. During the tutorial we'll grant you access right away and let you know. 
<br></br>
5. When you log in for the first time you will see a list of applications that are available in this science gateway. Applications that you are not able to run are greyed out but the other ones you can run. 
<br></br>
6. Once you are granted access, refresh the page and you should now see that you the Gaussian16 application is not greyed out.
<br></br>

#####Submit a Test Job
1. From the dashboard, click on the Gaussian16 application. The page title is "Create a New Experiment".
<br></br>
2. Here you can change the Experiment Name, add a description or select a different project if you have multiple projects.
<br></br>
3. We'll focus on the Application Inputs for this hands-on. The Gaussian16 application requires one input, an Input-File. 
<br></br>
4. The following is a preconfigured Gaussian input file. Download this to your local computer and then click the Browse button to upload the file:
<br></br>
       [npentane12diol.inp](../img/npentane12diol.inp)
<br></br>
5. You can click on the file to take a quick look at the file in a popup window.
<br></br>
6. Now we'll select what account to charge and where to run this job. Use "Resource Reservation for Tutorials" allocation for the job. Under Compute Resource make sure you select Expanse.
<br></br>
7. Then click Save and Launch.
<br></br>
8. You should then be taken to the "Experiment Summary" page which will update as the job progresses. 
<br></br>
9. When the job finishes you'll be able to download the .log file which is the primary output file of the gaussian application.
<br></br>
10. We'll come back to this experiment later in the tutorial.

#####More Details On...
1. <a href="/user-documentation/account-creation" target="_blank">Portal Account Creation</a>
2.  <a href="/user-documentation/create-experiment-launch-job" target="_blank">Submit Job</a>