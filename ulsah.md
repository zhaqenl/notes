ULSAH
=====


Ĉapitro 22a: Agordoadministrado
-------------------------------

- priparolas la aŭtomatan procezon por agordi multe da serviloj

### la 9-an de Februaro 2018

- priparolis, ĝenerale, la ĝeneralan atenditan konduton de Agordoadministradaj sistemoj.


Ĉapitro 22a: SMB
----------------

- priparolas la Vindoz-an specon de NFS

### la 9-an de Februaro 2018

- priparolis 'Sambda', kiu estas la SMB-a servilo por /UNIX/. Priparolis kelke da komando por uzi
  SMB, ekzemple, `smbclient`, kaj `smbstatus` por sencimigi. 


Ĉapitro 21a: Retodosiersistemo
------------------------------

- priparolas la alian metodon por kunhavi doseriojn kiu estas per la reto

### la 8-an de Februaro 2018

- priparolis kiel plejbonigi NFS-on per kontroli la rendimenton de nfsd kaj kiel ŝanĝi kiuj versioj
  por kuri. Lernis ke la uzado de ion, kiu estas simile al fajroŝirmilo kiam oni kontrolas la NFS-an
  klienton, estas nur iomete gravas. Lernis la komandon por montri la NFS-ajn
  statistikojn. Priparolis la alternativon de la memfarita metodo de NFS (kiu estas la dediĉita
  NFS-a servilo, inkluzive la avantaĝoj). Ankaŭ priparolis la alian metodon por alternative fari la
  aŭtomatan taskon por surmeti (anstataŭ por meti ion ene /etc/fstab). Legos, sekve, pri SMB.

### la 6-an de Februaro 2018

- priparolis la metodon kiu NFS uzas por trakti la komunajn dosierujojn (per eksportoj) kaj la
  detaloj de sia agordo, ekzemple, sia sekuriga agordo (kaj priparolis la malgrandegajn detalojn por
  precizigi la metodon por eksporti la dosierojn/dosierujo). Ankaŭ priparolis la diversajn aferojn
  kiu oni devas eviti, se eblas, ekzemple, oni devas eviti por uzi la 'AUTH_SYS'-an opcion kiel
  sekurigo de NFS, tial ke, ekzistas sekurigaj koncernoj, kaj por eviti uzi tute NFS3, anstataŭe,
  uzu NFS4. (paĝo 1276)

### la 5-an de Februaro 2018

- Antaŭe legas la eblojn de la btrfs-a dosiersistemo. Priparolis unu el la avantaĝo de btrfs kiu
  estas, estas pli bone ol ZFS, ĉefe, kiam oni ŝanĝas la hadvaroagordon. Ankaŭ priparolis la
  ĝeneralan sekurkopian strategion, kaj la gravaj demandoj pri ĉi tiu (kaj la gravaj faktoroj ke oni
  devas pripensi kiam oni volas pensi por fari ĉi tiun, ekzemple, mono).  La nuna ĉapitro ĉefe
  priparolas pri la diversaj specoj por transmeti dosierojn per la reto. Nune, ĉefe, priparolis la
  ĉefan kontraston inter 'stateful' kaj 'stateless' serviloj, kaj ankaŭ priparolis la rendimenton de
  ĉi tiu metodo por transmeti dosierojn (kaj la evidentan gravecon de sekurigo). Nune priparolas la
  detalojn de NFS (ekzemple, la diversaj versioj kiu ne estas kongrua kun unu la alian, do, la NFS-a
  serviloj uzas multe da versio de NFS). (paĝo 1259)


Ĉapitro 20a: Memorilo
---------------------

- priparolas pri la diversaj specoj de memoriloj, kaj siaj utiloj kaj malutiloj, se oni volas uzi
  specifan specon de memorilo

### la 4-an de Februaro 2018

- legas la eblojn de ZFS kaj Btrfs (tamen, unue, ZFS). La ĉapitro priparolas kelke da bazaj funkcioj
  de ZFS, ekzemple, sia propran aŭtomatan eraran rekonon kaj sia ĝenerala rendimento, kaj la bazaj
  komandoj por administri la dosiersistemon. (paĝo 1235)

