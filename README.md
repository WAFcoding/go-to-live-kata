Go to live! kata
==================================

Contained in this repo, there are some instructions for a new application that will go live in the next month!

You will need to:

1. Fork this repository.

2. Automate the creation of the infrastructure and the setup of the application.

   You have only these instructions:

   2.1 It works on Ubuntu Linux 14.04 x64

   2.2 It's based on the last version of WordPress (it will be more useful if we can parameterize the version)

   2.3 You can choose Apache, Nginx or whatever you want

   For any other issues or question you will have to ask to the developers. In this case please ask us without problems :)

3. Once deployed, the application should be secure, fast and stable. Assume that the machine is running on the public Internet and should be hardened and locked down.

4. Make any assumptions that you need to. This is an opportunity to showcase your skills, so if you want to, implement the deployment process with any additional features, tools or techniques you'd like to.

5. We are evaluating solutions based on the architecture and quality of the deployment. Show us just how beautiful, clean and pragmatic your code can be.

6. Once your solution is ready, please send us the link of your project.

### Prerequisites
Ubuntu 14.04 has to be running and it comes with docker and docker-compose installed.

To install docker visit https://docs.docker.com/engine/installation/linux/ubuntu/#recommended-extra-packages-for-trusty-1404

To install docker-compose visit https://docs.docker.com/compose/install/

### How it works

1. Move in your working directory
```
mv some/directory/
```
2. Download the start.sh file and the docker-compose.yml file

3. Run start.sh
```
sh start.sh
```
4. Go to http://127.0.0.3:8080 and type the blog name and user details

