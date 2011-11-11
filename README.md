# mintupdate-debian #

## TODO: Changelogs ##

`aptitude changelog` should get nice parsing, a la `aptitude-gtk`.

Changelogs for some packages display better than others; this appears to be due to loose [format policy](http://www.debian.org/doc/debian-policy/ch-source.html#s-dpkgchangelog).

From what I can tell, clickable hyperlinks (e.g., closes:# --> bugs.debian.org) are a an [ancient request](https://bugzilla.gnome.org/show_bug.cgi?id=59390).  Not sure if this is resolved in gtk3.

[solution?](http://www.daa.com.au/pipermail/pygtk/2004-December/009352.html)
