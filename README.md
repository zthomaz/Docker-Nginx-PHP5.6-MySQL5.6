# Docker-Nginx-PHP5.6-MySQL5.6
Build image
-----------

```bash
git clone https://github.com/zthomaz/Docker-Nginx-PHP5.6-MySQL5.6.git
cd Docker-Nginx-PHP5.6-MySQL5.6
sudo apt-get install make
```

Run container
-------------
```bash
sudo make run
```

Check Version PHP
-------------
```bash
sudo make test
```

Run bash on container (for debug)
-------------
```bash
sudo make bash
```

## Test container
http://localhost:8080/

## Remove container
sudo make clear
