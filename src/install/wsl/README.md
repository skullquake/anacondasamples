#Anaconda installation: WSL

### Anaconda 1

```
wget https://repo.continuum.io/archive/Anaconda-1.4.0-Linux-x86_64.sh
bash Anaconda-1.4.0-Linux-x86_64.sh
```
Modify `.bashrc`

```
PATH=/home/YOURUSER/anaconda/bin:$PATH
```

Reload

```
source ~/.bashrc
```

### Anaconda 3

```
wget https://repo.anaconda.com/archive/Anaconda3-5.3.0-Linux-x86_64.sh
bash Anaconda3-5.3.0-Linux-x86_64.sh
```

Modify `.bashrc`

```
PATH=/home/YOURUSER/anaconda3/bin:$PATH
```

Reload

```
source ~/.bashrc
```

### Test

```
jupyter notebook --no-browser
```
