# Fedora Bugs


# Image thumbnails not showing in Files on Fedora 43 (GNOME) 

After upgrading to Fedora 43 (GNOME), image thumbnails for new images are no longer showing in Files. Thumbnails for images I already had are still showing though. Does this happen for anyone else?

Link : [source](https://www.reddit.com/r/Fedora/comments/1p2fp4h/image_thumbnails_not_showing_in_files_on_fedora/)

How to fix:

```bash
sudo dnf install glycin-thumbnailer 
```


