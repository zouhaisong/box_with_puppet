# Quick Start
- install
`bundle install`

- build
`bundle exec veewee vbox build 'CentOS-6.5-x86_64-minimal'`

- export
`bundle exec veewee vbox export 'CentOS-6.5-x86_64-minimal'`

# Speed Up

- Download iso unless not exist CentOS-6.5-x86_64-minimal.iso locally
`wget -c http://yum.singlehop.com/CentOS/6.5/isos/x86_64/CentOS-6.5-x86_64-minimal.iso`

- Move CentOS-6.5-x86_64-minimal.iso to ./iso
mv CentOS-6.5-x86_64-minimal.iso ./iso


# Users
veewee/veewee
vagrant/vagrant

# Tips
Sometime yum repo don't work while install puppet. Try more times or use vpn

# Resources
https://github.com/jedi4ever/veewee/blob/master/doc/vagrant.md

