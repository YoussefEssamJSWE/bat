# bat packaging

Debian and Snap packaging for the `bat` command-line file viewer written in Rust.

This repository contains the packaging metadata required to build:

- a Debian package using the files under the `debian/` directory
- a Snap package using `snap/snapcraft.yaml`

The packaging is intentionally small and close to upstream. It is meant to be
used together with the official `bat` source code (fetched from upstream Git)
to produce `.deb` and `.snap` artifacts for Ubuntu/Debian-based systems.
