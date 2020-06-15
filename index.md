---
layout: default
---

A single html file that securely stores passwords. Passwords are encrypted with a master password. Passwords are displayed by clicking on them

Adapted from [Helpful Sheep - HTML password manager](https://helpfulsheep.com/2012-01-20-html-password-manager/)

Uses [Stanford Javascript Crypto Library](http://bitwiseshiftleft.github.io/sjcl/)

To Save changes click the Save button, don't attempt to use the browser **File/Save** menu option to save changes(it doesn't work)

To re-login press **F5**

To Reset Master password, enter in place of Password: **reset**

The **Secret Message** and **Authentication Data** fields are optional, they are used as additional keys to encrypt passwords

**CAUTION**: If the Master password is reset, all passwords will be lost and must be re-registered. Always have a **backup** copy of this file.

<a href="https://github.com/alexandrecvieira/html-password-manager/releases/latest" target="_blank">Download Latest Release</a>

## Features

* Easy data inclusion using the browser
* Easy data query using the browser
* Case insensitive and accent insensitive search
* Accessible from mobile devices via Dropbox

## Using
### Setting the master password on first use

The "Secret Message" and "Authentication Data" fields are optional but increase encryption security, they are used as additional keys to encrypt passwords

![Master Password](images/setup-master-password.gif)

### Inserting data

![Inserting Data](images/insert-data.gif)

### Saving data

![Save Data](images/save-date.gif)

### Searching

![Search](images/search.gif)

### Deleting data

![Delete](images/del-data.gif)

### Mobile access from Dropbox

Just query by mobile device from your Dropbox app

![Mobile](images/mobile-access.gif)
