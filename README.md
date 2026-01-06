# ubuntu-nginx-web-server
Connected securely to Ubuntu EC2 using SSH key pair authentication, created firewall and user
sudo apt update
sudo apt upgrade -y
sudo apt install nginx -y
sudo systemctl start nginx
sudo systemctl enable nginx
systemctl status nginx

sudo ufw status
sudo ufw allow open ssh
sudo ufw allow 'nginx HTTP'
sudo ufw enable

sudo adduser devuser

