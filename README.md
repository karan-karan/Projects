# Projects
deploy_Web_service_on_kubernetes



![pipiline](https://github.com/karan-karan/Projects1/assets/88554113/e80711b8-42d2-4dc5-96d3-1430209d7d05)




Created a pipeline which automatically trigerred when the new code gets comitted, after the code gets commited CI pipelie gets triggered which create the image and upload the image on DockerHub.




After CI pipeline successfully executed then it will trigger the CD pipeline which take image from dockerhub and deploy the containers on kubernetes PODs.
