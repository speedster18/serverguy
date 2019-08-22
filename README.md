The code is designed and tested on RHEL7 and CentOS with Network configuration as NAT.
The ansible code is runnning successfully and the output is also copied in the Manual installation file uploaded to github.

STEPS:

1. Run the below command on Git Bash (dekstop) to clone the repository.
*
git pull https://github.com/speedster18/serverguy.git
*
2. Setup a basemachine of RHEL7.
3. Install ansible on the system using command>
*
yum install ansible (assuming the machine is already configured with basic yum)
*
4. Run the the YML file
and

VOILA the system is configured with docker running with specified functionality.


CAUTION:
*
If the ansible playbook fails due to docker pull authentication
then pull the docker images manually first by commands
docker pull athimel/apache2-php5-mysql
*