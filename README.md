
Websites for atlasaarkarts.net and the 2008 Delhi International Literary Festival, managed by Sudeep Sen.



#### setup

Point nameservers to the correct IP address.
sudo cp etc/nginx/atlasaarkarts.net /etc/nginx/sites-available/atlasaarkarts.net
sudo ln -s /etc/nginx/sites-available/atlasaarkarts.net /etc/nginx/sites-enabled/
sudo /etc/init.d/nginx/restart
