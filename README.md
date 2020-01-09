# image-shrink-backup

Tool to shrink and backup a Raspbian image

1. Create a custom Raspbian image

1. Insert the SD card into your computer

1. Run `resize.sh` on Linux or `resize-mac.sh` on Mac

    First, the rootfs partition will be resized down to a minimum size, then it
    will ask if you want to back up the image. If you want to backup the image,
    continue and provide a filename.

    You now have your shrunk-down image saved on your computer in `~backups`.

    You can share this image with others. When they boot it they will need to
    expand the filesystem using `raspi-config`.
