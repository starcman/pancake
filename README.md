# Block websites using hosts file & cron

Copy the file
```
cp hosts.sh /srv/
```

Switch to root user
```
sudo su 
```

Open crontab
```
crontab -e
```

Add the script to cron tab 
```
* /30 * * * * /srv/hosts.sh
```