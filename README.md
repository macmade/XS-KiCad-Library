XS-KiCad-Library
================

[![Issues](http://img.shields.io/github/issues/macmade/XS-KiCad-Library.svg?logo=github)](https://github.com/macmade/XS-KiCad-Library/issues)
![Status](https://img.shields.io/badge/status-active-brightgreen.svg?logo=git)
![License](https://img.shields.io/badge/license-ohl-brightgreen.svg?logo=open-source-initiative)  
[![Contact](https://img.shields.io/badge/follow-@macmade-blue.svg?logo=twitter&style=social)](https://twitter.com/macmade)
[![Sponsor](https://img.shields.io/badge/sponsor-macmade-pink.svg?logo=github-sponsors&style=social)](https://github.com/sponsors/macmade)

### About

KiCad Library for XS-Labs projects.

### How To Use

From KiCad's "Preferences" menu, choose "Configure Paths..." and add the path to this repository as `XS_KICAD_DIR`.

Then from  KiCad's "Preferences" menu, choose "Manage Footprint Libraries..." and add the path to the `${XS_KICAD_DIR}/XS.pretty` as `XS`.  
You can do that globally or per project.

### Standards

This library uses IPC-7251, IPC-2222 and IPC-2221 to determine pads and holes sizes:

```
Hole Diameter: Max Lead Diameter   + ( 0.25 | 0.20 | 0.15 )
Pad Diameter:  Hole Diameter + 0.1 + ( 0.60 | 0.50 | 0.40 )
```

License
-------

All project files are released under the terms of the CERN Open Hardware License - CERN OHL v.1.2.

Repository Infos
----------------

    Owner:          Jean-David Gadina - XS-Labs
    Web:            www.xs-labs.com
    Blog:           www.noxeos.com
    Twitter:        @macmade
    GitHub:         github.com/macmade
    LinkedIn:       ch.linkedin.com/in/macmade/
    StackOverflow:  stackoverflow.com/users/182676/macmade
