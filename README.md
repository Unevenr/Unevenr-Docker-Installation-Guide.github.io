I downloaded ubuntu iso on VMWare
I went through installation process
Writing changes to disks

https://www.hostinger.com/tutorials/run-docker-wordpress

Sudo apt update
sudo apt-get install ca-certificates curl gnupg lsb-release
sudo mkdir -p /etc/apt/keyrings

curl -fsSL https://download.docker.com/linux/ubuntu/gpg | sudo gpg --dearmor -o /etc/apt/keyrings/docker.gpg

echo \ "deb [arch=$(dpkg --print-architecture) signed-by=/etc/apt/keyrings/docker.gpg] https://download.docker.com/linux/ubuntu \ $(lsb_release -cs) stable" | sudo tee /etc/apt/sources.list.d/docker.list > /dev/null

sudo apt-get update

sudo apt-get install docker-ce docker-ce-cli containerd.io docker-compose-plugin

sudo docker run hello-world

systemctl start docker
docker compose version
mkdir wordpress
cd wordpress

Sudo docker compose up -d

http://localhost:8000/

Log in, go through setup, then go to dashboard

 

PROOF OF FINISHED PROJECT SCREENSHOTS BELOW:
 
 