### la 2-an de Februaro 2018

- antaŭe legis kaj komprenis (finfine) plejparto de la klarigo de la RAID-a agordo (kaj la
  kontrastoj inter la diversaj specoj de RAID, kaj la plej ofte uzitaj specoj). La ŝubcapitro
  priparolis la ĉefajn avantaĝojn por uzi la RAID-an agordon, kaj, tio estas la ebla funkcia
  avantaĝo, tamen, la pli grava kialo, estas la redundo de la dataoj ene la diversaj diskoj. Kiam
  unu disko malsukcesas, plejofte, nur la, eble, rapida funkciado de la diskoj estas afekciita, la
  dataoj kiu estas ene la diversaj diskoj estas 'spegulita'. (paĝo 1213)

### la 1-an de Februaro 2018

- legu (kaj komprenu pli bone), plejparton da klarigon de la kontrasto inter krei 'Subdiskon' kaj
  trakti 'LVM' (ankaŭ legu kelke da kontrastoj inter la diversaj specoj de 'subdiskon' kaj la bazaj
  tavoloj de memora administrado)

### la 30-an de Januaro 2018

- lernis, ke la durdiska miso de niaj aparatoj estas neevitbla (kaj kiel oni pli bone interpretas la
  fidindecan precizigon de niaj durdiskoj), kaj se eĉ SSD pli rapidas ol HDD, ankoraŭ ekzistas la
  pli bona uzado de ĉi tiuj durdiskaj specoj. Ankaŭ lernis la diversaj specoj de la durdiska (aŭ
  aparata) interfaco (ĉefe priparolis la kontrastojn inter la rapidojn de la diversaj specoj). (paĝo
  1164)

### la 23-an de Januaro 2018

- legas nune pri la diversaj specoj de memoriloj, kaj la ĉapitroj ankaŭ priparolas pri la optima
  scenaro de uzado de la diversaj specoj (antaŭe, legis, ĉefe, pri HAProxy kaj sia funkcio kiam
  retŝarĝa ekvilibrigo)


Ĉapitro 19a: Retejgastigo
-------------------------

- priparolas pri la detaloj de retaplikaĵoj, precipe, la specifaj detaloj de HTTP (kaj sia historio,
  ekzemple, la devenoj de HTTP 1,0, 1,1, kaj 2,0) kaj HTTPS (TLS (kiu estas preskaŭ simila al SSL))

### la 22-an de Januaro 2018

- legis pri kelke da detaloj de la funkcioj kaj la diversaj specoj de kaŝmemoro, pri la alia funkcio
  de provizanto de nubaj servoj por funkcii kiam retnodo, kaj pri la agordoj de httpd kaj NGINX (1123)

### la 21-an de Januaro 2018

- legis pri kelke da historio de HTTP kaj HTTPS kaj kelke da ŝanĝoj ke okazis. Legis ankaŭ, precipe,
  pri la stako de retaplikaĵo (1098)


Ĉapitro 18a: Trudaĵo kaj Fiprogramaro
-------------------------------------

- priparolos pri la evoluo de retpoŝtaĵo en la antaŭaj jaroj (kaj ankaŭ priparolos pri la mekanismo
  de retpoŝtaĵoj)

### la 19-an de Januaro 2018

- legas nune pri la alia alternativo de sendmail krom Exim, kiu estas Postfix. (nune en paĝo 1069,
  kiu priparolos pri la alirrajto de Postfix)

### la 18-an de Januaro 2018

- priparolis, unue, ĉefe, pri la ĉefa agordo de Exim, tiam, nune priparolas, denove, pri la listo de
  alirrajlo de Exim kaj la signifo de ĝia detalado (de ekzemplo de la listo de alirrajlo) (1047)

### la 15-an de Januaro 2018

- legis ĝis paĝo 1028, subĉapitro 18,9, kiu estas pri Exim. Priparolis anstataŭe pri la aliaj
  funkcioj de sendmail.

### la 14-an de Januaro 2018

