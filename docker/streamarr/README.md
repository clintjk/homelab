# streamarr
A media management stack
## About
Contains:
 - Jellyfin
 - Jellyseer
 - Radarr
 - Sonarr
 - Prowlarr
 - qbittorrent
## Notes
Refer to https://trash-guides.info/Hardlinks/How-to-setup-for/Docker/  
  
Make sure to set permissions to the data folder:
````
sudo chown -R $USER:$USER /data
sudo chmod -R a=,a+rX,u+w,g+w /data
````

Set the qbittorrent download path to `/data/torrents`
