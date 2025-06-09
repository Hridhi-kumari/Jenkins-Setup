# Jenkins-Setup
This guide provides step-by-step instructions to install and configure Jenkins, an open-source automation server commonly used for continuous integration and continuous delivery (CI/CD) pipelines.
## STEPS
* **SSH** into your VM.
*  Create a file name **jenkins.sh**.
   * ```sudo nano jenkins.sh```
* Paste the script code and then click **Ctrl+X**, **Y** and then **Enter**.
* Now give execute permission to **jenkins.sh**.
   * ```sudo chmod +x jenkins.sh ```
*  Run **jenkins.sh**
   * ```sudo ./jenkins.sh```
* To access the jenkins web interface open your browser and navigate to:
   * ```http://<your-server-ip>:8080```
* To unlock jenkins and retrieve the initial jenkins password:
   * ```sudo cat /var/lib/jenkins/secrets/initialAdminPassword```
* Now create admin user after that you **Jenkins** is ready.
