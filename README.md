# provisioning

## Installation

```
$ cd ~
$ sudo xcodebuild -license
$ xcode-select --install
$ ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"
$ brew install ansible
$ brew install git
$ sudo mkdir -p /usr/local/etc/ansible
$ sudo sh -c "echo localhost > /usr/local/etc/ansible/hosts"
$ git clone https://github.com/daichike/provisioning.git
$ cd provisioning
$ ansible-playbook install.yml
```

## See also

* [daichike/dotfiles](https://github.com/daichike/dotfiles)
