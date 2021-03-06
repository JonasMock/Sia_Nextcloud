# Sia_Nextcloud

Create your own low-cost, secure cloud storage platform with blockchain backend.
You don't have to trust a centralized company anymore, Sia allows you to distribute and encrypt your data. Only the owner of the private key has access to the files.

  Renter Prices (estimated, 20.10.2018):<br><br>
  Fees for Creating a Set of Contracts:   &nbsp;72.81 SC / 0,44 € <br>
  Download 1 TB:     &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;     8.49 SC / 0,05 € <br>
  Store 1 TB for 1 Month:&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;96.29 SC / 0,58 € <br>
  Store 1 TB for Allowance Period:&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;288.9 SC / 1,73 € <br>
  Upload 1 TB:&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; 7.48 SC / 0,04 € <br>

More information about Sia: https://sia.tech/ <br>
More information about Nextcloud: https://nextcloud.com/

Requirements:

- At least 500 Siacoin (SC)
- 6 GB of free disk space, preferably on a solid-state drive (SSD)
- Docker Community Edition (free) installed on your system


Michael Lynch already created a detailed tutorial how to setup Docker, Sia and Nextcloud.

Tutorial: https://mtlynch.io/sia-nextcloud/#create-files-and-folders-for-docker <br>
More Sia projects from Michael Lynch: https://github.com/mtlynch

I've made the following changes to his configuration:

- Changed Sia_Version to 1.3.6
- Use latest Nextcloud version (Sia AddOn has to be installed manually in Nextcloud 14)
- Use API authetication, in Sia version 1.3.6 this authetication is enforced by default (https://gitlab.com/NebulousLabs/Sia/merge_requests/3239)
