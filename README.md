#Crave Fixer

###This repo will always updating with fixes when i find any issues with this server 

<br />

###Update Packages

- Use this `sources.list` to get all packages that you will need in future
>[!NOTE]
>Some package like `qemu` npt availabel with default crave `sources.list` file
>

```sh
wget https://github.com/mrx7014/Crave-Fixer/blob/main/sources.list;sudo mv /etc/apt/sources.list /etc/apt/sources.list.old;sudo cp sources.list /etc/apt; sudo apt-get update -y;sudo apt-get upgrade -y
```