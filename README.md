# OWA-honeypot
A basic flask based Outlook Web Honey pot

![](docs/OWA_honeypot_1.png)

## Why?
Most corps have some form of OWA and I couldn't find an out of the box OWA only honeypot (I'm sure if I spent more than 2 minutes googling I probably would have found one) and I wanted to mess around with some ideas I have. So I spent some time putting this together, maybe it could help someone else :)

## Requirements
python3 + flask

## How to install
git clone https://github.com/joda32/owa-honeypot.git
cd owa-honeypot
python3 -m venv env
source env/bin/activate
pip install -r requirements.txt

## Running in HTTPS 
I have this currently running behind an NGINX proxy serving HTTPS with Lets Encrypt. Setup instructions / examples can be found here https://www.digitalocean.com/community/tutorials/how-to-serve-flask-applications-with-uswgi-and-nginx-on-ubuntu-18-04 

python owa_pot.py



![](docs/OWA_honeypot_2.png)
![](docs/OWA_honeypot_3.png)
