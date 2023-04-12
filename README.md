# suricata-wazuh

yum install epel-release yum-plugin-copr
yum copr enable @oisf/suricata-6.0
yum install suricata

sudo yum -y install epel-release
sudo yum -y install suricata

sudo yum install python-yaml
sudo yum install curl

sudo suricata-update

OPTIONS="-i eth0 --user suricata "

sudo systemctl enable suricata
sudo systemctl start suricata
