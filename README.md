# Raspberry Pi 4 Music Server & Home Lab

I run Plex Media Server on a Raspberry Pi 4 with Raspberry Pi OS Desktop
(64-bit). The music files live on a USB stick connected to the Pi. Plex
catalogues the library so I can browse and stream it from other devices.

## Docker services

| Service | Purpose |
| --- | --- |
| Homepage | Dashboard with links to my local services |
| Beszel and Beszel Agent | System and resource monitoring |
| Uptime Kuma | Availability monitoring for services |
| Portainer CE | Web interface for managing Docker containers |

This project demonstrates how I use a single Linux machine to host a media
library, monitor system health and service availability, and manage
containerised applications.
