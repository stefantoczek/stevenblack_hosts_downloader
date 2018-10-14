# stevenblack_hosts_downloader
Simple shell script for ubuntu linux to add entry in anacrontab to download stevenblack hosts daily


usage:

    git clone https://github.com/stefantoczek/stevenblack_hosts_downloader.git && cd stevenblack_hosts_downloader
    sudo bash host_adblock_update.sh
    
that's it, you can check if script successfully added entry in anacrontab by running
    cat /etc/anacrontab
