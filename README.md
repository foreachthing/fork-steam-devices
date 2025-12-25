# Installation

## Fedora
Copy `60-steam-input.rules` and `60-steam-vr.rules` files to `/etc/udev/rules.d/`.

Run `sudo udevadm control --reload-rules && sudo udevadm trigger` to reload the udev rules.
 
