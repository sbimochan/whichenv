# Which Env ?

### Edit `~/.bashrc` file to permanently store variable or according to your SHELL.

```bash
export whichenv = "dev"
```

Similarly add these variables in other environments like qa, staging, prod, etc.

### Reload

```bash
source ~/.bashrc
```

### Install whichenv

```bash
sudo curl https://raw.githubusercontent.com/sbimochan/whichenv/master/whichenv -o /usr/local/bin/whichenv && sudo chmod +x /usr/local/bin/whichenv
```

### Execute it

```bash
whichenv
```
