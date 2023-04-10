# DevOps-Project


CI/CD PIPELINE USING GIT, JENKINS, MAVEN

Step 1: Setup Jenkins Server
The first step in setting up a CI/CD pipeline with Jenkins is to set up a Jenkins server. You can do this by downloading the Jenkins installer from the official website (https://www.jenkins.io/download/) and installing it on your local machine or a server.

Step 2: Run 1st Jenkins Job
Once you have installed Jenkins, the next step is to create your first Jenkins job. You can do this by logging in to the Jenkins web console, clicking on the "New Item" button, and selecting "Freestyle project". From there, you can configure your job to execute any build script or command. 

Step 3: Integrate Git with Jenkins
To integrate Git with Jenkins, you will need to install the Git plugin on your Jenkins server. You can do this by navigating to the "Manage Jenkins" page, clicking on "Manage Plugins", and searching for the Git plugin. Once you have installed the plugin, you will need to configure Jenkins to connect to your Git repository.

Step 4: Run Jenkins Job to Pull Code from GitHub
With Git integrated into Jenkins, you can now create a Jenkins job that pulls code from your Git repository. To do this, create a new Jenkins job and configure it to pull code from your repository. You will need to provide Jenkins with your Git repository URL, authentication credentials (if required), and any other necessary configuration settings.

