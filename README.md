### Install:

You need to copy the github repo and install the requested python librairies.

```bash
git clone "https://github.com/vltn17/AutomaticGitPush.git"
cd AutomaticGitPush

pip install PyGithub
```

### Setup:

You need to these functions to begin.

```bash
gitPush --setLoginInfos
```

### Use in cmd:

To use this script with cmd call you need to create (for windows) a .cmd script that run the python script. Do not miss to add your .cmd script to your path.


Exemple:

gitPush.cmd
```bash
@echo off

python <the path to the python script .py> %cd% %1
```

!!! Modulo symbols with number are very important. There pass argument to the python script. 