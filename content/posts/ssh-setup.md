---
date: "2025-03-18T12:01:21+05:45"
draft: false
title: "SSH Setup"
---

#### Copy the public and private key to the .ssh directory

```bash
cp ~/[filePath]/id_rsa* ~/.ssh/
```

#### Setup config file

```bash
sudo nano ~/.ssh/config
```

#### Config file configuration

```bash
Host acme-server
    HostName 34.231.213.345
    User pratik
    IdentityFile ~/.ssh/id_rsa
```

#### SSH to the server

```bash
ssh acme-server
```
