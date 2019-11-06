# macbook-setup

Ansible for MacBook

## Prerequisites

Starting with macOS Catalina, Macs will now use zsh as the default login shell and interactive shell across the operating system.

### Step 0 - Create environment file

```
touch .zshenv
```

### Step 1 - Install Oh My Zsh

Oh My Zsh is an open source, community-driven framework for managing your zsh configuration. It comes with a bunch of features out of the box and improves your terminal experience.

Install Oh My Zsh:

```
sh -c "$(curl -fsSL https://raw.githubusercontent.com/robbyrussell/oh-my-zsh/master/tools/install.sh)"
```

### Step 2 - Install brew

Brew `https://brew.sh/`

### Step 3 - Install Ansible

Ansible `brew install ansible`

## Running

Open a terminal and execute `sh run`. You will be prompted for your password in order to perform some tasks as `sudo`.

## Issues

```
fatal: [127.0.0.1]: FAILED! => {"changed": false, "msg": "file (/Users/waraich/.zshenv) is absent, cannot continue", "path": "/Users/waraich/.zshenv"}
```
