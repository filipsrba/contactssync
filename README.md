# contactssync
PowerShell script for Mirosoft 365 - "contacts sync"

What is case use for this code?
You have two partners tenants in Microsoft 365 and you want to sync only Exchange Online Contacts without other trusting creation.
In this case you syncing only specific group of users which them you want to cooperate.

The script "Download contacts" is for partner tenant to download and provide you an csv file. 
The script "Upload contacts" is for your tenant where you will upload members which are stored in download csv.

You can also automate it when there is often changes. 
There is reflecting of deleted members based on prevously file by comparing and same was for renaming of users.
