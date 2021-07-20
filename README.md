# Making scripts for shell in Unix systems.
## Commit 
### How use it
  1. First clone the repository.
  2. execute this command in the terminal
    only one scriipt: `ln -s path/script /usr/bin`
    whole directory: `export var_name:$PATH:/path/script`
  3. Enjoy it!
- `commit`: "file for add to state" "message of the commit"

  > ###### Description and example
  > `commit` script make git add, commit, and push in the same time.
  > ```
  > $ commit . "My first commit"
  > ```

## Install and update GitHub Client
  ### How use it

  ```
  $ ./ghclientinstall [apt|dnf|zypper|mac|windows]  [-i|-u|-p|-pu|-c|-cu|-s|-su]
  ```
  __options installing__ 
  - `apt`: Debian and ubuntu
  - `dnf`: Fedore, CentOs, Red Hat Enterprise Linux
  - `zypper`: oppenSUSE/SUSE Linuz
  - `mac`: macOs ( HomeBrew default)

    `-p`: Install via MacPort
    
    `-pu`: Update via MacPort
    
    `-c`: Install via Conda
    
    `-cu`: Update via Conda
    
  - `windows`: windows ( WinGet defaul )

    `-s`: Install via Scoop
    
    `-su`: Update via Scoop
    
    `-c`: Install via Chocolately
    
    `-cu`: Update via Chocolately
    

  ###### Description and example
  Install:
  ```
  $ ./ghclientinstall apt -i
  ```
  Update:
  ```
  $ ./ghclientinstall zypper -u
  ```
  ### More information
  If you need other way of installation you can read ![GitHub Cli Docs installation](https://github.com/cli/cli#installation)
  ### Manual installation
  Read official docs in ![Github Docs install cli](https://github.com/cli/cli/blob/trunk/docs/install_linux.md)
