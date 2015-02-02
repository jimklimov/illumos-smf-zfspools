# illumos-smf-zfspools
ZFS pools as SMF services, as detailed in my article on OI Wiki
http://wiki.openindiana.org/oi/Advanced+-+ZFS+Pools+as+SMF+services+and+iSCSI+loopback+mounts

NOTE: Currently the SMF method scripts and manifests presented here are
considered templates. Some manual chiseling work is expected from the
user to tune these for realities of a particular system. See the Wiki
article for more details.

Generally users only interested in making a ZFS pool an SMF instance
should only fetch the resources from `phase1-zfs-pool` directory.

Scripts here are kept not-executable to remind that they need to be
manually tuned first.

Hope this helps,
Jim Klimov
