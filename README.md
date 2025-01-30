# journal-team

## Virtual rooms

- [Room 1](https://meet.google.com/deb-ccfz-bah)
- [Room 2](https://meet.google.com/dwi-thof-rdh)

## PHP versions

- [search](https://github.com/elifesciences/search) runs on PHP 8.3

To verify your local PHP version, run
```
php --version
```

### To change PHP versions on Ubuntu

Manage versions of PHP using the [`ondrej PPA`](https://launchpad.net/~ondrej/+archive/ubuntu/php/+index).

Install a specific PHP version with:
```
sudo apt install php8.3-cli php8.3-curl php8.3-mbstring php8.3-dom
```

Switch to a particular PHP version with:
```
sudo update-alternatives --config php
```

### To change PHP versions on OS X

Manage versions of PHP using `brew`. To check if you have PHP 8.3 installed, run:
```
brew ls --versions | grep '^php[ @]'
```
If you do not have PHP 8.3, install it with:
```
brew install php@8.3
```
If you are not on PHP 8.3, switch to it with:
```
brew unlink php@[current version]
```
followed by
```
brew link php@8.3
```

## Common PHP tools

These tools apply to any PHP project we work on:

- [Composer 2](https://getcomposer.org/)
