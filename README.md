# Dockerized Ansible-enabled Debian 7.0 "Wheezy"

Dockerfile definition for a Debian 7.0 image with the backported Ansible package.

Note that this backported package lags behind the most recent Ansible version, 
which is OK for most cases, unless you need some of the latest [Ansible modules][mods].

If you need a more up-to-date Ansible version, consider the [vivaserver/ansible:precise][prec] image.

The Docker image is also available for pulling from the [Docker Hub][vsrv]:

    $ sudo docker pull vivaserver/ansible:wheezy

[prec]: https://github.com/vivaserver/docker-ansible-precise
[mods]: http://docs.ansible.com/modules_by_category.html
[vsrv]: https://registry.hub.docker.com/u/vivaserver/ansible/

## License

Released under the [MIT License](http://www.opensource.org/licenses/MIT).

## Copyright

(c)2015 [Cristian R. Arroyo](mailto:cristian.arroyo@vivaserver.com)
