# nginx -s reload

# certbot certonly --standalone -d app.automatedlife.com.au --staple-ocsp -m info@blueskylabs.com.au

# certbot certonly --webroot 

# certbot certonly --webroot -w /etc/letsencrypt --dry-run --domains sitesentry.bsdl.xyz

# Add cron job to host machine
## sudo su -
## vim /etc/crontab
## chmod +x /root/docker.sh

## // cronjob will runs at 12 am everyday
## 0 0 * * * /usr/bin/bash /root/docker.sh

