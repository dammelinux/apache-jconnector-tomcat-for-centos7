# apache-jconnector-tomcat-for-centos7
#clone all directory / 
# bin
# boot
# home
# etc ...

#command use scripts

cd /
chmod +x setup.sh
./setup.sh

#### fix error = /bin/bash^M: bad interpreter: No such file or directory

#### => sed -i -e 's/\r$//' setup.sh

