# Metapackages

Run the `update` script to automatically generate new dependency
lists.  The result will be based on the published seed lists, filtered
by:

- The Packages files (nonexistent packages will be skipped)

- debootstrap (packages not yet added to debootstrap will not be added
  to ubuntu-base)

`update.cfg` tells `update` where seeds are located and which distro release to build against
