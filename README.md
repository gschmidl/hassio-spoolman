# hassio-spoolman

Home Assistant repository to run Spoolman as an addon

# Installation

Use the following link to add the repository:

[![Open your Home Assistant instance and show the add add-on repository dialog with a specific repository URL pre-filled.](https://my.home-assistant.io/badges/supervisor_add_addon_repository.svg)](https://my.home-assistant.io/redirect/supervisor_add_addon_repository/?repository_url=https%3A%2F%2Fgithub.com%2Fgschmidl%2Fhassio-spoolman)

Alternatively go to the Add-On Store, Click the three dots, then Repositories, and then add the following:

```
https://github.com/gschmidl/hassio-spoolman
```

# Creating the storage directory

You'll need to execute the following in a HA console to create the storage directory. Sorry, I don't know how to do it automatically and all inquiries remained unanswered.

```
cd /config/addons_config
mkdir spoolman
chown 1000:1000 spoolman
```
