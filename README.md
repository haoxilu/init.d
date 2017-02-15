```
   ______              __           __
  /\__  _\          __/\ \__       /\ \
  \/_/\ \/     ___ /\_\ \ ,_\      \_\ \
     \ \ \   /' _ `\/\ \ \ \/      /'_` \
      \_\ \__/\ \/\ \ \ \ \ \_  __/\ \L\ \
      /\_____\ \_\ \_\ \_\ \__\/\_\ \___,_\
      \/_____/\/_/\/_/\/_/\/__/\/_/\/__,_ /
```

Batch scripts for Ruby production environment install on Ubuntu Server.

[![wercker status](https://app.wercker.com/status/2dd2ff58518cae2dd75e4556e6d931c5/s/master "wercker status")](https://app.wercker.com/project/bykey/2dd2ff58518cae2dd75e4556e6d931c5)

## Requirements

* Ubuntu Server 14.04

## Usage

Install packages first

```bash
curl -sSL https://git.io/vDX0J | bash # mirror china
sudo apt-get update
sudo apt-get install -y curl
curl -sSL https://git.io/vVHhe | bash
```

### Install Nginx

Nginx [official package](http://nginx.org/packages/ubuntu/)

```bash
curl -sSL https://git.io/vDX0L | bash
```

### Install Rbenv + Ruby

```bash
curl -sSL https://git.io/vXBW1 | bash
```

### Install RVM + Ruby

```bash
curl -sSL https://git.io/vXBzD | bash
```

Use Ruby China mirror site for RubyGems and Ruby:

```
MIRROR=1 curl -sSL https://git.io/vXBzD | bash
```

### Install MongoDB

```bash
curl -sSL https://git.io/vDX03 | bash
```

### Install Redis

```bash
curl -sSL https://git.io/vDX0G | bash
```

### Install ElasticSearch

```bash
curl -sSL https://git.io/vDX0n | bash
sudo service elasticsearch status
```

### Install Docker

```bash
curl -sSL https://git.io/vDX0W | bash
sudo docker info
```

### Install Mycat

```bash
curl -sSL https://git.io/vDX08 | bash
mycat status
```

### Install Haproxy

```bash
curl -sSL https://git.io/vDX0E | bash
```