- legis pri la diversaj agordaj opcioj de /sendmail/, kaj la uzado de /m4/ por la agordaj dosieroj
  de /sendmail/ (1012)

### la 12-an de Januaro 2018

- legis ĉefe, pri la konceptoj, ke estas rilata al /Mail Transport Agent/, ekzemple, la plej uzita
  ekzemplo de /MTA/, kiu estas /Exim/ kaj /Postfix/ (996)

### la 11-an de Januaro 2018

- legis denove pri /PAM/, kaj nune legas pri la diversaj konsistegaĵoj de retpoŝtaĵo (legos sekve
  pri trudaĵo kaj fiprogramaro) (978)


Ĉapitro 17a: Ununuran Ensaluton
-------------------------------

- priparolos pri la du ĉefa koncepto de sekureco, kiu estas: idento kaj aŭtentigo

### la 9-an de Januaro 2018

- nune estas en paĝo 954; legu antaŭe pri /LDAP/ kaj la alternativo metodo kiu estas /Kerberos/

### la 8-an de Januaro 2018

- legu antaŭe pri la diversaj ĝustigaj metodoj, ke oni povas uzi por ripari la /BIND/ (935)


Ĉapitro 16a: La Domajnan Nomsistemon
------------------------------------

- priparolas pri la ĝenerala mekaniko de la domajna nomsistemo

### la 7-an de Januaro 2018

- legu ĝis paĝo 912, kiu priparolas pri la alia detalo pri /DNSSEC/

### la 5-an de Januaro 2018

- legu antaŭe pri la ekzemploj de la agordo de BIND. Nune legas pri la antaŭanto de /DNSSEC/ (897)

### la 4-an de Januaro 2018

- legu ĝis subĉapitro 16,8, kiu estas la agordaj ekzemploj de /BIND/. Antaŭe priparolis pri la
  daŭrigo de la diversaj deklaroj de la `named.conf` (paĝo 880)

### la 2-an de Januaro 2018

- priparolis pri la diversaj deklaroj ke la `named.conf` dosiero uzas

### la 31-an de Decembro 2017

- priparolis pri la diversaj specoj de registroj de la domajna nomsistemo

### la 29-an de Decembro 2017

- nune, la ĉapitro priparolas pri kelke da utilaĵo por serĉi la detalojn pri la domajna nomsistemo
  de la celaĵa retpaĝaro. (paĝo 837)

### la 28-an de Decembro 2017

- la nova ĉapitro ĉefe priparolas pri la ĉefa funkcio de la domajna nomsistemo kaj la procezo de por
  serĉi la interretan protokolon de nur la nomo de la reteja adreso (paĝo 818)


Ĉapitro 15a: Interretan Protokolan Enkursigon
---------------------------------------------

- priparolas pri la detaloj, de kiel la Interreto gvidas siajn paketojn

### la 26-an de Decembro 2017

- legis ĝis paĝo 793, pri /Border Gateway Protocol/, kaj antaŭe priparoli pri la diversaj enkursigaj
  protokoloj


Ĉapitro 14a: Fizikan Retkonektado
---------------------------------

- priparolas, ĉefe, pri la optima agordaĵo de nia fizika retkonektado

### la 22-an de Decembro 2017

- legu, ĝis paĝo 770, pri la kelke da bona kutimo pri la agordaĵo de la reto en la hejmo, aŭ en la
  oficejo

### la 21-an de Decembro 2017

- legu, ĝis paĝo 742. legu, antaŭe, pri 'Nuba komputado'


Ĉapitro 13a: _/TCP/IP Networking/_
----------------------------------

- priparolas pri, TCP/IP kiam la retkonektada sistemo de la Interreto

### la 19-an de Decembro 2017

- legu, ĝis paĝo 724, pri la priparolado de /VPC's/ (post la priparolado pri /IPFilters/)

### la 18-an de Decembro 2017

- legu ĝis, sube Subĉapitro 13,14: Fajroŝirmiloj kaj /NAT/, en paĝo 712

### la 17-an de Decembro 2017

