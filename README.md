about
=====

diffrpm create a "diff" between two RPM files.

usage
=====

    diffrpm FILE1 FILE2

example
-------

    $ ./diffrpm httpd-tools-2.2.15-29.el6.centos.x86_64.rpm httpd-2.2.15-30.el6.centos.x86_64.rpm
    Only in httpd-2.2.15-30.el6.centos.x86_64.rpm:: etc
    Only in httpd-tools-2.2.15-29.el6.centos.x86_64.rpm:/usr: bin
    Only in httpd-2.2.15-30.el6.centos.x86_64.rpm:/usr: lib64
    Only in httpd-2.2.15-30.el6.centos.x86_64.rpm:/usr: sbin
    Only in httpd-2.2.15-30.el6.centos.x86_64.rpm:/usr/share/doc: httpd-2.2.15
    Only in httpd-tools-2.2.15-29.el6.centos.x86_64.rpm:/usr/share/doc: httpd-tools-2.2.15
    Only in httpd-tools-2.2.15-29.el6.centos.x86_64.rpm:/usr/share/man: man1
    Only in httpd-2.2.15-30.el6.centos.x86_64.rpm:/usr/share/man: man8
    Only in httpd-2.2.15-30.el6.centos.x86_64.rpm:: var

