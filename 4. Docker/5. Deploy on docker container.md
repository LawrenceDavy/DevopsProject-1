Create a new jenkins job where we will connect our jenkins server to our docker server, so we can transfer the an updated version of our project .war file to docker when the jenkins build executes.
<br>
<img src="https://github.com/LawrenceDavy13/DevopsProject-1-Java/blob/main/images/docker/dockercontainer1.png">
<br>
<img src="https://github.com/LawrenceDavy13/DevopsProject-1-Java/blob/main/images/docker/dockercontainer2.png">
<br>
<br>
Use a existing build we created earlier to keep some our the settings
<br>
<img src="https://github.com/LawrenceDavy13/DevopsProject-1-Java/blob/main/images/docker/dockercontainer3.png">
<br>
<img src="https://github.com/LawrenceDavy13/DevopsProject-1-Java/blob/main/images/docker/dockercontainer4.png">
<br>
<img src="https://github.com/LawrenceDavy13/DevopsProject-1-Java/blob/main/images/docker/dockercontainer5.png">
<br>
<br>
In post build actions, add the location of the project file from the jenkins server to the source file and set the location of where the project will end up in the docker server in the remote directory section.
<br>
<img src="https://github.com/LawrenceDavy13/DevopsProject-1-Java/blob/main/images/docker/dockercontainer6.png">
<br>
<hr>
Build the job and see if the artifact gets tranferred over.
<img src="https://github.com/LawrenceDavy13/DevopsProject-1-Java/blob/main/images/docker/dockercontainer7.png">
<br>
<img src="https://github.com/LawrenceDavy13/DevopsProject-1-Java/blob/main/images/docker/dockercontainer8.png">
<br>
<img src="https://github.com/LawrenceDavy13/DevopsProject-1-Java/blob/main/images/docker/dockercontainer9.png">
<br>
<img src="https://github.com/LawrenceDavy13/DevopsProject-1-Java/blob/main/images/docker/dockercontainer10.png">




