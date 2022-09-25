# Pipeline process :
## orbs : 
- ###  node
- ###  eb 
- ###  aws-eb-cli
- ###  aws-cli

## jobs :
 ### we have to jobs building and then deploying.
 - ### bulid : run scripts to install dependencies and build files to upload it for both api and frontend.
 - ### deploy: run scripts to trigger a shell file which runs the deploy script.
 
## workflows :
### simply we make the doply process runs after the build is done.
