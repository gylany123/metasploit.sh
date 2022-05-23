# metasploit.sh
apt update && apt upgrade -y
apt  install wget curl wget git -y

curl -LO https://raw.githubusercontent.com/Hax4us/Metasploit_termux/master/metasploit.sh

chmod +x metasploit.sh

./metasploit.sh
