# dev_RIVagrantDocker
Reference Implementation Vagrant Docker Conversion Template 

##### For Ubuntu Error timeout with SSH insecure key
[https://github.com/hashicorp/vagrant/issues/11199](https://github.com/hashicorp/vagrant/issues/11199) <br/>

Fix: Extend timeout by adding in Vagrantfile line: <br/>
```
# Default is 300, so you could double it at first to see if that works
config.vm.boot_timeout = 600
```

##### Using RHEL 7 Universal Base Images for Docker
[https://developers.redhat.com/blog/2020/03/24/red-hat-universal-base-images-for-docker-users/](https://developers.redhat.com/blog/2020/03/24/red-hat-universal-base-images-for-docker-users/) <br/>


