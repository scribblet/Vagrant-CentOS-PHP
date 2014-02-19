# _Project_

_Vagrantfile and Puppet manifests for creating a CentOS based PHP Development VM. Contains Apache2, MySQL, PHP 5.5, composer, phpMyAdmin and MailCatcher._

## Project Setup

_How do I, as a developer, start working on the project?_ 

1. _Install Vagrant_
2. _Check out this GitHub repository to a new directory_
3. _Run `vagrant up` inside the directory that contains this repository_

## More Information

### _Symfony2_

- _Modify AppKernel.php to return a cache and log directory relative to /tmp/symfony2_
- _Vagrant user is a member of the www-data group and the www-data group has write permissions to vhost directories and /tmp/symfony2_

### _Default Network Settings_

> - Network IP: 10.0.0.100
> - Port Forward -> Host: 1080 to Guest: 80

### _Virtual Hosts_
_ross.dev_
> - Directory: /srv/vhosts/ross.dev
> - Document Root: /srv/vhosts/ross.dev/web

### _PHP_

> - 5.5
> - Opcode Cache installed (php-opcache)

## License