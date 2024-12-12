## Hi there 👋

Config Setup is an orginzation of repo's that are there to help setup a local enviorment.

This is currently build around Ubuntu but could be expanded to other operating systems that support git and asdf.

#### Install Dependencies
```bash
sudo apt update
sudo apt install software-properties-common \
  git zsh tmux dirmngr gpg gawk \
  build-essential libssl-dev zlib1g-dev \
  libbz2-dev libreadline-dev libsqlite3-dev \
  libncursesw5-dev xz-utils tk-dev libxml2-dev \
  libxmlsec1-dev libffi-dev liblzma-dev
```

#### Run the Install Script
```
curl -sS https://raw.githubusercontent.com/config-setup/setup/refs/heads/main/setup | bash
```
