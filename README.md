# install-zombie-plague-5.0.8-in-vps
Install This From Ubuntu 18.04







How To Install Zombie Plague 5.0.8 In CS1.6 Android With VPS Linux ✔


>>> First Install CS1.6

-> - apt update

-> - apt upgrade

-> - wget http://www.mediafire.com/file/px1sqa0fn3j8r3l/YeniTemel2018_Temiz.zip/file

-> - dpkg --add-architecture i386

-> - apt update

-> - apt install lib32z1 libstdc++6:i386 rar unrar zip unzip

-> - unzip YeniTemel2018_Temiz.zip

-> - mv temiz /opt/server

-> - cd /opt/server

-> - screen ./xash3d -game cstrike +map de_dust2 +maxplayers 32 +port 27015 +public 1



>>> Install Zombie Plague 5.0.8



-> - cd /opt/server/cstrike

-> - wget https://www.mediafire.com/file/da5joufplr3qt84/vx.zip/file

-> - unzip vx.zip

-> - Press A For Install All File ZP In Cstrike

-> - cd /opt/server

-> - Then Open Server : screen ./xash3d -game cstrike +map de_dust2 +maxplayers 32 +port 27015 +public 1



>>> Install FastDL 



-> - apt install apache2

-> - cd /var/www/html

-> - mkdir FastDL

-> - ln -s /opt/server/cstrike/ /var/www/html/FastDL/

-> - cd /opt/server/cstrike

-> - apt install nano

-> - nano server.cfg

-> - Copy You IP

-> - Paste In Here : sv_downloadurl "http://you ip/FastDL/cstrike/"

-> - Save

-> Now All can install file with fastdl
