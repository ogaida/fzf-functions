# some fzf functions

tested on debian bookworm

## requirements

install some packages

```bash
sudo apt install libiconv-hook-dev jq miller file wget 
```

## download fzf

fzf ist available from repo but the version is a bit old

```bash
wget https://github.com/junegunn/fzf/releases/download/v0.64.0/fzf-0.64.0-linux_amd64.tar.gz
tar -xzvf fzf-0.64.0-linux_amd64.tar.gz
sudo mv fzf /usr/bin/
```

## functions

### file_search

### file_stats

### kontoauszug_check

### kontoauszug_filter_by_range