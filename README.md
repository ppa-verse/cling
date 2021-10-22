# PPA for Cling and xeus-cling

This repository contains Debian packages for
[Cling](https://github.com/dimitry-ishenko-cpp/cling) and
[xeus-cling](https://github.com/dimitry-ishenko-cpp/xeus-cling), along with
several other supporting packages.

You can install it on your system as follows:

```bash
curl https://ppa-verse.github.io/cling/cling.list | \
    sudo tee /etc/apt/sources.list.d/cling.list

curl https://ppa-verse.github.io/cling/KEY.gpg    | \
    sudo gpg --no-default-keyring --keyring /usr/share/keyrings/cling-keyring.gpg --import

sudo apt update
```

To install [Cling](https://github.com/dimitry-ishenko-cpp/cling) run:

```bash
sudo apt install cling
```

To install [xeus-cling](https://github.com/dimitry-ishenko-cpp/xeus-cling) run:

```bash
sudo apt install xeus-cling
```