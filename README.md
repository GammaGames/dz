# dz

ez docker, originally based on a [gist](https://gist.github.com/ipedrazas/2c93f6e74737d1f8a791)

I would recommend making an alias and adding it to your `.bashrc`
```sh
alias dz='. ~/Documents/dz/dz'
```

### Commands

| Command | Description |
|----------------------------------|--------------------------------------------------------------------------|
| `dz` | runs `dz ip` command |
| `dz ip [-all] [ID]` | print a container's name, IPs, ports, networks and gateways (all containers running if blank)<br>-all option to search non running containers |
| `dz v [filter]` | prints volumes with sizes (dangling if blank, all if 'all') |`
| `dz sh [USERNAME] <ID>` | bash into a container with optional username |
| `dz logs [NUM_LINES] <ID>` | tailg (and follow) a container's logs (0 lines if blank) |
| `dz bb [COMMAND]` | start a busybox container with optional command |
| `dz ub [COMMAND]` | start a ubuntu container with optional command |
