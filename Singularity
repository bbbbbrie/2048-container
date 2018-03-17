BootStrap: docker
From: ubuntu:artful

%post
    apt-get -y update && apt-get -y install figlet lolcat 2048-qt
    /usr/bin/figlet "hello, world" | /usr/games/lolcat
    /usr/bin/figlet "Let's play 2048..." | /usr/games/lolcat
    /usr/bin/figlet "...in a container!" | /usr/games/lolcat
