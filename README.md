### setup_script

Automates post-installation environment replication across WSL, Raspberry Pi, and Kali Linux. Restores packages, dotfiles, databases, services, and configuration from Restic backups.

### Usage

This script assumes a user account is setup and logged in, as well as curl being installed.

```sh
bash <(curl -sSL https://raw.githubusercontent.com/jb49088/setup_script/master/setup)
```

<!-- CODE_STATISTICS_START -->

### Code Statistics

```
--------------------------------------------------------------------------------
Language                      files          blank        comment           code
--------------------------------------------------------------------------------
Bourne Again Shell                1             70             23            283
Text                              3              0              0            175
Markdown                          1             11              4             36
--------------------------------------------------------------------------------
SUM:                              5             81             27            494
--------------------------------------------------------------------------------
```
<!-- CODE_STATISTICS_END -->

<!-- PROJECT_STRUCTURE_START -->

### Project Structure

```
setup_script
├── packages
│   ├── kali
│   │   └── apt.txt
│   ├── pi
│   │   └── apt.txt
│   └── wsl
│       └── yay.txt
├── README.md
└── setup

5 directories, 5 files
```
<!-- PROJECT_STRUCTURE_END -->
