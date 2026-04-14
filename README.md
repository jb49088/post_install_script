### setup_script

Automates post-installation environment replication across WSL and Raspberry Pi. Restores packages, dotfiles, databases, services, and configuration from Restic backups.

### Usage

```sh
bash <(curl -sSL https://raw.githubusercontent.com/jb49088/setup_script/master/setup)
```

<!-- CODE_STATISTICS_START -->

### Code Statistics

```
--------------------------------------------------------------------------------
Language                      files          blank        comment           code
--------------------------------------------------------------------------------
Bourne Again Shell                1             48             23            175
Text                              4              0              0            159
Markdown                          1             10              4             36
JSON                              1              0              0             33
--------------------------------------------------------------------------------
SUM:                              7             58             27            403
--------------------------------------------------------------------------------
```
<!-- CODE_STATISTICS_END -->

<!-- PROJECT_STRUCTURE_START -->

### Project Structure

```
setup_script
|-- README.md
|-- packages
|   |-- kali
|   |   `-- apt.txt
|   |-- pi
|   |   `-- apt.txt
|   |-- windows
|   |   `-- winget.json
|   `-- wsl
|       |-- npm.txt
|       `-- yay.txt
`-- setup

6 directories, 7 files
```
<!-- PROJECT_STRUCTURE_END -->
