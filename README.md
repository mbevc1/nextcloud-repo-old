# nextcloud-repo
Nextcloud RPM repo

## RHEL/CentOS

Add repository setting:

```
$ sudo vim /etc/yum.repos.d/trivy.repo
[nextcloud]
name=Nextcloud repository
baseurl=https://mbevc1.github.io/nextcloud-repo/rpm/releases/$releasever/$basearch/
gpgcheck=0
enabled=1
$ sudo yum -y update
$ sudo yum -y install nextcloud
```
