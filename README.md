# packer

```
# ISO chacksum on windows
certutil -hashfile bodhi-4.1.0-64.iso MD5

# KS md5 password hash
openssl passwd -1 "password"
```

```
packer validate web.json
packer build web.json
packer build -force web.json
```
