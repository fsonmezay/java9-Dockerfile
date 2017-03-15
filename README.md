# java9-Dockerfile

```bash 

sudo docker build -t mydockerjava9 .

# run docker image
sudo docker run -it --rm mydockerjava9 
mkdir /var/mountfolder 

# exit docker image
exit

# mount Desktop to folder /var/mountfolder which is in docker
sudo docker run -v /home/ferdi/Desktop:/var/mountfolder -it --rm mydockerjava9

```
