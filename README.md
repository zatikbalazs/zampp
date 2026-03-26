# ZAMPP Stack
(Homebrew + Apache + MySQL + PHP + phpMyAdmin)

The easiest way to set up and manage your local PHP web development environment.  
Available for: macOS, Linux and Windows (WSL only).

## How to use?
Paste this into a macOS Terminal or Linux shell prompt:
```shell
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/zatikbalazs/zampp/HEAD/zampp.sh)"
```
Note: the zampp.sh script will never be downloaded or installed anywhere on your system. Only the software stack itself will be installed, if you decide to do so. To manage services, update or delete the stack, please re-run the above command in your terminal any time you want.

## What does ZAMPP do?
ZAMPP installs and configures everything you need to start PHP web development on your machine:
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

## How does ZAMPP work?
ZAMPP is a shell script that uses Homebrew under the hood.

## Is ZAMPP free?
Yes, ZAMPP is 100% free and open source.
