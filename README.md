# Sia_Nextcloud

Requirements:

- At least 500 Siacoin (SC)
- 6 GB of free disk space, preferably on a solid-state drive (SSD)
- Docker Community Edition (free) installed on your system


Michael Lynch already created a detailed tutorial how to setup Docker, Sia and Nextcloud.

Tutorial: https://mtlynch.io/sia-nextcloud/#create-files-and-folders-for-docker

I've made the following changes to his configuration:

- Changed Sia_Version to 1.3.6
- Use lates Nextcloud version (Sia AddOn has to be installed manually in Nextcloud 14)
- Use API authetication, in Sia version 1.3.6 this authetication is enforced by default (https://gitlab.com/NebulousLabs/Sia/merge_requests/3239)
