## balena xmas

### Hardware required

* Raspberry Pi Zero
* SD Card
* 5v RGB LED stripe

### Connecting the hardware

Connect the data pins for your WS281x lights on the RPi to PIN18 and GROUND.

![alt text](https://github.com/adambutler/balena-xmas/assets/balena-xmas-tree.png)

### Setup and installation

Running this project is as simple as deploying it to balenaCloud application. You can do it in just one click by using the button below:

[![](https://balena.io/deploy.png)](https://dashboard.balena-cloud.com/deploy?repoUrl=https://github.com/adambutler/balena-xmas/)

You can also deploy in the traditional manner using the balena CLI and `balena push` command. For more information [check out the docs](https://www.balena.io/docs/learn/deploy/deployment/).

#### Install via Git

```
$ git clone git@github.com:adambutler/balena-xmas.git
```
Then add your balena application's remote:
```
$ git remote add balena username@git.balena-cloud.com:username/myapp.git
```
and push the code to the newly added remote:
```
$ git push balena master
```
It should take a few minutes for the code to push.

## Configure environment variables 

```
LED_BRIGHTNESS=255 (full)
LED_COUNT=300
```

