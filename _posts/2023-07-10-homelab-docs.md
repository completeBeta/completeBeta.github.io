---
title: Hello World
date: 2023-07-10 12:00:00 -500
categories: [testing]
tags: [introduction] # tag names MUST always be lowercase! 
---

# Welcome to the first post

"Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum."

"Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum."

## Hardware

"Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. 

Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum."

* one
* two
* three
* four
* five

## Code Blocks
To add code blocks we use back ticks and we can specify the language we are using.

### Language Seperation
by placing the name of the language after the back ticks; like such

We will then receive the correct output in the selected language with proper highlighting.

#### JavaScript

```javascript
console.log('hello world!')
```

#### YAML

Everyone's favourite markup :P (YAML); Below is a guacamole container yml file.

```yml
version: "2"
services:
  guacamole:
    image: oznu/guacamole
    container_name: guacamole
    volumes:
      - postgres:/config
    ports:
      - 8081:8080
volumes:
  postgres:
    driver: local
```

#### Bash/ Shell

```bash
Sudo apt update && sudo apt upgrade -y
```

or we can try out some new flatpak installs

```shell
sudo flatpak install firefox
```


## Photos
 We can implement photos simply by either providing a directory and have them stored in the github repo or just link to them.

![img-description](https://hexus.net/media/uploaded/2019/8/52fbc0ff-52c8-4237-b546-4af68a54ece3.jpg)

with the image above simply linking to an indexed image on the internet. ***This will only be used for this post and all other images should be stored in their own folder to ensure that images do not go missing***
 