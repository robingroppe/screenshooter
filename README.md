# screenshooter
A simple Script to create a Screenshot, upload it to your webspace and copy the URL in you clipboard.
It's using SSH per default but can be configured to use FTP for the insane ones under us.

Works with Cinnamon, Gnome, Unity, MATE and KDE. :)

You may need to install curl for the screenshot to be uploaded and xclip for the URL to get copied in your clipboard and set up a certificate for SSH.
Unfortunately on MATE you need to install gnome-screenshot as of this time mate-screenshot is not able to write directly into a file.
