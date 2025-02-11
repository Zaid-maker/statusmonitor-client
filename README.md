# statusmonitor-client
A free status monitor solution, used to monitor a machine's resources usage. Developed in NodeJS, this is an early version.
You can selfhost a [statusmonitor-server](https://github.com/DottoXD/statusmonitor-server) instance and connect those 2, you will get a beautiful status page that shows your machines stats.

# update 0.0.5
+ network in/out per second monitor

# features
This project can currently monitor the ram usage, the cpu usage, the disk usage and the system uptime.
Tested on dedicated servers, vpses, vms and docker containers.

# known issues
There are no known issues at the moment.

# simple setup guide
You can easily setup [statusmonitor-client](https://github.com/DottoXD/statusmonitor-client) in 3 steps!

**Step one: clone the repo:**
*make sure to do this in an empty directory!*
```
git clone https://github.com/DottoXD/statusmonitor-client .
```

**Step two: install every dependency!**
```
npm install
```

**Step three: start the server!**
```
node index.js
```

## install script
[Here!](https://github.com/DottoXD/statusmonitor-client/blob/main/install.sh)
Note: The script is a beta version and may have bugs! Please open an issue to report any bug!
```
wget -O - https://raw.githubusercontent.com/DottoXD/statusmonitor-client/main/install.sh | sh
```

## uninstall script
[Here!](https://github.com/DottoXD/statusmonitor-client/blob/main/uninstall.sh)
Note: The script is a beta version and may have bugs! Please open an issue to report any bug!
```
wget -O - https://raw.githubusercontent.com/DottoXD/statusmonitor-client/main/uninstall.sh | sh
```
