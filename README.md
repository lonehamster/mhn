The Heart of Honeypot(蜜罐之心)
====================
使用方法：

首先安装git

    $ Ubuntu系统下
    $ sudo apt install git -y
    
安装THH    

    $ cd /opt/
    $ sudo git clone https://github.com/lonehamster/THH.git
    $ cd THH/
    $ sudo ./install.sh


配置

    ===========================================================
    THH Configuration
    ===========================================================
    Do you wish to run in Debug mode?: y/n n
    Superuser email: YOUR_EMAIL@YOURSITE.COM
    Superuser password: 
    Server base url ["http://1.2.3.4"]: 
    Honeymap url ["http://1.2.3.4:3000"]:
    Mail server address ["localhost"]: 
    Mail server port [25]: 
    Use TLS for email?: y/n n
    Use SSL for email?: y/n n
    Mail server username [""]: 
    Mail server password [""]: 
    Mail default sender [""]: 
    Path for log file ["mhn.log"]: 


 sudo supervisorctl status
    geoloc                           RUNNING    pid 31443, uptime 0:00:12
    honeymap                         RUNNING    pid 30826, uptime 0:08:54
    hpfeeds-broker                   RUNNING    pid 10089, uptime 0:36:42
    mhn-celery-beat                  RUNNING    pid 29909, uptime 0:18:41
    mhn-celery-worker                RUNNING    pid 29910, uptime 0:18:41
    mhn-collector                    RUNNING    pid 7872,  uptime 0:18:41
    mhn-uwsgi                        RUNNING    pid 29911, uptime 0:18:41
    mnemosyne                        RUNNING    pid 28173, uptime 0:30:08


## LICENSE

Modern Honeypot Network

Copyright (C) 2019 - Anomali, Inc.

This program free software; you can redistribute it and/or
modify it under the terms of the GNU Lesser General Public
License as published by the Free Software Foundation; either
version 2.1 of the License, or (at your option) any later version.

This program is distributed in the hope that it will be useful,
but WITHOUT ANY WARRANTY; without even the implied warranty of
MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the GNU
Lesser General Public License for more details.

You should have received a copy of the GNU Lesser General Public
License along with this program; if not, write to the Free Software
Foundation, Inc., 51 Franklin Street, Fifth Floor, Boston, MA  02110-1301  USA
