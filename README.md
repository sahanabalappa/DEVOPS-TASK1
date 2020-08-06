# DEVOPS-TASK1


JOB#1
If Developer push to dev branch then Jenkins will fetch from dev and deploy on dev-docker environment.

JOB#2
If Developer push to master branch then Jenkins will fetch from master and deploy on master-docker environment.
both dev-docker and master-docker environment are on different docker containers.

JOB#3
Manually the QA team will check (test) for the website running in dev-docker environment. If it is running fine then Jenkins will merge the dev branch to master branch and trigger #job 2

### Pre-requisite :
  * OS: Base OS is Windows 10. Server OS is RedHat Enterprise Linux 8 (RHEL8) in Virtual Box.
  * In RHEL8 some of the softwares needed are Docker (also need the httpd image downloaded in it), Jenkins (also github plugin should be installed in it), ngrok program.
  * In Windows we need git bash software.
  * At the starting stop the firewalld in RHEL8 and start the docker and jenkins services.
  
  ## steps to achieve the task:
  
### 1. Giving Jenkins all the power of Linux :
jenkins ALL=(ALL) NOPASSWD:ALL

### 2. Creating the git repository :
	 * Creating a git repository with 2 branches one for master and another for developer

### 3. Creating the Production Job in Jenkins :

https://github.com/sahanabalappa/DEVOPS-TASK1/blob/master/Production_execute_shell_code

### 4. Creating the Production Deployment Job in Jenkins :







