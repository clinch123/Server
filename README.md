# SERVER
Im starting out with the whole CI/CD thing. So if you see something I could do better or have any suggestions hit me up!


## HomeLab
- GNS3
- Vagrant
- KVM (Unraid)

## CI/CD

## Home Automation : Bridge:Internal
- homeAssistant : 8123

## INDEXER : Bridge:DMZ
- Sonarr : 8989
- Radarr : 7676
- Lidarr : 8787
- Bazarr : 6767
- Jackett : 9117

## VPN : HOST
- Zerotier : 9993
- OpenVPN : 1194

## Network Services : Bridge:Services
- DNS Server (PiHole)
- NetBox
- Authelia
- Redis

## Management : Bridge:Internal
- Portainer : 9000
- Authelia : 9091
- Cloudflare DNS Update (Custom)
- phpMyAdmin (Host) : 3306
- Watchtower (All Networks)
- Organizr : 8080
- Guacamole : 8081
- HealthChecks : 8000
- LDAPAuth : 8888/9001

## MediaPlayer : Bridge:DMZ
- Jellyfin : 8096/8920/7359/1900

## Monitoring : Bridge:Internal
- OpenNMS : 8980/61616/8101
- Grafana : 3000
- Snipe-it : 9002

## Downloader : Bridge:DMZ
- SabNZBVPN : 8082/8090/8118
- Transmission : 9091 (In SabNZBVPN)

## SQL : Bridge: SQL
- PostGreSQL :5432
- MySQL : 3307

## User Front End : Bridge:DMZ
- Obmi : 3579
- Heimdall : 2080
- EmulatorJS : 3001
- NginxReverse Proxy : 443/80

## Storage : Bridge:Internal
- Nextcloud : 2443
- Davos : 8083
- Paperless-NG : 800
- GdriveMount (On Unraid)
- DonMelton Transcoding
