# INSTALL CLOUDPANEL ON DEBIAN 11

Before running the installer, we need to update the system and install the required packages
```bash
apt update && apt -y upgrade && apt -y install curl wget sudo
```



I'm using Debian 11 LTS and MariaDB 10.11 

```bash
curl -sS https://raw.githubusercontent.com/iseeyoucopy/cloudpanel/main/install.sh -o install.sh;
sudo DB_ENGINE=MARIADB_10.11 bash install.sh.sh

```

