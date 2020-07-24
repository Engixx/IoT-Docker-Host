
# IoT-Docker-Host
Automated Builds docker host for IoT purposes (MQTT brocker, PostgreSQL, Gateway MQTT to PostgreSQL, etc.)

# Prerequest
- create a Ubuntu EC2 Instance on AWS. Obtain the static IP adress.
- install the docker engine on Ubuntu:
-- sudo apt update
-- sudo apt install apt-transport-https
-- curl -fsSL https://download.docker.com/linux/ubuntu/gpg | sudo apt-key add -
-- sudo add-apt-repository "deb [arch=amd64] https://download.docker.com/linux/ubuntu $(lsb_release -cs) stable"
-- sudo apt update
-- sudo apt install docker-ce
-- sudo systemctl status docker
-- sudo usermod -aG docker $USER
