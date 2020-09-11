### Notice:
This was snagged from SelfhostedPro's repository. There was a lot of extra stuff in there I didn't want/need, so this is the DB Tech version of the application template for Portainer v1.x and v2.x.

# Portainer Templates for DB Tech

This is a template focused on helping people spin up selfhosted services using Portainer.

### Prerequisites

1. A server/NAS with docker installed
2. A Portainer setup.

### Installing

1. Login to your portainer setup go to settings 
2. Enable Use external templates
3. For Portainer Version 1.x Add the url: `https://raw.githubusercontent.com/dnburgess/dbtechtemplate/master/Template/v1/template.json` then go to app templates and hit refresh at the top.
3. For Portainer Version 2.x Add the url: `https://raw.githubusercontent.com/dnburgess/dbtechtemplate/master/Template/v2/template.json` then go to app templates and hit refresh at the top.

### Information
All templates are already configured to bind mount to various places on your drive. This branch works without the need for OMV. The following folders are all created in /portainer/

* **Files** - General file storage.
  * **AppData** - Subfolder where application data (unrelated to served data) is stored.
    * **Config** - Subfolder where configuration files for every container are stored.
* **Downloads** - Where bittorrent and usenet downloaders download files to.
* **TV** - Where tv shows are stored/moved to after downloaded.
* **Movies** - Where movies are stored/moved to after downloaded.
* **Music** - Where music is stored/moved to after downloaded.
* **Books** - Where books are stored/moved to after downloaded.
* **Comics** - Where comics are stored/moved to after downloaded.
* **Podcasts** - Where podcasts are stored/moved to after downloaded.
## App List

- Bitwarden_rs
- Pi-Hole
- Whoogle
- YouTubeDL-Material
- DashMachine
- Nginx Proxy Manager
- Watchtower
- bookstack
- Chevereto
- duplicati
- lychee
- nextcloud
- openvpn-as
- qbittorrentVPN
- radarr


## Authors
* **NASHosted** - *Current Work*
* **SelfhostedPro** - *Current Work*
* **Jos Visser** - *Initial work* - [Qballjos](https://github.com/Qballjos)

See also the list of [contributors](https://github.com/SelfhostedPro/selfhosted_templates/contributors) who participated in this project.

## Acknowledgments

* LinuxServer.io for the old Template
* Inspiration being too lazy to create each container template manualy