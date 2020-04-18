# PACKAGE MANAGEMENT

## Advanced package tools

| Key              | equals               | Description                                      |
| :--------------- | :------------------- | :----------------------------------------------- |
| apt install      | apt-get install      | install pakage ( -y = yes all question)          |
| apt remove       | apt-get remove       | remove pakage (but leave config file)            |
| apt purge        | apt-get purge        | remove package and config file                   |
| apt autoremove   | apt-get autoremove   | remove automatically all unused packages         |
| apt search       | apt-get search       | search for package                               |
| apt show         | apt-get show         | show information about package                   |
| apt update       | apt-get update       | Resynchronize sources                            |
| apt upgrade      | apt-get upgrade      | upgrade all installed packages to newest version |
| apt full-upgrade | apt-get dist-upgrade | same as upgrade and also upgrade dependencies    |

### **help apt**

```bash
apt --help
```

## DPKG

| Key                 | Description                            |
| :------------------ | :------------------------------------- |
| dpkg -l             | find version of installed applications |
| dpkg -i package.deb | install package                        |
| dpkg -r package.deb | remove package                         |
