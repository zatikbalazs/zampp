# ZAMPP Dashboard
Launch your local PHP web stack with a single command. > Enjoy a full development environment without the bloat of a desktop application. Available for: macOS, Linux and Windows (WSL only).

## How to use?
Paste this into a macOS Terminal or Linux shell prompt:
```shell
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/zatikbalazs/zampp/HEAD/zampp.sh)"
```
__Zero footprint:__ The ZAMPP Dashboard runs entirely in-memory and never installs itself on your machine. Only the web stack is added if you choose to install it. To manage services, update, or uninstall the stack, simply re-run the command in your terminal at any time.

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
The ZAMPP Dashboard is a shell script powered by Homebrew. It runs directly from GitHub and leaves no footprint on your system. Your web stack is only installed once you explicitly choose to do so.

## Is the ZAMPP Dashboard free?
Yes, the ZAMPP Dashboard is 100% free and open source.

## Support & Contributions
If you enjoy using ZAMPP, please give it a star on GitHub to help others find it.

If you run into any errors or bugs, please let me know by opening an [issue](https://github.com/zatikbalazs/zampp/issues) or sending a [pull request](https://github.com/zatikbalazs/zampp/pulls).
