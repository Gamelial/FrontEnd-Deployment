**FrontEnd-Deployment**

React-Django-App
Virtual Machine for Frontend

sudo apt update

Clone the Project

1.Install Pip and Python Virtual Environment Package
bash sudo apt install python3-pip python3-virtualenv -y

2.Create and Activate Virtual Environment
bash python3 -m virtualenv venv source venv/bin/activate

3.Clone the Project
bash git clone https://github.com/Gamelial/React-Django-App.git cd React-Django-App

ls cd ComputexFrontend

Next Step FRONTEND APP ls cd ComputexFrontend ls cd src ls cd components ls cd api ls nano auth.ts

THE BACKEND IP ADDRESS :8000"; GO TO Frontend Computer sudo apt install nginx -y sudo apt update curl -sL
https://deb.nodesource.com/setup_18.x | sudo bash - sudo apt install nodejs -y npm install npm run build ls to see if u see disk sudo cp -r dist/* /var/www/html sudo systemctl restart nginx

RUN THE BACK END gunicorn --bind 0.0.0.0:8000 Computex.wsgi:application

THEN GO TO THE PAGE

Verify Deployment

Open a web browser and navigate to your server’s IP address or domain name. Your React site should now be live and accessible

GO TO AZURE PORTAL TO OPEN THE INBOUND RULES AND OUTBOUND RULES 

**Add IP address of frontend**

on the backend port inbound Add the densitnation port 8000 Add IP address of backend on the frontend port inbound
Add the densitnation port 8000 Add port 443 Add Port 22 Add Port 80 Add port 8080 Add port 8000 Add
Port 8000 with the Frontend IP Address
