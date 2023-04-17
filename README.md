# slack-handler-patcher
found this solution somewhere in web, i can't sure its author, if you know the author, can post an issue, i will special the source and author here.

this repo is to fix linux slack app not redirect after login in web, it is cause by xdg-open, so the solution is wrapper a custom xdg-open to open slack://* protocal in special way, you can review the source and fix the scripts easily by your self, enjoy it.

### usage

- clone repo

```
git clone https://github.com/indiefun/slack-handler-patcher.git
```

- confirm path

confirm the path in xdg-open script, if wrong, you can fix it

```
cd slack-handler-patcher
cat xdg-open
```

- install wrapper

run the install.sh

```
sudo ./install.sh
```

- open slack, then login again, now it will redirect correctly, enjoy it
