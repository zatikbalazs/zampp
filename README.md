# ZAMPP Dashboard
Get your local PHP web stack up and running with a single command! No need to install a desktop application.  
Available for: macOS, Linux and Windows (WSL only).

## How to use?
Paste this into a macOS Terminal or Linux shell prompt:
```shell
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/zatikbalazs/zampp/HEAD/zampp.sh)"
```
__Cool stuff: the ZAMPP Dashboard will never get installed anywhere on your system. Only the web stack will be installed, if you decide to do so. To manage services, update or delete the web stack, please re-run the command in your terminal anytime you wish.__

## What does the ZAMPP Dashboard do?
It lets you install and manage (update, restart, delete) your local PHP web stack.

## What exactly happens during installation?
The ZAMPP Dashboard installs and configures everything you need to start PHP web development on your machine:
- installs Homebrew
- installs Apache
- installs MySQL
- installs PHP
- installs phpMyAdmin
- enables port 80 in Apache
- creates a www directory for the user
- configures DocumentRoot
- sets access_log and error_log locations
- loads php_module
- enables PHP in Apache
- configures DirectoryIndex
- loads rewrite_module
- sets AllowOverride All
- enables phpMyAdmin in Apache
- sets blowfish_secret
- enables passwordless login in phpMyAdmin
- creates a phpinfo.php file to test PHP
- starts the httpd service
- starts the mysql service
- starts the php service

## How does the ZAMPP Dashboard work?
The ZAMPP Dashboard is a shell script that uses Homebrew under the hood. It gets called directly from Github and doesn't get installed anywhere on your system. Only your web stack will be installed once you deliberately decide to do so.

## Is the ZAMPP Dashboard free?
Yes, the ZAMPP Dashboard is 100% free and open source.
