# Simple Node App configured for Oracle Cloud
An Introduction to running a Simple Node.JS application on Oracle Cloud (ACCS)

This repository provides code sample to run Node.JS application (v6) in a Docker Container on Oracle Cloud Platform.

Steps:

1. Clone this repository / Download as zip 

2. Feel free to make changes to app.js file, it is currently create a simple HTTP server and listening on port 8080. The manifest.json file has templatized configuration to run on Oracle Cloud. 

3. Run the code locally to confirm first. In terminal window type "node MyServer.js" to start the execution. Open a new tab and type "curl localhost:8080" and you should see the ouput "Hello World from Oracle Cloud!". Alternatively you can confirm on the browser at localhost:8080. If you do not see the output, something has gone wrong and try to resolve the errors before moving on to the following steps.

2. Zip the two files namely app.js and manifest.json and name ziped file "hello-node-accs.zip".

Oracle Cloud Steps:

1. Log in / Sign up for Oracle Cloud (free trial) at http://cloud.oracle.com/. Enter your account credentials in the Identity Domain, User Name, and Password fields.

2. In the Oracle My Services dashboard, click the Action (Hamburger menu icon) Menu, and select Oracle Application Container Cloud Service. Note that newer accounts may not have "Application Container Cloud Service" listed, therefore you can't use this tutorial untill further notice.

3. To open the Oracle Application Container Cloud Service console, click Services.

4. In the Applications list view, click 'Create Application' and select 'Node' for your runtime framework.

5. In the Application section, enter a name for your application and click Browse.

6. On the File Upload dialog box, select the 'hello-node-accs.zip' file you created in the previous section and click Open.

7. Keep the default values in the Instances and Memory fields and click Create.

8. Wait until the application is created. The URL is enabled when the creation is completed.

9. Click the URL of your application to see the Server response in your browser window as ""Hello World from Oracle Cloud!".

Congratulatoins you are running Node.JS app on Oracle Cloud now and you can make edits to your code, re-deploy the zipped file and continue to run it on the cloud.
