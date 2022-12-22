pt update && apt upgrade -y

apt install curl -y

bash <(curl -Ls https://raw.githubusercontent.com/thcweb/drthcxray/main/install.sh)

sudo apt install software-properties-common
sudo add-apt-repository ppa:certbot/certbot
sudo apt-get install certbot
sudo certbot certonly --standalone --preferred-challenges http --agree-tos --email (email) -d (domain) 
