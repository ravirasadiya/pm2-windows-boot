# pm2-windows-startup
Utility to make [PM2](https://github.com/Unitech/PM2) automatically resurrect on Windows startup.

## Installation and usage
``` bash
> npm install pm2-windows-startup -g
> pm2-startup install
```

PM2 will now automatically revive the saved processes on startup. To save the current list of processes execute:

``` bash
> pm2 save
```

## Uninstall
```bash
> pm2-startup uninstall
```

This removes the registry entry that starts the process on startup
