docker-cleanup-volumes.sh
======================

Shellscript to delete orphaned docker volumes in /var/lib/docker/volumes and /var/lib/docker/vfs/dir

usage: sudo ./docker-cleanup-volumes.sh [--dry-run]

--dry-run : Use the --dry-run option to have the script print the volumes that would have been deleted without actually deleting them.
