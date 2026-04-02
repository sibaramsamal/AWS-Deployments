## Frequently used commands

1. Reload the daemon after making any change in files or directory before restarting the service
```
sudo systemctl daemon-reload
```

2. Restart the service
```
sudo systemctl restart <service name without .service>
```

3. For checking the logs and running status of a service
```
sudo journalctl -u <service-name>.service -f
```

4. To stop any service
```
sudo systemctl stop <service name without .service>
```

5. To change the server timezone
```
sudo timedatectl set-timezone Asia/Kolkata

Then to verify it: 
timedatectl
```

6. For removing or deleting folder(Complete removal and irreversible)
```
rm -rf folder_name

rm file_name
```

7. Create or edit some file:
```
nano <location of file/file name>
then after doing changes: (ctrl + x) then y then enter
```

8. 