# pacrepoman
## pacman repository manager
pacrepoman is a cli tool for Arch Linux to manage repositories in the Pacman configuration file usable within scripts without relying on user interaction required by text editors.
## Usage: `pacrepoman [option] <name> <url OR path> <siglevel>`
```
-h --help                                  Display this help.
-l --list                                  List all repositories in /etc/pacman.conf.
-q --query <name>                          Query repository <name> in /etc/pacman.conf.
-a --add <name> <url OR path> <siglevel>   Add repository <name> and location, server <url> or mirrorlist <path>, to /etc/pacman.conf.
                                           Specifying trust level <siglevel> is optional.
-r --remove <name>                         Remove repository <name> from /etc/pacman.conf.
-e --enable <name>                         --- NOT YET IMPLEMENTED --- Enable (uncomment) repository <name> in /etc/pacman.conf.
-d --disable <name>                        --- NOT YET IMPLEMENTED --- Disable (comment) repository <name> in /etc/pacman.conf.
```
## Changelog
### v0.1.0
- Initial release
