# rp-pppoe

Forked version of rp-pppoe with ClearOS changes applied

## Update usage
  Add __#kojibuild__ to commit message to automatically build

* git clone git://github.com/clearos/rp-pppoe.git
* cd rp-pppoe
* git checkout c7
* git remote add upstream git://git.centos.org/rpms/rp-pppoe.git
* git pull upstream c7
* git checkout clear7
* git merge --no-commit c7
* git commit
