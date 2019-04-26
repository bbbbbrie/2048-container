BootStrap: library
From: ubuntu:18.10

%help
    Get the elusive 2048 tile.

%runscript
    /opt/2048-cli/2048
%environment
    export PATH=/opt/2048-cli:/usr/bin:/usr/local/sbin:/bin:/usr/local/bin:/usr/sbin:/sbin

%post
    apt-get -y update && apt-get -y install figlet gcc git lolcat libncurses5-dev make
    git clone https://github.com/tiehuis/2048-cli.git /opt/2048-cli
    cd /opt/2048-cli
    make
    /usr/bin/figlet "hello, world" | /usr/games/lolcat
    /usr/bin/figlet "Let's play 2048..." | /usr/games/lolcat
    /usr/bin/figlet "...in a container!" | /usr/games/lolcat

%labels
    Author Brie Carranza
