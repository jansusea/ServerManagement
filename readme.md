python3 -m pip -r install requirements.txt


sudo killall -9 uwsgi
udo service nginx restart
sudo uwsgi uwsgi.ini

