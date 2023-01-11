# OpenSSH backport for Enterprise Linux 8

Pre-built RPM packages are uploaded to [release page](https://github.com/MoeTools/openssh-el8/releases), use at your own risk.

## Install

Usually `openssh`, `openssh-server`, `openssh-client` is enought for common usage.

- Enable EPEL `dnf install epel-release`

- Download RPM packages form [release page](https://github.com/MoeTools/openssh-el8/releases)

-  `dnf localinstall ./*.rpm`

## Build

- You need to enable EPEL and PowerTools repository first.

- Source Tarball are not downloaded, use `--undefine=_disable_source_fetch` with `rpmbuild` command to download automatically.