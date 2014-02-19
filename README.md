# _Project_

_Description: Vagrantfile and Puppet manifests for creating a CentOS based PHP Development VM_

## Project Setup

_How do I, as a developer, start working on the project?_ 

1. _Install Vagrant_
2. _Check out this GitHub repository to a new directory_
3. _Run `vagrant up` inside the directory that contains this repository_

## More Information

### _Symfony2_

- _Modify AppKernel.php to return a cache and log directory relative to /tmp/symfony2_
- _Vagrant user is a member of the www-data group and the www-data group has write permissions to vhost directories and /tmp/symfony2_

## Defaults

### Network Settings

> - Network IP: 10.0.0.100
> - Hostname: ross.dev

## License