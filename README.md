# linux_server_configration
IP & SSH Port:
IP : 146.148.49.116
ssh:2200
Hosted Web Application:
http://146.148.49.116/
Software

I installed ubuntu trusty.

Configuration firwall

sudo ufw deny incoming sudo ufw allow outgoing sudo ufw allow 2200/tcp sudo ufw allow www sudo ufw allow ntp sudo ufw enable

Configuration grader

grader user take sudo permession setup permitrootlogin no setup passwordauthontication no create .ssh directory and chmod 700 for it create authonticated_keys file in .ssh directory and chmod 644 for it paste copy of key based in authonticated_keys

3rd party

install flask install postgerSQL install python install alchemySQL
