
# Linux Utilities

#### Sources: Ubuntu repo, GitHub, vendor websites.

Simple alphabetical list (*Ctrl+F* everything) of useful Linux programs and packages - biased to my work, interests, and anticipated needs. Compiled over a number of years from Linux magazines and web searches.

###### *List is less than 1/70th of the packages in the main Ubuntu repository.*

A tick in the repo column means the package should exist in the main Ubuntu repo. Nevertheless, some packages can be hidden away - these are marked with *'use apt'* - use `apt search <pkg>` to search and `sudo apt-get install <pkg>` to install.

Some of the programs listed are included by default with Ubuntu-based distros. Nevertheless, they remain, since on some distro installs they are curiously absent.

**Ubuntu repo search**: http://packages.ubuntu.com/

----

package | description | repo | URL | notes |
---- | ---- | ---- | ---- | ---- |
p7zip | file archiver | :heavy_check_mark: | [7-Zip.org](http://www.7-zip.org/) | also p7Zip-full |
abcde | CD ripper | :heavy_check_mark: | [Andrews Corner](http://www.andrews-corner.org/linux/abcde/index.html) | |
abiword | lightweight wordprocessor | :heavy_check_mark: | | |
abricotine | Markdown editor | :heavy_multiplication_x: | [Abricotine](https://github.com/brd/Abricotine) | |
adb | Android tools | :heavy_check_mark: | | |
afick | file integrity notifier | :heavy_multiplication_x: | [AFICK](https://sourceforge.net/projects/afick/) | |
afl | fuzzer | :heavy_check_mark: | [afl](http://lcamtuf.coredump.cx/afl/) | |
aide | host-based IDS | :heavy_check_mark: | | |
aircrack-ng | wireless WEP/WPA cracker | :heavy_check_mark: | | |
alacritty | GPU-accelerated terminal emulator | :heavy_multiplication_x: | [alacritty](https://github.com/jwilm/alacritty) | |
alien | .rpm to .deb converter | :heavy_check_mark: | | |
anjuta | C/C++ editor | :heavy_check_mark: | | |
ansible | alternative to Puppet/Chef | :heavy_check_mark: | | dependencies are merely Python/SSH; `pip install ansible` |
ansifilter | remove control codes | :heavy_multiplication_x: | [AnsiFilter](http://andre-simon.de/doku/ansifilter/en/ansifilter.php) | |
antimony | CAD modeller | :heavy_multiplication_x: | [Antimony](http://www.mattkeeter.com/projects/antimony/) | |
antiword | Word files converted to text/PS/PDF | :heavy_check_mark: | | |
anydesk | TeamViewer-like remote desktop | :heavy_multiplication_x: | [AnyDesk](https://anydesk.com/remote-desktop) | |
apachetop | *top* for Apache | :heavy_check_mark: | | use `apt` |
apktool | read binary XML | :heavy_multiplication_x: | | |
aqemu | *Qemu* + KVM GUI | :heavy_check_mark: | | |
ardour | audio editor | :heavy_check_mark: | | |
arecabackup | backup | :heavy_multiplication_x: | [Areca Backup](http://areca-backup.org) | Java |
argus | IP network transaction auditor | :heavy_check_mark: | | |
argyll | monitor colour callibrator | :heavy_check_mark: | | GUI is dispcalgui |
arista | media converter | :heavy_check_mark: | transcoder.org | |
asciinema | terminal activity recorder | :heavy_multiplication_x: | [asciinema](http://asciinema.org/) | `asciinema rec >> exit` |
astyle | C indenter | :heavy_check_mark: | | |
asunder | CD ripper | :heavy_check_mark: | | |
athena-jot | data generator | :heavy_check_mark: | | |
atril | MATE PDF viewer | :heavy_check_mark: | | |
attr | filesystem extended attribute utils | :heavy_check_mark: | | |
audacious | music player | :heavy_check_mark: | | |
audacity | sound editor | :heavy_check_mark: | | |
aview | images to ASCII art | :heavy_check_mark: | | |
auditd | user auditing | :heavy_check_mark: | | auditctl, aureport, ausearch, autrace |
aura | background setter | :heavy_multiplication_x: | [Aura](https://sourceforge.net/projects/desktop-aura/) | |
autmater | webhost look-up | :heavy_multiplication_x: | | extensive look-up |
automysqlbackup | periodic backups of *MySQL* DBs | :heavy_check_mark: | | |
avahi-daemon | discover hosts | :heavy_check_mark: | | name instead of IP |
avidemux | video editor/converter | :heavy_multiplication_x:| | for quick edits to single video clip |
awffull | weblog analyser | :heavy_check_mark: | | localhost-based |
axel | terminal download accelerator | :heavy_check_mark: | | |
babeltrace | trace conversion | :heavy_check_mark: | | |
backerupper | tar.gz backups | :heavy_multiplication_x: | [Backerupper](https://sourceforge.net/projects/backerupper/) | allows file exclusion | |
bacula | backup | :heavy_check_mark: | | |
bashate | Bash script linter | :heavy_check_mark: | | |
beast | music synthesis | :heavy_check_mark: | | |
bfbtester | exe brute-force tester | :heavy_check_mark: | | |
billreminder | bill reminders | :heavy_multiplication_x: | [Bill Reminder](http://billreminder.gnulinuxbrasil.org) | |
binary-analyser | analyse binaries | :heavy_multiplication_x: | [Binary Analyser](https://bitbucket.org/mihaila/bindead/wiki/Home) | |
bing-ip2hosts | enumerate hostnames via Bing | :heavy_check_mark: | | |
binstats | stats tool for binaries | :heavy_check_mark: | | |
binwalk | binary file searcher | :heavy_check_mark: | [binwalk](https://github.com/devttys0/binwalk) | sub-files + code |
birdfont | font editor | :heavy_multiplication_x: | [BirdFont](http://birdfont.org) | |
bleachbit | file cleaner | :heavy_check_mark: | | |
bluelog | bluetooth scanner | :heavy_multiplication_x: | | |
blueman | bluetooth GUI | :heavy_check_mark: | | |
bluemon | de/activate programs on bluetooth link quality | :heavy_check_mark: | | |
bluetooth | support library | :heavy_check_mark: | | |
bmon | bandwidth monitor | :heavy_check_mark: | | |
bootchart | boot time analyser | :heavy_check_mark: | | |
boxbackup-client | Box backup | :heavy_check_mark: | [boxbackup](http://www.boxbackup.org/) | rsynch-like and encrypted |
boxbackup-server | Box backup | :heavy_check_mark: | [boxbackup](http://www.boxbackup.org/) | |
brandy | BBC Micro emulator | :heavy_check_mark: | | |
brasero | ISO burner | :heavy_check_mark: | | |
bridge-utils | configure ethernet bridge | :heavy_check_mark: | | |
broadband-speed | | :heavy_multiplication_x: | [Broadband Speed](https://github.com/sivel/speedtest-cli) | |
brutex | combine WFuzz/Hydra to brute-force ports | :heavy_multiplication_x: | [BruteX](https://github.com/1N3/BruteX) | |
btproxy | MITM Bluetooth analysis | :heavy_multiplication_x: | [btproxy](https://github.com/conorpp/btproxy ) | |
btscanner | scanner for bluetooth devices | :heavy_check_mark: | | |
bum | bootup manager | :heavy_check_mark: | | also *sysv-rc-conf* |
bvi | hex editor | :heavy_check_mark: | | vi-like |
byobu | screen command manager/multiplexer | :heavy_check_mark: | | through function keys |
cadubi | ASCII art drawing | :heavy_check_mark: | | |
calibre | ebook converter/library | :heavy_check_mark: | | |
catfish | GUI file search using *mlocate* | :heavy_check_mark: | | |
cccc | C/C++ code analyser | :heavy_check_mark: | | |
ccextractor | subtitle extractor | :heavy_multiplication_x: | [CCExtractor](https://sourceforge.net/projects/ccextractor/) | |
celestia | celestial simulator | :heavy_check_mark: | | |
cellwriter | handwriting recogniser | :heavy_check_mark: | | |
cflow | C code analyser | :heavy_check_mark: | | |
cdparanoia | CD ripper | :heavy_check_mark: | | |
ccrypt | AES, recursive file encrypter | :heavy_check_mark: | | overwrites files, passphrases allegedly unsalted |
checkbashisms | | :heavy_check_mark: | | in *devscripts* |
checkinstall | installation tracker | :heavy_check_mark: | | source > package > install with package manager |
checksecurity | basic security check | :heavy_check_mark: | | |
chaosreader | trace network sessions, export to HTML | :heavy_check_mark: | | |
cherrytree | notes organiser with 7zip encryption | :heavy_check_mark: | [CentOS version](http://rpm.pbone.net/index.php3/stat/4/idpl/26487133/dir/redhat_el_6/com/cherrytree-<ver>) | |
chkrootkit | rootkit detector | :heavy_check_mark: | | |
chntpw | change Windows SAM password | :heavy_check_mark: | | |
cinelerra | non-linear video editor | :heavy_check_mark: | | |
ckport | exe function/call checker | :heavy_check_mark: | | |
claws-mail | GTK mail client | :heavy_check_mark: | | |
clementine | music player/streamer | :heavy_check_mark: | | |
cloc | count lines of code | :heavy_check_mark: | [CLOC](https://sourceforge.net/projects/cloc/) | most languages |
clonezilla | HDD backup/cloner | :heavy_check_mark: | | |
cloudcompare | photo to 3D point map | :heavy_multiplication_x: | [CloudCompare](http://cloudcompare.org/) | |
cmatrix | terminal Matrix | :heavy_check_mark: | | |
cmdlauncher | commands to GUI | :heavy_multiplication_x: | [CmdLauncher](http://cmdlauncher.topbug.net/) | |
cmospwd | decrypt CMOS password | :heavy_check_mark: | | |
cmsmap | CMS vulnerability scanner | :heavy_multiplication_x: | [CMSmap](https://github.com/dionach/CMSmap) | |
cmus | terminal music player | :heavy_check_mark: | | |
cockpit | web interface managing multiple servers | :heavy_multiplication_x: | [PPA](ppa:cockpit-project/cockpit) | |
codeblocks | C editor | :heavy_check_mark: | | |
codecounter | C/BASIC/web code counter | :heavy_multiplication_x: | [CodeCounter](https://github.com/Tinram/CodeCounter) | |
codelite | C editor | :heavy_check_mark: | | PHP/JS/Python also supported |
collectd, kcollectd | system stats harvester/monitoring daemon | :heavy_check_mark: | | |
collectl | performance/benchmarking data | :heavy_check_mark: | | |
colorgrab | dropper | :heavy_multiplication_x: | [Colorgrab](https://github.com/Acolarh/colorgrab) | |
colorhug | colorimeter | :heavy_check_mark: | | |
conduit | sync tool for GNOME (files, bookmarks) | :heavy_check_mark: | | |
contextfree | image generator | :heavy_check_mark: | | |
converseen | batch image converter/resizer | :heavy_check_mark: | [Converseen](https://sourceforge.net/projects/converseen/) | GUI for *ImageMagick* |
convertall | unit converter | :heavy_check_mark: | | |
compiz | window and compositing manager | :heavy_check_mark: | | |
compizconfig-settings-manager | compiz configuration settings | :heavy_check_mark: | | screen inverter |
conky | GUI system monitor | :heavy_check_mark: | | |
cpu-g | CPU-Z like CPU analyser | :heavy_multiplication_x: | [CPU-G](https://sourceforge.net/projects/cpug/) | |
cpupower | CPU frequency manager | :heavy_multiplication_x: | | |
cppcheck | C code linter | :heavy_check_mark: | | |
cpuid | x86 CPU info | :heavy_check_mark: | | |
credcrack | credential harvester | :heavy_multiplication_x: | [CredCrack](https://github.com/gojhonny/CredCrack) | |
crunch | password list generator | :heavy_check_mark: | | |
cryptcat | encrypted *netcat* | :heavy_check_mark: | | |
cryptocat | encrypted IM | :heavy_multiplication_x: | [CryptoCat](https://crypto.cat/) | |
cryptkeeper | encfs GUI for GNOME | :heavy_check_mark: | | |
cryptote | encrypted tabbed notes | :heavy_multiplication_x: | [Cryptote](http://panthema.net/2009/cryptote/#downloads) | |
cscope | C interactive checker | :heavy_check_mark: | | |
ctags | C code indexing tool | :heavy_check_mark: | | |
cups-pdf | print to PDF | :heavy_check_mark: | | |
curl | terminal transfer data | :heavy_check_mark: | | |
cutegram | IM | :heavy_multiplication_x: | [Cutegram](http://aseman.co/en/products/cutegram/) | |
cvassistant | multiple CV manager | :heavy_multiplication_x: | [CVAssistant](https://sourceforge.net/projects/cvassistant/) | |
curl-loader | HTTP benchmark | :heavy_multiplication_x: | [curl-loader](https://sourceforge.net/projects/curl-loader/) | |
cutereport | report generator | :heavy_multiplication_x: | [CuteReport](https://sourceforge.net/projects/qreport/) | |
cxref | C code to LaTeX/HTML | :heavy_check_mark: | | |
cyberfox | 64-bit browser | :heavy_multiplication_x: | | |
cython | Python C extensions | :heavy_check_mark: | | |
darkhttpd | tiny file server | :heavy_multiplication_x: | [Darkhttpd](https://unix4lyfe.org/darkhttpd/) | 34kB |
darkstat | network traffic analyzer | :heavy_check_mark: | | |
darktable | RAW images | :heavy_check_mark: | darktable.org, [TR](http://www.techrepublic.com/blog/diy-it-guy/diy-enhance-your-graphic-design-work-with-darktable/)| |
darling | Mac terminal Wine | :heavy_multiplication_x: | [Darling](http://darlinghq.org/) | |
datacleaner | database scanner | :heavy_multiplication_x: | | |
dateutils | terminal date/time utilities | :heavy_multiplication_x: | [Dateutils](http://www.fresse.org/dateutils/) | |
dban | disk destroyer | :heavy_multiplication_x: | [DBAN](https://dban.org/) | |
dconf-tools | power management config | :heavy_check_mark: | | |
dcraw | terminal RAW converter | :heavy_check_mark: | | |
ddrescue | data recovery tool | :heavy_check_mark: | | see *gddrescue* |
deadbeef | music player | :heavy_multiplication_x: | [deadbeef](https://sourceforge.net/projects/deadbeef/) [PPA](ppa:starws-box/deadbeef-player) | |
debreate | Debian package manager | :heavy_multiplication_x: | [Debreate](https://antumdeluge.github.io/debreate-web/) | |
debsums | package checksum comparisons | :heavy_check_mark: | | |
deja-dup | backup tool | :heavy_check_mark: | | |
denyhosts | SSH protection | :heavy_check_mark: | | |
devicesinlan | LAN scanner | :heavy_multiplication_x: | [DevicesInLAN](https://sourceforge.net/projects/devicesinlan/) | |
devilspie2 | run script upon window interaction | :heavy_check_mark: | [Devilspie2](http://gusnan.se/devilspie2/) | |
devede | create DVDs/DVD menus | :heavy_check_mark: | | |
devscripts | Debian package maintainance | :heavy_multiplication_x: | | |
devtodo | terminal todo list | :heavy_check_mark: | | |
dhcpcd | DHCP server for autoconfiguring networking | :heavy_check_mark: | | `sudo dhcpcd wlan0` |
dhcpdump | parse DHCP packets from *tcpdump* | :heavy_check_mark: | | |
dia | diagram editor | :heavy_check_mark: | | |
dialog | Bash dialog | :heavy_check_mark: | | |
diffmerge | diff | :heavy_multiplication_x: | [DiffMerge](http://sourcegear.com/diffmerge/downloads.php)| |
difftree | compare dirs | :heavy_multiplication_x: | [DiffTree](https://github.com/rondilley/difftree)| |
diffuse | file compare/merge | :heavy_check_mark: | | |
digikam | photo manager | :heavy_check_mark: | | KDE-based |
ding | GUI dictionary | :heavy_check_mark: | | |
discourse | phpBB | :heavy_multiplication_x: | [Discourse](http://www.discourse.org/) | |
discover | automate pen test tasks | :heavy_multiplication_x: | [discover](https://github.com/leebaird/discover) | |
dispalgui | GUI for *Argyll* colour management | :heavy_check_mark: | | |
distorm | x86 disassembler | :heavy_check_mark: | | not obvious how to use |
dmitry | server host info | :heavy_check_mark: | | |
dnstracer | trace DNS queries to source | :heavy_check_mark: | | |
dnswalk | DNS debugger/nameserver lookup | :heavy_check_mark: | | |
docker | container runtime | :heavy_check_mark: | docker.io | |
docker-doc | docker documentation | :heavy_check_mark: | | |
docker-registry | | :heavy_check_mark: | | |
doona | daemon vulnerability | :heavy_multiplication_x: | | |
dos2unix | convert EOL chars | :heavy_check_mark: | | *tofromdos* may be better |
downtimed | downtime monitor | :heavy_check_mark: | | |
doxygen | C/PHP auto-documenter | :heavy_check_mark: | | |
doxygen-doxywizard | config GUI for *doxygen* | :heavy_check_mark: | | |
drgeo | geometric sketcher | :heavy_check_mark: | | |
dsniff | network sniffer | :heavy_check_mark: | | |
dstat | resources stats | :heavy_check_mark: | | |
dukto | LAN transfer tool | :heavy_multiplication_x: | [Dukto](https://github.com/guilhem/dukto) | |
duplicity | encrypted backup | :heavy_check_mark: | [Duplicity](http://duplicity.nongnu.org/) | built on rsync |
dvdbackup | DVD ripper | :heavy_check_mark: | | |
e4defrag | ext4 defragger | :heavy_multiplication_x: | | |
easy-rsa | certificate generator | :heavy_check_mark: | | very useful for OpenVPN |
eiciel | GUI ACL editor | :heavy_check_mark: | [eiciel](http://rofi.roger-ferrer.org/eiciel/) | |
eko | audio editor | :heavy_multiplication_x: | [Eko](http://semiletov.org/eko/) | |
elfparser | ELF analyser | :heavy_multiplication_x: | [ELF parser](http://elfparser.com/download.html) | |
emilpro | disassembler | :heavy_multiplication_x: | | |
emma | *MySQL* GUI editor | :heavy_check_mark: | | |
encryptpad | text editor with encryption | :heavy_multiplication_x: | [EncryptPad](http://evpo.net/encryptpad/) | |
encryptr | SpiderOak note storage | :heavy_multiplication_x: | [Encryptr](https://spideroak.com/) | |
engauge-digitizer | graph digitizer: extract nums | :heavy_check_mark: | | |
enscript | text converter PS/HTML/RTF | :heavy_check_mark: | | |
ent | entropy checker | :heavy_check_mark: | | |
entr | trigger actions on file change | :heavy_check_mark: | [Entr](http://entrproject.org/) | |
eqonmize | financial app | :heavy_multiplication_x: | [Eqonmize](https://github.com/Eqonomize/Eqonomize) | |
espeak | audio speaker + GUIs | :heavy_check_mark: | | GUI is gespeaker |
etckeeper | version control of /etc | :heavy_check_mark: | | |
etherape | GUI network monitor | :heavy_check_mark: | | |
ethtool | display/change ethernet device settings | :heavy_check_mark: | | |
etcher | ISO to USB | :heavy_multiplication_x: | [Etcher](https://etcher.io/) | Chrome-bloated |
etm | event and task manager | :heavy_multiplication_x: | [ETM](http://people.duke.edu/~dgraham/etmqt/) | |
exelearning | authoring tool | :heavy_multiplication_x: | [eXeLearning](http://exelearning.net/) [PPS](pps:exelearning/exelearning) | |
exiftool | edit EXIF data | :heavy_check_mark: | [EXIFtool](http://sno.phy.queensu.ca/~phil/exiftool/) | |
exmplayer | GUI to MPlayer video | :heavy_check_mark: | | |
extundelete | recover deleted files | :heavy_check_mark: | | |
fail2ban | set firewall rules for multiple wrong logins | :heavy_check_mark: | | |
fatback | recover data from disks/USBs | :heavy_check_mark: | | `fatback /dev/sdbx -o /recfiles -a` |
fatsort | FAT filesystem file sorter | :heavy_check_mark: | | |
fbcat | framebuffer grabber | :heavy_check_mark: | | outputs .ppm convert with *ImageMagick* |
fcrackzip | ZIP cracker | :heavy_check_mark: | | |
fdupes | compare files in two directories | :heavy_check_mark: | | uses hashes |
featherpad | text editor (C++) | :heavy_multiplication_x: | [featherpad](https://github.com/tsujan/FeatherPad) | few dependencies |
fehashmac | terminal hasher | :heavy_multiplication_x: | [fehashmac](https://sourceforge.net/projects/fehashmac) | |
fern-wifi-cracker | GUI for *aircrack* | :heavy_multiplication_x: | | |
ffmeg | media conversion utility | :heavy_check_mark: | | |
figlet | ASCII lettering from text | :heavy_check_mark: | | |
filefrag | file defragger | :heavy_multiplication_x: | | |
fileverifier | verify files | :heavy_multiplication_x: | | |
filezilla | FTP/SFTP | :heavy_check_mark: | | |
filezillasecure | Filezilla fork: multithreadubg | :heavy_multiplication_x: | [FileZillaSecure](http://www.filezillasecure.com/) | no plaintext passwords |
findmyhash | queries multiple websites for hash | :heavy_multiplication_x: | | |
firejail | sandbox apps | :heavy_check_mark: | | [firejail](https://github.com/netblue30/firejail) |
fishsynch | sync files | :heavy_multiplication_x: | [FishSynch](https://sourceforge.net/projects/fishsync/) | |
fiziko | pen-and-ink drawings from code | :heavy_multiplication_x: | [Fiziko](https://github.com/jemmybutton/fiziko) | |
flashlight | auto info tool for pen tests | :heavy_multiplication_x: | [flashlight](https://github.com/galkan/flashlight) | |
flasm | dis/assembler for Flash bytecode | :heavy_check_mark: | | |
flawfinder | C/C++ code checker | :heavy_check_mark: | | simpler than *splint* |
flif | lossless image encoder | :heavy_multiplication_x: | [FLIF](https://github.com/FLIF-hub/FLIF) | |
flightgear | flight simulator | :heavy_check_mark: | flightgear.com | |
flow | diagrams | :heavy_multiplication_x: | | |
flowblade | video editor | :heavy_multiplication_x: | | |
fmap | web app vulnerabilities | :heavy_multiplication_x: | | |
focuswriter | word processor | :heavy_check_mark: | gotcode.org/focuswriter | |
fog | clone rollout system | :heavy_multiplication_x: | [FOG](https://sourceforge.net/projects/freeghost/files/FOG) | |
fontforge | font editor | :heavy_multiplication_x: | [FontForge](http://fontforge.github.io/) | |
foremost | recover files based on headers and footers | :heavy_check_mark: | | |
fotoxx | photo editor | :heavy_check_mark: | | good at editing, poor interface |
fping | ICMP to network hosts | :heavy_check_mark: | | |
fracplanet | fractals | :heavy_check_mark: | | |
fraqtive | 3D Mandelbrot/Julia | :heavy_check_mark: | | |
freebasic | BASIC compiler | :heavy_multiplication_x: | [FreeBASIC](http://freebasic.net/) | |
freefilesynch | GUI folder compare and sync | :heavy_check_mark: | | |
freemind | mindmap editor | :heavy_multiplication_x: | [FreeMind](https://sourceforge.net/projects/freemind/?source=directory) | Java |
freeplane | mindmap editor | :heavy_check_mark: | | Java |
frescobaldi | sheet music editor | :heavy_check_mark: | | |
freshmemory | flashcards | :heavy_multiplication_x: | [Fresh Memory](https://sourceforge.net/projects/freshmemory/) | |
fruitywifi | wireless network auditing tool | :heavy_multiplication_x: | [FruityWifi](https://github.com/xtr4nge/FruityWifi) | |
fsarchiver | tar.gz alternative | :heavy_check_mark: | fsarchiver.org | |
fsearch | file search | :heavy_multiplication_x: | [FSearch](http://www.fsearch.org/) | |
fslint | problem file manager/cleaner | :heavy_check_mark: | | |
fswebcam | webcam | :heavy_check_mark: | | `sudo fswebcam /dev/video0 x.jpg` |
funkload | web server benchmarker | :heavy_check_mark: | [funkload](http://funkload.nuxeo.org/) | includes unit testing |
fusil | fuzzer | :heavy_check_mark: | | collection of scripts |
fuzz | fuzz exes with datastream input | :heavy_check_mark: | | |
fwbuilder | firewall admin GUI | :heavy_check_mark: | | |
gadmin-samba | GUI config for Samba | :heavy_check_mark: | | |
gadmin-rsync | GUI config for rsync | :heavy_check_mark: | | |
gadmin-openvpn-client | GUI config for OpenVPN | :heavy_check_mark: | | |
gadmin-openvpn-server | config for OpenVPN | :heavy_check_mark: | | |
gajim | GPG Jabber client | :heavy_check_mark: | | |
gatling | static page web server | :heavy_check_mark: | | |
gcad3d | CAD | :heavy_multiplication_x: | [gCAD3D](http://gcad3d.org/) | |
gcc | GNU C compiler | :heavy_check_mark: | | |
gcolor2 | GUI colour picker | :heavy_check_mark: | | prefer *GPick* |
gconf-editor | GConf editor | :heavy_check_mark: | | |
gdb | GNU Debugger | :heavy_check_mark: | | |
gddrescue | `dd` drive/data recovery | :heavy_check_mark: | [ddrescue](https://launchpad.net/ddrescue-gui) | [PPA](ppa:hamishmb/myppa) |
gdm | GNOME display manager | :heavy_check_mark: | | |
gdmap | visual HDD space usage | :heavy_check_mark: | | |
geany | lightweight editor/IDE | :heavy_check_mark: | | |
gethead | HTTP header vulnerability tool | :heavy_multiplication_x: | [gethead](https://github.com/httphacker/gethead) | |
gfortran | GNU Fortran 95 compiler | :heavy_check_mark: | | |
ghex | GUI hex viewer | :heavy_check_mark: | | |
ghostwriter | *FocusWriter*-like text editor | :heavy_multiplication_x: | [GhostWriter](http://wereturtle.github.io/ghostwriter/) | Markdown default |
giada | DJ tool | :heavy_multiplication_x: | | |
gigolo | mount manager | :heavy_check_mark: | | |
gimp | image editor | :heavy_check_mark: | | |
gimp-dcraw | GIMP RAW plugin | :heavy_check_mark: | | |
gimp-ufraw | GIMP RAW importer | :heavy_check_mark: | | |
git | source control | :heavy_check_mark: | | git, git-gui, gitk, gitg, git-doc, git-extras |
git-extras | Git extensions | :heavy_check_mark: | | |
gitg | *Git* repo viewer | :heavy_check_mark: | | |
git-gui | *Git* GUI, integrates with gitk | :heavy_check_mark: | | `git gui` |
gitk | *Git* repo viewer | :heavy_check_mark: | | |
gkrellm | GUI system monitor | :heavy_check_mark: | | |
glances | *top*-like app (sophisticated) | :heavy_multiplication_x: | [Glances](https://nicolargo.github.io/glances/) | `pip install glances` |
glchess | chess | :heavy_check_mark: | | uses Crafty engine; use `apt` |
glogg | GUI logfile view/query | :heavy_check_mark: | [glogg](http://glogg.bonnefon.org/) | |
gmysqlcc | GUI *MySQL* client | :heavy_check_mark: | | |
gnect | connect4 | :heavy_check_mark: | | |
gnofract | fractal generator | :heavy_multiplication_x: | | .deb SourceForge package; good images |
gnome-battery-bench | [Gnome Battery Bench](https://github.com/GNOME/gnome-battery-bench) | :heavy_multiplication_x: | | |
gnome-builder | GNOME app builder | :heavy_multiplication_x: | [Gnome Builder](https://github.com/chergert/gnome-builder) | |
gnome-network-admin | GUI for *whois*/ping | :heavy_check_mark: | | |
gnome-rdp | remote desktop | :heavy_check_mark: | | |
gnome-system-monitor | GNOME monitor | :heavy_check_mark: | | |
gnome-tweak-tool | GNOME 3 editor | :heavy_check_mark: | | |
gnucash | financial accounting app | :heavy_check_mark: | | |
gnumeric | spreadsheet | :heavy_check_mark: | | |
goaccess | Apache realtime logfile viewer | :heavy_check_mark: | [GoAccess](https://goaccess.io/download) | avoid repo version; `goaccess -f <f> -a` |
golly | game of life | :heavy_check_mark: | | |
googler | terminal Google search | :heavy_multiplication_x: | [googler](https://github.com/jarun/googler) | |
gosync | GDrive sync | :heavy_multiplication_x: | [GoSync](https://github.com/hschauhan/gosync/) | |
gparted | view/manage partitions | :heavy_check_mark: | | |
gnupg2 | GPG versino 2 | :heavy_check_mark: | | |
gnuplot | graphs | :heavy_check_mark: | | core |
gnuplot-x11 | graphics | :heavy_check_mark: | | |
gnuplot-qt | graphics | :heavy_check_mark: | | |
govie | movie utility | :heavy_multiplication_x: | [Govie](https://github.com/narenaryan/Govie) | |
gpgdir | encrypt directories | :heavy_check_mark: | | |
gphoto2 | terminal digital camera processor | :heavy_check_mark: | | |
gpgit | terminal GPG file encryption switches simplified | :heavy_multiplication_x: | [GPGit](https://github.com/Tinram/GPGit) | |
gpick | screen colour pick/palette/inverter | :heavy_check_mark: | | |
gpm | mouse interface/copy-paste on terminal | :heavy_check_mark: | | |
grabber | web app scanner | :heavy_multiplication_x: | | |
graphviz | graph tools | :heavy_check_mark: | | |
graudit | grep rough source code audit | :heavy_multiplication_x: | [graudit](https://github.com/wireghoul/graudit/) | |
graylog | manage network of PCs logfiles in 1 place | :heavy_multiplication_x: | [Graylog](https://www.graylog.org/) | |
grdesktop | GUI for rdesktop | :heavy_check_mark: | | |
grive2 | GDrive syncer | :heavy_multiplication_x: | [Grive2](https://github.com/vitalif/grive2/) | |
grsynch | GUI for rsynch | :heavy_check_mark: | | |
grub-customizer | GRUB GUI editor | :heavy_multiplication_x: | [GRUB customizer](https://launchpad.net/grub-customizer) | |
gscan2pdf | PDFs from scans | :heavy_check_mark: | | |
gsettings | GNOME database changer | :heavy_check_mark: | | |
gsmartcontrol | GUI for *smartctl* | :heavy_check_mark: | | |
gsync | GDrive syncer | :heavy_check_mark: | | `pip install gsync` |
gtkam | GUI transfer from cameras | :heavy_check_mark: | | |
gtkhash | GUI hash calculator | :heavy_check_mark: | | |
gtg | GNOME todo organiser | :heavy_check_mark: | | |
guake | multi-tabbed/multi-coloured terminal | :heavy_check_mark: | | |
gufw | GUI for *ufw* | :heavy_check_mark: | | |
gvfs-backends | SMB browsing | :heavy_check_mark: | | |
haguichi | GUI for VPN app | :heavy_multiplication_x: | [Haguichi](https://www.haguichi.net/) | |
handbrake | DVD ripper/video transcoder | :heavy_check_mark: | [handbrake](https://handbrake.fr) | |
hardinfo | hardware info | :heavy_check_mark: | | |
harvester | info harvester | :heavy_multiplication_x: | | Kali tools |
hash-identifier | identify hash | :heavy_multiplication_x: | [hash-identifier](http://tools.kali.org/password-attacks/hash-identifier) | |
haveged | random number generator | :heavy_check_mark: | | |
hdparm | tune HDD parameters | :heavy_check_mark: | | |
heartbeat | high-availability servers | :heavy_check_mark: | | |
helm | music synthesizer | :heavy_multiplication_x: | [Helm](http://tytel.org/helm/) | |
highlight | convert code to HTML/RTF | :heavy_check_mark: | | |
hnwatch | terminal news feed | :heavy_multiplication_x: | | |
hostmap | enumerate (v)hosts of IP | :heavy_multiplication_x: | [Hostmap](http://g33kinfo.com/info/hostmap-0-2-2-tar) | |
ht | terminal hex view/disassemble | :heavy_check_mark: | | use `apt`, called *hte* |
htop | hyper *top* | :heavy_check_mark: | | |
httperf | HTTP benchmark | :heavy_check_mark: | | |
http-logs-analyzer | HTTP logs analyzer | :heavy_multiplication_x: | [logs-analyzer](https://github.com/flrnull/http-logs-analyzer) | |
homebank | *GNU Cash*-like | :heavy_check_mark: | | |
hping3 | send packets to network hosts | :heavy_check_mark: | | |
httping | HTTP pinger | :heavy_check_mark: | | |
httpstat | http request timer | :heavy_multiplication_x: | [httpstat](https://github.com/reorx/httpstat) | |
httrack | copy websites | :heavy_check_mark: | | |
hugin | panorama stitcher + photo editor | :heavy_check_mark: | | |
hwinfo | hardware info | :heavy_check_mark: | | deprecated |
hx | terminal hex editor | :heavy_multiplication_x: | [hx](https://github.com/krpors/hx) | |
hydra | GUI network brute-forcer | :heavy_check_mark: | | |
hydrogen | drum machine | :heavy_check_mark: | | |
i7z | Core CPU reporting | :heavy_check_mark: | | |
icinga | *nagios*-like network monitor | :heavy_check_mark: | icinga.org | |
iftop | network interface usage | :heavy_check_mark: | icinga.org | |
imagemagick | terminal image manipulator | :heavy_check_mark: | | |
i-nex | system hardware lister | :heavy_multiplication_x: | [i-nex](https://sourceforge.net/projects/i-nex/) | uses Gambas |
indent | C indenter | :heavy_check_mark: | | |
indicator-cpufreq | change CPU freq | :heavy_check_mark: | | |
infernal-twin | auto wireless hacking tool | :heavy_multiplication_x: | [infernal-twin](https://github.com/entropy1337/infernal-twin) | |
inguma | pentest framework | :heavy_multiplication_x: | | |
inkscape | vector imager | :heavy_check_mark: | | |
innotop | *MySQL* InnoDB monitor | :heavy_check_mark: | | Red Hat repo |
inotify | monitor filesystem events | :heavy_check_mark: | | especially good for Samba folders |
instarecon | auto digital reconnaissance | :heavy_multiplication_x: | [title](https://github.com/vergl4s/instarecon) | high level reconn |
inxi | system info | :heavy_multiplication_x: | | in Red Hat repo |
ioping | disk I/O benchmarker | :heavy_check_mark: | | |
iotop | I/O monitor | :heavy_check_mark: | | |
iperf | network bandwidth performance | :heavy_check_mark: | | |
ipgrab | *tcpdump*-like, detailed header info | :heavy_check_mark: | | (more explicit than *tcpdump*) |
iproute2 | IP tools | :heavy_check_mark: | | |
ipsec-tools | IPsec utilities | :heavy_check_mark: | | |
ipset | tool for kernel IP sets | :heavy_check_mark: | | |
iptables-persistent | iptables setup on boot | :heavy_check_mark: | | `sudo service iptables-persistent start` |
iptraf | IP LAN monitor | :heavy_check_mark: | | |
ipython | enhanced python shell and env | :heavy_check_mark: | | |
iridium | Chromium-based browser | :heavy_multiplication_x: | [Iridium](https://iridiumbrowser.de) | enhanced privacy over Chrome |
isohybrid | DVD.iso > bootable from Flash | :heavy_check_mark: | | |
isomaster | CD/DVD image editor | :heavy_check_mark: | | |
java | | :heavy_check_mark: | | `apt-get install default-jre` |
jarte | lightweight wordprocessor (with DocX support) | :heavy_check_mark: | | |
jbit | 6502 simulator | :heavy_multiplication_x: | [JBit](https://sourceforge.net/projects/jbit/) | |
jed | code editor | :heavy_check_mark: | | |
jedit | code editor | :heavy_check_mark: | |
jitsi | encrypted IM/VOIP | :heavy_multiplication_x: | | Java |
joomscan | Joomla scanner | :heavy_multiplication_x: | | |
jonny | GUI for John | :heavy_multiplication_x: | [Jonny](https://github.com/shinnok/johnny) | |
jpeginfo | JPEG nfo/integrity | :heavy_check_mark: | | |
jq | terminal JSON stream editor | :heavy_check_mark: | | |
julia | fast math-oriented language | :heavy_check_mark: | | |
kaku | music player | :heavy_multiplication_x: | [kaku](http://kaku.rocks/) | |
kanboard | project manager | :heavy_multiplication_x: | [Kanboard](https://kanboard.net/) | |
katoolin | auto install Kali linux tools | :heavy_multiplication_x: | [katoolin](https://github.com/LionSec/katoolin) | |
kazam | video screen recorder | :heavy_check_mark: | | |
kdecachegrind | PHP cache analyser | :heavy_multiplication_x: | | |
kdenlive | video editor | :heavy_check_mark: | | KDE |
keepassx | password vault | :heavy_check_mark: | | |
keepassxc | password vault | :heavy_multiplication_x: | [KeePassXC](https://keepassxc.org) | revised *KeePassX* |
kerkythea | renderer | :heavy_multiplication_x: | [Kerkythea](http://www.kerkythea.net/cms/) | |
kexi | database GUI (MySQL/SQLite/PostgreSQL) | :heavy_multiplication_x: | [Kexi](http://kexi-project.org/) | |
kismet | Wireless 802.11b sniffer/monitor | :heavy_check_mark: | | |
knotter | Celtic knot app | :heavy_multiplication_x: | [Knotter](https://sourceforge.net/projects/knotter/) [info](http://knotter.mattbas.org/Knotter) | |
kolormanager | X color calibration | :heavy_multiplication_x: | [KolorManager](http://oyranos.org/kolormanager) | |
komodoedit | code editor | :heavy_multiplication_x: | | |
krita | image editor | :heavy_check_mark: | krita.org | hand-drawn target |
krop | PDF cropper/editor | :heavy_multiplication_x: | [Krop](http://arminstraub.com/software/krop) | |
lamaperia | printable maps from OpenStreetMap | :heavy_multiplication_x: | [Lamaperia](https://github.com/federicomenaquintero/lamaperia) | |
lame | MP3 encoder | :heavy_check_mark: | | |
lazagne | credentials recovery | :heavy_multiplication_x: | [LaZagne](https://github.com/AlessandroZ/LaZagne) | Windows version is considered a Trojan |
lepton | JPEG compressor | :heavy_multiplication_x: | [lepton](https://github.com/dropbox/lepton) | |
libmarkdown-php | Markdown library | :heavy_check_mark: | | |
libreoffice-dbg | debugger | :heavy_check_mark: | | |
libssl-dev | OpenSSL libaries | :heavy_check_mark: | | |
libtomcrypt | crypto toolkit | :heavy_check_mark: | | |
liferea | GUI RSS | :heavy_check_mark: | | |
lightworks | video editor | :heavy_multiplication_x: | [LightWorks](https://www.lwks.com/) | 720p only |
lightzone | RAW editor | :heavy_multiplication_x: | [LightZone](http://lightzoneproject.org/) | |
linkchecker | website link checker | :heavy_check_mark: | | |
linklint | website link checker | :heavy_check_mark: | | |
linphone | *Skype* replacement | :heavy_check_mark: | | requires SIP account |
linux-crashdump | kernel crashdump set-up | :heavy_check_mark: | | |
linux-firmware | drivers | :heavy_check_mark: | | apparently includes wireless drivers |
linux-malware-detect | Linux malware detector | :heavy_multiplication_x: | [linux-malware-detect](https://github.com/rfxn/linux-malware-detect) | |
linuxrespin | distro builder | :heavy_multiplication_x: | [Linux Respin](http://www.linuxrespin.org/) | |
lives | video editor | :heavy_check_mark: | | good for real-time editing |
lm-sensors | for `sensors` | :heavy_check_mark: | | |
lmms | audio editor | :heavy_check_mark: | | |
ln | vector image generator | :heavy_multiplication_x: | [ln](https://github.com/fogleman/ln) | |
lnav | logfile reader with colour | :heavy_check_mark: | lnav.org | |
logkeys | keylogger | :heavy_check_mark: | | ! |
logwatch | log analysis emailer | :heavy_check_mark: | | |
lshw-gtk | lshw hardware GUI | :heavy_check_mark: | | |
lttng | program tracing | :heavy_check_mark: | | almost as powerful as SystemTap |
luckybackup | rsync-based GUI backup | :heavy_check_mark: | | |
lynis | security auditor | :heavy_check_mark: | | |
lyx | Latex WYSIWYG | :heavy_check_mark: | | 500MB |
lzop | fast compression | :heavy_check_mark: | | |
macchanger | spoof network card MAC | :heavy_check_mark: | | |
mailutils | mail utilities | :heavy_check_mark: | | |
maltego | people-places analysis tool | :heavy_multiplication_x: | [Maltego](https://paterva.com/web7/) | Java |
mandelbulber | 3D Mandelbrot | :heavy_check_mark: | | |
mariadb-server | MariaDB | :heavy_check_mark: | | |
mariadb-client | MariaDB | :heavy_check_mark: | | |
markdown | Markdown to HTML | :heavy_check_mark: | | |
masterpdfeditor | PDF editor | :heavy_multiplication_x: | [MasterPDFEditor](https://code-industry.net/get-masterpdfeditor/) | powerful, limited |
mat | metadata anonymiser tool | :heavy_check_mark: | | use `apt`; `mat -d <file>` |
maths | maths problem solver | :heavy_multiplication_x: | [maths](https://code.launchpad.net/~nasc-team) [PPA](ppa:nasc-team/daily) | |
mdpress | Markdown viewer | :heavy_check_mark: | | |
medusa | router/network brute-forcer | :heavy_check_mark: | | |
meld | GUI diff | :heavy_check_mark: | | |
mermaid | diagrams with Markdown derivative | :heavy_multiplication_x: | [Mermaid](https://github.com/knsv/mermaid) | |
mesa-utils | MesaGL utilities | :heavy_check_mark: | | |
md5deep | batch/recursive md5sum | :heavy_check_mark: | | |
mdadm | software RAID controller | :heavy_check_mark: | | |
meshlab | triangular mesh creator | :heavy_check_mark: | | |
micro | text editor | :heavy_multiplication_x: | [Micro](https://github.com/zyedidia/micro) | |
midori | lightweight browser | :heavy_check_mark: | | |
minitube | native YouTube client | :heavy_check_mark: | | |
minuet | music trainer | :heavy_multiplication_x: | [Minuet](https://github.com/KDE/minuet) | |
mixxx | audio mixer/editor | :heavy_check_mark: | | |
mlocate | for `locate` | :heavy_check_mark: | | if `locate` is missing |
mmv | mass move/rename | :heavy_check_mark: | | |
mongodb | MongoDB | :heavy_check_mark: | | meta package; or `pecl install mongo` |
monit | notify upon server log-ins | :heavy_multiplication_x: | | |
monitorix | GUI system monitor | :heavy_multiplication_x: | [Monitorix](http://www.monitorix.org/) | |
moreutils | isutf8, *parallel*, sponge | :heavy_check_mark: || |
most | read `man` pages in colour | :heavy_check_mark: | | |
mpd | music player daemon | :heavy_check_mark: | | (works remotely) |
mpg123 | terminal MP3 player | :heavy_check_mark: | | decoding library very good |
mplayer | movie player | :heavy_check_mark: | | |
mps-youtube | YouTube music player | :heavy_check_mark: | [mps-youtube](https://github.com/mps-youtube/mps-youtube) | |
mtools | multi-cast connection tester | :heavy_multiplication_x: | | |
mtr | ping and *traceroute* combined | :heavy_check_mark: | | also mtr-tiny |
mundus | home file cleaner | :heavy_multiplication_x: | | |
mupen64plus | N64 console emulator | :heavy_check_mark: | | |
musescore | music score editor | :heavy_check_mark: | | |
mypaint | painting program | :heavy_check_mark: | | |
mysql | MySQL database | :heavy_check_mark: | | |
mysql-utilities | *MySQL* | :heavy_check_mark: | | |
mysql-workbench | *MySQL* | :heavy_check_mark: | | |
mysqltuner | mysqld settings analyser | :heavy_check_mark: | | mysqltuner.pl |
mytop | *MySQL* monitor | :heavy_check_mark: | | |
mz | versatile packet/network traffic generator | :heavy_check_mark: | | |
nagios-nrpe-server | Nagios component for remote server | :heavy_check_mark: | nagios.org | |
nast | terminal Wireshark | :heavy_check_mark: | nast.berlios.de | |
nbtscan | scan network for NetBIOS info (Samba) | :heavy_check_mark: | | |
ncdu | disk usage analyser | :heavy_check_mark: | | |
ncrack | network cracker | :heavy_multiplication_x: | | |
ncrypt | terminal file encrypt | :heavy_multiplication_x: | [Ncrypt](https://sourceforge.net/projects/ncrypt/) | only SHA-1 key hashing |
ncursesfm | terminal file manager | :heavy_multiplication_x: | [NcursesFM](https://github.com/FedeDP/ncursesFM) | |
neofetch | system info | :heavy_multiplication_x: | [neofetch](https://github.com/dylanaraps/neofetch) | |
nemo-fileroller | FileRoller for Nemo | :heavy_check_mark: | | |
netcat | TCP/IP Swiss army knife | :heavy_check_mark: | | |
netcatgui | GUI for *netcat* | :heavy_multiplication_x: | [netcatgui](https://github.com/shinnok/netcatgui) | |
net-creds | sniffs data from interface/pcap | :heavy_multiplication_x: | [net-creds](https://github.com/DanMcInerney/net-creds) | |
netdiscover | active/passive network address scanner using arp requests | :heavy_check_mark: | | |
nethogs | bandwidth hog monitor | :heavy_check_mark: | | |
netperf | network benchmark | :heavy_check_mark: | | |
netrw | *netcat*-like, transport files over network | :heavy_check_mark: | | |
netsurf | lightweight browser | :heavy_check_mark: | | |
netwag | GUI *netwox* | :heavy_check_mark: | | |
netwox | networking utilities | :heavy_check_mark: | | |
neural-enhance | image enhancer | :heavy_multiplication_x: | [Neural Enhance](https://github.com/alexjc/neural-enhance) | |
newsbeuter | terminal RSS reader | :heavy_check_mark: | | |
nginx | web/proxy server | :heavy_check_mark: | | |
ngrep | network traffic grep | :heavy_check_mark: | | |
nightingale | music player | :heavy_multiplication_x: | [Nightingale](http://getnightingale.com/) | |
nikto | web server security scanner | :heavy_check_mark: | | |
nipper-ng | security analysis of switches/routers | :heavy_multiplication_x: | | |
nixnote | Evernote client | :heavy_multiplication_x: | [NixNote](https://sourceforge.net/projects/nevernote/?source=directory) | |
nload | network load | :heavy_check_mark: | | use `apt` |
nltk | natural language processing for Python | :heavy_check_mark: | | |
nmap | network scanner | :heavy_check_mark: | | |
nmapsi4 | GUI for *NMap* | :heavy_check_mark: | | |
nmcli | CLI for NetworkManager | :heavy_check_mark: | | |
nmon | network/CPU/disk performance | :heavy_check_mark: | | |
notepas | code editor | :heavy_multiplication_x: | | |
notes-up | editor supporting Markdown | :heavy_multiplication_x: | [Notes-up](https://github.com/Philip-Scott/Notes-up) | PDF export |
npm | NodeJS package manager | :heavy_check_mark: | | |
ntfs-3g | NTFS driver | :heavy_check_mark: | | r/w |
ntfsfix | fix NTFS | :heavy_multiplication_x: | | |
ntfsundelete | recover NTFS files | :heavy_check_mark: | | |
ntop | network usage in browser | :heavy_check_mark: | | |
nutty | network utility | :heavy_multiplication_x: | [Nutty](https://launchpad.net/nutty) [PPA](ppa:bablu-boy/nutty.0.1) | |
obnam | incremental daily backups with SFTP/GPG support | :heavy_check_mark: | | |
obs | video recording/livestreaming | :heavy_multiplication_x: | [OBS](https://obsproject.com/) | |
ocrfeeder | OCR text scanner | :heavy_check_mark: | | |
octave | numerical computation library and GUI | :heavy_check_mark: | | matlab-like |
oletoy | file format analyser | :heavy_multiplication_x: | [OleToy](https://github.com/renyxa/re-lab) | |
omd | Nagios fork | :heavy_multiplication_x: | [OMD](http://omdistro.org/) | easier setup than *Nagios* |
onedrive-d | OneDrive sync | :heavy_multiplication_x: | [onedrive-d](https://github.com/xybu92/onedrive-d) | |
onetime | one-time pad | :heavy_check_mark: | | |
oolite | Elite game | :heavy_check_mark: | oolite.org | |
openarena | Quake-like FPS | :heavy_check_mark: | oolite.org | |
openshot | video editor | :heavy_check_mark: | | good all rounder |
openssh-server | OpenSSH | :heavy_check_mark: | | |
openvpn | VPN | :heavy_check_mark: | | |
opera | browser | :heavy_check_mark: | | use `apt` |
oprofile | in-depth profiling | :heavy_check_mark: | | |
optipng | optimise PNGs | :heavy_check_mark: | | |
orca | screenreader | :heavy_check_mark: | | |
osync | rsync simplifier | :heavy_multiplication_x: | [Osync](https://github.com/deajan/osync) | |
p0f | passive OS fingerprinting tool | :heavy_check_mark: | | quieter than *nmap* |
pack | password analyser | :heavy_multiplication_x: | | |
packeth | GUI Ethernet packet generator | :heavy_check_mark: | | |
packetsender | GUI to create and send packets | :heavy_multiplication_x: | [packetsender](https://packetsender.com/download ) | |
pamix | PulseAudio mixer | :heavy_multiplication_x: | [PAmix](https://github.com/patroclos/PAmix) | |
pandoc | DocX/RTF/HTML/Markdown converter | :heavy_check_mark: | [Pandoc](http://pandoc.org/) | |
parallel | multi-threaded Bash scripts | :heavy_check_mark: | | in *moreutils* |
parted | disk partitioner | :heavy_check_mark: | | creates GPT partitions, but does not resize |
passwordsafe | password vault | :heavy_check_mark: | [Password Safe](https://sourceforge.net/projects/passwordsafe/)| |
patator | multi-purpose brute-forcer | :heavy_multiplication_x: | | |
pavucontrol | PulseAudio volume control | :heavy_check_mark: | | |
pdftotext | PDF to text | :heavy_check_mark: | | in poppler-utils |
peazip | multi-zip GUI and converter | :heavy_multiplication_x: | [PeaZip](https://sourceforge.net/projects/peazip/) | |
pemcracker | PEM cracker | :heavy_multiplication_x: | [pemcracker](https://github.com/bwall/pemcracker) | |
pentbox | security and stability tester | :heavy_multiplication_x: | | |
percona-toolkit | *MySQL* toolkit | :heavy_check_mark: | | |
perf | code performance monitor | :heavy_check_mark: | | |
pdfbooklet | PDF printer | :heavy_multiplication_x: | [PDFbooklet](https://sourceforge.net/projects/pdfbooklet/) | |
pdfcrack | PDF password cracker | :heavy_check_mark: | | |
pdfedit | PDF editor | :heavy_check_mark: | | good at text, no image editing |
pdfgrep | PDF search | :heavy_check_mark: | [PDFgrep](https://pdfgrep.org/) |
pdfmod | PDF editor | :heavy_check_mark: | | simple but good: edit meta data. remove page, extract page |
pdnsd | proxy DNS server | :heavy_check_mark: | | |
pgadmin3 | GUI admin for *PostgresSQL* | :heavy_check_mark: | | |
pgpdump | GPG/PGP file visualiser | :heavy_check_mark: | | |
phatch | batch image converter | :heavy_check_mark: | | |
phoronix | benchmark suite | :heavy_multiplication_x: | [phoronix](http://phoronix-test-suite.com/) | |
photorec | file recovery tool | :heavy_multiplication_x: | cgsecurity.org | |
php-markdown | PHP Markdown renderer | :heavy_check_mark: | | |
php5-mongo | PHP *MongoDB* driver | :heavy_check_mark: | | use `apt` |
php5-mysqlnd | MySQLi driver | :heavy_check_mark: | | `get->result`; use `apt` |
php-codesniffer | phpcs in terminal | :heavy_check_mark: | | |
phplint | PHP linter | :heavy_multiplication_x: | | |
phpunit | PHP unit test suite | :heavy_check_mark: | | |
phrasendrescher | SSH dictionary attacker | :heavy_multiplication_x: | | `pd ssh -d pass.txt -t <IP> -v`) |
pic | graphics programming language | :heavy_multiplication_x: | [piC](http://www.kohala.com/start/troff/troff.html) | |
picard | audio file manager | :heavy_check_mark: | | |
pigz | multi-core GZIP | :heavy_check_mark: | | |
pinta | Paint.NET clone | :heavy_check_mark: | | |
piper | mouse config | :heavy_multiplication_x: | [Piper](https://github.com/libratbag/piper) | |
pitivi | video editor | :heavy_check_mark: | | suitable for: clips to combine, add audio track, filter |
playonlinux | MS games through Wine | :heavy_check_mark: | | |
playshell | terminal media player | :heavy_multiplication_x: | [PlayShell](https://sourceforge.net/projects/playshell/) | |
plecast | Wordpress plugin analyser | :heavy_multiplication_x: | | |
plumecreator | bookwriting editor | :heavy_multiplication_x: | | |
pmd | source code analyser | :heavy_multiplication_x: | [PMD](https://sourceforge.net/projects/pmd/) | |
pmount | mount removable devices as normal user | :heavy_check_mark: | | |
pngcrush | PNG compressor | :heavy_check_mark: | | |
pnscan | multi-threaded port scanner | :heavy_check_mark: | | |
pokerth | poker game | :heavy_check_mark: | | |
polygen | random sentences from grammar definitions | :heavy_check_mark: | | |
portdog | port scanner detector | :heavy_multiplication_x: | [PortDog](https://github.com/puniaze/PortDog) | |
postgresql | PostgreSQL | :heavy_check_mark: | | |
potamus | music player using dirs | :heavy_multiplication_x: | [Potamus](http://offog.org/code/potamus/) | |
povray | terminal raytacer | :heavy_check_mark: | | |
powertop | power consumption analyser | :heavy_check_mark: | | |
printer-driver | | :heavy_check_mark: | | |
privoxy | SOCKS requests to HTTP requests | :heavy_check_mark: | | block UDP leaks in *Tor* |
procenv | show process environment | :heavy_check_mark: | [procenv](https://github.com/jamesodhunt/procenv.git) | |
processing | Programming language | :heavy_multiplication_x: | | |
procinfo | reporter of /proc and /sys | :heavy_check_mark: | | also contains *lsdev* |
profile-sync-daemon | move browser profiles to RAM | :heavy_multiplication_x: | [profile-sync-daemon](https://github.com/graysky2/profile-sync-daemon) | SystemD |
prometheus.io | Nagios replacement for microservices | :heavy_multiplication_x: | https://github.com/prometheus | |
proxychains | redirect connections through proxy servers | :heavy_check_mark: | | |
psad | port scan detector | :heavy_check_mark: | | from iptables |
psensor | sensors | :heavy_check_mark: | | |
pst-utils | read MS Outlook PST files | :heavy_check_mark: | | .pst to .mbox |
publican | docbook XML publisher | :heavy_check_mark: | | |
puddletag | music file tag editor | :heavy_check_mark: | | |
putty | PuTTY for Linux | :heavy_check_mark: | | |
pv | pipe view meter | :heavy_check_mark: | | SSH bench etc |
pwgen | password generator | :heavy_check_mark: | | |
pybackpack | rdiff GUI | :heavy_check_mark: | | |
pychecker | Python linter | :heavy_check_mark: | | |
pylint | Python linter | :heavy_check_mark: | | |
pyrenamer | mass file renamer | :heavy_check_mark: | | |
pyrit | GPU WPA2 wireless cracker | :heavy_check_mark: | | |
python-mysqldb | Python *MySQL* API | :heavy_check_mark: | | |
python-pip | Python installer | :heavy_check_mark: | | `apt-get install python3-pip` |
python(3)-psutil | psutil | :heavy_check_mark: | | access reporting tools through python |
python-setuptools | | :heavy_check_mark: | | needed for *python-mysqldb* |
qalc | terminal calculator | :heavy_check_mark: | | |
qemu | processor emulator | :heavy_check_mark: | | `apt-get install kvm qemu-kvm qemu-kvmextras` |
qemu-kvm | multiple virtual PCs | :heavy_check_mark: | | |
qmmp | music player | :heavy_check_mark: | | |
qownnotes | notepad with Markdown | :heavy_multiplication_x: | [QOwnNotes](http://www.qownnotes.org/) | |
qmplay2 | video/YouTube player | :heavy_multiplication_x: | [QMPlay2](https://github.com/zaps166/QMPlay2) | GPU acceleration |
qrencode | QR generator | :heavy_check_mark: | | `qrencode -o f.png 'txt'` # -s height of pixel, -l H highest level of error correction|
qtox | encrypted IM | :heavy_multiplication_x: | | |
qtpfsgui | HDR tonemapper | :heavy_check_mark: | | |
qtqr | GUI QR generator | :heavy_check_mark: | | |
qtractor | audio/MIDI multitrack sequencer | :heavy_check_mark: | | |
qtvirtmanager | virtual hosts manager | :heavy_multiplication_x: | [QtVirtManager](https://github.com/F1ash/qt-virt-manager) | |
quetoo | Quake2 remake | :heavy_multiplication_x: | [QueToo](https://github.com/jdolan/quetoo) | |
quiterss | RSS reader | :heavy_check_mark: | | uses WebKit |
qupzilla | lightweight Chromium-based browser | :heavy_check_mark: | | |
qweborf | HTTP network sharing tool | :heavy_check_mark: | [QWeborf](https://github.com/ltworf/weborf) | |
rabbitvcs | SVN GUI | :heavy_check_mark: | | |
radamsa | fuzzer | :heavy_multiplication_x: | https://github.com/aoh/radama | swine to compile |
rand | random character generator | :heavy_check_mark: | | |
rapidsvn | SVN GUI | :heavy_check_mark: | | |
rarcrack | RAR cracker | :heavy_multiplication_x: | [rarCrack](https://sourceforge.net/projects/rarcrack/) | |
raspiraw | RaspPi RAW processing | :heavy_multiplication_x: | https://github.com/illes/raspiraw | |
ratproxy | passive web app security assessor | :heavy_check_mark: | | |
rats | rough auditing tool for security | :heavy_check_mark: | | |
rawtherapee | RAW file editor | :heavy_check_mark: | | |
rclone | sync files to/from GDrive/OneDrive | :heavy_multiplication_x: | [RClone](http://rclone.org/) | |
rcrack | cracker via rainbow tables | :heavy_multiplication_x: | | |
rdiff-backup | remote incremental backup | :heavy_check_mark: | | |
realvnc | remote desktop client | :heavy_check_mark: | | |
reaver | router WPS PIN brute-forcer | :heavy_check_mark: | | |
recoll | document text search | :heavy_check_mark: | | e.g. create text indexes of PDFs|
recsveditor | CSV editor | :heavy_multiplication_x: | [reCsvEditor](https://sourceforge.net/projects/recsveditor/) | Java |
rednotebook | calendar + notebook | :heavy_check_mark: | [RedNotebook](https://sourceforge.net/projects/rednotebook/) | |
reformat | text formatter | :heavy_check_mark: | | line length, margin |
remmina | remote desktop client | :heavy_check_mark: | | RDP must be enabled on Windows |
remnux | Linux malware analyser | :heavy_multiplication_x: | [remnux](https://sourceforge.net/projects/remnux/ ) | |
retext | ReText and Markdown editor | :heavy_check_mark: | [retext](https://github.com/retext-project/retext)| |
retroshare | encrypted IM | :heavy_multiplication_x: | [RetroShare](http://retroshare.net) | |
rdesktop | Linux to Windows remote desktop | :heavy_check_mark: | | okay for private network, not Internet |
recode | charset conversion in file | :heavy_check_mark: | | |
recoverjpeg | recover JPEGs/MOVs | :heavy_check_mark: | | from SD card |
regexxer | file regex view and replace | :heavy_check_mark: | | |
richochet | TOR chat | :heavy_multiplication_x: | [richochet](https://ricochet.im/) | |
rig | random person id generator | :heavy_check_mark: | | |
rkhunter | rootkit hunter | :heavy_check_mark: | | |
rmlint | duplicate file remover | :heavy_multiplication_x: | [rmlint](https://github.com/sahib/rmlint) | |
rnd | random data generator | :heavy_multiplication_x: | [RND](https://github.com/Tinram/RND) | |
rosaimagewriter | USB Flash tool | :heavy_multiplication_x: | | |
rosegarden | music editor | :heavy_check_mark: | | |
rsmangler | word permutations | :heavy_multiplication_x: | | |
rsnapshot | filesystem snapshot | :heavy_check_mark: | | |
rssh | restricted shell | :heavy_check_mark: | | give user only: scp, sftp, rsync |
rst2pdf | ReText to PDF | :heavy_check_mark: | | |
rsyncrypto | rsync encryption | :heavy_check_mark: | | |
rtgen | rainbow table generator | :heavy_multiplication_x: | | `rtgen md5 loweralpha-numeric 1 5 0 3800 33554432 0` |
ruby | Ruby interpreter | :heavy_check_mark: | | irb |
rustc | Rust language compiler | :heavy_multiplication_x: | | cargo is project manager |
samhain | IDS | :heavy_check_mark: | | |
sane | document scan tools | :heavy_check_mark: | | |
sbackup | simple backup | :heavy_check_mark: | | |
screenruler | pixel ruler | :heavy_check_mark: | | |
screenstudio | screencast creator | :heavy_multiplication_x: | [ScreenStudio](http://screenstudio.crombz.com/) | |
scribus | desktop publisher/PDF editor | :heavy_check_mark: | | |
secure-delete | wipe files/swap/memory | :heavy_check_mark: | | |
sendemail | terminal email client | :heavy_check_mark: | | |
sendmail | mail agent | :heavy_check_mark: | | |
sentinel | 1980's game | :heavy_multiplication_x: | [Sentinel](https://github.com/kochsoft/free_sentinel_gl/wiki/Free-Sentinel-GL) | |
sentry | brute-force blocker | :heavy_multiplication_x: | [sentry](https://github.com/msimerson/sentry) | |
sfk | extensive file utilities | :heavy_multiplication_x: | [Swiss File Knife ](http://stahlworks.com/dev/swiss-file-knife.html) | |
sg3-utils | SCSI utils | :heavy_check_mark: | | |
shellcheck | Bash lint | :heavy_check_mark: | shellcheck.net | |
shellnoob | shell code generator | :heavy_multiplication_x: | | |
shellpic | preview images in SSH | :heavy_multiplication_x: | [Shellpic](https://github.com/larsjsol/shellpic) | |
shotcut | video editor | :heavy_multiplication_x: | [Shotcut](https://shotcut.org/) | |
shwr | HTML presentations | :heavy_multiplication_x: | [Shwr](https://shwr.me/) | |
siege | server stress tester | :heavy_check_mark: | | |
sigil | ebook editor | :heavy_multiplication_x: | [Sigil](https://sigil-ebook.com/) | |
silver-searcher | source code grep | :heavy_multiplication_x: | [Silver Searcher](https://github.com/ggreer/the_silver_searcher) | |
simplebackup | backup utility | :heavy_check_mark: | | |
simplescreenrecorder | record programs/games | :heavy_multiplication_x: | [SimpleScreenRecorder](http://www.maartenbaert.be/simplescreenrecorder/) | |
simon | voice recognition | :heavy_check_mark: | | |
sipcrack | SIP log-in dumper/cracker | :heavy_check_mark: | | |
sipvicious | audit SIP-based VoIP systems | :heavy_multiplication_x: | | |
sirikali | GUI for gocryptfs/encfs/securefs | :heavy_multiplication_x: | [SiriKali](https://mhogomchungu.github.io/sirikali/) | |
sk1 | vector graphics editor | :heavy_multiplication_x: | [sK1](http://sk1project.org/) | |
skipfish | web app reconnaissance tool | :heavy_check_mark: | | |
skrooge | money accounting | :heavy_check_mark: | | |
skype | | :heavy_check_mark: | | |
skype-ghetto | open source alternative | :heavy_multiplication_x: | [Skype-Ghetto](https://github.com/stanfieldr/ghetto-skype) | |
slack | multi-server config manger | :heavy_check_mark: | | uses existing tools |
slowhttptest | DDoS simulator | :heavy_check_mark: | | |
slurm | bandwidth monitor | :heavy_check_mark: | | |
smartmontools | monitor/control storage that supports SMART | :heavy_check_mark: | | |
smbclient | Samba client | :heavy_check_mark: | | |
smbmap | SMB network mapper | :heavy_multiplication_x: | [smbmap](https://github.com/ShawnDEvans/smbmap) | |
smemstat | memory monitoring tool | :heavy_check_mark: | | Debian |
smplayer | video player | :heavy_check_mark: | | GPU acceleration |
snapper | BTRFS filesystem snapshots | :heavy_check_mark: | | |
snort | IDS | :heavy_check_mark: | | |
socat | multipurpose relay for bidirectional data transfer | :heavy_check_mark: | | bench etc |
softethervpn | VPN | :heavy_multiplication_x: | | |
sox | terminal audio file manipulator | :heavy_check_mark: | | |
sparta | internal network infrastructure pen tool | :heavy_multiplication_x: | [sparta](https://github.com/secforce/sparta) | |
sparkleshare | dropbox alternative using SSH and *Git* | :heavy_check_mark: | | |
speedtest-cli | bandwidth speed tester | :heavy_check_mark: | [speedtest-cli](https://github.com/sivel/speedtest-cli) | `pip install speedtest-cli` |
spek | acoustic spectrum analyser | :heavy_check_mark: | [Spek](https://github.com/alexkay/spek) | |
splint | C linter | :heavy_check_mark: | | |
sqlbrute | brute forcing SQL injection | :heavy_multiplication_x: | [SQLBrute](https://github.com/GDSSecurity/SQLBrute) | |
sqlcipher | SQLite encryption | :heavy_check_mark: | | |
sqlite3 | SQLite | :heavy_check_mark: | | |
sqlitebrowser | SQLite GUI | :heavy_check_mark: | | simpler than *sqliteman* |
sqliteman | SQLite GUI | :heavy_check_mark: | | *SQLiteStudio* is better for unicode data import |
sqlitestudio | SQLite manager | :heavy_multiplication_x: | [SQLiteStudio](https://sqlitestudio.pl/index.rvt) | |
sqlmap | SQL injection tool | :heavy_check_mark: | [SQLMap](http://sqlmap.org/) | |
sqlninja | MS SQL Server injection | :heavy_multiplication_x: | [sqlninja](https://sourceforge.net/projects/sqlninja) | |
sqlsus | *MySQL* attacker | :heavy_multiplication_x: | | |
srm | secure file deletion | :heavy_multiplication_x: | [SRM](https://sourceforge.net/projects/srm/) | slow, punishing on SSDs |
ssldump | SSLv3/TLS network protocol analyzer | :heavy_check_mark: | | |
sshguard | SSH brute-force protection | :heavy_check_mark: | [SSHGuard](http://www.sshguard.net/) | more intelligent than *fail2ban* |
sslscan | SSL scanner | :heavy_check_mark: | | |
sshfs | mount remote filesystem | :heavy_check_mark: | | Gnome already does this through GVFS |
sshpass | send password to SCP etc from script | :heavy_check_mark: | | |
sshtalk | SSH chat server | :heavy_multiplication_x: | | |
sshuttle | VPN | :heavy_check_mark: | [sshuttle](https://github.com/apenwarr/sshuttle) | |
ssr | screen recorder | :heavy_multiplication_x: | [SSR](http://www.maartenbaert.be/simplescreenrecorder/) | |
standardnotes | notes app | :heavy_multiplication_x: | [standardnotes](https://github.com/standardnotes) | |
statsprocessor | word generator | :heavy_multiplication_x: | | |
strace | system call tracer | :heavy_check_mark: | | |
stress | stress CPU/memory/disk | :heavy_check_mark: | | |
structure-synth | 3D structure generator | :heavy_check_mark: | | |
stunnel | SSL tunnel for own apps | :heavy_check_mark: | [STunnel](https://www.stunnel.org/index.html) | |
subbrute | enumerate DNS records/subdomains | :heavy_multiplication_x: | [subbrute](https://github.com/TheRook/subbrute) | |
subversion | SVN | :heavy_check_mark: | | |
sucrack | SU brute-forcer | :heavy_check_mark: | | |
sunflow | raytracer | :heavy_check_mark: | | Java-based |
suricata | IDS | :heavy_check_mark: | | |
sux | su for X | :heavy_check_mark: | | |
svg-edit | SVG editor | :heavy_multiplication_x: | | |
swaks | SMTP test tool | :heavy_check_mark: | | |
swatch | log file event notifier | :heavy_check_mark: | | |
synfig | vector 2D animation | :heavy_check_mark: | | |
sysbench | system benchmarker | :heavy_check_mark: | [info](https://www.howtoforge.com/how-to-benchmark-your-system-cpu-file-io-mysql-with-sysbench)| |
sysdig | system exploration/troubleshooting | :heavy_check_mark: | | |
sysstat | system stats/benchmarking | :heavy_check_mark: | | *sar* as binary log reader |
system-config-lvm | LVM partitioning GUI | :heavy_check_mark: | | |
system-config-samba | Samba GUI | :heavy_check_mark: | | |
systemd-analyze | SystemD analyser | :heavy_check_mark: | | |
systemd-ui | SystemD GUI | :heavy_check_mark: | | |
systemdgenie | SystemD utility | :heavy_multiplication_x: | [systemdgenie](https://cgit.kde.org/systemdgenie.git) | |
systemtap | kernel instrumentation | :heavy_check_mark: | | |
sysv-rc-conf | SysV runlevel config tool | :heavy_check_mark: | | use `apt`|
taskwarrior | terminal ToDo list | :heavy_multiplication_x: | [Taskwarrior](https://taskwarrior.org/) | |
tasque | task manager | :heavy_check_mark: | | |
tcpdump | terminal network traffic analyzer | :heavy_check_mark: | | |
tcpflow | TCP flow recorder | :heavy_check_mark: | | |
tcpick | TCP stream sniffer/connection tracker | :heavy_check_mark: | | |
tcpspy | TCP/IP connections logger | :heavy_check_mark: | | |
tcptrace | graphical *tcpdump* output | :heavy_check_mark: | | |
tcpxtract | extract files from network traffic | :heavy_check_mark: | | |
terminator | multiple terminals | :heavy_check_mark: | | |
terminix | terminal emulator | :heavy_multiplication_x: | [Terminix](https://github.com/gnunn1/terminix) | |
termpix | terminal image viewer | :heavy_multiplication_x: | [Termpix](https://github.com/hopey-dishwasher/termpix) | |
testdisk | disk/partition recovery tool | :heavy_check_mark: | | |
tesseract-ocr | OCR processor | :heavy_check_mark: | | |
tetravex | number block game | :heavy_check_mark: | | (gno) Tetravex |
texmaker | Latex editor | :heavy_check_mark: | | |
tig | terminal *Git* history viewer | :heavy_check_mark: | | |
tiger | report root vulnerabilities | :heavy_check_mark: | | |
tigerVNC | remote desktop | :heavy_check_mark: | | |
tinyproxy | non-caching HTTP proxy | :heavy_check_mark: | | |
tlp | laptop power manager | :heavy_multiplication_x: | [TLP](http://linrunner.de/en/tlp/tlp.html) | |
tmux | terminal multiplexer | :heavy_check_mark: | | |
todo.txt | terminal notes | :heavy_multiplication_x: | [todo.txt](http://todotxt.com/) | |
tofromdos | EOL character converter | :heavy_check_mark: | | |
tomahawk | media player | :heavy_check_mark: | | |
tor | anonymising overlay | :heavy_check_mark: | | get source, **not** repo version |
torcs | racing car simulator | :heavy_check_mark: | [torcs](https://sourceforge.net/projects/torcs/) | |
torsocks | use SOCKS-friendly apps with Tor | :heavy_check_mark: | | e.g. SSH |
tox | encrypted chat | :heavy_multiplication_x: | [Tox](https://github.com/qTox/qTox) | see *qTox* |
traceroute | trace packets | :heavy_check_mark: | | |
transmageddon | media file converter | :heavy_check_mark: | | |
trash-cli | terminal trash bin control | :heavy_check_mark: | | trash-empty, trash-list |
tree | terminal directory tree lister | :heavy_check_mark: | | |
treeline | *TreePad*/XML/bookmark editor | :heavy_check_mark: | [Treeline](http://treeline.bellz.org) | |
treepad | notes manager | :heavy_multiplication_x: | [TreePad](http://www.treepad.com/linux/treepadlite/) | |
trickle | bandwidth throttler | :heavy_check_mark: | | |
trimage | PNG/JPG compressor | :heavy_check_mark: | | |
trupax | encrypt files and folders | :heavy_multiplication_x: | [TruPax](https://coderslagoon.com/) | |
tshark | terminal Wireshark | :heavy_check_mark: | | |
tsung | HTTP benchmark and database tester | :heavy_check_mark: | [TSung](http://tsung.erlang-projects.org) | sophisticated |
tt-rss | tiny tiny RSS | :heavy_check_mark: | | |
ttf-mscorefonts-installer | MS TTF fonts | :heavy_check_mark: | | |
tuxguitar | music app including scoresheet | :heavy_check_mark: | [Tuxguitar](http://tuxguitar.herac.com.ar) | |
ubuntu-tweak | Ubuntu config tool | :heavy_check_mark: | | use `apt` |
ufraw | RAW importer | :heavy_check_mark: | | |
ufw | firewall | :heavy_check_mark: | | |
umplayer | video player | :heavy_multiplication_x: | | supposed better DVD playback than VLC |
unetbootin | .iso to USB boot | :heavy_check_mark: | | |
unhtml | remove HTML tags from file | :heavy_check_mark: | | |
unison | file sync tool | :heavy_check_mark: | | Windows to Linux too |
units | terminal unit converter | :heavy_check_mark: | | |
unity-tweak-tool | config tool for Unity | :heavy_check_mark: | | |
unoconv | Office .doc converter | :heavy_multiplication_x: | [Unoconv](http://dag.wiee.rs/home-made/unoconv/) | |
unshield | extract CAB files from InstallShield | :heavy_check_mark: | | |
unsort | jumbles lines in file | :heavy_check_mark: | | |
usbview | GUI *lsusb* | :heavy_check_mark: | | |
valac | Vala compiler | :heavy_check_mark: | | |
valentinastudio | MySQL/PostgreSQL/MSSQL browser| :heavy_multiplication_x: | [Valentina Studio](valentina-db.com/en/all-downloads/vstudio/current) | |
valgrind | memory debugger and profiler | :heavy_check_mark: | | |
valkyrie | GUI for *valgrind* | :heavy_check_mark: | | |
vbindiff | visual binary file compare | :heavy_check_mark: | | |
vega | web app tester | :heavy_multiplication_x: | | Java |
veracrypt | TrueCrypt replacement | :heavy_multiplication_x: | [VeraCrypt](http://veracrypt.codeplex.com/) | |
vidalia | TOR GUI frontend | :heavy_check_mark: | | |
vim | programming/text editor | :heavy_check_mark: | | |
vinagre | GNOME remote desktop client | :heavy_check_mark: | | |
virt-manager | virtual machine manager | :heavy_check_mark: | virt-manager.org | good options range), frontend for Qemu |
virtualbox | virtual machines | :heavy_check_mark: | virtualbox.org | GPU acceleration |
visual-studio-code | editor | :heavy_multiplication_x: | [Visual Studio Code](http://code.visualstudio.com/) | huge, limited |
vmware | virtual machines | :heavy_check_mark: | | GPU acceleration |
tightvnc | remote desktop viewer | :heavy_check_mark: | | |
vobcopy | CD/MP4 track copier | :heavy_check_mark: | | |
voiphopper | VoIP security testing tool | :heavy_multiplication_x: | | |
voipong | VoIP sniffer/call detector | :heavy_multiplication_x: | | |
vokoscreen | screencast creator | :heavy_check_mark: | | |
vpaint | vector paint | :heavy_multiplication_x: | [VPaint](http://vpaint.org/) | |
vrms | virtual Stallman: list non-free packages | :heavy_check_mark: | | |
w3af | web app vulnerability framework | :heavy_check_mark: | | |
waidps | wireless auditing + IDS | :heavy_multiplication_x: | [waidps](https://github.com/SYWorks/waidps) | |
wallpaperd | wallpaper rotator | :heavy_multiplication_x: | | |
wammu | (old) phone manager, info exporter | :heavy_check_mark: | | |
wapiti | web app vulnerability scanner | :heavy_check_mark: | | |
wbox | HTTP testing tool and configuration-less HTTP server | :heavy_check_mark: | | |
wdiff | word diff | :heavy_check_mark: | | extended diff |
webcamoid | webcam tool | :heavy_multiplication_x: | [Webcamoid](http://webcamoid.github.io/) | |
webshag | web server auditor | :heavy_multiplication_x: | | |
webslayer | web app brute-forcer | :heavy_multiplication_x: | | |
wfuzz | web app brute-forcer | :heavy_check_mark: | [WFuzz](https://github.com/xmendez/wfuzz) | |
wget | web file retriever | :heavy_check_mark: | | |
whipper | CD ripper | :heavy_multiplication_x: | [Whipper](https://github.com/JoeLametta/whipper) | |
whiptail | TUI shell interface | :heavy_check_mark: | | |
whois | WHOIS client | :heavy_check_mark: | | |
whycanticonnect | connection analyser | :heavy_multiplication_x: | [Why Can't I Connect?](https://sourceforge.net/projects/wciconnect/) | |
wicd | wireless manager | :heavy_check_mark: | | |
wifite | wireless auditor/attacker | :heavy_check_mark: | | |
wig | web app info gatherer | :heavy_multiplication_x: | [wig](https://github.com/jekyc/wig) | e.g CMS version |
winff | GUI video/audio batch converter | :heavy_check_mark: | | uses ffmpeg |
wings3d | 3D modeller | :heavy_check_mark: | | |
wireguard | VPN | :heavy_multiplication_x: | [WireGuard](https://www.wireguard.io/) | |
wireshark | GUI network traffic analyzer | :heavy_check_mark: | | |
wkhtmltopdf | HTML to PDF | :heavy_check_mark: | | WebKit-based |
wordgrinder | terminal wordprocessor | :heavy_multiplication_x: | [WordGrinder](http://cowlark.com/wordgrinder/) | |
workrave | RSI timer | :heavy_check_mark: | | |
wpscan | Wordpress scanner | :heavy_multiplication_x: | | |
wtop | Apache top | :heavy_multiplication_x: | [WTop](https://github.com/ClockworkNet/wtop) | |
x264 | video encoder | :heavy_check_mark: | | |
x265 | video compressor | :heavy_multiplication_x: | [x265](http://x265.org) | |
x2go | remote GUI connection | :heavy_multiplication_x: | [X2Go](http://wiki.x2go.org/doku.php)| with SSH |
xa65 | 6502 CPU cross-assembler | :heavy_check_mark: | [xa65](http://www.floodgap.com/retrotech/xa/) | |
xaos | fractals | :heavy_check_mark: | | |
xauth | X authentication - needed for remote X GUI | :heavy_check_mark: | | |
xcalib | for screen invert | :heavy_check_mark: | | |
xchm | .chm file reader | :heavy_check_mark: | | |
xclip | terminal to X clipboard | :heavy_check_mark: | | |
xdebug | phpX-xdebug | :heavy_check_mark: | | where 'X' is version |
xdg-app | app sandbox | :heavy_multiplication_x: | [PPA](ppa:alexlarsson/xdg-app) | |
xdotool | simulate mouse/key input | :heavy_check_mark: | | |
xfractint | fractals | :heavy_check_mark: | | |
xicc | set ICC colour profile for X | :heavy_check_mark: | | |
xiphos | Bible | :heavy_check_mark: | | |
xmlcopyeditor | XML editor | :heavy_check_mark: | | |
xmlint | XML linter | :heavy_check_mark: | | |
xnee | X11 user-action recorder | :heavy_check_mark: | | |
xnretro | retro photo effects | :heavy_multiplication_x: | | |
xowa | Wikipedia reader | :heavy_multiplication_x: | [Xowa](https://sourceforge.net/projects/xowa/?source=directory) | |
xplico | network analysis | :heavy_multiplication_x: | [Xplico](http://www.xplico.org/) | browser-based |
xprobe | remote OS identification | :heavy_check_mark: | | *nmap*-like; calls *xprobe2* |
xrdp | RDP server | :heavy_check_mark: | | |
xresprobe | X resolution probe | :heavy_check_mark: | | |
xsane | document scanner GUI | :heavy_check_mark: | | |
xscreensaver-data-extra | extra Gnome screensavers | :heavy_check_mark: | | |
xspy | keylogger | :heavy_multiplication_x: | | ! |
xsser | XSS auditor | :heavy_multiplication_x: | | |
xul-ext-lightning | Thunderbird calendar | :heavy_check_mark: | | |
xsel | access X clipboard (pipe in/out) | :heavy_check_mark: | | |
xz-utils | xz files | :heavy_check_mark: | | |
yara | exe malware identifier | :heavy_check_mark: | | |
youtube-dl | YouTube downloader | :heavy_check_mark: | | |
yersinia | advanced, obtuse network vulnerabilities checker | :heavy_check_mark: | | |
zabbix | network monitoring package | :heavy_check_mark: | | |
zap | zed attack proxy | :heavy_multiplication_x: | | web app vulnerabilities |
zeal | documentation browser | :heavy_multiplication_x: | [Zeal](https://https://github.com/zealdocs/zeal) | |
zenmap | *NMap* GUI | :heavy_check_mark: | | |
zentyal | server GUI setup + Exchange replacement | :heavy_check_mark: | | |
zerotier | easy VPN | :heavy_multiplication_x: | [ZeroTier](http://zerotier.com) | |
zim | 'desktop wiki' notepad | :heavy_check_mark: | | |
zmap | large network scanner | :heavy_check_mark: | | no connects like *nmap*, open ports |
zurmo | CRM | :heavy_multiplication_x: | [Zurmo](http://zurmo.org) | |
zzuf | app fuzzer | :heavy_check_mark: | | |


## License

Licensed under the [MIT License](https://github.com/Tinram/Linux-Utilities/blob/master/LICENSE).