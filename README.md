![retrosmart-preview](https://github.com/mdomlop/retrosmart-icon-theme/blob/master/preview.png "Retrosmart look")

Retrosmart icon theme
=====================

Retrosmart icon theme is a set of icons mainly based on the Haiku OS look.
Mainly the icons were taked from that project (with MIT license, and therefore
GPL compatible), some others were created from scratch or crafted from *other
forgotten sources* in the internet (with unknown licenses).

Due to *that last circumstace* I can not fully guarantee a GPL compatible
license for any else of this images.

If you found a image that has not a fully GPL compatible license, PLEASE WRITE
ME AN EMAIL AND THEN I WILL DELETE IT FOREVER.

For installation instructions please read
[INSTALL](https://github.com/mdomlop/retrosmart-icon-theme/blob/master/INSTALL.md) file.

Thank you.


Install instructions
--------------------

### Classic method ###

- Build and install:

        $ ./configure
        $ make
        # make install

- Uninstall:

        # make uninstall

### Debian package ###

- Build and install:

        $ make dpkg
        # dpkg -i retrosmart-icon-theme_*.deb

- Uninstall:

        # apt purge retrosmart-icon-theme

### Arch Linux package ###

- Build and install:

        $ make pacman
        # pacman -U retrosmart-icon-theme-local-*.pkg.tar.xz

- Uninstall:

        # pacman -Rsc retrosmart-icon-theme-local
