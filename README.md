# utat-ansible
Collection of Ansible scripts for UTAT IT. 

## Current Playbooks
* `install-go`: Installs [go](https://golang.org/). Duh. 
* `install-duplicacy`: Installs latest [duplicacy](https://github.com/gilbertchen/duplicacy) from source
* `duplicacy-init`: Initializes duplicacy to backup to Google Drive via cron, using a basic filter set
* `duplicacy-maint`: Runs basic maintenance on a duplicacy backup, including exhaustive prune and integrity checking. 
