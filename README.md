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


TEMPLATES I USED:
 ![image](https://github.com/Unevenr/Unevenr-Docker-Installation-Guide.github.io/assets/112726183/8ef9a80f-84c4-41b0-9d14-0fa45434458f)

 ![image](https://github.com/Unevenr/Unevenr-Docker-Installation-Guide.github.io/assets/112726183/cf9cd769-7784-4377-a171-7944710b5c4e)

 

PROOF OF FINISHED PROJECT SCREENSHOTS BELOW:
 ![image](https://github.com/Unevenr/Unevenr-Docker-Installation-Guide.github.io/assets/112726183/a1e8713f-af94-4cb1-bc58-4175fb1a6b91)

 ![image](https://github.com/Unevenr/Unevenr-Docker-Installation-Guide.github.io/assets/112726183/4b5efd86-adeb-4dc9-b805-e8d7041efeb4)

