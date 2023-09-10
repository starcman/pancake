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

Add the script to cron tab (runs every 30 mins)
```
* /30 * * * * /srv/hosts.sh
```