- legu ĝis, sube sekcio 'Eĥosondo: ekzamenu, se la gastigo estas vivanta', en paĝo 699

### la 15-an de Decembro 2017

- legu ĝis, sube sekcio Subĉapitro 13,9: Baza Agordo de Retkarto, en paĝo 670

### la 14-an de Decembro 2017

- legu ĝis, sube sekcio _/Subĉapitro 13,5: Routing/_ en paĝo 651

### la 12-an de Decembro 2017

- sube sekcio _/Packets and Encapsulation/_ en paĝo 626


Ĉapitro 12a: _/Printing/_
-------------------------

- priparolas pri, la bagatelan taskon de presoj

### la 11-an de Decembro 2017

- sube sekcio _/12.2: CUPS Server Administration/_ en paĝo 603


Ĉapitro 11a: _/Drivers and the Kernel/_
---------------------------------------

- priparolas pri, la linuksa kerno kiel la abstraktada tavolo inter la aparataro kaj la programaro

### la 10-an de Decembro 2017

- sube sekcio _/11.8: Booting Alternate Kernels in the Cloud/_ en paĝo 585

### la 8-an de Decembro 2017

- sube sekcio _/Loadable kernel modules en Linukso/_ en paĝo 574

### la 7-an de Decembro 2017

- sube sekcio _/Tuning Linux Kernel Parameters/ en paĝo 562

### la 5-an de Decembro 2017

- sube sekcio _/Modern device file management/_ (paĝo 551)


Ĉapitro 10a: _/Logging/_
------------------------

- priparolas pri, la diversa metodo por protokolado de sistemunuaj agadoj

### la 4-an de Decembro 2017

- sube sekcio _/10.7 Logging Policies/_
  + antaŭe priparoli pri kiel la regado de protokoloj

### la 3-an de Decembro 2017

- sube sekcio _/Config file examples/_ de /Rsyslog/
  + antaŭe priparoli pri kiel /RainerScript/, kaj /Rsyslog legacy options, kaj ktp.

### la 28-an de Novembro 2017

- legis ULSAH ĝis paĝo 511
  + sube sekcio _/Rsyslog Architecture/_
  + antaŭe priparoli pri kiel manipuli la sistemajn protokolon


Ĉapitro 9a: _/Cloud Computing/_
-------------------------------

- priparolas pri, la uzado de interretaj sistemunuo kaj iliaj ekzemploj

### la 27-an de Novembro 2017

- legis ULSAH ĝis paĝo 491
  + sube sekcio _/DigitalOcean/_

### la 24-an de Novembro 2017

- legis, ULSAH ĝis paĝo 478
  + sube subsekcio _Networking_ de _Cloud Computing_


Ĉapitro 8a: _/User Management/_
-------------------------------

- priparolas pri, la mastrumado de uzantoj en la sistemo

### la 23-an de Novembro 2017

- legis, ULSAH ĝis deveno de paĝo 457
  + sube sekcio _Risk Reduction with PAM_

### la 21-an de Novembro 2017

- legis, ULSAH ĝis deveno de paĝo 446
  + sube sekcio _Configuring roles and administrative privileges_

### la 20-an de Novembro 2017

- legis, ULSAH ĝis deveno de paĝo 432
  + sube sekcio _8.2 The Linux /etc/shadow file_

### la 19-an de Novembro 2017

- legis, ULSAH ĝis deveno de paĝo 422
  + sube sekcio _8.1 Account Mechanics_
    * antaŭe priparolis Git kiam revizia mastrumado; pip kaj rvm


Ĉapitro 7a: _/Scripting and the Shell/_
---------------------------------------

- priparolas pri, la kreado de skriptoj por ripetaj taskoj

### la 17-an de Novembro 2017

- legis, ULSAH ĝis deveno de paĝo 398
  + sube sekcio _Ruby as a filter_
    * antaŭe priparolis antaŭparolo al Ruby programado

### la 16-an de Novembro 2017

- legis, ULSAH ĝis deveno de paĝo 387
  + sube sekcio _Loops_ (Python)

