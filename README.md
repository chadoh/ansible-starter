Ansible Starter
===============

A simple example of an [Ansible] setup for use with [Vagrant].

It requires you use an apt-compatible OS (Debian, Ubuntu).

It installs basic packages such as curl and git, then installs

* [RVM]
* Ruby 1.9.2 (& sets it as the default)
* Postgresql

And it sets up an example dev and test database (which are actually the
dev and test database for the [pcmag] project) and runs `bundle install`
in the project directory.

But you could have figured all of this out by reading playbook.yml just
as quickly as you read this.

  [Ansible]: http://ansible.cc
  [Vagrant]: http://www.vagrantup.com
  [RVM]: https://rvm.io
  [pcmag]: https://github.com/chadoh/pcmag
