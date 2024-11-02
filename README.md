# pacrepoman
## the pacMAN repoSITORY manAGER
pacrepoman manages Pacman Repositories directly from the command line. Adding, removing, enabling, disabling Pacman Repositories without the need for a text editor. And without the need for user interaction when used within a script.
## Usage
```
pacrepoman [option] <name> <url OR path> <siglevel>

-h --help                                   Display this help.

-l --list                                   List all repositories 
                                            in "$conff".

-q --query <name>                           Query repository <name>
                                            in "$conff".

-a --add <name> <url OR path> <siglevel>    Add repository <name> and location, 
                                            server <url> or mirrorlist <path>, 
                                            to "$conff". 
                                            Specifying trust level <siglevel> 
                                            is optional.

-r --remove <name>                          Remove repository <name> 
                                            from "$conff".

-e --enable <name>                          --- NOT YET IMPLEMENTED --- 
                                            Enable repository <name> 
                                            in "$conff".

-d --disable <name>                         --- NOT YET IMPLEMENTED --- 
                                            Disable repository <name> 
                                            in "$conff".
```
## Changelog
### 0.1.0.20241102
- Switched to GNU Lesser General Public License v2.1
- Changed versioning to Major.Minor.Patch.Build Date*-Build Number**
- Changed header, changelog and help style
- Revised header, description and help.

*Date format YYYYMMDD  
**Number format XX; only used if there is more than one build per date

### 0.1.0.20230520
- Initial release
