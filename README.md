
# Linux Utilities

Personal reference list of Linux programs and packages &ndash; biased to my work, interests, and needs when setting-up Linux boxes.

Approximately 1.3k programs (1% of Ubuntu repo), arranged alphabetically.

#### Sources

*Ubuntu* repository, *GitHub*, *SourceForge*, vendor websites.  
Collated over a number of years from Linux magazines, web searches, and repo hunting.

#### Notes

A tick in the repo column means the package should exist in the main Ubuntu repo. Nevertheless, some packages can be hidden away &ndash; these are marked with *'use apt'* (`apt search <pkg>` to search and `sudo apt install <pkg>` to install).

Some of the programs listed are included by default with Ubuntu-based distros. Nevertheless, they remain, since on some distro installs they are curiously absent.

[**Ubuntu repo search**](https://packages.ubuntu.com/)

----

package | description | repo | URL | notes |
:--- | :--- | :---: | :--- | :--- |
0xtools | */proc/* profiler | :heavy_multiplication_x: | [0xtools](https://github.com/tanelpoder/0xtools) | |
p7zip | file archiver | :heavy_check_mark: | [7-Zip](https://www.7-zip.org/) | also *p7Zip-full* <a id="7zip"></a> |
abcde | CD ripper | :heavy_check_mark: | [ABCDE](https://www.andrews-corner.org/linux/abcde/index.html) | |
abiword | lightweight wordprocessor | :heavy_check_mark: | | |
abricotine | Markdown editor | :heavy_multiplication_x: | [Abricotine](https://github.com/brrd/Abricotine) | |
acl | ACL utilities | :heavy_check_mark: | | |
adb | Android Debug Bridge | :heavy_check_mark: | | |
aescrypt | cross-platform file encryption | :heavy_multiplication_x: | [AESCrypt](https://github.com/paulej/AESCrypt) | |
afick | file integrity notifier | :heavy_multiplication_x: | [AFICK](https://sourceforge.net/projects/afick/) | |
afl | fuzzer | :heavy_check_mark: | [AFL](https://lcamtuf.coredump.cx/afl/) [Google's](https://github.com/google/AFL) | |
aide | host-based IDS | :heavy_check_mark: | | |
aircrack-ng | wireless cracker | :heavy_check_mark: | [aircrack-ng](https://github.com/aircrack-ng/aircrack-ng) | <a id="aircrack"></a> |
alacritty | GPU-accelerated CLI emulator | :heavy_multiplication_x: | [alacritty](https://github.com/jwilm/alacritty) | |
alien | *.rpm* to *.deb* converter | :heavy_check_mark: | | |
amass | attack surface mapper | :heavy_multiplication_x: | [Amass](https://github.com/OWASP/Amass) | |
ananicy | nice-ness daemon | :heavy_multiplication_x: | [Ananicy](https://github.com/Nefelim4ag/Ananicy) | |
anbox | Android runtime | :heavy_multiplication_x: | [anbox](https://github.com/anbox/anbox) | |
anjuta | C/C++ editor | :heavy_check_mark: | | |
anki | flashcards | :heavy_multiplication_x: | [Anki](https://apps.ankiweb.net/) [repo](https://github.com/ankitects/anki) | |
ansible | alternative to Puppet/Chef | :heavy_check_mark: | | only dependencies are Python/SSH; `pip install ansible` |
ansifilter | remove control codes | :heavy_multiplication_x: | [Ansifilter](http://andre-simon.de/doku/ansifilter/en/ansifilter.php) | |
antimony | CAD modeller | :heavy_multiplication_x: | [Antimony](https://www.mattkeeter.com/projects/antimony/) | |
antiword | Word files converted to text/PS/PDF | :heavy_check_mark: | | |
apachetop | `top` for Apache | :heavy_check_mark: | | use `apt` |
apfs-fuse | FUSE driver for mounting Apple filesystem | :heavy_multiplication_x: | [apfs-fuse](https://github.com/sgan81/apfs-fuse) | |
apktool | reverse engineer Android apk files | :heavy_check_mark: | | |
apostrophe | Markdown editor | :heavy_multiplication_x: | [Apostrophe](https://gitlab.gnome.org/somas/apostrophe) | |
appimagecraft | AppImage builder | :heavy_multiplication_x: | [appimagecraft](https://github.com/TheAssassin/appimagecraft) | |
appimagelauncher | run AppImages | :heavy_multiplication_x: | [AppImageLauncher](https://github.com/TheAssassin/AppImageLauncher/) | |
appimagelint | AppImage checker | :heavy_multiplication_x: | [appimagelint](https://github.com/TheAssassin/appimagelint) | |
appimagepool | AppImageHub Client | :heavy_multiplication_x: | [AppImagePool](https://github.com/prateekmedia/appimagepool) | |
aqemu | [Qemu](#qemu) + KVM GUI | :heavy_check_mark: | | |
arandr | GUI for xrandr (X settings) | :heavy_check_mark: | | |
ardour | audio editor | :heavy_check_mark: | | |
arecabackup | backup | :heavy_multiplication_x: | [Areca Backup](https://areca-backup.org) | Java-based |
argus | IP network transaction auditor | :heavy_check_mark: | | |
argyll | monitor colour callibrator | :heavy_check_mark: | | GUI is [dispcalgui](#dispcalgui) <a id="argyll"></a> |
aria2 | CLI advanced download manager | :heavy_check_mark: | | |
arista | media converter | :heavy_check_mark: | | |
arp-scan | ARP scanner/fingerprinting | :heavy_check_mark: | | |
arpwatch | Ethernet MAC address monitor | :heavy_check_mark: | | |
artha | offline thesaurus | :heavy_check_mark: | | |
asciinema | terminal recorder | :heavy_check_mark: | [asciinema](https://asciinema.org/) [repo](https://github.com/asciinema/asciinema) | `asciinema rec >> exit` |
astyle | code formatter | :heavy_check_mark: | [Artistic Style](https://astyle.sourceforge.net/) | C/C++/Java; good for other langs too |
asunder | CD ripper | :heavy_check_mark: | [Asunder](http://littlesvr.ca/asunder/) | |
athena-jot | data generator | :heavy_check_mark: | | |
atril | MATE PDF viewer | :heavy_check_mark: | | |
attr | filesystem extended attribute utils | :heavy_check_mark: | | |
audacious | music player | :heavy_check_mark: | [Audacious](https://audacious-media-player.org/) | |
audacity | sound editor | :heavy_check_mark: | | |
aview | images to ASCII art | :heavy_check_mark: | | |
auditd | user auditing | :heavy_check_mark: | | `auditctl`, `aureport`, `ausearch`, `autrace` |
aura | background setter | :heavy_multiplication_x: | [Aura](https://sourceforge.net/projects/desktop-aura/) | |
automater | webhost look-up | :heavy_multiplication_x: | | extensive look-up |
auto-cpufreq | laptop power manager | :heavy_multiplication_x: | [auto-cpufreq](https://github.com/AdnanHodzic/auto-cpufreq) | |
automysqlbackup | periodic backups of MySQL DBs | :heavy_check_mark: | | |
autossh | auto restart SSH sessions | :heavy_check_mark: | | |
autotrash | purge trash files | :heavy_check_mark: | | |
avahi-daemon | discover hosts | :heavy_check_mark: | | name instead of IP |
avidemux | video editor/converter | :heavy_multiplication_x: | | for quick edits to single video clip |
awffull | weblog analyser | :heavy_check_mark: | | localhost-based |
axel | CLI download accelerator | :heavy_check_mark: | | |
azpainter | image editor | :heavy_multiplication_x: | [AzPainter](https://osdn.net/projects/azpainter/releases/67130) | 16-bit colours |
b2 | BBC Micro emulator | :heavy_multiplication_x: | [b2](https://github.com/tom-seddon/b2) | |
babeltrace | trace conversion | :heavy_check_mark: | | |
babe-qt | tiny Qt music player | :heavy_multiplication_x: | [babe-qt](https://github.com/milohr/babe-qt) | |
backerupper | *tar.gz* backups | :heavy_multiplication_x: | [Backerupper](https://sourceforge.net/projects/backerupper/) | allows file exclusion | |
backintime | backup tool | :heavy_check_mark: | [backintime](https://github.com/bit-team/backintime) | |
bacon | BASIC to C converter | :heavy_multiplication_x: | [BaCon](https://chiselapp.com/user/bacon/repository/bacon/home) | |
bacula | backup | :heavy_check_mark: | | |
bandwhich | TUI bandwidth utilisation | :heavy_multiplication_x: | [bandwhich](https://github.com/imsnif/bandwhich) | |
bandwidthd | track network usage | :heavy_check_mark: | | HTML/image output|
bashate | Bash script linter | :heavy_check_mark: | | |
bashtop | resource monitor | :heavy_multiplication_x: | [bashtop](https://github.com/aristocratos/bashtop) | see [bpytop](#bpytop) |
bat | `cat` on steroids | :heavy_multiplication_x: | [bat](https://github.com/sharkdp/bat) |  |
beast | music synthesis | :heavy_check_mark: | | |
bed | daemon vulnerability checker | :heavy_multiplication_x: | [bed](https://github.com/crunchsec/bed/) | |
bench | CLI benchmark tool | :heavy_multiplication_x: | [bench](https://github.com/Gabriel439/bench) | |
bfbtester | EXE brute-force tester | :heavy_check_mark: | | |
binary-analyser | analyse binaries | :heavy_multiplication_x: | [Binary Analyser](https://bitbucket.org/mihaila/bindead/wiki/Home) | |
bing-ip2hosts | enumerate hostnames via Bing | :heavy_check_mark: | | |
binstats | binary stats | :heavy_check_mark: | | overview of installed binaries |
binwalk | binary file searcher | :heavy_check_mark: | [binwalk](https://github.com/devttys0/binwalk) | sub-files + code |
birdfont | font editor | :heavy_multiplication_x: | [BirdFont](https://birdfont.org) | |
bit | [Git](#git) CLI client | :heavy_multiplication_x: | [bit](https://github.com/chriswalz/bit) | |
blast | API load tester | :heavy_multiplication_x: | [blast](https://github.com/dave/blast) | |
bleachbit | system cleaner | :heavy_check_mark: | | |
bless | GUI hex editor | :heavy_check_mark: | | |
blip | MySQL monitor | :heavy_multiplication_x: | [blip](https://cashapp.github.io/blip/) [repo](https://github.com/cashapp/blip) | |
bluelog | Bluetooth scanner | :heavy_multiplication_x: | | |
blueman | GUI Bluetooth | :heavy_check_mark: | | |
bluemon | de/activate programs on Bluetooth link quality | :heavy_check_mark: | | |
bluetooth | Bluetooth support | :heavy_check_mark: | | |
bluetuith | TUI Bluetooth manager | :heavy_multiplication_x: | [bluetuith](https://github.com/darkhz/bluetuith) | |
bluez | Bluetooth tools | :heavy_check_mark: | | |
bmon | bandwidth monitor | :heavy_check_mark: | | |
bonzomatic | shader coding tool | :heavy_multiplication_x: | [Bonzomatic](https://github.com/Gargaj/Bonzomatic) | |
bookworm | eBook reader | :heavy_multiplication_x: | [Bookworm](https://babluboy.github.io/bookworm/) | |
boostchanger | CPU controller | :heavy_multiplication_x: | [boostchanger](https://github.com/nbebaw/boostchanger) | |
bootchart | boot time analyser | :heavy_check_mark: | | |
bootiso | ISO to USB booter | :heavy_multiplication_x: | [bootiso](https://github.com/jsamr/bootiso) | |
borgbackup | CLI backup tool | :heavy_check_mark: | | uses compression and encryption |
boxbackup-client | Box backup | :heavy_check_mark: | [boxbackup](https://www.boxbackup.org/) | `rsync`-like and encrypted |
boxbackup-server | Box backup | :heavy_check_mark: | [boxbackup](https://www.boxbackup.org/) | |
boxxy | isolate apps | :heavy_multiplication_x: | [boxxy](https://github.com/queer/boxxy) | |
bpfcc-tools | eBPF tools | :heavy_check_mark: | | |
bpytop | resource monitor | :heavy_multiplication_x: | [bpytop](https://github.com/aristocratos/bpytop) | <a id="bpytop"></a> |
brandy | BBC Micro emulator | :heavy_check_mark: | | |
brasero | ISO burner | :heavy_check_mark: | | |
bridge-utils | configure Ethernet bridge | :heavy_check_mark: | | |
broadband-speed | | :heavy_multiplication_x: | [speedtest-cli](https://github.com/sivel/speedtest-cli) | |
brutex | combine [WFuzz](#wfuzz)/[Hydra](#hydra) to brute-force ports | :heavy_multiplication_x: | [BruteX](https://github.com/1N3/BruteX) | |
btop | resource monitor | :heavy_check_mark: | [btop](https://github.com/aristocratos/btop) | |
btproxy | MITM Bluetooth analysis | :heavy_multiplication_x: | [btproxy](https://github.com/conorpp/btproxy) | |
btscanner | scanner for Bluetooth devices | :heavy_check_mark: | | |
buku | browser-independent bookmark manager | :heavy_multiplication_x: | [Buku](https://github.com/jarun/Buku) | |
bum | bootup manager | :heavy_check_mark: | | also [sysv-rc-conf](#sysv-rc-conf) |
bvi | hex editor | :heavy_check_mark: | | vi-like |
bwm-ng | CLI bandwidth monitor | :heavy_check_mark: | | |
byobu | screen command manager/multiplexer | :heavy_check_mark: | | through function keys |
byzanz | small screencast creator | :heavy_check_mark: | | |
cadubi | ASCII art drawing | :heavy_check_mark: | | |
calibre | eBook converter/library | :heavy_check_mark: | | |
catfish | GUI file search using [mlocate](#mlocate) | :heavy_check_mark: | | |
catimg | CLI image viewer | :heavy_multiplication_x: | [catimg](https://github.com/posva/catimg) | |
cccc | C/C++ code analyser | :heavy_check_mark: | | |
ccextractor | subtitle extractor | :heavy_multiplication_x: | [CCExtractor](https://sourceforge.net/projects/ccextractor/) | |
celestia | celestial simulator | :heavy_check_mark: | | |
cellwriter | handwriting recogniser | :heavy_check_mark: | | |
cfg2html | collect and display system config info | :heavy_multiplication_x: | [cfg2html](https://github.com/cfg2html/cfg2html) | |
cflow | C source control flow analyser | :heavy_check_mark: | | |
cdparanoia | CD ripper | :heavy_check_mark: | | |
ccrypt | AES recursive file encrypter | :heavy_check_mark: | | overwrites files, passphrases allegedly unsalted |
checkbashisms | | :heavy_check_mark: | | in [devscripts](#devscripts) |
checkinstall | installation tracker | :heavy_check_mark: | | source > package > install with package manager |
checksecurity | basic security check | :heavy_check_mark: | | |
chaosreader | trace network sessions, export to HTML | :heavy_check_mark: | | |
cherrytree | notes organiser with [7-Zip](#7zip) encryption | :heavy_check_mark: | [CentOS version](https://rpm.pbone.net/info_idpl_26487133_distro_redhatel6_com_cherrytree-0.33.4-1.el6.nux.noarch.rpm.html) | |
chkrootkit | rootkit detector | :heavy_check_mark: | | |
chm2pdf | *.chm* to PDF converter | :heavy_check_mark: | | |
chntpw | change Windows SAM password | :heavy_check_mark: | | |
cinelerra | non-linear video editor | :heavy_multiplication_x: | | |
ckport | EXE function/call checker | :heavy_check_mark: | | |
claws-mail | GTK mail client | :heavy_check_mark: | | |
clementine | music player/streamer | :heavy_check_mark: | | |
cloaker | GUI file encryption | :heavy_multiplication_x: | [Cloaker](https://github.com/spieglt/Cloaker) | |
cloakify | text steganography tool | :heavy_multiplication_x: | [Cloakify](https://github.com/TryCatchHCF/Cloakify) | |
cloc | count lines of code | :heavy_check_mark: | [CLOC](https://sourceforge.net/projects/cloc/) | most languages |
clonezilla | HDD backup/cloner | :heavy_check_mark: | | |
cloudcompare | photo to 3D point map | :heavy_multiplication_x: | [CloudCompare](https://cloudcompare.org/) | |
clusterssh | admin. simultaneous SSH shells | :heavy_check_mark: | | |
cmatrix | CLI Matrix | :heavy_check_mark: | | |
cmdlauncher | commands to GUI | :heavy_multiplication_x: | [CmdLauncher](http://cmdlauncher.topbug.net/) | |
cmospwd | CMOS/BIOS password recovery | :heavy_check_mark: | | pre-UEFI |
cmsmap | CMS vulnerability scanner | :heavy_multiplication_x: | [CMSmap](https://github.com/dionach/CMSmap) | |
cmus | CLI music player | :heavy_check_mark: | | |
cockpit | server manager web interface | :heavy_check_mark: | [Cockpit](https://cockpit-project.org/) | |
cockpit-docker | Cockpit docker manager | :heavy_multiplication_x: | [cockpit-docker](https://github.com/Xantios/cockpit-docker) | |
codeblocks | C editor/IDE | :heavy_check_mark: | | |
codecounter | C/BASIC/web code counter | :heavy_multiplication_x: | [CodeCounter](https://github.com/Tinram/CodeCounter) | |
codelite | C editor | :heavy_check_mark: | | PHP/JS/Python also supported |
collectd, kcollectd | system stats harvester/monitoring daemon | :heavy_check_mark: | | |
collectl | collect performance data | :heavy_check_mark: | [Collectl](https://collectl.sourceforge.net/) | |
colordiff | colourise diff output | :heavy_check_mark: | | |
colorgrab | dropper | :heavy_multiplication_x: | [colorgrab](https://github.com/Acolarh/colorgrab) | |
colorhug | colorimeter | :heavy_check_mark: | | |
conduit | sync tool for GNOME (files, bookmarks) | :heavy_check_mark: | | |
contextfree | image generator | :heavy_check_mark: | | |
converseen | batch image manipulator | :heavy_check_mark: | [Converseen](https://sourceforge.net/projects/converseen/) | GUI for [ImageMagick](#imagemagick) |
convertall | unit converter | :heavy_check_mark: | | |
compiz | window and compositing manager | :heavy_check_mark: | | <a id="compiz"></a> |
compizconfig-settings-manager | [compiz](#compiz) config settings | :heavy_check_mark: | | screen inverter |
conky | GUI system monitor | :heavy_check_mark: | | |
corectrl | hardware profile manager | :heavy_multiplication_x: | [CoreCtrl](https://gitlab.com/corectrl/corectrl) | |
cpu-g | GUI CPU analyser | :heavy_multiplication_x: | [CPU-G](https://sourceforge.net/projects/cpug/) | |
cpu-x | GUI CPU/motherboard analyser | :heavy_multiplication_x: | [CPU-X](https://github.com/X0rg/CPU-X) | |
cpufetch | CLI CPU analyser | :heavy_multiplication_x: | [cpufetch](https://github.com/Dr-Noob/cpufetch) | |
cpupower | CPU frequency manager | :heavy_multiplication_x: | | |
cppcheck | C code linter | :heavy_check_mark: | | |
cpuid | CPU info | :heavy_check_mark: | | |
cpulimit | limit process CPU usage | :heavy_check_mark: | | |
crazydiskmark | GUI disk benchmarker | :heavy_multiplication_x: | [crazydiskmark](https://github.com/fredcox/crazydiskmark) | ppa:fredcox-p/crazydiskmark |
credcrack | credential harvester | :heavy_multiplication_x: | [CredCrack](https://github.com/gojhonny/CredCrack) | |
croc | CLI file transfer | :heavy_multiplication_x: | [croc](https://schollz.com/tinker/croc6/) [repo](https://github.com/schollz/croc) | |
crunch | password list generator | :heavy_check_mark: | | |
cryptcat | encrypted [netcat](#netcat) | :heavy_check_mark: | | [flaws?](https://github.com/deurstijl/decryptcat) |
cryptocat | encrypted IM | :heavy_multiplication_x: | [CryptoCat](https://crypto.cat/) | |
cryptkeeper | GUI encfs for GNOME | :heavy_check_mark: | | |
cryptote | encrypted tabbed notes | :heavy_multiplication_x: | [Cryptote](https://panthema.net/2009/cryptote/#downloads) | |
cscope | C interactive checker | :heavy_check_mark: | | |
csvtool | CLI CSV file manipulator | :heavy_check_mark: | | |
ctags | C code indexing tool | :heavy_check_mark: | | |
ctop | TUI Docker container metrics | :heavy_multiplication_x: | [ctop](https://github.com/bcicen/ctop) | *docker-ctop* |
cuda-z | CUDA-enabled GPU info | :heavy_multiplication_x: | [CUDA-Z](https://cuda-z.sourceforge.net/) | |
cudatext | code editor | :heavy_multiplication_x: | [CudaText](https://cudatext.github.io/) | |
cups-pdf | print to PDF | :heavy_check_mark: | | |
curl | CLI transfer data | :heavy_check_mark: | | |
cute | HTTP request creator | :heavy_multiplication_x: | [CuTE](https://github.com/PThorpe92/CuTE) | |
cvassistant | multiple CV manager | :heavy_multiplication_x: | [CVAssistant](https://sourceforge.net/projects/cvassistant/) | |
curl-loader | HTTP benchmark | :heavy_multiplication_x: | [curl-loader](https://sourceforge.net/projects/curl-loader/) | |
cutereport | report generator | :heavy_multiplication_x: | [CuteReport](https://sourceforge.net/projects/qreport/) | |
cutter | GUI radare2 binary analyser/disassembler | :heavy_multiplication_x: | [cutter](https://github.com/radareorg/cutter) | |
cxref | C code to LaTeX/HTML | :heavy_check_mark: | | |
cyberfox | 64-bit browser | :heavy_multiplication_x: | | |
cython | Python C extensions | :heavy_check_mark: | | |
dangerzone | document sanitiser | :heavy_multiplication_x: | [dangerzone](https://github.com/firstlookmedia/dangerzone) | |
darkhttpd | tiny file server | :heavy_multiplication_x: | [Darkhttpd](https://unix4lyfe.org/darkhttpd/) | 34kB |
darkstat | network traffic analyser | :heavy_check_mark: | [Darkstat](https://unix4lyfe.org/darkstat/) | |
darktable | RAW images | :heavy_check_mark: | [Darktable](https://www.darktable.org/) | |
darling | Mac CLI Wine | :heavy_multiplication_x: | [Darling](https://www.darlinghq.org/) | |
datacleaner | database scanner | :heavy_multiplication_x: | | |
dateutils | CLI date/time utilities | :heavy_multiplication_x: | [Dateutils](http://www.fresse.org/dateutils/) | |
davfs2 | mount WebDAV resource | :heavy_check_mark: | | |
dban | disk destroyer | :heavy_multiplication_x: | [DBAN](https://dban.org/) | |
dbbench | database benchmarking tool | :heavy_multiplication_x: | [dbbench](https://github.com/sj14/dbbench) | |
dbdeployer | MySQL database deployer | :heavy_multiplication_x: | [dbdeployer](https://github.com/datacharmer/dbdeployer) | |
dconf-editor | GUI dconf editor | :heavy_check_mark: | | |
dcraw | CLI RAW converter | :heavy_check_mark: | | |
ddd | GUI debugger for GDB etc | :heavy_check_mark: | | includes Python, Bash |
ddrescue | data recovery tool | :heavy_check_mark: | | see [gddrescue](#gddrescue) |
deadbeef | music player | :heavy_multiplication_x: | [deadbeef](https://deadbeef.sourceforge.net/) [repo](https://github.com/DeaDBeeF-Player/deadbeef) | |
deadman | CLI website status checker | :heavy_multiplication_x: | [deadman](https://github.com/upa/deadman) | uses ping |
debconf-utils | debconf utilities | :heavy_check_mark: | | |
deborphan | unused packages finder | :heavy_check_mark: | | |
debreate | Debian package manager | :heavy_multiplication_x: | [Debreate](https://antumdeluge.github.io/debreate-web/) | |
debsums | package checksum comparisons | :heavy_check_mark: | | |
deen | data en-/decoding | :heavy_multiplication_x: | [deen](https://github.com/takeshixx/deen) | |
deja-dup | GUI backup tool using [duplicity](#duplicity) | :heavy_check_mark: | [DejaDup](https://wiki.gnome.org/Apps/DejaDup) | [GnuPG](#gpg) encryption, no compression |
delve | Go debugger | :heavy_multiplication_x: | [delve](https://github.com/go-delve/delve) | |
denyhosts | SSH protection | :heavy_check_mark: | | |
desktop-files-creator | .desktop file creator | :heavy_multiplication_x: | [desktop-files-creator](https://github.com/alexkdeveloper/desktop-files-creator) | |
devicesinlan | LAN scanner | :heavy_multiplication_x: | [DevicesInLAN](https://sourceforge.net/projects/devicesinlan/) | |
devilspie2 | run script upon window interaction | :heavy_check_mark: | [Devilspie2](https://www.gusnan.se/) | |
devede | create DVDs/DVD menus | :heavy_check_mark: | | |
devscripts | Debian package maintenance | :heavy_multiplication_x: | | <a id="devscripts"></a> |
devtodo | CLI ToDo list | :heavy_check_mark: | | |
dh-autoreconf | autoreconf helper | :heavy_check_mark: | | |
dhcpcd | DHCP server for auto-configuring networking | :heavy_check_mark: | | `sudo dhcpcd wlan0` |
dhcpdump | parse DHCP packets from [`tcpdump`](#tcpdump) | :heavy_check_mark: | | |
dia | diagram editor | :heavy_check_mark: | | |
dialog | Bash dialog | :heavy_check_mark: | | |
diction | sentence style helper (en/de) | :heavy_check_mark: | | |
diffmerge | diff | :heavy_multiplication_x: | [DiffMerge](http://sourcegear.com/diffmerge/downloads.php) | |
diffoscope | file/dir diff | :heavy_check_mark: | [diffoscope](https://diffoscope.org/) | |
diffpdf | PDF diff | :heavy_multiplication_x: | [diffpdf](https://gitlab.com/pianoslum/diffpdf) | |
difftree | compare directories | :heavy_multiplication_x: | [difftree](https://github.com/rondilley/difftree) | |
diffuse | file compare/merge | :heavy_check_mark: | | |
dify | image diff | :heavy_multiplication_x: | [dify](https://github.com/jihchi/dify) | |
digikam | photo manager | :heavy_check_mark: | | KDE-based |
ding | GUI dictionary | :heavy_check_mark: | | |
discover | automate pen test tasks | :heavy_multiplication_x: | [discover](https://github.com/leebaird/discover) | |
dispcalgui | GUI for [Argyll](#argyll) colour management | :heavy_check_mark: | | <a id="dispcalgui"></a> |
dissy | GUI for `objdump` | :heavy_check_mark: | | |
dive | Docker image explorer | :heavy_multiplication_x: | [dive](https://github.com/wagoodman/dive) | |
dmitry | server host info | :heavy_check_mark: | | |
dnsdiag | DNS testing tools | :heavy_multiplication_x: | [dnsdiag](https://dnsdiag.org/) | `pip3 install dnsdiag`; `dnsping`, `dnstraceroute`, `dnseval` |
dnsmasq-utils | manage DHCP leases | :heavy_check_mark: | | |
dnstracer | trace DNS queries to source | :heavy_check_mark: | | |
dnswalk | DNS debugger/nameserver lookup | :heavy_check_mark: | | |
docker | container runtime | :heavy_check_mark: | [Docker](https://www.docker.com/) | <a id="docker"></a> |
docker-doc | [Docker](#docker) documentation | :heavy_check_mark: | | |
docker-registry | | :heavy_check_mark: | | |
dog | DNS tool | :heavy_check_mark: | [dog](https://dns.lookup.dog/) | |
doggo | DNS tool | :heavy_multiplication_x: | [doggo](https://github.com/mr-karan/doggo) | |
dolphie | MySQL monitor | :heavy_multiplication_x: | [dolphie](https://pypi.org/project/dolphie/) [repo](https://github.com/charles-001/dolphie) | |
doona | daemon vulnerability | :heavy_multiplication_x: | | |
dos2unix | convert EOL chars | :heavy_check_mark: | | [tofromdos](#tofromdos) may be better |
downtimed | downtime monitor | :heavy_check_mark: | | |
doxygen | C/PHP auto-documenter | :heavy_check_mark: | | <a id="doxygen"></a> |
doxygen-doxywizard | config GUI for [doxygen](#doxygen) | :heavy_check_mark: | | |
dragit | GUI file transfer tool | :heavy_multiplication_x: | [dragit](https://github.com/sireliah/dragit) | |
drgeo | geometric sketcher | :heavy_check_mark: | | |
drive | CLI GDrive client | :heavy_multiplication_x: | [drive](https://github.com/odeke-em/drive) | |
droidcam | turn phone into PC webcam | :heavy_multiplication_x: | [droidcam](https://github.com/dev47apps/droidcam) | |
dsniff | network sniffer | :heavy_check_mark: | | |
dstat | resource stats tool | :heavy_check_mark: | [Dstat](http://dag.wiee.rs/home-made/dstat/) | |
dsvpn | Dead Simple VPN | :heavy_multiplication_x: | [dsvpn](https://github.com/jedisct1/dsvpn) | |
dtrx | archive viewer/unpacker | :heavy_check_mark: | | |
duc | TUI/GUI disk usage analyser | :heavy_check_mark: | [Duc](https://duc.zevv.nl/) [repo](https://github.com/zevv/duc) | use `apt` |
duf | disk usage monitor | :heavy_multiplication_x: | [duf](https://github.com/muesli/duf) | |
dukto | LAN transfer tool | :heavy_multiplication_x: | [dukto](https://github.com/guilhem/dukto) | |
dupeguru | duplicate file finder | :heavy_multiplication_x: | [dupeGuru](https://dupeguru.voltaicideas.net/) [repo](https://github.com/arsenetar/dupeguru) | |
duplicity | encrypted backup | :heavy_check_mark: | [Duplicity](https://duplicity.gitlab.io/) | built on `rsync` <a id="duplicity"></a> |
dvdbackup | DVD ripper | :heavy_check_mark: | | |
e4defrag | ext4 defragger | :heavy_multiplication_x: | | |
earlyoom | faster OOM | :heavy_check_mark: | [earlyoom](https://github.com/rfjakob/earlyoom) | |
easyeffects | equalizer | :heavy_check_mark: | [easyeffects](https://github.com/wwmm/easyeffects) | revamped *PulseEffects* |
easy-rsa | certificate generator | :heavy_check_mark: | [repo](https://github.com/OpenVPN/easy-rsa) [doc](https://easy-rsa.readthedocs.io/en/latest/) [AW](https://wiki.archlinux.org/index.php/Easy-RSA) | OpenVPN etc |
easyssh | GUI SSH connection manager | :heavy_multiplication_x: | [easyssh](https://github.com/muriloventuroso/easyssh) | |
edotool | input device activity simulator | :heavy_multiplication_x: | [edotool](https://github.com/evuraan/edotool) | |
efiboots | boot manager | :heavy_multiplication_x: | [efiboots](https://github.com/Elinvention/efiboots) | |
eiciel | GUI ACL editor | :heavy_check_mark: | [Eiciel](https://rofi.roger-ferrer.org/eiciel/) [repo](https://github.com/rofirrim/eiciel) | |
elfparser | ELF analyser | :heavy_multiplication_x: | [elfparser](https://github.com/jacob-baines/elfparser) | |
elfutils | ELF utilities | :heavy_check_mark: | | |
emilpro | disassembler | :heavy_multiplication_x: | | |
emma | MySQL GUI client | :heavy_check_mark: | | |
encryptpad | text editor with encryption | :heavy_multiplication_x: | [EncryptPad](https://evpo.net/encryptpad/) | |
encryptr | SpiderOak note storage | :heavy_multiplication_x: | [Encryptr](https://spideroak.com/) | |
engauge-digitizer | graph digitizer: extract nums | :heavy_check_mark: | | |
enscript | text converter PS/HTML/RTF | :heavy_check_mark: | | |
ent | entropy checker | :heavy_check_mark: | | |
entr | trigger actions on file change | :heavy_check_mark: | | |
eqonmize | financial app | :heavy_multiplication_x: | [Eqonmize](https://github.com/Eqonomize/Eqonomize) | |
eric | Python IDE | :heavy_check_mark: | [Eric](https://eric-ide.python-projects.org/) | |
espeak | text speaker + GUIs | :heavy_check_mark: | | GUI is [gespeaker](#gespeaker) <a id="espeak"></a> |
etcher | ISO to USB | :heavy_multiplication_x: | [Etcher](https://etcher.io/) [repo](https://github.com/resin-io/etcher) | Chrome-bloated |
etckeeper | version control of */etc* | :heavy_check_mark: | | |
etherape | GUI network monitor | :heavy_check_mark: | | |
ethtool | display/change Ethernet device settings | :heavy_check_mark: | | |
ethr | network performance analyser | :heavy_multiplication_x: | [ethr](https://github.com/Microsoft/ethr) | |
etm | event and task manager | :heavy_multiplication_x: | [ETM](https://people.duke.edu/~dgraham/etmqt/) | |
exa | colourful `ls` replacement | :heavy_multiplication_x: | [Exa](https://the.exa.website/) [repo](https://github.com/ogham/exa) | |
exelearning | authoring tool | :heavy_multiplication_x: | [eXeLearning](https://exelearning.net/en/) | pps:exelearning/exelearning |
exiftool | edit EXIF data | :heavy_check_mark: | [EXIFtool](https://exiftool.org/) | |
exiv2 | EXIF/metadata editor | :heavy_check_mark: | | |
exmplayer | GUI for MPlayer | :heavy_check_mark: | | |
extundelete | recover deleted files | :heavy_check_mark: | | |
f3 | flash memory analyser | :heavy_multiplication_x: | [f3](https://github.com/AltraMayor/f3) | |
fail2ban | set firewall rules for multiple wrong logins | :heavy_check_mark: | | <a id="fail2ban"></a> |
falco | security tool | :heavy_multiplication_x: | [falco](https://github.com/falcosecurity/falco) | |
fancontrol-gui | fan controller | :heavy_multiplication_x: | [fancontrol-gui](https://github.com/Maldela/fancontrol-gui) | |
fatback | recover data from disks/USBs | :heavy_check_mark: | | `fatback /dev/sdbx -o /recfiles -a` |
fatsort | FAT filesystem file sorter | :heavy_check_mark: | | |
fbcat | framebuffer grabber | :heavy_check_mark: | | outputs *.ppm* convert with [ImageMagick](#imagemagick) |
fcrackzip | ZIP cracker | :heavy_check_mark: | | |
fd-find | alternative `find` | :heavy_check_mark: | [fd](https://github.com/sharkdp/fd) | |
fdupes | compare files in two directories | :heavy_check_mark: | | uses hashes |
featherpad | C++ editor | :heavy_multiplication_x: | [FeatherPad](https://github.com/tsujan/FeatherPad) | few dependencies |
fehashmac | CLI hasher | :heavy_multiplication_x: | [fehashmac](https://sourceforge.net/projects/fehashmac) | |
fern-wifi-cracker | GUI for [aircrack](#aircrack) | :heavy_multiplication_x: | | |
ffmpeg | media playing/conversion utility | :heavy_check_mark: | | <a id="ffmpeg"></a> |
ffuf | web fuzzer | :heavy_multiplication_x: | [ffuf](https://github.com/ffuf/ffuf) | |
figlet | ASCII lettering from text | :heavy_check_mark: | | |
filefrag | file defragger | :heavy_multiplication_x: | | |
fileverifier | verify files | :heavy_multiplication_x: | | |
filezilla | FTP/SFTP | :heavy_check_mark: | | |
filezillasecure | Filezilla fork: multithreading | :heavy_multiplication_x: | [FileZillaSecure](http://www.filezillasecure.com/) | no plaintext passwords version |
finch | MySQL benchmarker | :heavy_multiplication_x: | [finch](https://github.com/square/finch) | |
findimagedupes | duplicate image finder | :heavy_check_mark: | | |
findmyhash | query multiple websites for hash | :heavy_multiplication_x: | [findmyhash](https://github.com/Talanor/findmyhash) | |
fio | flexible I/O tester | :heavy_check_mark: | | | <a id="fio"></a>
firejail | sandbox untrusted apps | :heavy_check_mark: | [firejail](https://github.com/netblue30/firejail) | |
firewalld | versatile firewall | :heavy_check_mark: | | |
fishsynch | sync files | :heavy_multiplication_x: | [Fish Synch](https://sourceforge.net/projects/fishsync/) | |
fiziko | pen-and-ink drawings from code | :heavy_multiplication_x: | [fiziko](https://github.com/jemmybutton/fiziko) | |
flac | FLAC tools | :heavy_check_mark: | | |
flameshot | screenshot tool | :heavy_multiplication_x: | [flameshot](https://github.com/lupoDharkael/flameshot) | |
flashlight | auto info tool for pen tests | :heavy_multiplication_x: | [flashlight](https://github.com/galkan/flashlight) | |
flasm | dis/assembler for Flash bytecode | :heavy_check_mark: | | |
flatseal | GUI Flatpak permissions manager | :heavy_multiplication_x: | [Flatseal](https://github.com/tchx84/flatseal) | |
flawfinder | C/C++ code checker | :heavy_check_mark: | | simpler than [splint](#splint) |
flif | free lossless image format encoder | :heavy_multiplication_x: | [FLIF](https://github.com/FLIF-hub/FLIF) | <a id="flif"></a> |
flifcrush | [FLIF](#flif) image optimiser | :heavy_multiplication_x: | [flifcrush](https://github.com/matthiaskrgr/flifcrush) | <a id="flif"></a> |
flightgear | flight simulator | :heavy_check_mark: | | |
flow | diagrams | :heavy_multiplication_x: | | |
flowblade | video editor | :heavy_check_mark: | [flowblade](https://github.com/jliljebl/flowblade) | |
fmap | web app vulnerabilities | :heavy_multiplication_x: | | |
focus | task reminder | :heavy_multiplication_x: | [Focus](https://github.com/nagyation/Focus) | |
focuswriter | word processor | :heavy_check_mark: | | <a id="#focuswriter"></a> |
fog | network computer cloning | :heavy_multiplication_x: | [FOG](https://fogproject.org/) | |
fontfinder | GUI Google font browser | :heavy_multiplication_x: | [fontfinder](https://gitlab.com/mmstick/fontfinder/) | |
fontforge | font editor | :heavy_multiplication_x: | [FontForge](https://github.com/fontforge) | |
fonts-croscore | fonts for improved screen readability | :heavy_check_mark: | | |
fonts-crosextra-carlito | Calibri-compatible font | :heavy_check_mark: | | |
fonts-crosextra-caladea | Cambria-compatible font | :heavy_check_mark: | | |
font-manager | GNOME font manager | :heavy_check_mark: | | |
foremost | recover/extract files | :heavy_check_mark: | | |
forkrun | run commands in parallel | :heavy_multiplication_x: | [forkrun](https://github.com/jkool702/forkrun) | |
forkstat | CLI process monitor | :heavy_check_mark: | | |
fotoxx | photo editor | :heavy_check_mark: | | good at editing, poor interface |
fping | ICMP to network hosts | :heavy_check_mark: | | |
fpm | package converter | :heavy_multiplication_x: | [fpm](https://github.com/jordansissel/fpm) | |
fracplanet | fractals | :heavy_check_mark: | | |
fractalnow | fast fractal generator | :heavy_check_mark: | | |
fraqtive | 3D Mandelbrot/Julia | :heavy_check_mark: | | |
freac | audio encoder/ripper | :heavy_multiplication_x: | [freac](https://freac.org/) [repo](https://github.com/enzo1982/freac) | |
freebasic | BASIC compiler | :heavy_multiplication_x: | [FreeBASIC](https://freebasic.net/) | |
freefilesynch | GUI folder compare and sync | :heavy_check_mark: | | |
freemind | mindmap editor | :heavy_multiplication_x: | [FreeMind](https://sourceforge.net/projects/freemind/?source=directory) | Java-based |
freeplane | mindmap editor | :heavy_check_mark: | | Java-based |
frescobaldi | sheet music editor | :heavy_check_mark: | | |
freshmemory | flashcards | :heavy_multiplication_x: | [Fresh Memory](https://sourceforge.net/projects/freshmemory/) | |
frogr | Flickr uploader/organiser | :heavy_check_mark: | | |
fruitywifi | wireless network auditing tool | :heavy_multiplication_x: | [FruityWifi](https://github.com/xtr4nge/FruityWifi) | |
fsarchiver | *tar.gz* alternative | :heavy_check_mark: | [fsarchiver](https://www.fsarchiver.org/) | |
fsearch | file search | :heavy_multiplication_x: | | |
fslint | problem file manager/cleaner | :heavy_check_mark: | | |
fsmon | file system monitor | :heavy_multiplication_x: | [fsmon](https://github.com/nowsecure/fsmon) | |
fswatch | file change monitor | :heavy_multiplication_x: | [fswatch](https://github.com/emcrisostomo/fswatch) | |
fswebcam | webcam | :heavy_check_mark: | | `sudo fswebcam /dev/video0 x.jpg` |
ftrace | ELF function analyser | :heavy_multiplication_x: | [ftrace](https://github.com/elfmaster/ftrace) | |
funkload | web server benchmarker | :heavy_check_mark: | | includes unit testing |
fusil | fuzzer | :heavy_check_mark: | | collection of scripts |
fuzz | fuzz EXEs with datastream input | :heavy_check_mark: | | |
fwbuilder | firewall admin GUI | :heavy_check_mark: | | |
fwlogwatch | firewall log analyser | :heavy_check_mark: | | |
fzf | TUI fuzzy finder | :heavy_check_mark: | [repo](https://github.com/junegunn/fzf) | |
g213colours | key colour customiser for G213 keyboard | :heavy_multiplication_x: | [G213Colors](https://github.com/SebiTimeWaster/G213Colors) | requires [python3-usb](#python3-usb) |
gadmin-samba | GUI config for Samba | :heavy_check_mark: | | |
gadmin-rsync | GUI config for `rsync` | :heavy_check_mark: | | |
gadmin-openvpn-client | GUI config for OpenVPN | :heavy_check_mark: | | |
gadmin-openvpn-server | GUI config for OpenVPN | :heavy_check_mark: | | |
gajim | GPG Jabber client | :heavy_check_mark: | | |
gaupol | subtitles editor | :heavy_check_mark: | [gaupol](https://otsaloma.io/gaupol/) | |
gamemode | optimise system performance | :heavy_multiplication_x: | [gamemode](https://github.com/Feralinteractive/gamemode) | |
gatling | static page web server | :heavy_check_mark: | | |
gcad3d | CAD | :heavy_multiplication_x: | [gCAD3D](https://gcad3d.org/) | |
gcc | GNU C compiler | :heavy_check_mark: | | |
gcolor2 | GUI colour picker | :heavy_check_mark: | | prefer [GPick](#gpick) |
gconf-editor | GConf editor | :heavy_check_mark: | | |
gdb | GNU debugger | :heavy_check_mark: | | |
gddrescue | `dd` drive/data recovery | :heavy_check_mark: | [ddrescue-gui](https://launchpad.net/ddrescue-gui) | ppa:hamishmb/myppa <a id="gddrescue"></a> |
gdm | GNOME display manager | :heavy_check_mark: | | |
gdmap | visual HDD space usage | :heavy_check_mark: | | |
geany | code editor/IDE | :heavy_check_mark: | | |
gearlever | AppImage manager | :heavy_multiplication_x: | [gearlever](https://github.com/mijorus/gearlever) | |
genisoimage | create CD/DVD images | :heavy_check_mark: | | |
gespeaker | GUI for [eSpeak](#espeak) | :heavy_check_mark: | | <a id="gespeaker"></a> |
gethead | HTTP header vulnerability tool | :heavy_multiplication_x: | [gethead](https://github.com/httphacker/gethead) | |
geeqie | GTK image viewer | :heavy_check_mark: | [Geeqie](https://www.geeqie.org/) | good for multiple image comparison, sidecar files |
gfio | GUI for [fio](#fio) | :heavy_check_mark: | | |
gfortran | GNU Fortran 95 compiler | :heavy_check_mark: | | |
gh-ost | MySQL trigger-less schema migrator | :heavy_multiplication_x: | [gh-ost](https://github.com/github/gh-ost) | |
ghex | GUI hex viewer | :heavy_check_mark: | | |
ghostwriter | [FocusWriter](#focuswriter)-like text editor | :heavy_multiplication_x: | [GhostWriter](https://ghostwriter.kde.org/) | Markdown default |
giada | DJ tool | :heavy_multiplication_x: | | |
gifcurry | video editor for GIFs | :heavy_multiplication_x: | [gifcurry](https://github.com/lettier/gifcurry) | |
gigolo | mount manager | :heavy_check_mark: | | |
gimp | image editor | :heavy_check_mark: | | |
gimp-dcraw | GIMP RAW plugin | :heavy_check_mark: | | |
gimp-ufraw | GIMP RAW importer | :heavy_check_mark: | | |
git | source control | :heavy_check_mark: | | `git`, *git-gui*, `gitk`, `gitg`, *git-doc*, `git-extras` <a id="git"></a> |
git-big-picture | [Git](#git) branch visualisation | :heavy_check_mark: | | |
git-crypt | [Git](#git) file encryption | :heavy_check_mark: | | |
git-extras | [Git](#git) extensions | :heavy_check_mark: | | |
git-gui | [Git](#git) GUI | :heavy_check_mark: | | `git gui` |
git-repair | [Git](#git) repo repair | :heavy_check_mark: | | use with `git fsck` and `git gc` |
git-secrets | prevent sensitive data being committed | :heavy_multiplication_x: | [git-secrets](https://github.com/awslabs/git-secrets) | |
gitg | [Git](#git) repo viewer | :heavy_check_mark: | | |
gitin | commit/branch/status explorer for [Git](#git) | :heavy_multiplication_x: | [gitin](https://github.com/isacikgoz/gitin) | |
gitinspector | [Git](#git) repo stat tool | :heavy_check_mark: | | |
gitk | [Git](#git) repo browser | :heavy_check_mark: | | |
gitkraken | [Git](#git) GUI | :heavy_multiplication_x: | [GitKraken](https://www.gitkraken.com/) | |
gkrellm | GUI system monitor | :heavy_check_mark: | | |
glade | GTK+ GUI creator | :heavy_check_mark: | | |
glances | `top`-like app (sophisticated) | :heavy_check_mark: | [Glances](https://nicolargo.github.io/glances/) | also `pip install glances` |
glchess | chess | :heavy_check_mark: | | uses Crafty engine; use `apt` |
glogg | GUI logfile view/query | :heavy_check_mark: | [glogg](http://glogg.bonnefon.org/) | |
gmysqlcc | GUI MySQL client | :heavy_check_mark: | | |
gnofract | fractal generator | :heavy_multiplication_x: | | *.deb* SourceForge package; good images |
gnome-battery-bench | | :heavy_multiplication_x: | [GNOME Battery Bench](https://github.com/GNOME/gnome-battery-bench) | |
gnome-bluetooth | GNOME Bluetooth tools | :heavy_check_mark: | | |
gnome-boxes | manage remote/virtual systems | :heavy_check_mark: | | |
gnome-builder | GNOME app builder | :heavy_multiplication_x: | [Gnome Builder](https://github.com/chergert/gnome-builder) | |
gnome-disk-utility | manage disks/media | :heavy_check_mark: | | |
gnome-network-admin | GUI for [`whois`](#whois)/`ping` | :heavy_check_mark: | | |
gnome-rdp | remote desktop | :heavy_check_mark: | | |
gnome-system-monitor | GNOME monitor | :heavy_check_mark: | | |
gnome-tweak-tool | GNOME 3 editor | :heavy_check_mark: | | |
gnucash | finance manager | :heavy_check_mark: | | <a id="gnucash"></a> |
gnumeric | spreadsheet | :heavy_check_mark: | | |
gnupg2 | GnuPG version 2 | :heavy_check_mark: | | <a id="gpg"></a> |
gnuplot | graphs | :heavy_check_mark: | | core |
gnuplot-x11 | graphics | :heavy_check_mark: | | |
gnuplot-qt | graphics | :heavy_check_mark: | | |
go-fuzz | fuzzer | :heavy_multiplication_x: | [go-fuzz](https://github.com/dvyukov/go-fuzz) | |
go-mysql | MySQL toolset | :heavy_multiplication_x: | [go-mysql](https://github.com/siddontang/go-mysql) | |
go-rsync | GUI for `rsync` | :heavy_multiplication_x: | [go-rsync](https://github.com/d2r2/go-rsync) | |
goaccess | CLI realtime logfile viewer | :heavy_check_mark: | [GoAccess](https://goaccess.io/download) [repo](https://github.com/allinurl/goaccess) | avoid distro repo; compile deps: `libgeoip-dev`, `libncursesw5-dev` |
gobuster | directory, DNS, vhost buster | :heavy_multiplication_x: | [gobuster](https://github.com/OJ/gobuster) | |
gocryptfs | encrypted overlay filesystem | :heavy_multiplication_x: | [gocryptfs](https://github.com/rfjakob/gocryptfs) | |
golly | game of life simulator | :heavy_check_mark: | | |
googler | CLI Google search | :heavy_multiplication_x: | [googler](https://github.com/jarun/googler) | |
gosync | GDrive sync | :heavy_multiplication_x: | [GoSync](https://github.com/hschauhan/gosync/) | |
gotop | TUI system monitor  | :heavy_multiplication_x: | [gotop](https://github.com/xxxserxxx/gotop) | |
gotty | CLI application projected as web app | :heavy_multiplication_x: | [GoTTY](https://github.com/yudai/gotty) | |
gource | source control visualisation tool | :heavy_check_mark: | | |
govie | movie utility | :heavy_multiplication_x: | [Govie](https://github.com/narenaryan/Govie) | |
gpa | GUI for [GnuPG](#gpg) | :heavy_check_mark: | | |
gparted | view/manage partitions | :heavy_check_mark: | | |
gpgdir | encrypt directories | :heavy_check_mark: | | |
gpgit | CLI [GnuPG](#gpg) file encryption simplified | :heavy_multiplication_x: | [GPGit](https://github.com/Tinram/GPGit) | |
gpg-tui | TUI [GnuPG](#gpg) manager | :heavy_multiplication_x: | [gpg-tui](https://blog.orhun.dev/introducing-gpg-tui/) [repo](https://github.com/orhun/gpg-tui) | |
gphoto2 | CLI digital camera processor | :heavy_check_mark: | | |
gpick | screen colour pick/palette/inverter | :heavy_check_mark: | | <a id="gpick"></a> |
gping | CLI visual ping host | :heavy_multiplication_x: | [gping](https://github.com/orf/gping) | |
gpm | mouse interface/copy-paste on CLI | :heavy_check_mark: | | |
gpt fdisk | GPT disk tools | :heavy_multiplication_x: | [GPT fdisk](https://sourceforge.net/projects/gptfdisk/) | also see `gdisk` in repo |
gqrx | GUI radio receiver | :heavy_check_mark: | [Gqrx](https://www.gqrx.dk/) | |
grabber | web app scanner | :heavy_multiplication_x: | | |
graphviz | graph tools | :heavy_check_mark: | | |
graudit | grep rough source code audit | :heavy_multiplication_x: | [graudit](https://github.com/wireghoul/graudit/) | |
graylog | manage PC logfiles in one place | :heavy_multiplication_x: | [Graylog](https://www.graylog.org/) | |
grdesktop | GUI for [rdesktop](#rdesktop) | :heavy_check_mark: | | |
grive2 | GDrive syncer | :heavy_multiplication_x: | [Grive2](https://github.com/vitalif/grive2/) | |
grsynch | GUI for `rsync` | :heavy_check_mark: | [Grsynch](https://sourceforge.net/projects/grsync/) | |
grub-customizer | GUI GRUB editor | :heavy_multiplication_x: | [GRUB customizer](https://launchpad.net/grub-customizer) | |
grv | CLI Git repo viewer | :heavy_multiplication_x: | [GRV](https://github.com/rgburke/grv) | |
gscan2pdf | PDFs from scans | :heavy_check_mark: | | |
gsconnect | Android connector | :heavy_multiplication_x: | [GSConnect](https://github.com/GSConnect) | |
gsettings | GNOME config CLI tool | :heavy_check_mark: | | |
gsmartcontrol | GUI for `smartctl` | :heavy_check_mark: | | |
gstm | GNOME SSH tunnel manager | :heavy_check_mark: | | |
gsync | GDrive syncer | :heavy_multiplication_x: | | `pip install gsync` |
gtkam | GUI transfer from cameras | :heavy_check_mark: | | |
gtkhash | GUI hash calculator | :heavy_check_mark: | | |
gtg | GNOME ToDo organiser | :heavy_check_mark: | | |
gtkstresstesting | benchmarker | :heavy_multiplication_x: | [GtkStressTesting](https://gitlab.com/leinardi/gst) | utilises `stress-ng` |
guake | multi-tabbed/multi-coloured CLI | :heavy_check_mark: | | |
guetzli | JPG encoder/compressor | :heavy_multiplication_x: | [guetzli](https://github.com/google/guetzli) | |
gufw | GUI for [ufw](#ufw) | :heavy_check_mark: | | |
guitar | GUI Git client | :heavy_multiplication_x: | [Guitar](https://github.com/soramimi/Guitar) | |
gvfs-backends | SMB browsing | :heavy_check_mark: | | |
haguichi | GUI for VPN app | :heavy_multiplication_x: | [Haguichi](https://www.haguichi.net/) | |
handbrake | DVD ripper/video transcoder | :heavy_check_mark: | [HandBrake](https://handbrake.fr) | |
hardinfo | hardware info | :heavy_check_mark: | | |
harvester | info harvester | :heavy_multiplication_x: | [theHarvester](https://github.com/laramies/theHarvester) | |
HAI | hash algorithm identifier| :heavy_multiplication_x: | [Hash-Algorithm-Identifier](https://github.com/AnimeshShaw/Hash-Algorithm-Identifier) | |
hash-identifier | identify hash | :heavy_multiplication_x: | [hash-identifier](https://www.kali.org/tools/hash-identifier/) | |
haveged | random number generator | :heavy_check_mark: | | |
hdparm | tune HDD parameters | :heavy_check_mark: | | |
hdck | HDD/media diagnostics | :heavy_multiplication_x: | [hdck](https://github.com/tomato42/hdck) | |
health-check | process monitoring tool | :heavy_check_mark: | | |
heaptrack | heap memory profiler | :heavy_multiplication_x: | [heaptrack](https://github.com/KDE/heaptrack) | |
heartbeat | high-availability servers | :heavy_check_mark: | | |
hegemon | TUI system monitor | :heavy_multiplication_x: | [hegemon](https://github.com/p-e-w/hegemon) | |
helm | music synthesizer | :heavy_multiplication_x: | [Helm](https://tytel.org/helm/) | |
hexyl | CLI hex editor | :heavy_multiplication_x: | [hexyl](https://github.com/sharkdp/hexyl) | |
highlight | convert code to HTML/RTF | :heavy_check_mark: | | |
hnwatch | CLI news feed | :heavy_multiplication_x: | | |
homebank | finance manager | :heavy_check_mark: | | |
hopper | GUI disassembler | :heavy_multiplication_x: | [Hopper](https://www.hopperapp.com/) | proprietary, demo |
hoptodesk | remote desktop | :heavy_multiplication_x: | [HopToDesk](https://www.hoptodesk.com/) | |
horst | CLI WLAN analyser | :heavy_check_mark: | | |
hostmap | enumerate (v)hosts of IP | :heavy_multiplication_x: | [Hostmap](http://g33kinfo.com/info/hostmap-0-2-2-tar) | |
hottoe | sound control app | :heavy_multiplication_x: | [hottoe](https://github.com/gandalfn/hottoe) | |
hping3 | TCP/IP packet generator | :heavy_check_mark: | | |
htmlq | CLI HTML stream processor | :heavy_multiplication_x: | [htmlq](https://github.com/mgdm/htmlq) | jq for HTML |
htop | hyper `top` | :heavy_check_mark: | | |
http-logs-analyzer | HTTP log analyser | :heavy_multiplication_x: | [http-logs-analyzer](https://github.com/flrnull/http-logs-analyzer) | |
httpdirfs | HTTP directory mounter | :heavy_multiplication_x: | [httpdirfs](https://github.com/fangfufu/httpdirfs) | |
httperf | HTTP benchmark | :heavy_check_mark: | | |
httping | HTTP pinger | :heavy_check_mark: | | |
httpry | HTTP logging and info | :heavy_check_mark: | | |
httpstat | HTTP request timer | :heavy_multiplication_x: | [httpstat](https://github.com/reorx/httpstat) | |
httptunnel | tunnels data in HTTP requests | :heavy_check_mark: | | |
httrack | copy websites | :heavy_check_mark: | | |
hugin | panorama stitcher + photo editor | :heavy_check_mark: | | |
hwinfo | hardware info | :heavy_check_mark: | | deprecated |
hx | CLI hex editor | :heavy_multiplication_x: | [hx](https://github.com/krpors/hx) | |
hydra | GUI network brute-forcer | :heavy_check_mark: | | <a id="hydra"></a> |
hydrogen | drum machine | :heavy_check_mark: | | |
hyperfine | CLI benchmark tool | :heavy_multiplication_x: | [hyperfine](https://github.com/sharkdp/hyperfine) | |
i7z | Core CPU reporting | :heavy_check_mark: | | |
icinga | [Nagios](#nagios)-like network monitor | :heavy_check_mark: | [Icinga](icinga.org) | |
idle3 | Python IDE | :heavy_check_mark: | | |
ifstat | interface statistics monitoring | :heavy_check_mark: | | `vmstat`-like |
iftop | network interface usage | :heavy_check_mark: | | |
imagemagick | CLI image manipulator | :heavy_check_mark: | | <a id="imagemagick"></a> |
imgp | image converter | :heavy_check_mark: | [imgp](https://github.com/jarun/imgp) | |
i-nex | GUI hardware lister | :heavy_multiplication_x: | [I-Nex](https://github.com/i-nex/I-Nex) | similar to *CPU-Z* |
incron | file system events daemon | :heavy_check_mark: | | |
indent | C code formatter | :heavy_check_mark: | | |
indicator-cpufreq | change CPU frequency | :heavy_check_mark: | | |
infernal-twin | auto wireless hacking tool | :heavy_multiplication_x: | [infernal-twin](https://github.com/entropy1337/infernal-twin) | |
inguma | pentest framework | :heavy_multiplication_x: | | |
inkscape | vector imager | :heavy_check_mark: | | |
innotop | MySQL InnoDB monitor | :heavy_multiplication_x: | [innotop](https://github.com/innotop/innotop) [.deb](https://sourceforge.net/projects/innotop/) | exists in CentOS EPEL |
innotopgo | MySQL InnoDB monitor | :heavy_multiplication_x: | [innotopgo](https://github.com/lefred/innotopgo) | |
inotify | monitor file system events | :heavy_check_mark: | | good for Samba folders |
input-remapper | input device button mapper | :heavy_multiplication_x: | [input-remapper](https://github.com/sezanzeb/input-remapper) | |
input-utils | kernel input layer utilities | :heavy_check_mark: | | `lsinput`, `input-events`, `input-kbd` |
instarecon | auto digital recon | :heavy_multiplication_x: | [instarecon](https://github.com/vergl4s/instarecon) | high level recon |
intel-gpu-tools | `intel_gpu_time`, `intel_gpu_top` | :heavy_check_mark: | | |
inxi | system info | :heavy_check_mark: | | |
ioping | disk I/O latency tool | :heavy_check_mark: | [ioping](https://github.com/koct9i/ioping) | |
iotop | I/O monitor | :heavy_check_mark: | | |
ipcalc | parameter calculator for IPv4 | :heavy_check_mark: | | |
iperf | network bandwidth performance | :heavy_check_mark: | | |
iperf3 | network bandwidth performance | :heavy_check_mark: | | |
ipgrab | [`tcpdump`](#tcpdump)-like, detailed header info | :heavy_check_mark: | | more explicit than [`tcpdump`](#tcpdump) |
iproute2 | IP tools | :heavy_check_mark: | | |
ipsec-tools | IPsec utilities | :heavy_check_mark: | | |
ipset | tool for kernel IP sets | :heavy_check_mark: | | |
iptables-persistent | iptables set-up on boot | :heavy_check_mark: | | `sudo service iptables-persistent start` |
iptraf | IP LAN monitor | :heavy_check_mark: | | |
ipython | enhanced Python shell and env | :heavy_check_mark: | | |
iridium | Chromium-based browser | :heavy_multiplication_x: | [Iridium](https://iridiumbrowser.de) | enhanced privacy over Chrome |
iris | colour palette editor | :heavy_multiplication_x: | [Iris](https://irisapp.info/) | |
isohybrid | DVD.iso > bootable from Flash | :heavy_check_mark: | | |
isomaster | CD/DVD image editor | :heavy_check_mark: | | |
jade | diagram editor | :heavy_multiplication_x: | [jade](https://github.com/jaallen85/jade) | |
java | | :heavy_check_mark: | | `apt-get install default-jre` |
jarte | lightweight wordprocessor (with .docx support) | :heavy_check_mark: | | |
jbit | 6502 CPU simulator | :heavy_multiplication_x: | [JBit](https://sourceforge.net/projects/jbit/) | |
jed | code editor | :heavy_check_mark: | | |
jedit | code editor | :heavy_check_mark: | |
jnettop | network traffic monitor | :heavy_check_mark: | | |
jo | CLI JSON creator | :heavy_check_mark: | | |
joomscan | Joomla scanner | :heavy_multiplication_x: | | |
john | password cracker | :heavy_multiplication_x: | | |
johnny | GUI for *john* | :heavy_multiplication_x: | [johnny](https://github.com/shinnok/johnny) | |
joplin | notes/todo app | :heavy_multiplication_x: | [Joplin](https://joplinapp.org/) | |
jp2a | JPG to ASCII art | :heavy_check_mark: | | |
jpeginfo | JPG info/integrity | :heavy_check_mark: | | |
jq | CLI JSON stream processor | :heavy_check_mark: | | |
julia | fast math-oriented language | :heavy_check_mark: | [Julia](https://julialang.org/) | |
kaku | music player | :heavy_multiplication_x: | [Kaku](http://kaku.rocks/) | |
kamailio | SIP proxy | :heavy_check_mark: | [kamailio](https://www.kamailio.org/) | |
kanboard | project manager | :heavy_multiplication_x: | [Kanboard](https://kanboard.net/) | |
katoolin | auto install Kali Linux tools | :heavy_multiplication_x: | [katoolin](https://github.com/LionSec/katoolin) | |
kazam | video screen recorder | :heavy_check_mark: | | |
kdecachegrind | PHP cache analyser | :heavy_multiplication_x: | | |
kdenlive | video editor | :heavy_check_mark: | | KDE |
kdiskmark | GUI disk benchmarker | :heavy_multiplication_x: | [KDiskMark](https://github.com/JonMagon/KDiskMark) | |
keepassx | password vault | :heavy_check_mark: | | <a id="keepassx"></a> |
keepassxc | password vault | :heavy_multiplication_x: | [KeePassXC](https://keepassxc.org) | revised [KeePassX](#keepassx) |
kerkythea | renderer | :heavy_multiplication_x: | [Kerkythea](https://kerkythea.net/) | |
kexi | database GUI (MySQL/[SQLite](#sqlite3)/[PostgreSQL](#postgresql)) | :heavy_multiplication_x: | [Kexi](https://kexi-project.org/en/) | |
kismet | wireless sniffer/monitor | :heavy_check_mark: | | |
kmon | TUI kernel module manager | :heavy_multiplication_x: | [kmon](https://github.com/orhun/kmon) | |
knock | subdomain scanner | :heavy_multiplication_x: | [knock](https://github.com/guelfoweb/knock) | |
knotter | Celtic knot app | :heavy_multiplication_x: | [Knotter](https://sourceforge.net/projects/knotter/) [info](https://knotter.mattbas.org/Knotter) | |
komodoedit | code editor | :heavy_multiplication_x: | | |
krita | image editor | :heavy_check_mark: | [Krita](https://krita.org/en/) | hand-drawn focus |
krop | PDF cropper/editor | :heavy_multiplication_x: | [Krop](http://arminstraub.com/software/krop) | |
ksnip | snipping tool | :heavy_multiplication_x: | [ksnip](https://github.com/DamirPorobic/ksnip) | |
kst | data plotting tool | :heavy_check_mark: | [Kst](https://kst-plot.kde.org/) | `kst2` |
kwipe | data eraser | :heavy_multiplication_x: | [KWipe](https://www.linux-apps.com/p/1127891) [repo](https://github.com/PyCoder/KWipe) | partition emphasis |
lamaperia | printable maps from OpenStreetMap | :heavy_multiplication_x: | [Lamaperia](https://github.com/federicomenaquintero/lamaperia) | |
lame | MP3 encoder | :heavy_check_mark: | | |
landrop | LAN file transfer | :heavy_multiplication_x: | [LANDrop](https://landrop.app/) [repo](https://github.com/LANDrop/LANDrop) | |
lazagne | credentials recovery | :heavy_multiplication_x: | [LaZagne](https://github.com/AlessandroZ/LaZagne) | |
lazpaint | image editor | :heavy_multiplication_x: | [LazPaint](https://lazpaint.github.io/) [repo](https://github.com/bgrabitmap/lazpaint) | |
lazydocker | TUI Docker manager | :heavy_multiplication_x: | [lazydocker](https://github.com/jesseduffield/lazydocker) | |
lazygit | TUI Git client | :heavy_multiplication_x: | [lazygit](https://github.com/jesseduffield/lazygit) | |
lcrack | password cracker | :heavy_check_mark: | | |
lepton | JPG compressor | :heavy_multiplication_x: | [lepton](https://github.com/dropbox/lepton) | |
lftp | CLI FTP | :heavy_check_mark: | | |
libmarkdown-php | Markdown library | :heavy_check_mark: | | |
libre-menu-editor | desktop menu editor | :heavy_multiplication_x: | [libre-menu-editor](https://codeberg.org/libre-menu-editor/libre-menu-editor) | |
libreoffice-dbg | debugger | :heavy_check_mark: | | |
libssl-dev | OpenSSL libraries | :heavy_check_mark: | | |
libtomcrypt | crypto toolkit | :heavy_check_mark: | | |
libtree | `ldd` tree | :heavy_multiplication_x: | [libtree](https://github.com/haampie/libtree) | |
liferea | GUI RSS | :heavy_check_mark: | | |
lightworks | video editor | :heavy_multiplication_x: | [LightWorks](https://www.lwks.com/) | 720p only |
lightzone | RAW editor | :heavy_multiplication_x: | | |
linkchecker | website link checker | :heavy_check_mark: | | |
linklint | website link checker | :heavy_check_mark: | | |
linphone | [Skype](#skype) replacement | :heavy_check_mark: | | requires SIP account |
linssid | GUI wireless scanner | :heavy_check_mark: | | |
linux-crashdump | kernel crashdump set-up | :heavy_check_mark: | | |
linux-firmware | drivers | :heavy_check_mark: | | apparently includes wireless drivers |
linux-malware-detect | Linux malware detector | :heavy_multiplication_x: | [linux-malware-detect](https://github.com/rfxn/linux-malware-detect) | |
linux-wifi-hotspot | GUI wireless hotspot tool | :heavy_multiplication_x: | [linux-wifi-hotspot](https://github.com/lakinduakash/linux-wifi-hotspot) | |
lives | video editor | :heavy_check_mark: | | requires <a href="#x264">x264</a>, *gpac* for decent output |
lldpd | LLDP discovery daemon | :heavy_check_mark: | | discover LAN switches etc, `lldpctl`, `lldpcli` |
lm-sensors | for `sensors` | :heavy_check_mark: | | |
lms | login manager settings | :heavy_multiplication_x: | [lms](https://gdm-settings.github.io/) | |
lmms | audio editor | :heavy_check_mark: | | |
ln | vector image generator | :heavy_multiplication_x: | [ln](https://github.com/fogleman/ln) | |
lnav | logfile reader with colour | :heavy_check_mark: | [lnav](https://lnav.org/) | |
localsend | file transfer | :heavy_multiplication_x: | [LocalSend](https://localsend.org/) | |
log2ram | RAM logger | :heavy_multiplication_x: | [log2ram](https://github.com/azlux/log2ram) | |
logcheck | logfile alerter | :heavy_check_mark: | | |
logisim | digital circuit designer | :heavy_multiplication_x: | [Logisim](https://sourceforge.net/projects/circuit/) | |
logkeys | keylogger | :heavy_check_mark: | | ! |
logwatch | logfile analyser | :heavy_check_mark: | | |
lshw-gtk | lshw hardware GUI | :heavy_check_mark: | | |
lsscsi | list SCSI devices | :heavy_check_mark: | | |
lttng | program tracing | :heavy_check_mark: | | almost as powerful as [SystemTap](#systemtap) |
luckybackup | `rsync`-based GUI backup | :heavy_check_mark: | | |
lynis | security auditor | :heavy_check_mark: | [Lynis](https://cisofy.com/lynis/) | |
lyx | Latex WYSIWYG | :heavy_check_mark: | | 500MB |
lzop | fast compression | :heavy_check_mark: | | |
macchanger | spoof network card MAC | :heavy_check_mark: | | |
macchina | system info | :heavy_multiplication_x: | [Macchina](https://github.com/Macchina-CLI/macchina) | |
magicrescue | file recovery by filetype/header bytes | :heavy_check_mark: | | |
magic-wormhole | secure file transfer | :heavy_multiplication_x: | [magic-wormhole](https://github.com/warner/magic-wormhole) | |
mailutils | mail utilities | :heavy_check_mark: | | |
maltego | people-places analysis tool | :heavy_multiplication_x: | [Maltego](https://paterva.com/web7/) | Java-based |
maltrail | malicious traffic detector | :heavy_multiplication_x: | [maltrail](https://github.com/stamparm/maltrail) | |
mandelbulber | 3D Mandelbrot | :heavy_check_mark: | | |
mangl | GUI man page viewer | :heavy_multiplication_x: | [mangl](https://github.com/zigalenarcic/mangl) | |
mariadb-server | MariaDB | :heavy_check_mark: | | |
mariadb-client | MariaDB | :heavy_check_mark: | | |
markdown | Markdown to HTML | :heavy_check_mark: | | |
marker | Markdown editor | :heavy_multiplication_x: | [Marker](https://github.com/fabiocolacio/Marker) | |
masterpdfeditor | PDF editor | :heavy_multiplication_x: | [MasterPDFEditor](https://code-industry.net/get-masterpdfeditor/) | powerful but proprietary |
mat2 | metadata anonymiser | :heavy_check_mark: | | use `apt`; `mat -d <file>` |
maths | maths problem solver | :heavy_multiplication_x: | [maths](https://code.launchpad.net/~nasc-team) | ppa:nasc-team/daily |
mattermost | team messaging | :heavy_multiplication_x: | [Mattermost](https://www.mattermost.org/) | |
mcfly | CLI history manager | :heavy_multiplication_x: | [mcfly](https://github.com/cantino/mcfly) | |
md5deep | batch/recursive `md5sum` | :heavy_check_mark: | | |
mdadm | software RAID controller | :heavy_check_mark: | | |
medusa | router/network brute-forcer | :heavy_check_mark: | | |
meld | GUI `sdiff` | :heavy_check_mark: | | |
mermaid | Markdown diagrams | :heavy_multiplication_x: | [Mermaid](https://github.com/knsv/mermaid) | |
mesa-utils | MesaGL utilities | :heavy_check_mark: | | |
meshlab | triangular mesh creator | :heavy_check_mark: | | |
meshroom | 3D photogrammetry/reconstruction | :heavy_multiplication_x: | [meshroom](https://github.com/alicevision/meshroom) | requires Nvidia GPU/CUDA |
metadata cleaner | metadata wiper | :heavy_multiplication_x: | [Metadata Cleaner](https://gitlab.com/rmnvgr/metadata-cleaner) | uses `mat2` |
micro | CLI editor | :heavy_multiplication_x: | [micro](https://micro-editor.github.io/) [repo](https://github.com/zyedidia/micro) | |
midori | lightweight browser | :heavy_check_mark: | | |
miller | terminal CSV viewer/processor | :heavy_multiplication_x: | [miller](https://github.com/johnkerl/miller) | |
mindforger | Markdown notebook/IDE | :heavy_multiplication_x: | [mindforger](http://mindforger.com/) | |
minitube | native YouTube client | :heavy_check_mark: | | |
minuet | music trainer | :heavy_multiplication_x: | [minuet](https://github.com/KDE/minuet) | |
missioncenter | GUI system monitor | :heavy_multiplication_x: | [Mission Center](https://missioncenter.io/) [repo](https://gitlab.com/mission-center-devs/mission-center) | |
mitmproxy | MITM HTTP proxy | :heavy_check_mark: | | |
mixxx | audio mixer/editor | :heavy_check_mark: | | |
mlocate | for `locate` | :heavy_check_mark: | | if `locate` is missing <a id="mlocate"></a> |
mmv | mass move/rename | :heavy_check_mark: | | |
mongodb | MongoDB | :heavy_check_mark: | | meta package; or `pecl install mongo` <a id="mongodb"></a> |
monit | notify upon server log-ins | :heavy_multiplication_x: | | |
monitorix | GUI system monitor | :heavy_multiplication_x: | [Monitorix](https://www.monitorix.org/) | |
moreutils | `combine`, `errno`, `isutf8`, [`parallel`](#parallel), `zrun` | :heavy_check_mark: | | <a id="moreutils"></a> |
most | advanced pager, includes colour, bin viewer | :heavy_check_mark: | | |
mp3diags | MP3 file analyser | :heavy_check_mark: | | |
mpd | music player daemon | :heavy_check_mark: | | |
mpg123 | CLI MP3 player | :heavy_check_mark: | | decoding library very good |
mplayer | CLI movie player | :heavy_check_mark: | | <a id="mplayer"></a>|
mps-youtube | YouTube music player | :heavy_check_mark: | [mps-youtube](https://github.com/mps-youtube/mps-youtube) | |
mpv | CLI movie player | :heavy_check_mark: | | based on <a href="#mplayer">mplayer</a> |
mtools | multi-cast connection tester | :heavy_multiplication_x: | | |
mtr | `ping` and [`traceroute`](#traceroute) combined | :heavy_check_mark: | | also [mtr-tiny](#mtr-tiny) |
mtr-tiny | `ping` and [`traceroute`](#traceroute) combined | :heavy_check_mark: | | <a id="mtr-tiny"></a> |
muffet | website link checker | :heavy_multiplication_x: | [muffet](https://github.com/raviqqe/muffet) | |
multitail | splitscreen logfile viewer | :heavy_check_mark: | | |
mundus | home file cleaner | :heavy_multiplication_x: | | |
mupen64plus | N64 console emulator | :heavy_check_mark: | | |
musescore | music score editor | :heavy_check_mark: | | |
mycli | CLI MySQL client | :heavy_check_mark: | [mycli](https://www.mycli.net/) [repo](https://github.com/dbcli/mycli) | |
mypaint | tablet-supporting paint program | :heavy_check_mark: | | |
mysql | MySQL database | :heavy_check_mark: | | <a id="mysql"></a> |
mysql-utilities | MySQL | :heavy_check_mark: | | |
mysql-workbench | MySQL | :heavy_check_mark: | | |
mysqldiffchecker | MySQL instances diff | :heavy_multiplication_x: | [mysqlDiffChecker](https://github.com/kenken0807/mysqlDiffChecker) | |
mysql-shell | mysqlsh | :heavy_check_mark: | | |
mysqlshell-plugins | MySQL Shell Plugins | :heavy_multiplication_x: | [mysqlshell-plugins](https://github.com/lefred/mysqlshell-plugins/) | |
mysqltuner | mysqld settings analyser | :heavy_check_mark: | [mysqltuner](https://raw.githubusercontent.com/major/MySQLTuner-perl/master/mysqltuner.pl) | |
mystatusgo | MySQL monitoring tool | :heavy_multiplication_x: | [myStatusgo](https://github.com/kenken0807/myStatusgo) | |
mytop | MySQL monitor | :heavy_check_mark: | | |
mz | versatile packet/network traffic generator | :heavy_check_mark: | | |
nagios-nrpe-server | Nagios component for remote server | :heavy_check_mark: | [Nagios](https://www.nagios.org/) | <a id="nagios"></a> |
nanotts | speech synthesizer | :heavy_multiplication_x: | [NanoTTS](https://github.com/gmn/nanotts) | |
nast | CLI [Wireshark](#wireshark) | :heavy_check_mark: | | |
nasty | [GnuPG](#gpg) password cracker | :heavy_check_mark: | | |
nbtscan | scan network for NetBIOS info (Samba) | :heavy_check_mark: | | |
ncdu | Ncurses disk usage viewer | :heavy_check_mark: | | |
ncrack | network cracker | :heavy_multiplication_x: | | |
ncrypt | CLI file encrypt | :heavy_multiplication_x: | [Ncrypt](https://sourceforge.net/projects/ncrypt/) | only SHA-1 key hashing |
ncursesfm | CLI file manager | :heavy_multiplication_x: | [ncursesFM](https://github.com/FedeDP/ncursesFM) | |
neofetch | system info | :heavy_check_mark: | [neofetch](https://github.com/dylanaraps/neofetch) | use `apt` |
nemo-fileroller | FileRoller for Nemo | :heavy_check_mark: | | |
netcat | TCP/IP Swiss army knife | :heavy_check_mark: | | <a id="netcat"></a> |
netcatgui | GUI for [netcat](#netcat) | :heavy_multiplication_x: | [netcatgui](https://github.com/shinnok/netcatgui) | |
net-creds | sniffs data from interface/pcap | :heavy_multiplication_x: | [net-creds](https://github.com/DanMcInerney/net-creds) | |
netdata | real-time performance monitor | :heavy_check_mark: | [netdata](https://www.netdata.cloud/) [repo](https://github.com/netdata/netdata) | *<IP>:19999* |
netdiag | network diagnosis tools | :heavy_check_mark: | | `trafshow`, `netwatch`, `statnet`, `tcpspray`, `tcpblast` <a id="netdiag"></a> |
netdiscover | active/passive network address ARP scanner | :heavy_check_mark: | | |
nethogs | bandwidth hog monitor | :heavy_check_mark: | | |
netperf | network benchmark | :heavy_check_mark: | | |
netplan | Ubuntu network manager | :heavy_check_mark: | | |
netrw | [netcat](#netcat)-like, transport files over network | :heavy_check_mark: | | |
netsurf | lightweight browser | :heavy_check_mark: | | |
net-tools | network tools | :heavy_check_mark: | | `ifconfig`, `route` |
netwag | GUI for [netwox](#netwox) | :heavy_check_mark: | | |
netwox | networking utilities | :heavy_check_mark: | | <a id="netwox"></a> |
neural-enhance | image enhancer | :heavy_multiplication_x: | [neural-enhance](https://github.com/alexjc/neural-enhance) | |
newsboat | CLI RSS reader | :heavy_check_mark: | | also newsbeuter |
nftables | netfilter firewall utility | :heavy_check_mark: | | `nft` |
nginx | web/proxy server | :heavy_check_mark: | | |
ngrep | network traffic grep | :heavy_check_mark: | | |
nightingale | music player | :heavy_multiplication_x: | [Nightingale](http://getnightingale.com/) | |
nikola | static website generator | :heavy_check_mark: | | |
nikto | web server security scanner | :heavy_check_mark: | | |
nipper-ng | security analysis of switches/routers | :heavy_multiplication_x: | | |
nitroshare | cross-platform network file transfer | :heavy_multiplication_x: | [NitroShare](https://nitroshare.net/) [repo](https://github.com/nitroshare/nitroshare-desktop) | |
nixnote | Evernote client | :heavy_multiplication_x: | [NixNote](https://sourceforge.net/projects/nevernote/) | |
nload | network load | :heavy_check_mark: | | use `apt` |
nltk | NLP for Python | :heavy_check_mark: | | |
nmap | network scanner | :heavy_check_mark: | | <a id="nmap"></a> |
nmapsi4 | GUI for [NMap](#nmap) | :heavy_check_mark: | | |
nmcli | CLI for NetworkManager | :heavy_check_mark: | | |
nmon | network/CPU/disk performance | :heavy_check_mark: | | |
nohang | low memory handler | :heavy_multiplication_x: | [nohang](https://github.com/hakavlad/nohang) | |
nomacs | image viewer | :heavy_check_mark: | [nomacs](https://nomacs.org/) | good for image comparison via sync |
notepas | code editor | :heavy_multiplication_x: | | |
notes-up | editor supporting Markdown | :heavy_multiplication_x: | [Notes-up](https://github.com/Philip-Scott/Notes-up) | PDF export |
novelwriter | text editor | :heavy_multiplication_x: | [novelWriter](https://novelwriter.io/) [repo](https://github.com/vkbo/novelWriter) | |
npkill | Node.js module remover | :heavy_multiplication_x: | [npkill](https://github.com/voidcosmos/npkill) | |
npm | Node.js package manager | :heavy_check_mark: | | |
nstreams | tcpdump output analyser | :heavy_check_mark: | | |
ntfs-3g | NTFS driver | :heavy_check_mark: | [NTFS-3G](https://www.tuxera.com/company/open-source/) | r/w |
ntfsfix | fix NTFS | :heavy_multiplication_x: | | |
ntfsundelete | recover NTFS files | :heavy_check_mark: | | |
ntfy | push notifier | :heavy_multiplication_x: | [ntfy](https://github.com/binwiederhier/ntfy) | |
ntop | top network users | :heavy_check_mark: | | |
nuttcp | network performance measurement | :heavy_check_mark: | | |
nutty | network utility | :heavy_multiplication_x: | [Nutty](https://launchpad.net/nutty) [repo](https://github.com/babluboy/nutty) | ppa:bablu-boy/nutty.0.1 |
nvme-cli  | NVMe management tool | :heavy_check_mark: | | |
nvidia-smi | NVidia GPU management CLI | :heavy_multiplication_x: | | |
nvtop | GPU monitor | :heavy_multiplication_x: | [nvtop](https://github.com/Syllo/nvtop) | |
obnam | incremental daily backups with SFTP/[GnuPG](#gpg) support | :heavy_check_mark: | | |
obs | video recording/livestreaming | :heavy_multiplication_x: | [OBS](https://obsproject.com/) | |
obsidian | Markdown mindmap tool | :heavy_multiplication_x: | [obsidian](https://obsidian.md/) | |
oclint | C/C++/ObjC static code analyser | :heavy_multiplication_x: | [OCLint](https://oclint.org/) [repo](https://github.com/oclint/oclint/) | |
ocrfeeder | OCR text scanner | :heavy_check_mark: | | |
ocrmypdf | OCR PDF files | :heavy_check_mark: | | |
octave | numerical computation library and GUI | :heavy_check_mark: | | Matlab-like |
od2txt | ODT to text converter | :heavy_check_mark: | | |
oletoy | file format analyser | :heavy_multiplication_x: | [re-lab](https://github.com/renyxa/re-lab) | |
olive | video editor | :heavy_multiplication_x: | [olive](https://olivevideoeditor.org) [repo](https://github.com/olive-editor/olive) | |
omd | Nagios fork | :heavy_multiplication_x: | [OMD](https://omdistro.org/) | easier set-up than [Nagios](#nagios) |
onedrive-d | OneDrive sync | :heavy_multiplication_x: | [onedrive-d](https://github.com/xybu92/onedrive-d) | |
onetime | one-time pad | :heavy_check_mark: | | |
onionshare | secure communications | :heavy_multiplication_x: | [onionshare](https://onionshare.org/) | |
openarena | Quake-like FPS | :heavy_check_mark: | | |
openrgb | hardware RGB lighting manager | :heavy_multiplication_x: | [OpenRGB](https://gitlab.com/CalcProgrammer1/OpenRGB) | |
openshot | video editor | :heavy_check_mark: | | good all rounder, requires Frei0r-plugins |
opensnitch | outgoing network connections manager | :heavy_multiplication_x: | [opensnitch](https://github.com/evilsocket/opensnitch) | |
openssh-server | OpenSSH | :heavy_check_mark: | | |
openvpn | VPN | :heavy_check_mark: | | |
opera | browser | :heavy_check_mark: | | use `apt` |
oprofile | system profiler | :heavy_check_mark: | | |
optipng | optimise PNGs | :heavy_check_mark: | | |
orca | screenreader | :heavy_check_mark: | | |
orchestrator | MySQL replication manager | :heavy_multiplication_x: | [orchestrator](https://github.com/github/orchestrator) | |
osync | `rsync` simplifier | :heavy_multiplication_x: | [osync](https://github.com/deajan/osync) | |
outrun | delegate tasks to remote machines | :heavy_multiplication_x: | [outrun](https://pypi.org/project/outrun/) | |
p0f | passive OS fingerprinting tool | :heavy_check_mark: | | quieter than [NMap](#nmap) |
pack | password analyser | :heavy_multiplication_x: | | |
packit | network injection/capture tool	 | :heavy_check_mark: | | |
packeth | GUI Ethernet packet generator | :heavy_check_mark: | | |
packetsender | GUI packet generator | :heavy_multiplication_x: | [Packet Sender](https://packetsender.com/download) | |
pamix | PulseAudio mixer | :heavy_multiplication_x: | [PAmix](https://github.com/patroclos/PAmix) | |
pandoc | DOCX/RTF/HTML/Markdown converter | :heavy_check_mark: | [Pandoc](https://pandoc.org/) | |
panwriter | Markdown editor | :heavy_multiplication_x: | [panwriter](https://github.com/mb21/panwriter) | tight integration with `pandoc` |
paper-clip | PDF metadata editor | :heavy_multiplication_x: | [paper-clip](https://github.com/Diego-Ivan/Paper-Clip) | |
parallel | multi-threaded Bash scripts | :heavy_check_mark: | | in [moreutils](#moreutils) <a id="parallel"></a> |
parted | disk partitioner | :heavy_check_mark: | | creates GPT partitions, but does not resize |
passwordsafe | password vault | :heavy_check_mark: | [Password Safe](https://sourceforge.net/projects/passwordsafe/) | |
patator | multi brute-forcer | :heavy_check_mark: | [patator](https://github.com/lanjelot/patator) | |
pavucontrol | PulseAudio volume control | :heavy_check_mark: | | independently adjust audio streams |
pax-utils | ELF checking utilities | :heavy_check_mark: | | `dumpelf`, `scanelf`, `lddtree`, `pspax` etc |
pbnj | monitor network changes | :heavy_check_mark: | | |
pdfbooklet | PDF printer | :heavy_multiplication_x: | [PDFbooklet](https://sourceforge.net/projects/pdfbooklet/) | |
pdfcrack | PDF password cracker | :heavy_check_mark: | | |
pdfedit | PDF editor | :heavy_check_mark: | | good at text, no image editing |
pdfgrep | PDF search | :heavy_check_mark: | [PDFgrep](https://pdfgrep.org/) |
pdfmod | PDF editor | :heavy_check_mark: | | simple but good: edit meta data, remove page, extract page |
pdfresurrect | PDF analyser | :heavy_multiplication_x: | [pdfresurrect](https://github.com/enferex/pdfresurrect) | |
pdfsam | PDF editor | :heavy_check_mark: | [PDFsam](https://pdfsam.org/) | |
pdnsd | proxy DNS server | :heavy_check_mark: | | |
pdfmixtool | PDF editor | :heavy_multiplication_x: | [pdfmixtool](https://scarpetta.eu/pdfmixtool/) [repo](https://gitlab.com/scarpetta/pdfmixtool) | |
pdftk | PDF tool | :heavy_check_mark: | | |
pdftotext | PDF to text | :heavy_check_mark: | | in *poppler-utils* |
peazip | multi-zip GUI and converter | :heavy_multiplication_x: | [PeaZip](https://sourceforge.net/projects/peazip/) | |
pemcracker | PEM cracker | :heavy_multiplication_x: | [pemcracker](https://github.com/bwall/pemcracker) | |
pentbox | security and stability tester | :heavy_multiplication_x: | | |
percona-toolkit | MySQL toolkit | :heavy_check_mark: | | |
perf | performance analysis tools | :heavy_check_mark: | | in *linux-tools-common* |
perf-tools-unstable | `perf` helper tools by Brendan Gregg | :heavy_check_mark: | | `iosnoop`, `iolatency`, `uprobe` |
perforator | *perf* extender | :heavy_multiplication_x: | [perforator](https://github.com/zyedidia/perforator) | |
pewpew | server stress tester | :heavy_multiplication_x: | [pewpew](https://github.com/bengadbois/pewpew) | |
pgadmin3 | GUI admin for [PostgresSQL](#postgressql) | :heavy_check_mark: | | |
pgpdump | [GnuPG](#gpg)/PGP file visualiser | :heavy_check_mark: | | |
phatch | batch image converter | :heavy_check_mark: | | |
phoronix | benchmark suite | :heavy_multiplication_x: | [Phoronix](http://phoronix-test-suite.com/) | |
photoflare | image editor | :heavy_multiplication_x: | [PhotoFlare](https://github.com/PhotoFlare/photoflare) | |
photorec | file recovery tool | :heavy_multiplication_x: | [photorec](https://www.cgsecurity.org/) | |
php7cc | PHP 7 incompatible code detector | :heavy_check_mark: | | |
php-markdown | PHP Markdown renderer | :heavy_check_mark: | | |
php-codesniffer | phpcs in CLI | :heavy_check_mark: | | |
phplint | PHP linter | :heavy_multiplication_x: | [phplint](https://github.com/overtrue/phplint) | |
phpunit | PHP unit test suite | :heavy_check_mark: | | not Mr Bergmann's PHPUnit |
phrasendrescher | SSH dictionary attacker | :heavy_multiplication_x: | | `pd ssh -d pass.txt -t <IP> -v`) |
pic | graphics programming language | :heavy_multiplication_x: | [piC](http://www.kohala.com/start/troff/troff.html) | |
picard | audio file manager | :heavy_check_mark: | | |
pigz | multi-threading GZIP | :heavy_check_mark: | | |
pingnoo | ping analyser | :heavy_multiplication_x: | [pingnoo](https://github.com/nedrysoft/pingnoo) | |
pinta | Paint.net clone | :heavy_check_mark: | | |
piper | mouse config | :heavy_multiplication_x: | [piper](https://github.com/libratbag/piper) | |
pitivi | video editor | :heavy_check_mark: | | suitable for: clips to combine, add audio track, filter |
pixelorama | sprite editor | :heavy_multiplication_x: | [Pixelorama](https://github.com/Orama-Interactive/Pixelorama) | |
pktstat | resolve packet details/connections | :heavy_check_mark: | | |
playonlinux | Microsoft games through Wine | :heavy_check_mark: | | |
playshell | CLI media player | :heavy_multiplication_x: | [playshell](https://sourceforge.net/projects/playshell/) | |
plecast | Wordpress plugin analyser | :heavy_multiplication_x: | | |
plumecreator | book writing editor | :heavy_multiplication_x: | | |
pmd | source code analyser | :heavy_multiplication_x: | [PMD](https://sourceforge.net/projects/pmd/) | Java-based |
pmount | mount removable devices as normal user | :heavy_check_mark: | | |
png2svg | PNG to SVG | :heavy_multiplication_x: | [png2svg](https://github.com/xyproto/png2svg) | |
pngcrush | PNG compressor | :heavy_check_mark: | | |
pnpm | leaner Node.js package manager | :heavy_multiplication_x: | [pnpm](https://github.com/pnpm/pnpm) | |
pnscan | multi-threaded port scanner | :heavy_check_mark: | | |
polygen | random sentences from grammar definitions | :heavy_check_mark: | | |
portainer | GUI Docker manager | :heavy_multiplication_x: | [portainer](https://www.portainer.io/) | |
portdog | port scan detector | :heavy_multiplication_x: | [PortDog](https://github.com/puniaze/PortDog) | |
portsentry | port scan detector | :heavy_check_mark: | | |
postgresql | PostgreSQL | :heavy_check_mark: | | <a id="postgressql"></a> |
potamus | music player using directories | :heavy_multiplication_x: | [Potamus](http://offog.org/code/potamus/) | |
povray | CLI raytracer | :heavy_check_mark: | | |
powertop | power consumption analyser | :heavy_check_mark: | | |
ppa-purge | disable a PPA | :heavy_check_mark: | | |
preload | adaptive binary preloader | :heavy_check_mark: | | |
prelockd | memory/OOM tool | :heavy_multiplication_x: | [prelockd](https://github.com/hakavlad/prelockd) | |
prettyeq | PulseAudio equaliser | :heavy_multiplication_x: | [prettyeq](https://github.com/keur/prettyeq) | |
printer-driver | various drivers | :heavy_check_mark: | | |
privoxy | SOCKS requests to HTTP requests | :heavy_check_mark: | | block UDP leaks in [Tor](#tor) |
procdump | create core dumps of apps | :heavy_multiplication_x: | [ProcDump](https://github.com/Microsoft/ProcDump-for-Linux) | |
procenv | show process environment | :heavy_check_mark: | [procenv](https://github.com/jamesodhunt/procenv) | |
processing | programming language | :heavy_multiplication_x: | | |
procinfo | `socklist`, `lsdev`, system stats from /proc | :heavy_check_mark: | | |
profile-sync-daemon | move browser profiles to RAM | :heavy_multiplication_x: | [profile-sync-daemon](https://github.com/graysky2/profile-sync-daemon) | systemd |
prometheus.io | [Nagios](#nagios) replacement for microservices | :heavy_multiplication_x: | [Prometheus](https://github.com/prometheus) | |
prowler | AWS security tool | :heavy_multiplication_x: | [prowler](https://github.com/toniblyx/prowler) | |
proxychains | redirect connections through proxy servers | :heavy_check_mark: | | |
psad | port scan detector | :heavy_check_mark: | | from iptables |
psensor | temperature sensors GUI | :heavy_check_mark: | | |
pspp | statistical analysis | :heavy_check_mark: | [PSPP](https://www.gnu.org/software/pspp/) | SPSS replacement |
pst-utils | read Microsoft Outlook *.pst* files | :heavy_check_mark: | | *.pst* to *.mbox* |
pstop | MySQL top from perf schema | :heavy_multiplication_x: | [ps-top](https://github.com/sjmudd/ps-top) | |
publican | docbook XML publisher | :heavy_check_mark: | | |
puddletag | music file tag editor | :heavy_check_mark: | | |
pulseeffects | equalizer for PulseAudio apps | :heavy_multiplication_x: | [pulseeffects](https://github.com/wwmm/pulseeffects) | ppa:yunnxx/gnome3 |
putty | PuTTY for Linux | :heavy_check_mark: | | |
pv | pipe view meter | :heavy_check_mark: | | benchmark SSH etc |
pwgen | password generator | :heavy_check_mark: | | |
pychecker | Python error checker | :heavy_check_mark: | | |
pylint | Python code static checker | :heavy_check_mark: | | |
pylint3 | Python 3 code static checker | :heavy_check_mark: | | |
pypy | Python JIT compiler | :heavy_check_mark: | | |
pyrenamer | mass file renamer | :heavy_check_mark: | | |
pyrit | GPU WPA2 wireless cracker | :heavy_check_mark: | | |
python3-csvkit | CSV utilities | :heavy_check_mark: | | |
python3-enigma | Enigma machine library | :heavy_check_mark: | [Py-Enigma](https://py-enigma.readthedocs.io/en/latest/) | |
python3-matplotlib | plotting system | :heavy_check_mark: | | |
python3-pip | Python 3 package installer | :heavy_check_mark: | | |
python3-psutil | psutil | :heavy_check_mark: | | access reporting tools |
python3-usb | Python 3 USB interface | :heavy_check_mark: | | <a id="python3-usb"></a> |
python-evdev | generic input event interface | :heavy_check_mark: | | |
python-mysqldb | Python MySQL API | :heavy_check_mark: | | <a id="python-mysqldb"></a> |
python-pip | Python installer | :heavy_check_mark: | | `apt-get install python3-pip` |
python-setuptools | | :heavy_check_mark: | | needed for [python-mysqldb](#python-mysqldb) |
qalc | CLI calculator | :heavy_check_mark: | | |
qemu | processor emulator | :heavy_check_mark: | | `apt-get install kvm qemu-kvm qemu-kvmextras` <a id="qemu"></a> |
qemu-kvm | multiple virtual PCs | :heavy_check_mark: | | |
qjournalctl | GUI for systemd `journalctl` | :heavy_multiplication_x: | [qjournalctl](https://github.com/pentix/qjournalctl) | |
qmmp | music player | :heavy_check_mark: | | |
qownnotes | notepad with Markdown | :heavy_multiplication_x: | [QOwnNotes](https://www.qownnotes.org/) | |
qmplay2 | video/YouTube player | :heavy_multiplication_x: | [QMPlay2](https://github.com/zaps166/QMPlay2) | GPU acceleration; good options |
qpdf | CLI PDF editor | :heavy_multiplication_x: | [QPDF](https://qpdf.sourceforge.io/) | |
qrencode | QR generator | :heavy_check_mark: | | `qrencode -o f.png 'txt'` # -s height of pixel, -l H highest level of error correction|
qtox | encrypted chat | :heavy_multiplication_x: | [qTox](https://github.com/qTox/qTox) | |
qtpfsgui | HDR tonemapper | :heavy_check_mark: | | |
qtqr | GUI QR generator | :heavy_check_mark: | | |
qtractor | audio/MIDI multitrack sequencer | :heavy_check_mark: | | |
qtvirtmanager | virtual hosts manager | :heavy_multiplication_x: | [qt-virt-manager](https://github.com/F1ash/qt-virt-manager) | |
quetoo | Quake2 remake | :heavy_multiplication_x: | [quetoo](https://github.com/jdolan/quetoo) | |
quiterss | RSS reader | :heavy_check_mark: | | uses WebKit |
qupzilla | lightweight Chromium-based browser | :heavy_check_mark: | | |
rabbitvcs | SVN GUI | :heavy_check_mark: | | |
radamsa | general purpose fuzzer | :heavy_multiplication_x: | [radamsa](https://gitlab.com/akihe/radamsa) | |
radeon-profile | Radeon GPU profiler | :heavy_multiplication_x: | [radeon-profile](https://github.com/marazmista/radeon-profile) | |
radeontop | Radeon GPU top | :heavy_check_mark: | | |
rand | random character generator | :heavy_check_mark: | | |
rapidscan | web vulnerability Scanner | :heavy_multiplication_x: | [rapidscan](https://github.com/skavngr/rapidscan) | |
rapidsvn | SVN GUI | :heavy_check_mark: | | |
rarcrack | RAR cracker | :heavy_multiplication_x: | [rarCrack](https://sourceforge.net/projects/rarcrack/) | |
rare | CLI regex parser | :heavy_multiplication_x: | [rare](https://github.com/zix99/rare) | |
raspiraw | RaspPi RAW processing | :heavy_multiplication_x: | [raspiraw](https://github.com/illes/raspiraw) | |
ratproxy | passive web app security assessor | :heavy_check_mark: | | |
rats | rough auditing tool for security | :heavy_check_mark: | | |
rawtherapee | RAW file editor | :heavy_check_mark: | [RawTherapee](http://rawtherapee.com) | |
rclone | `rsync` for cloud drives | :heavy_multiplication_x: | [RClone](https://rclone.org/) [repo](https://github.com/ncw/rclone) | <a id="rclone"></a> |
rclonebrowser | GUI for [rclone](#rclone) | :heavy_multiplication_x: | [RcloneBrowser](https://github.com/mmozeiko/RcloneBrowser) | |
rcrack | cracker via rainbow tables | :heavy_multiplication_x: | | |
rdiff-backup | remote incremental backup | :heavy_check_mark: | | |
realvnc | remote desktop | :heavy_check_mark: | | |
reaver | router WPS PIN brute-forcer | :heavy_check_mark: | | |
recoll | desktop/network GUI search engine | :heavy_check_mark: | | |
recsveditor | CSV editor | :heavy_multiplication_x: | [reCsvEditor](https://sourceforge.net/projects/recsveditor/) | Java-based |
rednotebook | calendar and notebook | :heavy_check_mark: | [RedNotebook](https://sourceforge.net/projects/rednotebook/) | |
redshift | diurnal screen colour temp adjuster | :heavy_check_mark: | | deps: *Geoclue-2.0* |
redshift-gtk | GUI for redshift | :heavy_check_mark: | | |
reformat | text formatter | :heavy_check_mark: | | line length, margin |
remarkable | Markdown editor | :heavy_multiplication_x: | [Remarkable](http://remarkableapp.github.io/) | deps: `python3-markdown`, `python3-bs4`, `wkhtmltopdf` |
remmina | remote desktop | :heavy_check_mark: | | |
remmina-plugin-vnc | VNC plugin for Remmina | :heavy_check_mark: | | |
remnux | Linux malware analyser | :heavy_multiplication_x: | [REMnux](https://sourceforge.net/projects/remnux/) | |
retext | ReText/Markdown editor | :heavy_check_mark: | [Retext](https://github.com/retext-project/retext) | |
rdesktop | CLI remote desktop client | :heavy_check_mark: | | *grdesktop* for GUI <a id="rdesktop"></a> |
recode | file charset conversion | :heavy_check_mark: | | |
recoverjpeg | recover JPGs/MOVs | :heavy_check_mark: | | from SD card |
regexxer | file regex view and replace | :heavy_check_mark: | | |
restic | CLI backup manager | :heavy_check_mark: | [restic](https://restic.net/) [repo](https://github.com/restic/restic) | |
richochet | [Tor](#tor) chat | :heavy_multiplication_x: | [richochet](https://ricochet.im/) | |
rig | random person id generator | :heavy_check_mark: | | |
rkhunter | rootkit hunter | :heavy_check_mark: | | |
rmlint | dups and cruft remover | :heavy_multiplication_x: | [rmlint](https://rmlint.readthedocs.io/en/master/) [repo](https://github.com/sahib/rmlint) | |
rnd64 | multi-threaded random data generator | :heavy_multiplication_x: | [RND64](https://github.com/Tinram/RND64) | |
rng-tools | daemon to use hardware TRNG | :heavy_check_mark: | | includes `rngtest` |
rooster | CLI password manager | :heavy_multiplication_x: | [rooster](https://github.com/conradkdotcom/rooster) | `scrypt`, AES-256, HMAC-SHA256 |
rosaimagewriter | USB Flash tool | :heavy_multiplication_x: | | |
rosegarden | music editor | :heavy_check_mark: | | |
rsmangler | word permutations | :heavy_multiplication_x: | | |
rsnapshot | filesystem snapshot | :heavy_check_mark: | | |
rssh | restricted shell | :heavy_check_mark: | | give user only: `scp`, `sftp`, `rsync` |
rst2pdf | ReText to PDF | :heavy_check_mark: | | |
rsyncrypto | `rsync` encryption | :heavy_check_mark: | | |
rtgen | rainbow table generator | :heavy_multiplication_x: | | `rtgen md5 loweralpha-numeric 1 5 0 3800 33554432 0` |
ruby | Ruby interpreter | :heavy_check_mark: | | `irb` |
ruffle | Flash emulator | :heavy_multiplication_x: | [ruffle](https://ruffle.rs/) | |
rustbuster | web fuzzer | :heavy_multiplication_x: | [rustbuster](https://github.com/phra/rustbuster) | |
rustc | Rust compiler | :heavy_multiplication_x: | | |
rustdesk | remote desktop | :heavy_multiplication_x: | [rustdesk](https://rustdesk.com) [repo](https://github.com/rustdesk/rustdesk) | |
rymdport | encrypted file sharing | :heavy_multiplication_x: | [rymdport](https://github.com/Jacalz/rymdport) | |
s-tui | CLI hardware monitor | :heavy_multiplication_x: | [s-tui](https://amanusk.github.io/s-tui/) [repo](https://github.com/amanusk/s-tui/) | |
samhain | IDS | :heavy_check_mark: | | |
sampler | CLI visualisation tool | :heavy_multiplication_x: | [sampler](https://github.com/sqshq/sampler) | |
sane | document scan tools | :heavy_check_mark: | | |
sane-airscan | SANE network scanner | :heavy_multiplication_x: | [sane-airscan](https://github.com/alexpevzner/sane-airscan) | |
savedesktop | desktop config save | :heavy_multiplication_x: | [SaveDesktop](https://github.com/vikdevelop/SaveDesktop) | |
sbackup | simple backup | :heavy_check_mark: | | |
scalpel | file recovery/data carver | :heavy_check_mark: | [scalpel](https://github.com/sleuthkit/scalpel) | |
scamper | network measurement tool | :heavy_check_mark: | | |
scrcpy | Android screen connector | :heavy_check_mark: | [scrcpy](https://github.com/Genymobile/scrcpy) | |
screenruler | pixel ruler | :heavy_check_mark: | | |
scribus | desktop publisher/PDF editor | :heavy_check_mark: | | |
scrot | CLI screen capture | :heavy_check_mark: | | |
scrypt | encryption utility | :heavy_check_mark: | [scrypt](https://github.com/Tarsnap/scrypt) | |
secure-delete | wipe files/swap/memory | :heavy_check_mark: | | |
sendemail | CLI email client | :heavy_check_mark: | | |
sendmail | mail agent | :heavy_check_mark: | | |
sentry | brute-force blocker | :heavy_multiplication_x: | [sentry](https://github.com/msimerson/sentry) | |
sfk | comprehensive file utilities | :heavy_multiplication_x: | [Swiss File Knife](http://stahlworks.com/dev/swiss-file-knife.html) | |
sg3-utils | SCSI utilities | :heavy_check_mark: | | |
shellcheck | Bash lint | :heavy_check_mark: | [ShellCheck](https://www.shellcheck.net/) | |
shellnoob | shell code generator | :heavy_multiplication_x: | [shellnoob](https://gitlab.com/kalilinux/packages/shellnoob) | |
shellpic | preview images in SSH | :heavy_multiplication_x: | [shellpic](https://github.com/larsjsol/shellpic) | |
sherlock | OSINT tool | :heavy_multiplication_x: | [sherlock](https://github.com/sherlock-project/sherlock) | |
shotcut | video editor | :heavy_multiplication_x: | [Shotcut](https://shotcut.org/) | |
shwr | HTML presentations | :heavy_multiplication_x: | [Shwr](https://shwr.me/) | |
siege | server stress tester | :heavy_check_mark: | | |
sigil | eBook editor | :heavy_multiplication_x: | [Sigil](https://sigil-ebook.com/) | |
silver-searcher | source code grep | :heavy_multiplication_x: | [TSS](https://github.com/ggreer/the_silver_searcher) | |
simplebackup | backup utility | :heavy_check_mark: | | |
simplescreenrecorder | record programs | :heavy_multiplication_x: | [SSR](https://www.maartenbaert.be/simplescreenrecorder/) | |
simon | voice recognition | :heavy_check_mark: | | |
singlefilez | webpage archiver | :heavy_multiplication_x: | [SingleFileZ](https://github.com/gildas-lormeau/SingleFileZ) | |
sipcrack | SIP log-in dumper/cracker | :heavy_check_mark: | | |
sipvicious | audit SIP-based VoIP systems | :heavy_multiplication_x: | | |
sirikali | GUI for gocryptfs/encfs/securefs | :heavy_multiplication_x: | [SiriKali](https://mhogomchungu.github.io/sirikali/) | |
skeema | CLI MySQL schema management | :heavy_multiplication_x: | [skeema](https://github.com/skeema/skeema) | |
skipfish | web app recon tool | :heavy_check_mark: | | |
skrooge | money accounting | :heavy_check_mark: | | |
slack-desktop | team messenger | :heavy_check_mark: | | proprietary |
slate | pixel art editor | :heavy_multiplication_x: | [slate](https://github.com/mitchcurtis/slate) | |
slowhttptest | server stress tool | :heavy_check_mark: | | |
slurm | bandwidth monitor | :heavy_check_mark: | | |
smartdeblur | restore blurred images | :heavy_multiplication_x: | [SmartDeblur](https://github.com/Y-Vladimir/SmartDeblur) | |
smartmontools | monitor/control storage that supports SMART | :heavy_check_mark: | | contains `smartctl` |
smbclient | Samba client | :heavy_check_mark: | | |
smbmap | SMB network mapper | :heavy_multiplication_x: | [smbmap](https://github.com/ShawnDEvans/smbmap) | |
smc | GUI system monitor | :heavy_multiplication_x: | [smc](https://github.com/hakandundar34coding/system-monitoring-center) | |
smem | memory reporting tool | :heavy_check_mark: | | |
smemstat | memory monitoring tool | :heavy_check_mark: | | |
smilla-enlarger | image upscaler | :heavy_multiplication_x: | [smilla-enlarger](https://github.com/lupoDharkael/smilla-enlarger) | |
smplayer | video player | :heavy_check_mark: | | GPU acceleration |
snapper | BTRFS filesystem snapshots | :heavy_check_mark: | | |
sngrep | SIP messages flow viewer | :heavy_check_mark: | [Sngrep wiki](https://github.com/irontec/sngrep/wiki) | |
snort | IDS | :heavy_check_mark: | | |
sntop | poll servers | :heavy_check_mark: | | uses `ping` |
socat | relay for bidirectional data transfer | :heavy_check_mark: | | |
softethervpn | VPN | :heavy_multiplication_x: | | |
sonic-pi | coding synth | :heavy_check_mark: | | |
sol-r | ray tracer | :heavy_multiplication_x: | [Sol-R](https://github.com/cyrillefavreau/Sol-R) | |
sox | CLI audio file manipulator | :heavy_check_mark: | | |
sparta | internal network infrastructure pen tool | :heavy_multiplication_x: | [sparta](https://github.com/secforce/sparta) | |
sparkleshare | Dropbox alternative using SSH and [Git](#git) | :heavy_check_mark: | | |
spectre-meltdown-checker | Spectre and Meltdown vulnerability/mitigation checker | :heavy_multiplication_x: | [spectre-meltdown-checker](https://github.com/speed47/spectre-meltdown-checker) | |
speedtest-cli | CLI Internet bandwidth speed tester | :heavy_check_mark: | [speedtest-cli](https://github.com/sivel/speedtest-cli) | `pip install speedtest-cli` |
speedometer | CLI network traffic monitor | :heavy_check_mark: | | |
spek | acoustic spectrum analyser | :heavy_check_mark: | [spek](https://github.com/alexkay/spek) | |
spirit | MySQL online schema changer | :heavy_multiplication_x: | [spirit](https://github.com/cashapp/spirit) | |
splint | C linter | :heavy_check_mark: | | <a id="splint"></a> |
sqlbrute | brute-force SQL injection | :heavy_multiplication_x: | [SQLBrute](https://github.com/GDSSecurity/SQLBrute) | |
sqlcipher | [SQLite](#sqlite3) encryption | :heavy_check_mark: | | |
sqlite3 | SQLite | :heavy_check_mark: | | <a id="sqlite3"></a> |
sqlitebrowser | [SQLite](#sqlite3) GUI | :heavy_check_mark: | | simpler than [sqliteman](#sqliteman) |
sqliteman | [SQLite](#sqlite3) GUI | :heavy_check_mark: | | [SQLiteStudio](#sqlitestudio) is better for unicode data import <a id="sqliteman"></a> |
sqlitestudio | [SQLite](#sqlite3) GUI | :heavy_multiplication_x: | [SQLiteStudio](https://sqlitestudio.pl) [repo](https://github.com/pawelsalawa/sqlitestudio) | <a id="sqlitestudio"><a> |
sqlmap | SQL injection tool | :heavy_check_mark: | [SQLMap](https://sqlmap.org/) [repo](https://github.com/sqlmapproject/sqlmap) | |
sqlninja | Microsoft SQL Server injection | :heavy_multiplication_x: | [sqlninja](https://sourceforge.net/projects/sqlninja) | |
sqlsus | MySQL attacker | :heavy_multiplication_x: | | |
srm | secure file deletion | :heavy_multiplication_x: | [SRM](https://sourceforge.net/projects/srm/) | slow, punishing on SSDs |
ssc | script to ELF | :heavy_multiplication_x: | [ssc](https://github.com/liberize/ssc) | |
ssldump | SSLv3/TLS network protocol analyser | :heavy_check_mark: | | |
sshguard | SSH brute-force protection | :heavy_check_mark: | [SSHGuard](https://www.sshguard.net/) | more intelligent than [fail2ban](#fail2ban) |
sslscan | SSL scanner | :heavy_check_mark: | | |
ssh-audit | SSH config analyser | :heavy_multiplication_x: | [ssh-audit](https://github.com/jtesta/ssh-audit) | |
sshfs | mount remote filesystem | :heavy_check_mark: | | GNOME already does this through gvfs |
sshpass | send password to SCP etc from script | :heavy_check_mark: | | |
sshsysmon | server monitoring via SSH | :heavy_multiplication_x: | [SshSysMon](https://sshsysmon.zdyn.net/) [repo](https://github.com/zix99/sshsysmon) | |
sshtalk | SSH chat server | :heavy_multiplication_x: | | |
sshuttle | VPN over SSH | :heavy_check_mark: | [sshuttle](https://github.com/apenwarr/sshuttle) | TCP, not UDP or ICMP |
stacer | GUI system monitor/manager/optimiser | :heavy_multiplication_x: | [Stacer](https://github.com/oguzhaninan/Stacer) | |
standardnotes | cross-platform encrypted notes app | :heavy_multiplication_x: | [standardnotes](https://standardnotes.org/) [repo](https://github.com/standardnotes) | includes Android |
statsprocessor | word generator | :heavy_multiplication_x: | | |
statusok | website/API monitor | :heavy_multiplication_x: | [statusok](https://github.com/sanathp/statusok) | |
strace | system call tracer | :heavy_check_mark: | | |
stress | CPU/memory/disk stresser | :heavy_check_mark: | | |
stress-ng | system stresser | :heavy_check_mark: | | |
structure-synth | 3D structure generator | :heavy_check_mark: | | |
stunnel | SSL tunnel for own apps | :heavy_check_mark: | [STunnel](https://www.stunnel.org/index.html) | |
subbrute | enumerate DNS records/subdomains | :heavy_multiplication_x: | [subbrute](https://github.com/TheRook/subbrute) | |
subversion | SVN | :heavy_check_mark: | | |
sucrack | `su` multi-threaded brute-forcer | :heavy_check_mark: | | |
sunflow | raytracer | :heavy_check_mark: | | Java-based |
suricata | IDS | :heavy_check_mark: | | |
sux | `su` for X | :heavy_check_mark: | | |
svar | voice activated recorder | :heavy_multiplication_x: | [svar](https://github.com/Arkq/svar) | |
svg-edit | SVG editor | :heavy_multiplication_x: | | |
swaks | SMTP test tool | :heavy_check_mark: | | |
swatch | log file event notifier | :heavy_check_mark: | | |
sxid | SUID/SGID/dir checker | :heavy_check_mark: | | |
symphytum | personal database | :heavy_multiplication_x: | [symphytum](https://github.com/giowck/symphytum) | |
syncthing | sync cloud/network app | :heavy_multiplication_x: | [Syncthing](https://syncthing.net/) | |
synfig | vector 2D animation | :heavy_check_mark: | | |
sysbench | system benchmarker | :heavy_check_mark: | [info](https://www.howtoforge.com/how-to-benchmark-your-system-cpu-file-io-mysql-with-sysbench) | |
sysdig | system exploration/troubleshooting | :heavy_check_mark: | | |
sysmontask | GUI system monitor | :heavy_multiplication_x: | [SysMonTask](https://github.com/KrispyCamel4u/SysMonTask) | |
sysstat | system stats/benchmarking | :heavy_check_mark: | | `sar` is binary log reader |
system-config-lvm | LVM partitioning GUI | :heavy_check_mark: | | |
system-config-samba | Samba GUI | :heavy_check_mark: | | |
systemd-ui | systemd GUI | :heavy_check_mark: | | `systemadm` |
systemdgenie | systemd utility | :heavy_multiplication_x: | [systemdgenie](https://cgit.kde.org/systemdgenie.git) | |
systemtap | kernel instrumentation | :heavy_check_mark: | | <a id="systemtap"></a> |
sysv-rc-conf | SysV runlevel config | :heavy_check_mark: | | use `apt` <a id="sysv-rc-conf"></a> |
tabview | CLI CSV viewer | :heavy_multiplication_x: | [tabview](https://github.com/TabViewer/tabview/) | `pip install tabview` |
taskwarrior | CLI ToDo list | :heavy_multiplication_x: | [Taskwarrior](https://taskwarrior.org/) | |
tasque | task manager | :heavy_check_mark: | | |
tcpdump | CLI network traffic analyser | :heavy_check_mark: | | <a id="tcpdump"></a> |
tcpflow | TCP flow recorder | :heavy_check_mark: | | |
tcpick | TCP stream sniffer/connection tracker | :heavy_check_mark: | | |
tcpreplay | replay saved [`tcpdump`](#tcpdump) files | :heavy_check_mark: | | |
tcpslice | extract from/stitch [`tcpdump`](#tcpdump) files | :heavy_check_mark: | | |
tcpspy | TCP/IP connections logger | :heavy_check_mark: | | |
tcptrace | graphical [tcpdump](#tcpdump) output | :heavy_check_mark: | | |
tcptrack | monitor tcp network connections | :heavy_check_mark: | | |
tcpxtract | extract files from network traffic | :heavy_check_mark: | | |
terminalizer | record terminal actions | :heavy_multiplication_x: | [terminalizer](https://github.com/faressoft/terminalizer) | |
terminator | multiple terminals | :heavy_check_mark: | | |
terminix | CLI emulator | :heavy_multiplication_x: | [terminix](https://github.com/gnunn1/terminix) | |
termpix | CLI image viewer | :heavy_multiplication_x: | [termpix](https://github.com/hopey-dishwasher/termpix) | |
termshark | TUI [Wireshark](#wireshark) | :heavy_multiplication_x: | [termshark](https://github.com/gcla/termsharkx) | |
testdisk | disk/partition recovery tool | :heavy_check_mark: | [TestDisk](https://www.cgsecurity.org/wiki/TestDisk_Download) | |
tesseract-ocr | OCR processor | :heavy_check_mark: | | |
texmaker | LaTeX editor | :heavy_check_mark: | | |
textadept | minimalist cross-platform text editor | :heavy_multiplication_x: | [textadept](https://orbitalquark.github.io/textadept/) [repo](https://github.com/orbitalquark/textadept/) | |
textosaurus | text editor (Qt/Scintilla) | :heavy_multiplication_x: | [textosaurus](https://github.com/martinrotter/textosaurus) | |
texttospeech | text speaker | :heavy_multiplication_x: | [texttospeech](https://gitlab.com/posktomten/texttospeech/) | |
thonny | Python editor/IDE | :heavy_check_mark: | [Thonny](https://thonny.org/) | |
thorium | lighter faster *Chromium* | :heavy_multiplication_x: | [thorium](https://thorium.rocks/) | |
tkdiff | GUI for diff | :heavy_multiplication_x: | [tkdiff](https://sourceforge.net/projects/tkdiff/) | |
tig | CLI [Git](#git) info viewer | :heavy_check_mark: | | |
tiger | report root vulnerabilities | :heavy_check_mark: | | |
tigervnc | remote desktop | :heavy_check_mark: | | |
tightvnc | remote desktop | :heavy_check_mark: | | |
timeshift | system restore utility | :heavy_check_mark: | | |
tinyproxy | non-caching HTTP proxy | :heavy_check_mark: | | |
tlp | laptop power manager | :heavy_check_mark: | [TLP](https://linrunner.de/tlp/) [repo](https://github.com/linrunner/TLP) | |
tmsu | file tagging app | :heavy_multiplication_x: | [TMSU](https://github.com/oniony/TMSU) | |
tmux | CLI multiplexer | :heavy_check_mark: | | |
todo.txt | CLI ToDo notes | :heavy_multiplication_x: | [todo.txt](http://todotxt.org/) | |
tofromdos | EOL character converter | :heavy_check_mark: | | <a id="tofromdos"></a> |
tomahawk | media player | :heavy_check_mark: | | |
tor | anonymising overlay | :heavy_check_mark: | | get source, **not** repo version <a id="tor"></a> |
torsocks | use SOCKS-friendly apps with [Tor](#tor) | :heavy_check_mark: | | e.g. SSH |
trace-cmd | kernel function tracing analyser | :heavy_check_mark: | | |
traceroute | trace packets | :heavy_check_mark: | | <a id="traceroute"></a> |
trafshow | show network traffic | :heavy_check_mark: | | see [Netdiag](#netdiag) |
transmageddon | media file converter | :heavy_check_mark: | | |
trash-cli | CLI trash bin control | :heavy_check_mark: | | `trash-empty`, `trash-list` |
tree | CLI directory tree lister | :heavy_check_mark: | | |
treeline | [TreePadLite](#treepadlite)/XML/bookmark editor | :heavy_check_mark: | [Treeline](http://treeline.bellz.org) | |
trelby | screenwriting program | :heavy_multiplication_x: | [Trelby](https://www.trelby.org/download/) | |
trickle | bandwidth throttler | :heavy_check_mark: | | |
trimage | PNG/JPG compressor | :heavy_check_mark: | | |
trupax | encrypt files and folders | :heavy_multiplication_x: | [TruPax](https://coderslagoon.com/) | |
tshark | CLI [Wireshark](#wireshark) | :heavy_check_mark: | | |
tsung | HTTP benchmark and database tester | :heavy_check_mark: | [TSung](http://tsung.erlang-projects.org) | sophisticated |
tt-rss | tiny tiny RSS | :heavy_check_mark: | | |
ttf-mscorefonts-installer | Microsoft TTF fonts | :heavy_check_mark: | | |
tuc | improved `cut` | :heavy_multiplication_x: | [tuc](https://github.com/riquito/tuc) | |
tuptime | historical (total) uptime | :heavy_check_mark: | | |
turbovnc | remote desktop | :heavy_multiplication_x: | [TurboVNC](https://turbovnc.org/) [repo](https://github.com/TurboVNC/turbovnc) | |
tuxguitar | music app including scoresheet | :heavy_check_mark: | [Tuxguitar](https://tuxguitar.herac.com.ar/) | |
typora | Markdown/Mermaid editor | :heavy_check_mark: | [Typora](https://typora.io/) | |
uberwriter | Markdown editor | :heavy_multiplication_x: | [UberWriter](https://uberwriter.github.io/uberwriter/) [repo](https://github.com/UberWriter/uberwriter) | |
ubuntu-tweak | Ubuntu config tool | :heavy_check_mark: | | use `apt` |
udptunnel | tunnel UDP over TCP | :heavy_check_mark: | | |
ugui_flif | GUI for [FLIF](#flif) | :heavy_multiplication_x: | [UGUI_FLIF](https://github.com/FLIF-hub/UGUI_FLIF) | |
ufraw | RAW processor | :heavy_check_mark: | [UFRaw](https://ufraw.sourceforge.net/) | |
uftrace | C program tracer | :heavy_check_mark: | | |
ufw | firewall | :heavy_check_mark: | | <a id="ufw"></a> |
ugrep | advanced `grep` | :heavy_check_mark: | [ugrep](https://github.com/Genivia/ugrep) | |
umplayer | video player | :heavy_multiplication_x: | | supposed better DVD playback than VLC |
uncrustify | code formatter | :heavy_check_mark: | | |
unetbootin | ISO to USB boot | :heavy_check_mark: | | |
unhide | find hidden processes | :heavy_check_mark: | | |
unhtml | remove HTML tags from file | :heavy_check_mark: | | |
unison | CLI file sync tool | :heavy_check_mark: | [unison](https://github.com/bcpierce00/unison) | |
unison-gtk | GUI for unison | :heavy_check_mark: | | |
units | CLI unit converter | :heavy_check_mark: | | |
unoconv | Microsoft Office *.doc* converter | :heavy_multiplication_x: | [Unoconv](http://dag.wiee.rs/home-made/unoconv/) | |
unshield | extract *.cab* files from InstallShield | :heavy_check_mark: | | |
unsnap | migrate Snap to Flatpak | :heavy_multiplication_x: | [unsnap](https://github.com/popey/unsnap) | |
unsort | jumbles lines in file | :heavy_check_mark: | | |
upscayl | image upscaler | :heavy_multiplication_x: | [upscayl](https://upscayl.github.io/) | |
urlwatch | webpage update monitor | :heavy_check_mark: | | |
usbimager | leightweight USB image writer | :heavy_multiplication_x: | [usbimager](https://gitlab.com/bztsrc/usbimager) | |
usbview | GUI `lsusb` | :heavy_check_mark: | [usbview](https://github.com/gregkh/usbview) | |
usermanager | GUI user/group manager | :heavy_multiplication_x: | [UserManager](https://github.com/xvass/UserManager) | |
valac | Vala compiler | :heavy_check_mark: | | |
vale | text linter | :heavy_multiplication_x: | [vale](https://github.com/errata-ai/vale) | |
valentinastudio | MySQL/[PostgreSQL](postgresql)/MSSQL browser| :heavy_multiplication_x: | [Valentina Studio](https://valentina-db.com/en/all-downloads/vstudio/current) | |
valgrind | memory debugger and profiler | :heavy_check_mark: | | <a id="valgrind"></a> |
valkyrie | GUI for [valgrind](#valgrind) | :heavy_check_mark: | | |
vbindiff | visual binary file compare | :heavy_check_mark: | | |
vega | web app tester | :heavy_multiplication_x: | | Java-based |
vegeta | HTTP load tester | :heavy_multiplication_x: | [vegeta](https://github.com/tsenart/vegeta) | |
ventoy | create bootable USB drives | :heavy_multiplication_x: | [Ventoy](https://ventoy.net) [repo](https://github.com/ventoy/Ventoy) | |
veracrypt | TrueCrypt replacement | :heavy_multiplication_x: | [VeraCrypt](https://www.veracrypt.fr/) | |
veusz | GUI scientific plotter | :heavy_check_mark: | [Veusz](https://veusz.github.io/) | |
vidalia | [Tor](#tor) GUI frontend | :heavy_check_mark: | | |
video-trimmer | video editor | :heavy_multiplication_x: | [video-trimmer](https://gitlab.gnome.org/YaLTeR/video-trimmer) | |
vim | code/text editor | :heavy_check_mark: | | |
vinagre | GNOME remote desktop client | :heavy_check_mark: | | |
vinetto | interrogate thumbs.db files | :heavy_check_mark: | | |
virt-manager | GUI VM manager | :heavy_check_mark: | [virt-manager](https://virt-manager.org/) | good options range; still 'experimental' |
virtualbox | virtual machines | :heavy_check_mark: | [Virtual Box](https://www.virtualbox.org/) | GPU acceleration |
vizex | disk usage visualiser | :heavy_multiplication_x: | [vizex](https://github.com/bexxmodd/vizex) | |
visual studio code | code editor/IDE | :heavy_multiplication_x: | [Visual Studio Code](https://code.visualstudio.com/) | also [vscodium](#vscodium) and a [snap](https://snapcraft.io/code) |
vivaldi | highly-customisable browser | :heavy_multiplication_x: | [Vivaldi](https://vivaldi.com/) | |
vmware | virtual machines | :heavy_check_mark: | | GPU acceleration |
vnstat | CLI network traffic monitor | :heavy_check_mark: | | |
vobcopy | CD/MP4 track copier | :heavy_check_mark: | | |
voiphopper | VoIP security testing tool | :heavy_multiplication_x: | | |
voipong | VoIP sniffer/call detector | :heavy_multiplication_x: | | |
vokoscreen | screencast creator | :heavy_check_mark: | | |
vpaint | vector paint | :heavy_multiplication_x: | [VPaint](https://www.vpaint.org/) | |
vrfy | verify email addresses | :heavy_check_mark: | | |
vrms | virtual Richard Stallman: list non-free packages | :heavy_check_mark: | | |
vscodium | VS Code without telemetry | :heavy_multiplication_x: | [VSCodium](https://vscodium.com/) | <a id="vscodium"></a> |
w3af | web app vulnerability framework | :heavy_check_mark: | | |
waidps | wireless auditing + IDS | :heavy_multiplication_x: | [waidps](https://github.com/SYWorks/waidps) | |
wallpaperd | wallpaper rotator | :heavy_multiplication_x: | | |
wammu | (old) phone manager, info exporter | :heavy_check_mark: | | |
wapiti | web app vulnerability scanner | :heavy_check_mark: | | |
warehouse | flatpak manager | :heavy_multiplication_x: | [warehouse](https://github.com/flattool/warehouse) | |
warpinator | LAN file transfer | :heavy_check_mark: | [warpinator](https://github.com/linuxmint/warpinator) | |
watchman | directory monitor tool | :heavy_multiplication_x: | [watchman](https://github.com/facebook/watchman) | |
wavemon | wireless network monitor | :heavy_check_mark: | | |
wbox | HTTP testing tool and config-less HTTP server | :heavy_check_mark: | | |
wdiff | word diff | :heavy_check_mark: | | extended diff |
webcamoid | webcam tool | :heavy_multiplication_x: | [Webcamoid](http://webcamoid.github.io/) | |
weborf | HTTP network file sharing | :heavy_check_mark: | [weborf](https://github.com/ltworf/weborf) | |
webp | webp-pixbuf-loader | :heavy_check_mark: | | |
webshag | web server auditor | :heavy_multiplication_x: | | |
webslayer | web app brute-forcer | :heavy_multiplication_x: | | |
wfuzz | web app brute-forcer | :heavy_check_mark: | [wfuzz](https://github.com/xmendez/wfuzz) | <a id="wfuzz"></a> |
wget | web file retriever | :heavy_check_mark: | | |
whatweb | web scanner | :heavy_check_mark: | | |
whipper | CD ripper | :heavy_multiplication_x: | [whipper](https://github.com/JoeLametta/whipper) | |
whiptail | TUI shell interface | :heavy_check_mark: | | |
whois | WHOIS client | :heavy_check_mark: | | <a id="whois"></a> |
whowatch | user login monitoring | :heavy_check_mark: | | |
whycanticonnect | connection analyser | :heavy_multiplication_x: | [Why Can't I Connect?](https://sourceforge.net/projects/wciconnect/) | |
wicd | wireless manager | :heavy_check_mark: | | |
wifite | CLI wireless auditor/attacker | :heavy_check_mark: | | |
wig | web app info gatherer | :heavy_multiplication_x: | [wig](https://github.com/jekyc/wig) | e.g CMS version |
winff | GUI media converter using ffmpeg/avconv | :heavy_check_mark: | | uses [ffmpeg](#ffmpeg) |
wings3d | 3D modeller | :heavy_check_mark: | | |
wireguard | VPN | :heavy_multiplication_x: | [WireGuard](https://www.wireguard.io/) | |
wireshark | GUI network traffic analyser | :heavy_check_mark: | | <a id="wireshark"></a> |
wkhtmltopdf | HTML to PDF | :heavy_check_mark: | | WebKit-based |
wordgrinder | CLI wordprocessor | :heavy_multiplication_x: | [WordGrinder](http://cowlark.com/wordgrinder/) | |
workrave | RSI timer | :heavy_check_mark: | | |
wpscan | WordPress scanner | :heavy_multiplication_x: | [wpscan](https://wpscan.org/) [repo](https://github.com/wpscanteam/wpscan) | |
wpseku | WordPress security scanner | :heavy_multiplication_x: | [WPSeku](https://github.com/m4ll0k/WPSeku) | |
wrk2 | HTTP benchmarker | :heavy_multiplication_x: | [wrk2](https://github.com/giltene/wrk2) | |
wtop | Apache top | :heavy_multiplication_x: | [wtop](https://github.com/ClockworkNet/wtop) | |
wuzz | CLI HTTP inspection tool | :heavy_multiplication_x: | [wuzz](https://github.com/asciimoo/wuzz) | |
x264 | video encoder | :heavy_check_mark: | | <a id="x264"></a> |
x265 | video compressor | :heavy_multiplication_x: | [x265](https://www.x265.org/) | |
x2go | remote GUI connection | :heavy_multiplication_x: | [X2Go](https://wiki.x2go.org/doku.php) | with SSH |
x86info | CPU info | :heavy_check_mark: | | |
xa65 | 6502 CPU cross-assembler | :heavy_check_mark: | [xa65](http://www.floodgap.com/retrotech/xa/) | |
xanmod | kernel performance patch | :heavy_multiplication_x: | [XanMod](https://xanmod.org/) | |
xaos | fractals | :heavy_check_mark: | | |
xauth | X authentication - needed for remote X GUI | :heavy_check_mark: | | |
xcalib | X monitor calibration | :heavy_check_mark: | | includes screen inverter <a id="xcalib"></a> |
xchm | *.chm* file reader | :heavy_check_mark: | | |
xclip | CLI to X clipboard | :heavy_check_mark: | | |
xdebug | phpN-xdebug | :heavy_check_mark: | | where 'N' is version |
xdg-app | app sandbox | :heavy_multiplication_x: | | ppa:alexlarsson/xdg-app |
xdotool | simulate keyboard/mouse inputs | :heavy_check_mark: | | |
xfractint | fractals | :heavy_check_mark: | | |
xicc | set ICC colour profile for X | :heavy_check_mark: | | |
xiphos | Bible | :heavy_check_mark: | | |
xmlcopyeditor | XML editor | :heavy_check_mark: | | |
xmlint | XML linter | :heavy_check_mark: | | |
xnee | X user-action recorder | :heavy_check_mark: | | |
xnretro | retro photo effects | :heavy_multiplication_x: | | |
xowa | Wikipedia reader | :heavy_multiplication_x: | [Xowa](https://sourceforge.net/projects/xowa/) | |
xplico | network analysis | :heavy_multiplication_x: | [Xplico](https://www.xplico.org/) | browser-based |
xplot | simple data plotter | :heavy_check_mark: | | |
xpra | attach/detach X programs | :heavy_check_mark: | | |
xprobe | remote OS identification | :heavy_check_mark: | | [NMap](#nmap)-like, calls `xprobe2` |
xrandr-invert-colors | X screen inverter | :heavy_multiplication_x: | [xic](https://github.com/zoltanp/xrandr-invert-colors) | [xcalib](#xcalib) alternative |
xrdp | RDP server | :heavy_check_mark: | | |
xresprobe | X resolution probe | :heavy_check_mark: | | |
xsane | document scanner GUI | :heavy_check_mark: | | |
xscreensaver-data-extra | extra GNOME screensavers | :heavy_check_mark: | | |
xsensors | temperature sensors GUI | :heavy_check_mark: | | |
xspy | keylogger | :heavy_multiplication_x: | | ! |
xsser | XSS auditor | :heavy_multiplication_x: | | |
xsuspender | suspend inactive X11 apps | :heavy_multiplication_x: | [xsuspender](https://github.com/kernc/xsuspender) | |
xul-ext-lightning | Thunderbird calendar | :heavy_check_mark: | | |
xsel | access X clipboard (pipe in/out) | :heavy_check_mark: | | |
xz-utils | xz files | :heavy_check_mark: | | |
yara | EXE malware identifier | :heavy_check_mark: | | |
youtube-dl | YouTube downloader | :heavy_check_mark: | | |
youtube-dl-gui | youtube-dl GUI | :heavy_multiplication_x: | [youtube-dl-gui](https://github.com/MrS0m30n3/youtube-dl-gui) | |
yersinia | network vulnerability checker | :heavy_check_mark: | | |
zabbix | network monitoring package | :heavy_check_mark: | | |
zap | zed attack proxy | :heavy_multiplication_x: | | web app vulnerabilities |
zbar-tools | QR and barcode utilities | :heavy_check_mark: | | `zbarimg` |
zeal | programming language docs browser | :heavy_check_mark: | [Zeal](https://github.com/zealdocs/zeal) | |
zeit | GUI for *at* and *cron* | :heavy_multiplication_x: | [zeit](https://bitbucket.org/blaze/zeit) | |
zenith | TUI system monitor | :heavy_multiplication_x: | [zenith](https://github.com/bvaisvil/zenith) | |
zenity | shell dialog boxes | :heavy_check_mark: | | |
zenmap | [NMap](#nmap) GUI | :heavy_check_mark: | | |
zentyal | server GUI set-up + MS Exchange replacement | :heavy_check_mark: | | |
zerotier | easy VPN | :heavy_multiplication_x: | [ZeroTier](https://www.zerotier.com/) | |
zim | 'desktop wiki' notepad | :heavy_check_mark: | | |
zint | barcode generator | :heavy_multiplication_x: | [zint](https://github.com/zint/zint) | |
zipcmp | zip contents comparison | :heavy_check_mark: | | |
zmap | large network scanner | :heavy_check_mark: | | no actual connects like [NMap](#nmap), open ports |
zopfli | zlib/gzip compressor | :heavy_check_mark: | [zopfli](https://github.com/google/zopfli) | |
zurmo | CRM | :heavy_multiplication_x: | [Zurmo](https://github.com/google/zopfli) | |
zzuf | app fuzzer | :heavy_check_mark: | [zzuf](https://github.com/samhocevar/zzuf) | |


## License

Licensed under the [MIT License](https://github.com/Tinram/Linux-Utilities/blob/master/LICENSE).
