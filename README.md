# oc8-dh
dockerfile for owncloud deployment 

This owncloud deployment has ldap support and libreofice as well.  You it can run with sqlite database. 

docker run -d -v /some/folder/for/storage:/var/www/owncloud/data/ -p 80:80 -p 443:443 arr0n/oc8-dh 
