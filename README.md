# What is this application?
This is a multi-container docker application that utilises docker containers to run. Below is the architecture of it's operation: 
<img src="https://res.cloudinary.com/kartik09/image/upload/v1703422611/Multi-container_docker_application_architecture_fof6pn.png" />

<hr/>

# How to run it on your system?
Here are the steps that you need to take in order to run this application on your local machine:
<ol>
  <li>Clone this repository on your local machine whereever you want.</li>
  <li>Install Docker Desktop on your device and run a docker instance using it.</li>
  <li>Once your docker instance is running on your device, open the terminal inside this folder where you have cloned the repository.</li>
  <li>Change the directory to 'multi-container-docker-application' and write the command below to run the application:</li>
  ```docker-compose -f docker-compose-dev.yml up --build```
</ol>
