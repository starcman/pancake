# Block websites using hosts file & cron

Copy the file
```
sudo cp hosts.sh /srv/
```

Switch to root user
```
sudo su 
```

Open crontab
```
crontab -e
```

Add the script to cron tab (runs every 5 mins)
```
*/5 * * * * /srv/hosts.sh
```