### la 14-an de Novembro 2017

- legis, ULSAH ĝis paĝo 368
  + Sekcio _7.2 Regular Expressions_
    * antaŭa paĝoj priparolis pri konsiletoj sur skriptan kreo

### la 13-an de Novembro 2017

- legis, ULSAH ĝis paĝo 355
  + Sekcio _From commands to scripts_ (komandinvito kiam reaga skripto programada medio)

### la 10-an de Novembro 2017

- legis, ULSAH ĝis paĝo 346
  + deveno de _Variables and quoting_

### la 9-an de Novembro 2017

- legis, ULSAH ĝis paĝo 329
  + deveno de _Chapter 7 Scripting and the Shell_


Ĉapitro 6a: _/Software Installation and Management/_
----------------------------------------------------

- priparolas pri, la generalan instalado kaj mastrumado de programadoj

### la 7-an de Novembro 2017

- legis, ULSAH ĝis paĝo 303
  + deveno de Sekcio _6.3 Linux Package Management Systems_

### la 6-an de Novembro 2017

- legis, ULSAH ĝis paĝo 287
  + deveno de _Chapter 6 Software Installation and Management_


Ĉapitro 5a: _/The Filesystem/_
------------------------------

- priparolas pri, ke la celumo de la dosiersistemo estas pri la traktado de risurcoj de la
  konservospaco de la sistemo

### la 5-an de Novembro 2017

- legis, ULSAH ĝis paĝo 274
  + ĝis _Linux ACL support_ (discussed about permission changing commands and friends)

### la 3-an de Novembro 2017

- legis ULSAH ĝis paĝo 262
  + ĝis _ls: list and inspect files_

### la 2-an de Novembro 2017

- legis, ULSAH ĝis paĝo 246
  + ĝis _Table 5.1: Standard directories and their contents_


Ĉapitro 4a: _/Process Control/_
-------------------------------

- priparolos pri, kio okazas al procezoj post la kulisoj

### la 31-an de Oktobro 2017

- legis, ULSAH ĝis paĝo 236
  + priparolis, pri kiel enhorarigi instrukciojn per /crontab/ agordoj kaj /systemd/ horloĝo

### la 30-an de Oktobro 2017

- legis, ULSAH ĝis paĝo 228
  + priparolante pri _The format of crontab files_

### la 29-an de Oktobro 2017

- legis, ULSAH ĝis paĝo 209
  + _kill: send signals_ sekcio

### la 27-an de Oktobro 2017

- legis ULSAH ĝis paĝo 199
  + _PID: process ID number_ sekcio
  + priparolis, diversajn atingokontrolajn skemojn 


Ĉapitro 3a: _/Access Control and Rootly Powers/_
------------------------------------------------

- priparolas pri, kiel la kerno traktas decidojn ke estas rilata al sekurigo

### la 26-an de Oktobro 2017

- legis, ULSAH ĝis paĝo 178
  + _Disabling the root account_ sekcio

### la 17-an de Oktobro 2017

- legis, ULSAH ĝis paĝo 172 de 1885
  + _sudo: limited su_ sekcio


Ĉapitro 2a: _/Booting and System Management Daemons/_
-----------------------------------------------------

- priparolas pri la procezo de prasarĝo

### la 16-an de Oktobro 2017

- legis, ULSAH ĝis paĝo 150 de 1885
  + legis, ĝis deveno de _2.9 Reboot and Shutdown Procedures_

### la 13-an de Oktobro 2017

- legis, ULSAH ĝis paĝo 144 de 1885
  + legis, ĝis deveno _Local services and customizations_

### la 12-an de Oktobro 2017

- legis, ĝis paĝo 125 de 1885 de Linuksa libro

### la 10-an de Oktobro 2017

- legis, ĝis paĝo 117 de Linuksa libro

### la 6-an de Oktobro 2017

- legis, ĝis paĝo 111 de 1885 de Linuksa libro


Ĉapitro 1a: _/Where to Start/_
------------------------------

- priparolas pri la antaŭparolo pri sistemadministrado

### la 5-an de Oktobro 2017

