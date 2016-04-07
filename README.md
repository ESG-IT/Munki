# Munki Setup on OS X El Capitan Server
[Link to guide](https://osxdominion.wordpress.com/2015/02/26/setting-up-munki-with-os-x-yosemite-server/)

## Preinstall Setup

### Open the Terminal and copy the following code
    mkdir /Library/Server/Web/Data/Sites/Default/repo && mkdir /Library/Server/Web/Data/Sites/Default/repo/catalogs && mkdir /Library/Server/Web/Data/Sites/Default/repo/pkgs && mkdir /Library/Server/Web/Data/Sites/Default/repo/pkgsinfo && mkdir /Library/Server/Web/Data/Sites/Default/repo/manifests && chmod -R a+rX /Library/Server/Web/Data/Sites/Default/repo

This creates the Munki folders and makes them available to anyone that is allowed.

### In Server.app

- Go to Websites

![Server.app(https://osxdominion.files.wordpress.com/2015/02/screen-shot-2015-02-18-at-8-42-17-am.png)
