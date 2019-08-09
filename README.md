Arch Breeze
===========

This is a Plymouth theme for Arch Linux inspired by KDE Breeze.

The script is insired by the script from the dark-arch theme. The spinner
image is taken from KDE Breeze splash screen.

The theme wasn't tested with all possible features Plymouth offers.
Please provide feedback or suggestions how to improve it.


Installation
------------

```
$ yay -S plymouth-theme-arch-breeze-git
```

Once installed you can set it as your theme:

```
$ sudo plymouth-set-default-theme -R arch-breeze
```


Customization
-------------

This theme contains several version of the logo:

![Preview of all logos](https://cdn.rawgit.com/jtyr/plymouth-theme-arch-breeze/master/arch_logo.svg)

The logo can be changed by changing the
`/usr/share/plymouth/themes/arch-breeze/logo.png` symlink:

```
$ ln -sf /usr/share/plymouth/themes/arch-breeze/logo{_symb_blue,}.png
```


License
-------

MIT


Author
------

Jiri Tyr
