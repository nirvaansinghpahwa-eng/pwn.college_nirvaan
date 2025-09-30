# Challenge 11: An Epic Filesystem Quest
In this challenge, I have hidden the flag! Here, you will use ls and cat to follow my breadcrumbs and find it! Here's how it'll work:
1.	Your first clue is in /. Head on over there.
2.	Look around with ls. There'll be a file named HINT or CLUE or something along those lines!
3.	cat that file to read the clue!
4.	Depending on what the clue says, head on over to the next directory (or don't!).
5.	Follow the clues to the flag!

## My solve
**Flag:** ` pwn.college{YkLAUrlBQB99Dcfb3DNveUjjE2P.QX5IDO0wCN2MzNzEzW}’


```
hacker@commands~an-epic-filesystem-quest:~$ cd /
hacker@commands~an-epic-filesystem-quest:/$ ls
CUE  bin  boot  challenge  dev  etc  flag  home  lib  lib32  lib64  libx32  media  mnt  nix  opt  proc  root  run  sbin  srv  sys  tmp  usr  var
hacker@commands~an-epic-filesystem-quest:/$ cat flag
cat: flag: Permission denied
hacker@commands~an-epic-filesystem-quest:/$ ls -a
.   .dockerenv  bin   challenge  etc   home  lib32  libx32  mnt  opt   root  sbin  sys  usr
..  CUE         boot  dev        flag  lib   lib64  media   nix  proc  run   srv   tmp  var
hacker@commands~an-epic-filesystem-quest:/$ cat CUE
Yahaha, you found me!
The next clue is in: /usr/share/racket/pkgs/frtime/opt

hacker@commands~an-epic-filesystem-quest:/$ cd /usr/share/racket/pkgs/frtime/opt
hacker@commands~an-epic-filesystem-quest:/usr/share/racket/pkgs/frtime/opt$ ls -a
.  ..  WHISPER  compiled  frtime-opt-lang.rkt  frtime-opt.rkt  lang  lowered-equivs.rkt
hacker@commands~an-epic-filesystem-quest:/usr/share/racket/pkgs/frtime/opt$ cat WHISPER
Lucky listing!
The next clue is in: /usr/local/lib/python3.8/dist-packages/outcome

hacker@commands~an-epic-filesystem-quest:/usr/share/racket/pkgs/frtime/opt$ cd /usr/local/lib/python3.8/dist-packages/outcome
hacker@commands~an-epic-filesystem-quest:/usr/local/lib/python3.8/dist-packages/outcome$ ls -a
.  ..  TIP  __init__.py  __pycache__  _impl.py  _util.py  _version.py  py.typed
hacker@commands~an-epic-filesystem-quest:/usr/local/lib/python3.8/dist-packages/outcome$ cat TIP
Lucky listing!
The next clue is in: /usr/share/locale/mn/LC_MESSAGES

The next clue is **hidden** --- its filename starts with a '.' character. You'll need to look for it using special options to 'ls'.
hacker@commands~an-epic-filesystem-quest:/usr/local/lib/python3.8/dist-packages/outcome$ cd /usr/share/locale/mn/LC_MESSAGES
hacker@commands~an-epic-filesystem-quest:/usr/share/locale/mn/LC_MESSAGES$ ls -a
.  ..  .EVIDENCE  iso_3166-1.mo  iso_3166-3.mo  iso_3166.mo  iso_4217.mo  iso_639-2.mo  iso_639-3.mo  iso_639.mo  iso_639_3.mo
hacker@commands~an-epic-filesystem-quest:/usr/share/locale/mn/LC_MESSAGES$ cat .EVIDENCE
Great sleuthing!
The next clue is in: /usr/local/lib/python3.8/dist-packages/traitlets/utils/__pycache__

Watch out! The next clue is **trapped**. You'll need to read it out without 'cd'ing into the directory; otherwise, the clue will self destruct!

hacker@commands~an-epic-filesystem-quest:/usr/share/locale/mn/LC_MESSAGES$ ls /usr/local/lib/python3.8/dist-packages/traitlets/utils/__pycache__
DOSSIER-TRAPPED          decorators.cpython-38.pyc    importstring.cpython-38.pyc   text.cpython-38.pyc
__init__.cpython-38.pyc  descriptions.cpython-38.pyc  nested_update.cpython-38.pyc  warnings.cpython-38.pyc
bunch.cpython-38.pyc     getargspec.cpython-38.pyc    sentinel.cpython-38.pyc
hacker@commands~an-epic-filesystem-quest:/usr/share/locale/mn/LC_MESSAGES$ cat /usr/local/lib/python3.8/dist-packages/traitlets/utils/__pycache__
/DOSSIER-TRAPPED
Great sleuthing!
The next clue is in: /opt/linux/linux-5.4/drivers/net/ethernet/sfc

The next clue is **delayed** --- it will not become readable until you enter the directory with 'cd'.

hacker@commands~an-epic-filesystem-quest:/usr/share/locale/mn/LC_MESSAGES$ cd /opt/linux/linux-5.4/drivers/net/ethernet/sfc
hacker@commands~an-epic-filesystem-quest:/opt/linux/linux-5.4/drivers/net/ethernet/sfc$ ls -a
.                Makefile    ef10.c        efx.c      falcon        io.h        mcdi_pcol.h   nic.c  selftest.c     siena_sriov.h  tx.h
..               REVELATION  ef10_regs.h   efx.h      farch.c       mcdi.c      mcdi_port.c   nic.h  selftest.h     sriov.c        tx_tso.c
.built-in.a.cmd  bitfield.h  ef10_sriov.c  enum.h     farch_regs.h  mcdi.h      mtd.c         ptp.c  siena.c        sriov.h        vfdi.h
Kconfig          built-in.a  ef10_sriov.h  ethtool.c  filter.h      mcdi_mon.c  net_driver.h  rx.c   siena_sriov.c  tx.c           workarounds.h
hacker@commands~an-epic-filesystem-quest:/opt/linux/linux-5.4/drivers/net/ethernet/sfc$ cat REVELATION
Lucky listing!
The next clue is in: /opt/linux/linux-5.4/arch/arm64/boot/dts/bitmain

The next clue is **delayed** --- it will not become readable until you enter the directory with 'cd'.

hacker@commands~an-epic-filesystem-quest:/opt/linux/linux-5.4/drivers/net/ethernet/sfc$ cd /opt/linux/linux-5.4/arch/arm64/boot/dts/bitmain
hacker@commands~an-epic-filesystem-quest:/opt/linux/linux-5.4/arch/arm64/boot/dts/bitmain$ ls -a
.  ..  Makefile  POINTER  bm1880-sophon-edge.dts  bm1880.dtsi
hacker@commands~an-epic-filesystem-quest:/opt/linux/linux-5.4/arch/arm64/boot/dts/bitmain$ cat POINTER
Great sleuthing!
The next clue is in: /usr/share/man/it/man5

The next clue is **delayed** --- it will not become readable until you enter the directory with 'cd'.

hacker@commands~an-epic-filesystem-quest:/opt/linux/linux-5.4/arch/arm64/boot/dts/bitmain$ cd /usr/share/man/it/man5
hacker@commands~an-epic-filesystem-quest:/usr/share/man/it/man5$ ls -a
.       adduser.conf.5.gz     deb-extra-override.5.gz  deb-split.5.gz     gshadow.5.gz     passwd.5.gz
..      apt.conf.5.gz         deb-old.5.gz             deluser.conf.5.gz  login.defs.5.gz  shadow.5.gz
NUGGET  apt_preferences.5.gz  deb-override.5.gz        faillog.5.gz       manpath.5.gz
hacker@commands~an-epic-filesystem-quest:/usr/share/man/it/man5$ cat NUGGET
Congratulations, you found the clue!
The next clue is in: /usr/local/lib/python3.8/dist-packages/jedi/third_party/typeshed/third_party/2and3/pymysql

hacker@commands~an-epic-filesystem-quest:/usr/share/man/it/man5$ cd /usr/local/lib/python3.8/dist-packages/jedi/third_party/typeshed/third_party/2and3/pymysql
hacker@commands~an-epic-filesystem-quest:/usr/local/lib/python3.8/dist-packages/jedi/third_party/typeshed/third_party/2and3/pymysql$ ls -a
.  ..  LEAD  __init__.pyi  charset.pyi  connections.pyi  constants  converters.pyi  cursors.pyi  err.pyi  times.pyi  util.pyi
hacker@commands~an-epic-filesystem-quest:/usr/local/lib/python3.8/dist-packages/jedi/third_party/typeshed/third_party/2and3/pymysql$ cat LEAD
CONGRATULATIONS! Your perserverence has paid off, and you have found the flag!
It is: pwn.college{YkLAUrlBQB99Dcfb3DNveUjjE2P.QX5IDO0wCN2MzNzEzW}
```

## What I learned
How to navigate through files and read their contents. Also learned about delayed files and trapped files.

## Incorrect tangents
None

## References
None
