# PiConfiguration
Current RaspberryPi setup with docker stack and compose files.

A simple setup to have some services running in my local network.

OS: DietPi
DNS handling via AdguardHome (might switch to bind9 in the future)
using docker as provider with the following containers:
- portainer (manage docker containers)
- traefik (reverse proxy to get rid of memorising ports)
- HomeAssistant (easily control all ZigBee devices from one dashboard)
- Paperless (manage documents properly)
- Mealie (userfriendly way to store my cooking recipes)
- Photoprism (mange photos properly)
- standard notes (secure and encrypted notes)
- chevereto (hosting images myself)
- linkwarden (more powerful way of bookmarking websites)
