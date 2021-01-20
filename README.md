
## sebolt.us "the adventurer" [🔩🔩](xn--8v8ha.ws)

- servi.us (servius.me) [📚📚](xn--zt8ha.ws) (with user data)
  - servos repo
  - current state, project doc editor with toolbox *mattdown.com*
  - personal tactician with ai editor?
  - strack studios

## Contact information

Located at [19500 130th AV NE, 98072](https://citresidentialservicing.myloancare.com/app/index.html#/Dashboard) in [Woodinville](https://www.ci.woodinville.wa.us/) ([Bothell](http://www.ci.bothell.wa.us/)) of [King County](https://www.kingcounty.gov/) to **Craigslist** [property](https://www.craigslist.com) on [**Ziply**](https://ziplyfiber.com/login) *bonded?*

For registration, see [corp](https://ccfs.sos.wa.gov/#/Dashboard), [license](https://secure.dor.wa.gov/), [copyright](https://eco.copyright.gov/eService_enu/start.swe?SWECmd=Login&SWEPL=1&SRN=&SWETS=1584673446735) [patent/trademark](https://www.uspto.gov/)

For news, see [CSPAN](https://www.c-span.org/), [BBC](http://feeds.bbci.co.uk/news/rss.xml), [Gutenberg](http://www.gutenberg.org/wiki/Main_Page), [Wikipedia](http://www.wikipedia.org/wiki/Special:Random)

## domain listings

*all domains listed below for sale, contact for more information*

### United States Land Grab of .us domains

abder.us - achomawi.us - antiloch.us- apalachicola.us - arecibo.us - arikara.us - atchafalaya.us - baranof.us - blackfeet.us - brasstownbald.us - brazoria.us - bunkerhill.us - cahokia.us - cather.us - cheaha.us - chequamegon.us - chiricahua.us - colville.us - congaree.us - croatan.us - escanaba.us - esselen.us - fakahatchee.us - faneuil.us - frissell.us - guayama.us - halelea.us - hidatsa.us - humacao.us - isleroyale.us - jerimoth.us - kabetogama.us - kahikinui.us - kalapana.us - kapapala.us - kipahoehoe.us - kisatchie.us - kobuk.us - koochiching.us - koolau.us - kootenai.us - lospadres.us - mackinac.us - malheur.us - mandan.us - maxhamish.us - missouria.us - moloaa.us - monongahela.us - moshannon.us - mukilteo.us - myakka.us - nantahala.us - nelchina.us - noatak.us - ossabaw.us - otoe.us - patos.us - pawnee.us - payette.us - plumas.us - richloam.us - samish.us - sapelo.us - shuksan.us - sixrivers.us - skymeadows.us - sproul.us - standingrock.us - stanislaus.us - susquehannock.us - talladega.us - tateshell.us - taumsauk.us - thunderbasin.us - timucuan.us - umpqua.us - unalaska.us - uncompahgre.us - uwharrie.us - voyageurs.us - waikoloa.us - wailua.us - wakeforest.us - whitebutte.us - whiteearth.us - whiteriver.us - witchita.us - yunque.us

### India land grab of .in

bhander.in - bhimgad.in - brahmagiri.in - chandoli.in - cotigao.in - gangokri.in - kotgarh.in - langtang.in - nanj.in - palpur.in - paracut.in - shoolpaneshwar.in - yawal.in

### Canadian land grab of .ca

aulavik.ca - kabetogama.ca - nopiming.ca - pukaskwa.ca

### Famous authors 

angelou.us - hurston.us - pynchon.us - salinger.us 

### Pairs of emoji

🙂🙂.ws - 🧦🧦.ws - 🧤🧤.ws - 👣👣.ws - [🌳🌳](xn--wh8ha.ws) with treeop.com - 👖👖.ws - 👓👓.ws - [⛓⛓](xn--l9ha.ws) with boxcha.in - [📮📮](xn--ku8ha.ws) with boxb.in - *gears?* - 🏳🏳 🏴🏴 🏳🏴 🏴🏳

### Other

bitstat.us - localstat.us - padp.in - projectb.in - projectp.in - slat.in - sloeg.in - statemap.us - tipt.in - victoryg.in - blockb.in - boltb.in - boxt.in - breadb.in - copco.in and cupco.in - tactician.us - mant.us

## Reference

- [GitHub star](https://github.com/bitmaus)
- [Microsoft, Aquent programmer writer](https://github.com/msebolt/) with Erwin McDaniel
- [RegExp online](https://regexr.com/)
- [icons](https://material.io/resources/icons/?style=baseline)

# strack
product, power tray/stick, color/size, in sealed box/bag, add slide tray, grid, power stick, stackable

order (seals, box/bag with logo, sticker, collector's business cards, toy) (version/OR/etc.) to ship...

https://www.usps.com/business/web-tools-apis/documentation-updates.htm

https://www.alibaba.com

## How to install servOS

*This process requires a BIOS that can boot from USB. Enter BIOS settings by pressing ESC, DEL, and/or a particular Function key on boot.*

1. Download [Arch Linux](https://www.archlinux.org/download) and use `dd` to image an USB.

   ```
   wget...
   dd if=arch_linux.iso of=/dev/sda status=progress
   ```

1. Boot to the USB and run the script.

   ```
   #iwctl --passphrase passphrase station device connect SSID #optional, for wireless
   pacman -Sy --noconfirm git
   git clone https://github.com/seboltus/servius
   chmod +x servius/servos/install.sh
   servius/servos/install.sh new
   ```

## How to install servius

Configure domains using **Google** [domain](https://domains.google.com), **Dynu** [email](https://www.dynu.com), and **GoDaddy** [emain](https://dcc.godaddy.com/domains/?isc=cjc1off30) *name.com? Tucows.com?*

Setup router with the following ports:

|Port|Function|
|-|-|
|80|http|
|443|https|
|2525|mail|
|587|tls|

Install certs using: (also configure haproxy)
```
certbot certonly --standalone -d ${site}, cp -r /etc/letsencrypt/live/${site} data/${site}
sudo -E bash -c 'cat /etc/letsencrypt/live/$DOMAIN/fullchain.pem /etc/letsencrypt/live/$DOMAIN/privkey.pem > /etc/haproxy/certs/$DOMAIN.pem'
```

Build a strack unit, attach an M.2 drive (enclosure) and run `servius/servos/install.sh old`. Deploy unit.

Go to site and setup user/password. Repeat build strack units for each additional and use add IP function.

### Additional commands

```
fdisk -l #show drives
df, ls -a, du -xhS | sort -h | tail -n15 #show file/folder info
lscpu #show hardware info
grep -R "term" #search

ip addr show #show network connections
ping google.com -c 2 #test network
```
