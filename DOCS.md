# Documentation Table of Contents

1. [Readme](README.md)

2. [Installation](README.md#installation)

    a. [Pre-install instructions](PREINSTALL-README.md)
   
    b. [Using a Fedora Atomic ISO, then rebasing (Recommended)](README.md#rebasing-recommended)
   
    c. [Generating an ISO based on a secureblue image](README.md#iso)
   
    d. [Post-install instructions](POSTINSTALL-README.md)
   
    e. [Post-install instructions, specific to nvidia](README.md#nvidia)
   
3. [Hardening](README.md#what)
   
    a. [Chromium policy hardening](config/files/usr/etc/chromium/policies/managed/hardening.json.readme.md)
   
    b. [Chromium switch hardening](config/files/usr/etc/chromium/chromium.conf.md)
   
    c. [Chromium in secureblue, compared to Vanadium](config/files/usr/etc/chromium/vanadium_comparison.readme.md)
   
    d. [Kernel sysctl hardening](config/files/usr/etc/sysctl.d/hardening.conf)
   
    e. [Kernel module hardening](config/files/usr/etc/modprobe.d/blacklist.conf)
   
    f. [DNS hardening](config/files/usr/etc/systemd/resolved.conf.d/securedns.conf)
   
    g. [Chrony hardening](config/files/usr/etc/chrony.conf)
   
    h. [Flatpak hardening](config/files/usr/share/ublue-os/firstboot/yafti.yml#L20)
   
    i. [What is hardened malloc?](https://github.com/GrapheneOS/hardened_malloc/)
   
    j. [Brute force protection](config/scripts/authselect.sh)
   
    k. [Password encryption hardening](config/files/usr/etc/login.defs)
   
    l. [KDE GHNS disablement](config/files/kinoite/usr/etc/xdg/kdeglobals)
   
4. Important information
   
    a. [FAQ](FAQ.md)
   
    b. [User namespaces](USERNS.md)
   
    c. [Gaming](FAQ.md#why-wont-flatpak-steam-run)
   
    d. [Contributing guidelines](CONTRIBUTING.md)
   
    e. [Code of conduct](CODE_OF_CONDUCT.md)