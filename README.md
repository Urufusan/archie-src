# Please read devdiary.txt !!!

## Welcome to the Release of archie-3.5



1. First start by FTPing the distribution:

-archie-3.5-beta-install.tar
-archie-3.5-beta-arch-version.tgz
-archie-3.5-beta-arch-base.tgz -- (for a full release install)

   where arch-version is one of: `sunos-4.1.4`, `sunos-5.4`, or `aix-3.2`.

2. Untar `archie-3.5-beta-install.tar`.

- ``tar xvpf archie-3.5-beta-install.tar``
 
   There you will find three scripts that will be used to install the
   binaries, `unwrap`, `untar`, and `unrotate`. We are trying out a new
   distribution approach. The single command, `unwrap` should take care of
   installing the server.

3. To install the server software, as superuser, type:

- ``./unwrap``

   And follow the instructions and suggestions. Please let us know what you
   think of this installation script.

4. Finally, don't forget to set the permissions. As superuser type:

- ``cd ~archie/config``
- ``make``

