# This repo is about my `Dockerplates`

This repository **Dockerplates** is my personal docker-compose file collection that I use on my homelab server. Here you can find templates, and configurations for a dashboard for all your services, tools for docker containers, a self hosted media server, a self hosted cloud storage, productivity tools and a self hosted website with php support.

> :warning: Be aware that products change over time. I do my best to keep up with the latest changes and releases in my free time, but please understand that this won’t always be the case.

I created them as free resources to be used in your homelab environment servers if you choose to use them. Keep in mind to tailor them to your specific infrastructure as they do not contain the environment variables or tokens needed to function correctly.

## Network diagram with these containers

Visual illustration

<img src="img/network-diagram.png">

## Showcase

### `traefik` reverse proxy

<img src="img/traefik.png">

Traefik is a leading modern reverse proxy and load balancer that makes deploying microservices easy. Traefik integrates with your existing infrastructure components and configures itself automatically and dynamically.

> Don't forget to forward port 80 and 443 in your routers settings or applications won't be exposed to the internet!

### `Flame` dashboard (changed to homepage)

<img src="img/flame.png">

Flame is self-hosted startpage for your server. Flame is very easy to setup and use. With built-in editors, it allows you to setup your very own application hub in no time - no file editing necessary. Although if you are keen on designing your own dashboard you can write your own CSS for it.

### `Homepage` dashboard

<img src="img/homepage.jpeg">

### `Jellyfin` media server

<img src="img/jellyfin.png">

Jellyfin is the volunteer-built media solution that puts you in control of your media. Stream to any device from your own server, with no strings attached. Your media, your server, your way.

### `Jellyseerr` media library management tool

<img src="img/jellyseerr.png">

Jellyseerr is a free and open source software application for managing requests for your media library. It is a fork of Overseerr built to bring support for Jellyfin & Emby media servers!

### `qBittorrent` torrent client

<img src="img/qbittorrent.png">

The Qbittorrent project aims to provide an open-source software alternative to µTorrent. qBittorrent is based on the Qt toolkit and libtorrent-rasterbar library.

### `Radarr` torrent client

<img src="img/radarr.png">

Radarr is a movie collection manager for Usenet and BitTorrent users.

### `Sonarr` torrent client

<img src="img/sonarr.jpeg">

Sonarr is a PVR for Usenet and BitTorrent users.

### `Portainer` container manager

<img src="img/portainer.png">

Portainer is a lightweight service delivery platform for containerized applications that can be used to manage Docker, Swarm, Kubernetes and ACI environments.

### `Dockge` compose file manager

<img src="img/dockge.png">

A fancy, easy-to-use and reactive self-hosted docker compose.yaml stack-oriented manager.

### `Uptime Kuma` monitoring tool

<img src="img/uptime.png">

A fancy, easy-to-use and reactive self-hosted uptime monitor.

### `Prowlarr` indexer

<img src="img/prowlarr.png">

Prowlarr is a indexer manager/proxy built on the popular arr .net/reactjs base stack to integrate with your various PVR apps. Prowlarr supports both Torrent Trackers and Usenet Indexers. It integrates seamlessly with Sonarr, Radarr, Lidarr, and Readarr offering complete management of your indexers with no per app Indexer setup required.

### `Pi-hole` dns ad blocker

<img src="img/pihole.png">

The Pi-hole® is a DNS sinkhole that protects your devices from unwanted content, without installing any client-side software.

### `Ansible` Ansible Semaphore UI for automation

<img src="img/ansible.png">

Ansible is an open source IT automation engine that automates provisioning, configuration management, application deployment, orchestration, and many other IT processes. It is free to use, and the project benefits from the experience and intelligence of its thousands of contributors. Link to ansible playbooks at the end of readme

### `WeKan` Open Source kanban

<img src="img/wekan.png">

WeKan is an Open Source software collaborative kanban board application. Whether you’re maintaining a personal todo list, planning your holidays with some friends, or working in a team on your next revolutionary idea, Kanban boards are an unbeatable tool to keep your things organized.