- legis, ĝis paĝo 82 de 1885 de Linuksa libro (konferencoj ke estas rilata al sistemadministrado)


Komandoj
--------

- la sekvontaj komandoj estas komandoj ke mi ne antaŭe sciis:

- `efibootmgr`
  + modifiku praŝargan sinsekvon (sur subtenata aparato)
  + -o modifikas la praŝargan sinsekvon ke estas bazi sur la argumentoj, respektive

- `gpart show/mount`
  + ekzamenu praŝargan subdiskon

- `boot0cfg`
  + modifiku MBR praŝargordagordo

- `mount -t msdos`
  + vidu ene ESP

- `sudo dd if=/boot/boot1.efifat of=/dev/ada0p1`
  + rekreu ESP subdiskon

- `ps`
  + raportu ekrankopio de la nunaj procezoj

- `systemctl`
  + esploru staton de /systemd/ 
  + ne argumentoj = `list-units`; elmontras ĉia sarĝita aktiva servoj, kontaktoskatoloj, celoj, surmetoj, kaj
    aparatoj
  + `--type-service` ŝarĝu nur la ŝargitajn kaj aktivajn servoj
  + `list-unit-files`; elmontru instalitajn unuajn dosierojn ĉu, au ĉu ne, la unua dosiero estas aktiva
  + `cat 'name'.service`; elmontru enhavojn de unua dosiero
  + `list-timers`; listigu horloĝojn de systemd

- `journalctl`
  + display system logs (kernel and service messages)
  + --list-boots; obtain list of prior boots
  + -b; access messages from prior boot using its index or its long-form ID
  + -u “insert unit here”; restrict logs to specified unit

- `fdisk`
  + manipulate disk partition table
  + -l; display partitions and exit

- `fsck`
  + check and repair a linux filesystem

- `visudo`
  + edit sudoers file then check its integrity

- `scp`
  + remote file copy that uses ssh

- `man capabilities`
  + check linux capabilities (permissions)

- `kill <type of signal> <pid>`
  + send a type of signal to provided pid (if type of signal is not provided, sends default TERM)
  + killall, however, kills process by the name

- `nice <value>`
  + run a program at given value (scheduling priority)
  + renice, on the other hand, readjusts given “nice” value

- `strace`
  + display process’ system calls and the signals it receives

- `df`
  + display file system disk udage

- `crontab`
  + -e tag created crontab config. for current user, -r removes it, -l lists contents

- `fuser _mountpoint_`
  + prints processes (pids) of _mountpoint_
  + -v tag produces human

- `lsof`
  + fuser alternative; lists open files

- `man hier`
  + shows manual page of general guidelines of the layout of a filesystem

- `file _argument_`
  + determine file type of given _argument_

- `man ascii`
  + shows table of control characters and their octal equivalents

- `getfacl`; `setfacl`
  + get file’s access control list; set file’s access control list

- (rhel) `rpm`
  + install, verify, query package status

- `dpkg`
  + debian package manager

- (freebsd) `pkg`
  + freebsd package manager
  + pkg help for a qrg on subcommands

- (freebsd) `portsnap`
  + akiru kaj ekstraktu densigan ekrankopion de la `ports tree` 
  + `make deinstall` por malinstali software installed through the ports system (in appropriate
    directory)
  + `portmaster` port update alternative

- `chsh`
  + modifiku salutan ŝelon

- `cut`
  + !!!
  + eligu la selektigitan dividaĵon de viĉoj el `FILE` al `stdout`

- `sort`
  + !!!
  + eligu la ordigitan version de `FILE` al `stdout`

- `uniq`
  + !!!
  + simile al `sort -u`, sed kun aldona `-c`, `-d`, and `-u`

- `wc`
  + kalkuli la nombron de viĉoj, vortoj, kaj signoj, en dosiero, respektive

- `tee`
  + !!!
  + duplikatu enigo al du lokoj, `stdout` kaj la dosiero

- `head`
  + eligu la unuan 10 viĉojn de la dosiero

- `tail`
  + eligu la lastan 10 viĉojn de la dosiero

