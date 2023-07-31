# Experiment of building Android OS on Github Actions server

Since I don't have a build server and my computer can't build an Android system due to weak specs, as an experiment I decided to try building the system using Workflow and Github Actions.

Results: it doesn't work because Github allocates too little memory and causes a NO SPACE LEFT ON DEVICE error, causing Workflow to stop with an error.

Below is a screenshot of the last failed launch with this error:

![image](https://github.com/difhel/Rising-OSS-oriole/assets/78644136/7e7dae06-2210-465b-9256-c06c71dbdb7f)
