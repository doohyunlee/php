# APACHE PHP7   [ 작성중 ] 
vagrant development environment construct

## Setting Info
Type | VM Spec | Data Shared | spec | php.ini setting
------------ | ------------- | ------------- | ------------- | -------------
php7 | memory:8192, cpus:4 | /var/www/html/data | apache2, php7, php gd, curl, redis, php mcrypt | short_open_tag=on, timezone=Asia/Seoul


## WINDOWS

### File Download
   * virtualBox install( https://www.virtualbox.org/ )
   * vagrant install( https://www.vagrantup.com/ )
   
### vagrant git clone or download
   
### "vagrant up --provision" command input [ workspace root ]  // Use --provision option only at first setting

Vagrant Account
* user : vagrant / vagrant
* root : root / vagrant

Vagrant Instruction
* workspace root move
* vagrant instruction action
  - vagrant up ( vagrant start ) or config.vm.provision add -> vagrant up --provision
  - vagrant halt ( vagrant halt )
  - vagrant reload ( vagrant reload )
  - vagrant box list ( vagrant box list )
  - vagrant box remove {vagrant name} ( vagrant box remove )
* vagrant up check -> vm

