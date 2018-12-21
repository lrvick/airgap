# Tools #

## Hardware Security Modules
- [btchip]: Utilities to interact with Ledger hardware wallets
- [trezorctl]: Utilities to interact with Trezor hardware wallet
- [keepkeyctl]: Utilities to interact with Keepkey hardware wallets
- [yubico-piv-tool]: Interact with PIV application on Yubikey
- [yubikey-hsm]: Manage YubiHSM Hardware Security Modules for servers.
- [yhsm-tools]: Various utilities for use of YubiHSM.
- [yubikey-personalization]: Various settings management for yubikeys.
- [ykneomgr]: Modify settings for Yubikey Neo

## Cryptocurrency
- [gen-hdwallet]: Simple script to export a bip44 wallet as jsony
- [bx]: Bitcoin tools for signing transactions, managing keys, etc.
- [electrum]: Utilities for popular bitcoin wallet format

## Entropy
- [haveged]: Daemon that acts as a software random number generator
- [rng-tools]: Daemon that supports many different hardware TRNG devices
- [infnoise]: Fetch entropy from the Infinite Noise TRNG

## Cryptography
- [gen-gpgchain]: Generate 4096RSA gpg keychain suitable for a hardware token
- [gnupg]: Perform PGP operations for local keys or smartcards
- [scrypt]: creating password key derivations using the Script algorithm
- [ssdeep]: Recursive piecewise hashing tool
- [hash-slinger]: Create TLSA records for the DANE protocol
- [seccure]: Tools for elliptic curve cryptography
- [monkeysphere]: Utilities for extended use cases of OpenGPG
- [pgpgpg]: Wrapper for using GnuPG in programs designed for PGP
- [signing-party]: Various OpenPGP related tools for assisting with signing.
- [pius]: Quick and easy signing of each UID on a PGP keyring
- [ssl-cert]: Simple debconf wrapper for OpenSSL
- [openssl]: Secure Socket Layer (SSL) binary and related cryptographic tools
- [gpgv]: GNU privacy guard - signature verification tool
- [pgpdump]: PGP packet visualizer
- [keyringer]: Distributed secret management using GnuPG and Git
- [keyutils]: Linux Key Management Utilities

## Backup
- [ssss]: Backup secrets into parts shared with multiple trusted individuals
- [paperkey]: Backup PGP key to paper in a human friendly format
- [qrencode]: Render data as QR code for easy transfer to mobile device
- [duplicity]: GPG encrypted backup solution
- [rsync]: Fast, versatile, remote (and local) file-copying tool

## Password Management
- [pass]: Simple text file based password manager based on GPG and Git
- [cpm]: Curses based password manager using PGP
- [kpcli]: Interact with KeePassX password manager databases
- [pwman3]: Console password management application
- [passwordmaker-cli]: Creates unique, secure passwords - CLI version
- [apg]: Automated Password Generator - Standalone version
- [libpwqulity-tools]: Tools for password quality checking and generation
- [pwgen]: Automatic Password generation
- [donkey]: One Time Password calculator
- [otpw-bin]: Generate One Time Password lists
- [hashalot]: Read and hash a passphrase
- [yapet]: Yet Another Password Encryption Tool

## Password Recovery
- [hydra]: Very fast logon cracker
- [pdfcrack]: PDF files password cracker.
- [fcrackzip]: password cracker for zip archives
- [rarcrack]: Password cracker for rar archives
- [ophcrack-cli]: Microsoft Windows password cracker using rainbow tables
- [chntpw]: NT SAM password recovery utility
- [john]: Active password list creation and cracking tool
- [crack]: Password guessing program
- [lcrack]: A generic password cracker
- [nasty]: recover the passphrase of your PGP or GPG-key

## Release Management
- [twine]: Prepare/Sign Python packages
- [debsigs]: Sign Debian packages

## RFID / NFC
- [mfoc]: MiFare Password Cracker
- [mfcuk]: MiFare Classic Universal toolKit (MFCUK)
- [libfreefare]: Mifare/desfire manipulation tools
- [nfctool]: Manage NFC devices and read/write tags via neard.
- [neard]: Near Field Communication (NFC) management daemon
- [ndeftool]: Create/Manipulate NDEF formatted packets
- [libchipcard-tools]: Tools for accessing chipcards
- [rfdump]: Tool to decode RFID tag data

## Utilities
- [vim]: Vi IMproved - enhanced vi editor
- [emacs]: GNU Emacs editor (metapackage)
- [nano]: Small, friendly text editor inspired by Pico
- [p7zip]: 7z file archiver with high compression ratio
- [jq]: Extract, manipulate, or create JSON
- [tmux]: Terminal window manager and multiplexer
- [ncdu]: Ncurses disk usage viewer
- [glances]: CLI curses based monitoring tool
- [htop]: Interactive processes viewer/manager
- [strace]: A system call tracer
- [gdb]: The GNU Debugger
- [guncat]: Concatenates files while decrypting PGP-encrypted sections
- [zfsnap]: Automatic snapshot creation and removal for ZFS
- [zfs-fuse]: ZFS on FUSE
- [usbutils]: Examine attached USB devices

## Programming Languages
- [python]: interactive high-level object-oriented language
- [nodejs]: evented I/O for V8 javascript
- [perl]: Larry Wall's Practical Extraction and Report Language

