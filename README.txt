## Nginx proxy server in a box.

This Repository is an example of how to configure a simple nginx proxy server.

It was created specifically to 

* proxy inbound traffic to dockers documentation on read the docs
* add a X-RTD-SLUG http header to it, so read the docs knows which documentation to serve
* provide SSL termination, that is.. Accept SSL traffic but only to redirect people to plain http://

But you can use it to configure for example a static site. 
All you'd need to to is rename and modify the readthedocs.conf file for your purposes

the create_ssl file is a helper to create a self-signed ssl certificate.

