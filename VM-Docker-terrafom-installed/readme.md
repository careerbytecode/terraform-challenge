once terraform apply is completed, wait for few min and log into server. 
once logged in continue as root user and run below command to ensure custom data execution is completed.

cat /var/log/docker_install_status.log

you should see : "DOCKER & TERRAFORM INSTALLATION COMPLETE" 

once done, run : docker --version , terraform --version
to see docker and terraform version.

if you see this, docker is installed and you can continue with your activities.