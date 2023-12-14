# swaylock

swaylock is a screen locking utility for Wayland compositors. It is compatible
with any Wayland compositor which implements the ext-session-lock-v1 Wayland
protocol.

See the man page, [swaylock(1)](swaylock.1.scd), for instructions on using swaylock.

## About this fork
This is a fork of swaylock, where I simply added (copied from swaylock-effects, actually, which is abandoned) the possibility of having a clock in swaylock.
To enable it, config options are the same as in swaylock-effects.

When building on archlinux, use `arch-meson` instead of `meson`.

**I MAKE NO GUARANTEES ON MANTAINING THIS FORK**.

For everything else, refer to [swaylock](https://github.com/swaywm/swaylock).


