# esphome
[net stop winnat]

docker volume create --driver local --opt type=nfs --opt device=${pwd}/esphome --opt o=bind,rw esphome
docker run -d --name="esphome" --net=host -p 6052:6052 -p 6123:6123 -e TZ=Asia/Bangkok -v esphome:/config -it esphome/esphome
