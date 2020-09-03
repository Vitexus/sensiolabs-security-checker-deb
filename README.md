SensioLabs Security Checker
===========================

Debian package with https://github.com/sensiolabs/security-checker 


Installation
------------


```shell
sudo apt install lsb-release wget
echo "deb http://repo.vitexsoftware.cz $(lsb_release -sc) main backports" | sudo tee /etc/apt/sources.list.d/vitexsoftware.list
sudo wget -O /etc/apt/trusted.gpg.d/vitexsoftware.gpg http://repo.vitexsoftware.cz/keyring.gpg
sudo apt update
sudo apt install sensiolabs-security-checker
```

Usage
-----

```shell
security-checker security:check ../path/to/composer.lock
```

![ScreenShot](safe.png?raw=true)

See also: https://github.com/VitexSoftware/netbeans-php-tools

