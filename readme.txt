this docker container is based on owncloud image.

 to install the container :-
   1.go to the folder in which you download. 
   2.open the terminal and hit "docker-compose up".
   3.go to the host os. open the browser and hit "172.18.0.3"(as default) or check IP of owncloud.
   4.click on storage & database. select MySQL and enter the username, password, databasename , hostname.(you can also see in docker-compose.yml file)
   
  done you owncloude in ready to use.

note:- make sure you have docker and docker-compose in install. 
firewalld is running. when you lunch docker-compose up and then stop the firewalld.
the update.
  
  IF you are host OS is in virtual box then check OS ip. in the plase of 172.18.0.3 -> "IP of OS":8080.
