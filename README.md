## balena xmas

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

## Required ENV

```
LED_BRIGHTNESS=255 (full)
LED_COUNT=300
```

## Connecting

Connect the data pins for your WS281x lights on the RPi to PIN18 and GROUND.
