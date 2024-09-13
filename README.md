![Logo](https://i.imgur.com/uv0El0Z.jpeg)

**DO NOT USE TREYYS VERSION**, **IF U WANNA START TREYY ILL GET MORE EVIDENCE OF YOU USING RACIAL SLURS AND STUFF TOO** ALSO LEARN TO CODE!

# Mythic Framework [![Awesome](https://cdn.jsdelivr.net/gh/sindresorhus/awesome@d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome#readme)
> A curated list of credits, links, and community information related to the framework.

## Description

- Custom written framework that was used for Mythic RP

## Official Discord
- [Discord Link](https://discord.gg/HAXNp9NW2f) - Offical Discord for community-driven support forum!

## Project Maintainers
- PLACEHOLDER - Maintainer

## Credits
- Alzar & Dr Nick - Original Maintainers and Creators


## Information

# 🚧DISCLAIMER🚧
We do not own this framework, and we am simply trying to give it the support it deserves. The framework was originally built by Alzar & Dr Nick. Alzar has taken the liberty of releasing the framework, which you can find by following the [original repository](https://github.com/Alzar/mythic-framework) 

## DO NOT FORGET TO CHANGE THE LICENSE KEYS in `environment.cfg`
Rename `example.environment.cfg` to `environment.cfg`
```cfg
# License Key
sv_licenseKey setme
set steam_webApiKey "setme"
```

# Requirements 
| Packages          | Link                                                                |
| ----------------- | ------------------------------------------------------------------ |
| NodeJS | [Download Here](https://nodejs.org/en/download?text=+) |
| MongoDB | [Download Here](https://www.mongodb.com/try/download/community) (v6.0.5) |
| MariaDB | [Download Here](https://mariadb.org/download/?t=mariadb&p=mariadb&r=10.6.12&os=windows&cpu=x86_64&pkg=msi&m=acorn) (v10.6.12)
| HeidiSQL | [Download Here](https://www.heidisql.com/download.php) (*can be installed via MariaDB)
  
# SQL Instaliation
Run the SQL provided in HeidiSQL, the mongo will build itself as the server starts

# NOTE:
This will not work out of the box, you will need to make modifications to the base to replace the WebAPI calls with whatever authentication source you're wanting to do. 

## Using Admin

In the MongoDB Compass, inside of the "auth" database under users, find yourself (or whoever you want to give admin too) and add a new dataset under the groups array called either admin, owner, or staff. If you're already in the server, soft or hard relog to retrieve the new permissions.

To use the admin tool, run `/admin` or `/staff`.

![image](https://github.com/user-attachments/assets/d8feb147-3148-4ecf-b2f9-e3d5813ae135)


![image](https://github.com/user-attachments/assets/b5680d3d-8667-4c38-a0d0-64437ce18f44)









