# 2048-container
A recipe for a Singularity container useful for playing 2048.  

## Construction
Build the container with something like ```sudo singularity build 2048.img Singularity``` or ```build-image.sh```. 

## Play 2048!
Run ```singularity exec 2048.img /usr/games/2048-qt``` or ```play-2048.sh``` after building the container.

![Score: 128](https://i.imgur.com/dIlPGLd.png)
