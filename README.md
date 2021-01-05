# Ubuntu

## Install Nodesource

```bash
curl -sL https://deb.nodesource.com/setup_15.x | sudo -E bash -

```

## Install NodeJS

```bash
sudo apt-get install -y nodejs
```


## Install NVM


```bash
curl -o- https://raw.githubusercontent.com/nvm-sh/nvm/v0.35.3/install.sh | bash

```


## Update Node.js

Install NodeJS

Next, let's install Nodejs version 15.4.0.

Simply run nvm install 15.4.0.

```bash
nvm install 15.4.0
nvm use v15.4.0

nvm ls

```

output:

```bash

->      v15.4.0
         system
default -> 15.4.0 (-> v15.4.0)
node -> stable (-> v15.4.0) (default)
stable -> 15.4 (-> v15.4.0) (default)
iojs -> N/A (default)
lts/* -> lts/fermium (-> N/A)
lts/argon -> v4.9.1 (-> N/A)
lts/boron -> v6.17.1 (-> N/A)
lts/carbon -> v8.17.0 (-> N/A)
lts/dubnium -> v10.23.1 (-> N/A)
lts/erbium -> v12.20.1 (-> N/A)
lts/fermium -> v14.15.4 (-> N/A)

```


