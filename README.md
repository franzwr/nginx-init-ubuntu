nginx-init-ubuntu
=================

Init script for Ubuntu 14.04, tailored for my own purposes: installed nginx through `passenger-install-nginx-module` on /opt/nginx.

To use, copy to `/etc/init.d`, add execute permissions

    cp nginx /etc/init.d/.
    chmod +x /etc/init.d/nginx

then try

    service nginx stop
    service nginx start
    service nginx restart

