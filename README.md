# esphome
#[net stop winnat]

#docker volume create --driver local --opt type=nfs --opt device=${pwd}/esphome --opt o=bind,rw esphome </br>
#docker run -d --name="esphome" --net=host -p 6052:6052 -p 6123:6123 -e TZ=Asia/Bangkok -v esphome:/config -it esphome/esphome
#docker run -d --name="esphome2" --net=host -p 8123:8123 -e TZ=Asia/Bangkok -v ///d/DockerLAB/esphome:/config esphome/esphome
