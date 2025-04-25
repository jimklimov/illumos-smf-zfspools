# illumos-smf-zfspools
ZFS pools as SMF services, as detailed in my article on OI Wiki
backed up at
https://web.archive.org/web/20200428053251/https://wiki.openindiana.org/oi/Advanced+-+ZFS+Pools+as+SMF+services+and+iSCSI+loopback+mounts
or https://github.com/jimklimov/illumos-articles/blob/master/articles/Advanced%20-%20ZFS%20Pools%20as%20SMF%20services%20and%20iSCSI%20loopback%20mounts%20-%20OpenIndiana%20Wiki.mht?raw=true
(as MHT archive, most browsers read that), and some time ago originally posted at
http://wiki.openindiana.org/oi/Advanced+-+ZFS+Pools+as+SMF+services+and+iSCSI+loopback+mounts

NOTE: Currently the SMF method scripts and manifests presented here are
considered templates. Some manual chiseling work is expected from the
user to tune these for realities of a particular system. See the Wiki
article or the scripts' sources for more details.

Generally users only interested in making a ZFS pool an SMF instance
should only fetch the resources from `phase1-zfs-pool` directory, then
update paths and pool names and follow other suggestions commented in
the script.

Scripts here are kept not-executable to remind that they need to be
manually tuned first.

For related trickery, please see also:

* https://github.com/jimklimov/illumos-articles
* https://github.com/jimklimov/illumos-splitroot-scripts
* https://github.com/jimklimov/illumos-smf-zones

...and loosely related by general theme:

* https://github.com/jimklimov/vboxsvc

Hope this helps,
Jim Klimov
