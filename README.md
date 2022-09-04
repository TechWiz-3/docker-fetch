# Docker fetch

Display info about docker container graphically. In development.  

Current output:

```css
      .
      :
    ___:____     |\/|
  ,'        `.    \  /
  |  O        \___/  |
~^~^~^~^~^~^~^~^~^~^~^~^~

Docker@Golden-Room
Total containers: 6
Running containers: 4
Total images: 30
Root dir: /volume1/@docker
```

Planned future output:
```css
$ ./dfetch --extended
      .
      :
    ___:____     |\/|
  ,'        `.    \  /
  |  O        \___/  |
~^~^~^~^~^~^~^~^~^~^~^~^~

Docker@Golden-Room
------------------
Client Version: 20.10.3
Server Version: 20.10.3


Total images: 30
Total containers: 6
Running containers: 4
Paused containers: 2
Latest container: AmazingBot (1 day ago)

Root dir: /volume1/@docker
Problems: 0

CPU Usage: 1%
RAM Usage: 780 MB
```
