# centos6-vault

On November 11, 2020 support for CentOS 6 ended. So we cannot use `yum` on
CentOS 6 official images, because the yum repositories are no longer operated.
This image replaces urls in `/etc/yum.repos.d` with https://vault.centos.org.
Use this image as drop-in replacement for official `centos:6` (`centos:6.10`).

## Credits

Derived from [centos5-vault] by じゅりあす (astj)

[centos5-vault]: https://github.com/astj/docker-centos5-vault
