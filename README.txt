proj3 README
For ubuntu
Run these commands using terminal
1.sudo su
go to the root directory
2.cd ..
3.cd ..
4.sudo apt-get install python2.7-dev
5.sudo apt-get install build-essential
6.copy the env folder and ez_setup.py to this current directory
6.sudo python ez_setup.py
7.sudo easy_install virtualenv
8.virtualenv --no-site-packages env
9.cd env/proj3/
10. ../bin/pserve --reload development.ini
11.Run the application using browser
    application url
    localhost:6543/upload
