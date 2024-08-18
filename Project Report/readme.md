**CAPSTONE PROJECT**

In this project we are deploying a react application. First, we are cloning the react application. Then we are writing the Docker and docker compose, then we write the build and deploy shell scripts. Build.sh is used to build and push the docker image to the respective docker hub repository. Deploy.sh file would pull the docker images from the respective docker hub according to the commit history.

Through Jenkins we would automate the CI/CD pipeline using GitHub webhook Jenkins would automatically build according to the recent commit history.

The security group of the project is configured such a way that only the application could be viewed by anyone with the IP-address, other services and login to the machine could be done only with my ip-address.


**Deployed Ip-Address:** http://15.207.98.144:80

**GitHub Url: https:**//github.com/cyril-doss14/Capstone-Project.git
