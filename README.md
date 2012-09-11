# Puppet for Java developers

Examples of using Puppet with other helpful tools for my talk Puppet for Java Developers.

* [Vagrant](http://vagrantup.com) for VM creation and provisioning
* [librarian-puppet](http://librarian-puppet.com/) for automatic module installation
* [puppet-rspec](http://rspec-puppet.com) for puppet manifest testing


## Installation


Install all required gems

```
bundle install
```

Install all Puppet modules with Puppet Librarian

```
librarian-puppet install
```

Run the specs with puppet-rspec

```
bundle exec rake
```

Start all the vms with Vagrant

```
vagrant up
```
