# chilipie-kiosk

**Raspberry Pi 2** image for booting directly into **full-screen Chrome**. Main features:

* **Boots directly to full-screen Chrome** - with all the features of a modern browser
* **No automatic updates** - no surprises due to Chrome (or other packages) suddenly updating
* **Automatic crash-recovery** - accidentally unplugging your kiosk won't result in "Chrome did not shut down correctly :("
* **Custom startup graphics** - displays [customizable graphics](home/background.png) while the browser is starting up
* **Lightweight window manager** - uses [Matchbox](https://www.yoctoproject.org/tools-resources/projects/matchbox) for minimal clutter and memory footprint
* **HDMI output control** - ready-made scripts for e.g. turning off the display outside of office hours
* **Cursor hiding** - if you leave a mouse plugged in, the cursor is hidden after a brief period of inactivity
* **Based on a recent Ubuntu** - if you want to add your own hacks, all the expected packages are one `apt-get` away

## Hardware

Not all hardware works perfectly with the Pi, so you'll want to do some digging. The product links are a configuration that's known to work, though:

* Raspberry Pi 2 ([verkkokauppa.com](https://www.verkkokauppa.com/fi/product/4657/fjxtn/Raspberry-Pi-2-model-B-yhden-piirilevyn-tietokone))
* 8+ GB microSD card ([verkkokauppa.com](https://www.verkkokauppa.com/fi/product/6501/dcmkv/Transcend-8GB-microSDHC-muistikortti-Class-10))
* Micro-USB power source (most people will have these laying around)
* Display cable, either
    * Regular HDMI for televisions, or
    * HDMI-to-DVI for computer displays

Optional extras:

* Case for the Pi ([verkkokauppa.com](https://www.verkkokauppa.com/fi/product/52391/fcrhq/Raspberry-Pi-muovikotelo-Raspberry-Pi-B-Pi-2-tietokoneille-l)) - if you're worried about looks and/or gathering dust
* USB WiFi-dongle ([verkkokauppa.com](https://www.verkkokauppa.com/fi/product/41271/dqnbc/Asus-USB-N10-Nano-WiFi-adapteri)) - if you can't get ethernet, which will usually be more reliable
* Big Red Button ([Dream Cheeky](http://dreamcheeky.com/big-red-button)) - if you want a simple way to interact with the kiosk

## Software

TODO
