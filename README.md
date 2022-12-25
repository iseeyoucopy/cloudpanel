Before running the installer, we need to update the system and install the required packages

apt update && apt -y upgrade && apt -y install curl wget sudo


Debian 11 LTS and MariaDB 10.11 

curl -sS https://raw.githubusercontent.com/iseeyoucopy/cloudpanel/main/install.sh -o install.sh;
sudo DB_ENGINE=MARIADB_10.11 bash install.sh.sh