- `grep`
  + eligu la vicojn ke svatas la modelon

- (rhel) `authconfig`
  + agordu pasvortan algoritmon

- `chfn`
  + modifiku la `GECOS` informadon de la uzanto 

- `pwconv`
  + bilancu la enhavojn de `shadow` dosiero kaj `passwd` dosiero

- `vipw`
  + modifiku la pasvortan dosieron

- `groupadd`, `groupmod`, `groupdel`
  + (as the names suggest)

- `vigr`
  + `vipw`, sed por `/etc/group`

- `mknod`
  + komdo por kreante la aparataraj dosieroj

- `udevadm`
  + informmendas informadoj pri la aparataraj, lanĉas eventojn, regas la /udevd/ procezon, kaj
    finfine, subaŭskultas la /udev/ kaj la kernajn okazojn.

- `lsusb`
  + enlistigu USB aparaton

- `dmesg`
  + eligu aŭ regu la kernan /ring/ bufron

- `lsmod`
  + eksponu la staton de la moduloj de la Linuksa Kerno

- `modprobe`
  + aldonu kaj viŝu la modulo el la Linuksan kernon

- `kldstat` (freebsd)
  + eksponu la staton de ĉia nune ŝarĝitaj moduloj

- `lpstat`
  + printu /cups/ statmesaĝon

- `lpoptions`
  + montru aŭ agordu, printilan agordojn

- `lpinfo`
  + enlistigu disponatan pelilon aŭ aparaton

- `lpadmin`
  + agordu /cups/ printilojn kaj klasojn

- `cupsdisable` kaj `cupsenable`
  + kontrolu la elejan flanketon de la atendvico

- `reject` kaj `accept`
  + kontrolu la enirejan flanketon de la atendvico

- `ipcalc`
  + montru detalojn pri IP-adreso

- `ip route show` aŭ `netstat -r` (por FreeBSD)
  + montru la enkursigan tabelon de la komputilo

- `ip neight`
  + ekzamenu kaj manipulu la kaŝmemoron ke estas kreita de /ARP/ kaj /ND/, aldonu aŭ forprenu
    elementojn, kaj elbufrigu aŭ presu la tablojn.

- `arp` kaj `ndp` (en FreeBSD)
  + manipulu la /ARP/ kaŝmemoron kaj atingu /NDP kaŝmemoron, respektive

- `ethtool`
  + serĉmendu aŭ regu retaĵan pelilon kaj aparatarajn agordojn

- `ssh acme-gw.acme.com`
  + por aliri la agordo de /Cisco/ enkursigilo (ne privilegia aliro)
  + ene, tajpu `enable` por aliri la 'privilegian' aliron.


Miksaĵo
-------

- grub.cfg in /boot/grub (generate with grub2-mkconfig for Red Hat and CentOS; update-grub for
  Debian and Ubuntu)

- grub-mkconfig configuration in etc/default/grub; run grub.cfg configurators after editing.

- edit /etc/grub.d/40_custom to change kernel listings in boot menu, set boot password, or change
  boot menu items’ names. run grub.cfg configurators after editing

- type c at grub boot screen to enter cmd mode

- edit _GRUB CMDLINE LINUX_ to make changes persistent

- GRUB = FreeBSD loader

- init; makes sure system runs right services and daemons

- /var/log/auth.log; debian-based, ubuntu’s sudo log location. /var/log/secure; redhat-based

- cron (command scheduler)
  + configuration syntax: _minute hour DayOfMonth MonthOfYear weekday (0 = Sunday)_
  + /etc/crontab (system-wide crontab)
  + /etc/cron.d determines which software packages can install crontab entries

- check `man systemd.time` for details on systemd timers

- apt-mirror
  + create shadow version of sources.list in /etc/apt; default is /var/spool/apt-mirror

- yum
  + Yellowdog Updater, Modified

- (freebsd) the real password file is located in /etc/master.passwd (readable only by root); 

- (freebsd) run `cap_mkdb /etc/login.conf` after editing the file to compile changes into the hashed
  version

