# samba-nextcloud-docker
Samba + Nextcloud + docker compose

# How to use

Edit `docker-compose.yml` file and change directories, username and passwords.
Then run `docker-compose up` and enjoy.

# SSL support
This `docker-compose.yml` doesn't have any reverse proxy to handle SSL (by default NextCloud image has no SSL support), but you can easily add `nginx-certbot` support to it.
