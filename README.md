# d77venom

My own collection of Venom Linux ports.

Install fakeroot to build like this (inside port directory):

```
fakeroot pkgbuild
```

To install use:

```
sudo pkgbuild -i
```

Alternatively add it to /etc/scratchpkg.repo file like this:

```
/usr/ports/d77venom	https://github.com/dani-77/d77venom master
```

Enjoy!
