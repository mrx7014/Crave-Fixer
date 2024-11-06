# Crave Fixer

### This repo will always updating with fixes when i find any issues with this server 

<hr>

### Update Packages

- Use this `sources.list` to get all packages that working on ubuntu
>[!NOTE]
>Some package like `qemu` not available with default crave `sources.list` file, So use this
>

```sh
cd /crave-devspaces;curl https://raw.githubusercontent.com/mrx7014/Crave-Fixer/master/sources.list >> sources.list;sudo mv /etc/apt/sources.list /etc/apt/sources.list.old;sudo cp sources.list /etc/apt; sudo apt-get update -y;sudo apt-get upgrade -y
```
