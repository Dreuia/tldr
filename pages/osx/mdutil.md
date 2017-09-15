# mdutil

> Manage the metadata stores used by Spotlight.

- Spotlight caches indexes of some network devices locally:

`mdutil -p`
   
- Cause each local store for the volumes indicated to be erased:

`mdutil -E`

- Display the indexing status of the listed volumes:

`mdutil -s`

- Apply command to all volumes:

`mdutil -a`

- Print verbose information when available:

`mdutil -v`