[unhide]: http://www.unhide-forensics.info/
[usbutils]: https://github.com/gregkh/usbutils
[mfoc]: https://github.com/nfc-tools/mfoc
[mfcuk]: https://github.com/nfc-tools/mfcuk
[libfreefare]: http://www.nfc-tools.org/index.php?title=Libfreefare
[nfctool]: http://manpages.ubuntu.com/manpages/trusty/man1/nfctool.1.html
[ndeftool]: https://github.com/nfcpy/ndeftool
[infnoise]: https://github.com/waywardgeek/infnoise
[rng-tools]: https://www.kernel.org/doc/Documentation/hw_random.txt
[haveged]: http://issihosts.com/haveged/
[bx]: https://github.com/libbitcoin/libbitcoin-explorer/wiki
[hash-slinger]: https://packages.qa.debian.org/h/hash-slinger.html
[duplicity]: http://duplicity.nongnu.org/
[perl]: https://www.perl.org/
[yapet]: http://www.guengel.ch/myapps/yapet/
[otpw-bin]: http://www.cl.cam.ac.uk/~mgk25/otpw.html
[ssdeep]: http://ssdeep.sourceforge.net/
[hashalot]: http://www.paranoiacs.org/~sluskyb/
[kpcli]: http://kpcli.sourceforge.net/
[donkey]: https://devel.ringlet.net/security/donkey/
[seccure]: http://point-at-infinity.org/seccure/
[pius]: https://www.phildev.net/pius/
[cpm]: http://www.harry-b.de/dokuwiki/doku.php?id=harry:cpm
[nasty]: https://www.vanheusden.com/nasty/
[twine]: https://github.com/dstufft/twine
[mac-robber]: http://www.sleuthkit.org/mac-robber/desc.php
[rkhunter]: http://rkhunter.sourceforge.net/
[chkrootkit]: http://www.chkrootkit.org/
[zfsnap]: https://github.com/zfsnap/zfsnap
[zfs-fuse]: https://packages.qa.debian.org/z/zfs-fuse.html
[neard]: https://01.org/linux-nfc
[cardpeek]: http://pannetrat.com/Cardpeek/
[libchipcard-tools]: https://www.aquamaniac.de/sites/libchipcard/
[rfdump]: http://www.rfdump.org/
[htop]: http://hisham.hm/htop/
[keyringer]: https://keyringer.pw/
[keyutils]: http://people.redhat.com/~dhowells/keyutils/
[guncat]: https://fbb-git.github.io/guncat/
[gpgv]: https://www.gnupg.org/
[pgpdump]: http://www.mew.org/~kazu/proj/pgpdump/en/
[debsigs]: http://metadata.ftp-master.debian.org/changelogs/main/d/debsigs/unstable_changelog
[strace]: https://strace.io/
[gdb]: http://www.gnu.org/software/gdb/
[ssl-cert]: http://metadata.ftp-master.debian.org/changelogs/main/s/ssl-cert/unstable_changelog
[openssl]: https://www.openssl.org/
[vim]: http://www.vim.org/
[nano]: https://www.nano-editor.org/
[emacs]: https://packages.qa.debian.org/e/emacs-defaults.html
[glances]: https://nicolargo.github.io/glances/
[monkeysphere]: http://web.monkeysphere.info/
[pgpgpg]: https://packages.qa.debian.org/p/pgpgpg.html
[signing-party]: https://pgp-tools.alioth.debian.org/
[tmux]: https://github.com/tmux/tmux/wiki
[ncdu]: https://dev.yorhel.nl/ncdu
[rsync]: http://rsync.samba.org/
[p7zip]: http://p7zip.sourceforge.net/
[lcrack]: https://packages.qa.debian.org/l/lcrack.html
[rarcrack]: http://rarcrack.sourceforge.net/
[ophcrack-cli]: http://ophcrack.sourceforge.net/
[chntpw]: http://pogostick.net/~pnh/ntpasswd/
[john]: http://www.openwall.com/john/
[crack]: https://dropsafe.crypticide.com/alecm/software/crack/
[hydra]: https://www.thc.org/thc-hydra/
[pdfcrack]: http://pdfcrack.sourceforge.net/
[fcrackzip]: http://oldhome.schmorp.de/marc/fcrackzip.html
[python]: https://www.python.org/
[nodejs]: https://nodejs.org/en/
[jq]: https://stedolan.github.io/jq/
[pwgen]: https://packages.qa.debian.org/p/pwgen.html
[libpwqulity-tools]: https://fedoraproject.org/wiki/Infrastructure/Fedorahosted-retirement
[passwordmaker-cli]: http://passwordmaker.org/
[apg]: https://packages.qa.debian.org/a/apg.html
[qrencode]: https://packages.qa.debian.org/q/qrencode.html
[gen-hdwallet]: https://github.com/lrvick/airgap/blob/master/scripts/gen-hdwallet
[gen-gpgchain]: https://github.com/lrvick/airgap/blob/master/scripts/gen-gpgchain
[paperkey]: http://www.jabberwocky.com/software/paperkey/
[pass]: https://www.passwordstore.org/
[pwman3]: http://pwman3.github.io/pwman3/
[yubikey-hsm]: https://www.yubico.com/products/yubihsm/
[yubico-piv-tool]: https://developers.yubico.com/yubico-piv-tool/
[yubikey-personalization]: https://developers.yubico.com/yubikey-personalization/
[yhsm-tools]: https://developers.yubico.com/python-pyhsm/
[ykneomgr]: https://developers.yubico.com/libykneomgr/
[gnupg]: https://www.gnupg.org/
[electrum]: https://electrum.org/#home
[scrypt]: http://www.tarsnap.com/scrypt.html
[binwalk]: https://github.com/devttys0/binwalk
[trezorctl]: https://github.com/trezor/python-trezor
[keepkeyctl]: https://github.com/keepkey/python-keepkey
[ssss]: http://point-at-infinity.org/ssss/
[btchip]: https://github.com/LedgerHQ/btchip-c-api
[libbitcoin-explorr]: https://github.com/libbitcoin/libbitcoin-explorer/wiki
