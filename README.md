```
sudo vi /etc/samba/smb.conf
```

Then add:

```
[思维导图]
  path = /some/path
```

Then:

```
sudo smbcontrol all reload-config
```

刷新Finder，可以看到已经生效:

![demo](./images/demo.jpg)


