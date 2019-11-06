# DNS list table to apply in DNS66 and related apps

| Provider | Support | Features | Logging | First IP | Second IP \* |
|----------|---------|----------|---------|----------|--------------|
| **Ads\/Tracking Block** |  |  |  |  |  |
| [BlahDNS](https://github.com/ookangzheng/blahdns) | :lock: [:lock_with_ink_pen:](https://doh-jp.blahdns.com/dns-query) | :closed_lock_with_key: :six: :no_pedestrians: :fire: | :negative_squared_cross_mark: | `108.61.201.119` | `[2001:19f0:7001:1ded:5400:01ff:fe90:945b]` |
| [DNSWarden](https://github.com/bhanupratapys/dnswarden) AdBlock | :computer: :lock: [:lock_with_ink_pen:](https://doh.dnswarden.com/adblock) | :closed_lock_with_key: :no_pedestrians: | [:negative_squared_cross_mark:](https://github.com/bhanupratapys/dnswarden#privacy-policy-and-tc) | `116.203.35.255:53` | `116.203.70.156:53` |
| [SecureDNS](https://securedns.eu) | :lock: [:lock_with_ink_pen:](https://ads-doh.securedns.eu/dns-query)[²](https://doh.securedns.eu/dns-query) | :closed_lock_with_key: :six: :no_pedestrians: | :negative_squared_cross_mark: | `146.185.167.43` | `[2a03:b0c0:0:1010::e9a:3001]` |
| [Tiarap](https://doh.tiar.app) | :computer: :lock: [:lock_with_ink_pen:](https://doh.tiar.app/dns-query) | :six: :no_pedestrians: | :negative_squared_cross_mark: | `174.138.21.128` | `2400:6180:0:d0::5f6e:4001` |
| [keweon](https://forum.xda-developers.com/showpost.php?p=73985083) [Physical](https://reinstall.keweon.center) | :computer: :lock: [:lock_with_ink_pen:](https://doh.asecdns.com/dns-query)[²](https://doh.asecdns.com/nebulo)[³](https://dns.keweon.center/nebulo) | :closed_lock_with_key: :no_pedestrians: :fire: | :negative_squared_cross_mark: | `176.9.62.58` | `176.9.62.62` |
| [keweon](https://forum.xda-developers.com/showpost.php?p=73985083) [Physical](https://reinstall.keweon.center) IPv6 | :computer: :lock: [:lock_with_ink_pen:](https://doh.asecdns.com/dns-query)[²](https://doh.asecdns.com/nebulo)[³](https://dns.keweon.center/nebulo) | :closed_lock_with_key: :six: :no_pedestrians: :fire: | :negative_squared_cross_mark: | `2a01:4f8:150:8023::58` | `2a01:4f8:150:8023::62` |
| [DNSWarden](https://github.com/bhanupratapys/dnswarden) IPv6 AdBlock | :computer: :lock: [:lock_with_ink_pen:](https://doh.dnswarden.com/adblock) | :closed_lock_with_key: :six: :no_pedestrians: | [:negative_squared_cross_mark:](https://github.com/bhanupratapys/dnswarden#privacy-policy-and-tc) | `[2a01:4f8:1c1c:75b4::1]:53` | `[2a01:4f8:1c1c:5e77::1]:53` |
|  |  |  |  |  |  |
| **Anti-Censorship** \* |  |  |  |  |  |
| [dns.watch](https://dns.watch) | :lock: | :closed_lock_with_key: | [:negative_squared_cross_mark:](https://dns.watch/why)\* | `84.200.69.80` | `84.200.70.40` |
| [Digital Courage](https://digitalcourage.de/support/zensurfreier-dns-server) | :lock: | :six: |  | `85.214.20.141` | `[2a01:238:42f6:ac00:2a29:4f7f:b6d:ef46]` |
| [DNSWarden](https://github.com/bhanupratapys/dnswarden) Uncensored | :computer: :lock: [:lock_with_ink_pen:](https://doh.dnswarden.com/uncensored) | :closed_lock_with_key: :six: | [:negative_squared_cross_mark:](https://github.com/bhanupratapys/dnswarden#privacy-policy-and-tc) | `116.203.35.255:5353` | `116.203.70.156:5353` |
| [AS250](https://twitter.com/as250) | :computer: |  |  | `194.150.168.168` |  |
| [Chaos Computer Club](https://www.ccc.de/censorship/dns-howto) | :computer: |  |  | `195.54.164.39` |  |
| [CCC ClaraNet](https://www.ccc.de/censorship/dns-howto) | :computer: |  |  | `212.82.225.7` | `212.82.226.212` |
| [dns.watch](https://dns.watch) IPv6 | :computer: | :closed_lock_with_key: :six: | [:negative_squared_cross_mark:](https://dns.watch/why)\* | `[2001:1608:10:25::1c04:b12f]` | `[2001:1608:10:25::9249:d69b]` |
| [DNSWarden](https://github.com/bhanupratapys/dnswarden) IPv6 Uncensored | :computer: :lock: [:lock_with_ink_pen:](https://doh.dnswarden.com/uncensored) | :closed_lock_with_key: :six: :no_pedestrians: | [:negative_squared_cross_mark:](https://github.com/bhanupratapys/dnswarden#privacy-policy-and-tc) | `[2a01:4f8:1c1c:75b4::1]:5353` | `[2a01:4f8:1c1c:5e77::1]:5353` |
| [OpenNIC](https://www.opennic.org) |  |  |  | [View Tier 1](https://servers.opennic.org/?tier=1) | [View Tier 2](https://servers.opennic.org/?tier=2) |
|  |  |  |  |  |  |
| **Non-logging only** |  |  |  |  |  |
| [Foundation of Applied Privacy](https://appliedprivacy.net/services/dns) | :lock: [:lock_with_ink_pen:](https://doh.appliedprivacy.net/query) | :closed_lock_with_key: :six: | [:negative_squared_cross_mark:](https://appliedprivacy.net/privacy-policy) | `37.252.185.232` | `[2a00:63c1:a:229::3]` |
|  |  |  |  |  |  |
| **TLS** |  |  |  |  |  |
| [BlahDNS 🇯🇵](https://github.com/ookangzheng/blahdns) | :lock: [:lock_with_ink_pen:](https://doh-jp.blahdns.com/dns-query) | :closed_lock_with_key: :no_pedestrians: :fire: | :negative_squared_cross_mark: | `108.61.201.119` | TLS:`dot-jp.blahdns.com` |
| [BlahDNS 🇩🇪](https://github.com/ookangzheng/blahdns/#server-information) | :lock: [:lock_with_ink_pen:](https://doh-de.blahdns.com/dns-query) | :closed_lock_with_key: :six: :no_pedestrians: :fire: | :negative_squared_cross_mark: | `159.69.198.101` | TLS:`dot-de.blahdns.com` |
| [BlahDNS 🇨🇭](https://github.com/ookangzheng/blahdns/#server-information) | :lock: [:lock_with_ink_pen:](https://doh-ch.blahdns.com/dns-query) | :closed_lock_with_key: :six: :no_pedestrians: :fire: | :negative_squared_cross_mark: | `[2a0a:e5c0:2:2:0:c8ff:fe68:bf48]` | TLS:`dot-ch.blahdns.com` |
| [SecureDNS](https://securedns.eu) | :lock: [:lock_with_ink_pen:](https://ads-doh.securedns.eu/dns-query)[²](https://doh.securedns.eu/dns-query) | :closed_lock_with_key: | :negative_squared_cross_mark: | TLS:`ads-dot.securedns.eu` | TLS²:`dot.securedns.eu` |
| [keweon aSecDNS](https://forum.xda-developers.com/showpost.php?p=73985083) | :computer: :lock: [:lock_with_ink_pen:](https://doh.asecdns.com/nebulo) | :no_pedestrians: :fire: |  | [View server lists](https://forum.xda-developers.com/showpost.php?p=73985083&postcount=6) | TLS:`dot.asecdns.com` |
|  |  |  |  |  |  |
| **Other** |  |  |  |  |  |
| [Captain Nemo](https://captnemo.in/doh) | [:lock_with_ink_pen:](https://doh.captnemo.in/dns-query) |  | [:person_with_pouting_face: :watch:](https://captnemo.in/dns/privacy) (1h) | `139.59.48.222` |  |
| [NekoMimiRouter](https://dns-over-https.com) | [:lock_with_ink_pen:](https://dns.dns-over-https.com/dns-query) |  | [:person_with_pouting_face: :watch:](https://dns-over-https.com/privacy) (?) | `[2001:470:f324:0:45:77:124:64]` |  |
|  |  |  |  |  |  |
| **Regional** |  |  |  |  |  |
| [keweon 🇺🇸 (Silicon Valley)](https://forum.xda-developers.com/showpost.php?p=73985083&postcount=6) | :computer: | :six: :no_pedestrians: :fire: | :negative_squared_cross_mark: | `45.32.140.26` | `[2001:19f0:ac01:639::26]` |
| [keweon 🇬🇧](https://forum.xda-developers.com/showpost.php?p=73985083&postcount=6) | :computer: | :six: :no_pedestrians: :fire: | :negative_squared_cross_mark: | `45.32.183.39` | `[2001:19f0:7402:a61::39]` |
| [keweon 🇺🇸 (Dallas)](https://forum.xda-developers.com/showpost.php?p=73985083&postcount=6) | :computer: | :six: :no_pedestrians: :fire: | :negative_squared_cross_mark: | `45.76.57.41` | `[2001:19f0:6401:9ed::41]` |
| [keweon 🇦🇺](https://forum.xda-developers.com/showpost.php?p=73985083&postcount=6) | :computer: | :six: :no_pedestrians: :fire: | :negative_squared_cross_mark: | `45.76.125.130` | `[2001:19f0:5801:b45::130]` |
| [keweon 🇸🇬](https://forum.xda-developers.com/showpost.php?p=73985083&postcount=6) | :computer: | :six: :no_pedestrians: :fire: | :negative_squared_cross_mark: | `45.76.151.221` | `[2001:19f0:4400:4f31::221]` |
| [keweon 🇯🇵](https://forum.xda-developers.com/showpost.php?p=73985083&postcount=6) | :computer: | :six: :no_pedestrians: :fire: | :negative_squared_cross_mark: | `45.77.25.72` | `[2001:19f0:7001:22a8::72]` |
| [keweon 🇫🇷](https://forum.xda-developers.com/showpost.php?p=73985083&postcount=6) | :computer: | :six: :no_pedestrians: :fire: | :negative_squared_cross_mark: | `45.77.62.37` | `[2001:19f0:6801:95e::37]` |
| [keweon 🇳🇱](https://forum.xda-developers.com/showpost.php?p=73985083&postcount=6) | :computer: | :six: :no_pedestrians: :fire: | :negative_squared_cross_mark: | `45.77.138.206` | `[2001:19f0:5001:d8d::206]` |
| [keweon 🇺🇸 (New Jersey)](https://forum.xda-developers.com/showpost.php?p=73985083&postcount=6) | :computer: | :six: :no_pedestrians: :fire: | :negative_squared_cross_mark: | `45.77.144.132` | `[2001:19f0:5:2962::132]` |
| [Public PiHole 🇳🇱](https://public-pihole.com) | :computer: | :closed_lock_with_key: |  | `51.158.168.202` |  |
| [Public PiHole 🇨🇦](https://public-pihole.com) | :computer: | :closed_lock_with_key: |  | `54.39.97.51` |  |
| [keweon 🇩🇪 (Frankfurt)](https://forum.xda-developers.com/showpost.php?p=73985083&postcount=6) | :computer: | :six: :no_pedestrians: :fire: | :negative_squared_cross_mark: | `104.207.131.11` | `[2001:19f0:6c01:61f::11]` |
| [keweon 🇮🇳](https://forum.xda-developers.com/showpost.php?p=73985083&postcount=6) | :computer: | :six: :no_pedestrians: :fire: | :negative_squared_cross_mark: | `139.59.33.236` | `[2400:6180:100:d0::30d:5001]` |
| [Public PiHole 🇸🇬](https://public-pihole.com) | :computer: | :closed_lock_with_key: |  | `139.99.74.182` |  |
| [BlahDNS 🇩🇪](https://github.com/ookangzheng/blahdns/#server-information) | :lock: [:lock_with_ink_pen:](https://doh-de.blahdns.com/dns-query) | :closed_lock_with_key: :six: :no_pedestrians: :fire: | :negative_squared_cross_mark: | `159.69.198.101` | `[2a01:4f8:1c1c:6b4b::1]` |
| [Antoine Aflalo 🇺🇸](https://www.aaflalo.me/2019/01/dns-over-https-server-aaflalo-me) | :lock: [:lock_with_ink_pen:](https://dns-nyc.aaflalo.me/dns-query) | :closed_lock_with_key: :no_pedestrians: |  | `168.235.81.167` | TLS:`dns-nyc.aaflalo.me:853` |
| [Public PiHole 🇫🇷](https://public-pihole.com) | :computer: | :closed_lock_with_key: |  | `163.172.170.19` |  |
| [Tiarap 🇯🇵](https://jp.tiar.app) | :computer: :lock: [:lock_with_ink_pen:](https://jp.tiar.app/dns-query) | :six: | :negative_squared_cross_mark: | `172.104.93.80` | `[2400:8902::f03c:91ff:feda:c514]` |
| [Antoine Aflalo 🇨🇭](https://www.aaflalo.me/2019/01/dns-over-https-server-aaflalo-me) | :lock: [:lock_with_ink_pen:](https://dns.aaflalo.me/dns-query) | :closed_lock_with_key: :no_pedestrians: |  | `176.56.236.175` | TLS:`dns.aaflalo.me:853` |
|  |  |  |  |  |  |
| **Run by corporate** |  |  |  |  |  |
| [CloudFlare + APNIC](https://1.1.1.1) | :computer: :lock: [:lock_with_ink_pen:](https://cloudflare-dns.com/dns-query)[²](https://mozilla.cloudflare-dns.com/dns-query) |  | [:bust_in_silhouette: :watch:](https://developers.cloudflare.com/1.1.1.1/commitment-to-privacy/privacy-policy/privacy-policy) | `1.0.0.1` | `1.1.1.1` |
| [~~Google~~](https://developers.google.com/speed/public-dns) | :computer: :lock: [:lock_with_ink_pen:](https://dns.google/dns-query)[²](https://dns.google.com/dns-query) |  | [:person_with_pouting_face: :alarm_clock:](https://developers.google.com/speed/public-dns/privacy) | ~~`8.8.4.4`~~ | ~~`8.8.8.8`~~ |
| [Comodo Dome Shield](https://www.comodo.com/secure-dns) | :computer: | :twisted_rightwards_arrows: |  | `8.20.247.10` | `8.26.56.10` |
| [Comodo Secure](https://www.comodo.com/secure-dns) | :computer: |:twisted_rightwards_arrows: |  | `8.20.247.20` | `8.26.56.26` |
| [Quad9](https://quad9.net) | :computer: [:lock_with_ink_pen:](https://dns9.quad9.net/dns-query) | :closed_lock_with_key: :fire: | [:bust_in_silhouette:](https://quad9.net/privacy) | `9.9.9.9` | `149.112.112.9` |
| [Quad9²](https://quad9.net/doh-quad9-dns-servers) | :computer: [:lock_with_ink_pen:](https://dns.quad9.net/dns-query) | :closed_lock_with_key: :fire: | [:bust_in_silhouette:](https://quad9.net/privacy) | `9.9.9.9` | `149.112.112.112` |
| [Quad9 HTTP](https://quad9.net/doh-quad9-dns-servers) | :computer: [:lock_with_ink_pen:](https://dns10.quad9.net/dns-query) |  | [:bust_in_silhouette:](https://quad9.net/privacy) | `9.9.9.10` | `149.112.112.110` |
| [Quad9 CDN](https://quad9.net/doh-quad9-dns-servers) | :computer: [:lock_with_ink_pen:](https://dns11.quad9.net/dns-query) |  | [:bust_in_silhouette:](https://quad9.net/privacy) | `9.9.9.11` | `149.112.112.11` |
| [Yandex](https://dns.yandex.com) | :computer: |  |  | `77.88.8.1` | `77.88.8.8` |
| [Yandex Safe](https://dns.yandex.com) | :computer: | :fire: |  | `77.88.8.2` | `77.88.8.88` |
| [Yandex Family](https://dns.yandex.com) | :computer: | :fire: :children_crossing: |  | `77.88.8.3` | `77.88.8.7` |
| [AdGuard](https://adguard.com/en/adguard-dns/overview.html) | :computer: :lock: [:lock_with_ink_pen:](https://dns.adguard.com/dns-query) | :closed_lock_with_key: :no_pedestrians: | [:person_with_pouting_face:](https://adguard.com/en/privacy/dns.html) | `176.103.130.130` | `176.103.130.131` |
| [AdGuard Family](https://adguard.com/en/adguard-dns/overview.html) | :computer: :lock: [:lock_with_ink_pen:](https://dns-family.adguard.com/dns-query) | :closed_lock_with_key: :no_pedestrians: :children_crossing: | [:person_with_pouting_face:](https://adguard.com/en/privacy/dns.html) | `176.103.130.132` | `176.103.130.134` |
| [dns.sb](https://dns.sb) | :computer: :lock: [:lock_with_ink_pen:](https://doh.dns.sb/dns-query) | :closed_lock_with_key: | [:negative_squared_cross_mark:](https://dns.sb/privacy)\* | `185.184.222.222` | `185.222.222.222` |
| [CleanBrowsing Security](https://cleanbrowsing.org/filters) | :computer: :lock: [:lock_with_ink_pen:](https://doh.cleanbrowsing.org/doh/security-filter) | :closed_lock_with_key: :fire: |  | `185.228.168.9` | `185.228.169.9` |
| [CleanBrowsing Adult](https://cleanbrowsing.org/filters) | :computer: :lock: [:lock_with_ink_pen:](https://doh.cleanbrowsing.org/doh/adult-filter) | :closed_lock_with_key: :children_crossing: :fire: |  | `185.228.168.10` | `185.228.169.10` |
| [CleanBrowsing Family](https://cleanbrowsing.org/filters) | :computer: :lock: [:lock_with_ink_pen:](https://doh.cleanbrowsing.org/doh/family-filter) | :closed_lock_with_key: :children_crossing: :fire: |  | `185.228.168.168` | `185.228.169.168` |
| [OpenDNS Family](https://www.opendns.com/setupguide/#familyshield) | :computer: [:lock_with_ink_pen:](https://doh.familyshield.opendns.com/dns-query) | :closed_lock_with_key: :twisted_rightwards_arrows: :children_crossing: |  | `208.67.220.123` | `208.67.222.123` |
| [OpenDNS](https://www.opendns.com) | :computer: [:lock_with_ink_pen:](https://doh.opendns.com/dns-query) | :closed_lock_with_key: :twisted_rightwards_arrows: |  | `208.67.220.220` | `208.67.222.222` |
| [Oracle DynDNS](https://dyn.com/labs/dyn-internet-guide) | :computer: |  | [:question:](https://dyn.com/legal/dyn-privacy-policy) | `216.146.35.35` | `216.146.36.36` |
| [CloudFlare + APNIC](https://1.1.1.1) IPv6 | :computer: :lock: [:lock_with_ink_pen:](https://cloudflare-dns.com/dns-query) | :six: | [:bust_in_silhouette: :watch:](https://developers.cloudflare.com/1.1.1.1/commitment-to-privacy/privacy-policy/privacy-policy) | `[2606:4700:4700::1001]` | `[2606:4700:4700::1111]` |
| [OpenDNS](https://www.opendns.com/about/innovations/ipv6) IPv6 | :computer: [:lock_with_ink_pen:](https://doh.opendns.com/dns-query) | :closed_lock_with_key: :six: :twisted_rightwards_arrows: |  | `2620:0:ccc::2` | `[2620:0:ccd::2]` |
| [Quad9](https://quad9.net) IPv6 | :computer: :lock: [:lock_with_ink_pen:](https://dns9.quad9.net/dns-query) | :closed_lock_with_key: :six: :fire: | [:bust_in_silhouette:](https://quad9.net/privacy) | `[2620:fe::9]` | `[2620:fe::fe:9]` |
| [Quad9²](https://quad9.net/doh-quad9-dns-servers) IPv6 | :computer: :lock: [:lock_with_ink_pen:](https://dns.quad9.net/dns-query) | :closed_lock_with_key: :six: :fire: | [:bust_in_silhouette:](https://quad9.net/privacy) | `[2620:fe::fe]` | `[2620:fe::fe:9]` |
| [Quad9 HTTP](https://quad9.net/doh-quad9-dns-servers) IPv6 | :computer: [:lock_with_ink_pen:](https://dns10.quad9.net/dns-query) | :six: | [:bust_in_silhouette:](https://quad9.net/privacy) | `[2620:fe::10]` | `[2620:fe::fe:10]` |
| [Quad9 CDN](https://quad9.net/doh-quad9-dns-servers) IPv6 | :computer: [:lock_with_ink_pen:](https://dns11.quad9.net/dns-query) | :six: | [:bust_in_silhouette:](https://quad9.net/privacy) | `[2620:fe::11]` | `[2620:fe::fe:11]` |
| [AdGuard](https://adguard.com/en/adguard-dns/overview.html) IPv6 | :computer: :lock: [:lock_with_ink_pen:](https://dns.adguard.com/dns-query) | :closed_lock_with_key: :six: :no_pedestrians: | [:person_with_pouting_face:](https://adguard.com/en/privacy/dns.html) | `[2a00:5a60::ad1:0ff]` | `[2a00:5a60::ad2:0ff]` |
| [AdGuard Family](https://adguard.com/en/adguard-dns/overview.html) IPv6 | :computer: :lock: [:lock_with_ink_pen:](https://dns-family.adguard.com/dns-query) | :closed_lock_with_key: :six: :no_pedestrians: :children_crossing: | [:person_with_pouting_face:](https://adguard.com/en/privacy/dns.html) | `[2a00:5a60::bad1:0ff]` | `[2a00:5a60::bad2:0ff]` |
| [Yandex](https://dns.yandex.com) IPv6 | :computer: | :six: |  | `[2a02:6b8::feed:0ff]` | `[2a02:6b8:0:1::feed:0ff]` |
| [Yandex Safe](https://dns.yandex.com) IPv6 | :computer: | :six: :fire: |  | `[2a02:6b8::feed:bad]` | `[2a02:6b8:0:1::feed:bad]` |
| [Yandex Family](https://dns.yandex.com) IPv6 | :computer: | :six: :fire: :children_crossing: |  | `[2a02:6b8::feed:a11]` | `[2a02:6b8:0:1::feed:a11]` |
| [dns.sb](https://dns.sb) IPv6 | :computer: :lock: [:lock_with_ink_pen:](https://doh.dns.sb/dns-query) | :closed_lock_with_key: :six: | [:negative_squared_cross_mark:](https://dns.sb/privacy)\* | `[2a09::]` | `[2a09::1]` |
| [CleanBrowsing Family](https://cleanbrowsing.org/filters) IPv6 | :computer: :lock: [:lock_with_ink_pen:](https://doh.cleanbrowsing.org/doh/family-filter) | :closed_lock_with_key: :six: :children_crossing: :fire: |  | `[2a0d:2a00:1::]` | `[2a0d:2a00:2::]` |  |
| [CleanBrowsing Adult](https://cleanbrowsing.org/filters) IPv6 | :computer: :lock: [:lock_with_ink_pen:](https://doh.cleanbrowsing.org/doh/adult-filter) | :closed_lock_with_key: :six: :children_crossing: :fire: |  | `[2a0d:2a00:1::1]` | `[2a0d:2a00:2::1]` |  |
| [CleanBrowsing Security](https://cleanbrowsing.org/filters) IPv6 | :computer: :lock: [:lock_with_ink_pen:](https://doh.cleanbrowsing.org/doh/security-filter) | :closed_lock_with_key: :six: :fire: |  | `[2a0d:2a00:1::2]` | `[2a0d:2a00:2::2]` |  |
|  |  |  |  |  |  |
| **Retired** |  |  |  |  |  |
| [eieiDNS](https://eieidns.com) | [:lock_with_ink_pen:](https://doh.eieidns.com/dns-query) | :closed_lock_with_key: :no_pedestrians: |  | `103.86.49.31` |  |
| [Norton ConnectSafe](https://dns.norton.com) |  | :fire: |  | `199.85.126.10` | `199.85.127.10` |
| [Norton + Adult](https://dns.norton.com) |  | :fire: :children_crossing: |  | `199.85.126.20` | `199.85.127.20` |
| [Norton + Adult + Other](https://dns.norton.com) |  | :fire: :children_crossing: |  | `199.85.126.30` | `199.85.127.30` |
|  |  |  |  |  |  |

- - - - - - - - - -

### Note
- (\*) Some entry will be use **Second IP** column, such as...
  - **IPv6 address** if specific DNS service provide only one IPv4 address, but also have IPv6 Address that can resolve as `6to4`
  - **TLS address** if specific DNS service provide only one IP address, but have DNS-over-TLS supported
- Because the DNS-over-HTTPS requests are similar to *when you're browsing websites*, it may possible to store your IP address by remote server, please re-check **Privacy Policy** on their services carefully!
- Some DNS that have DNSSEC available may not use the regular port (53), please re-check from the site of DNS service provider.
- DNS-over-TLS (DoT) commonly use port 853, and use port 443 for alternative, if available.
- Configuration for [personalDNSFilter](https://github.com/IngoZenz/personaldnsfilter)
  - To adding DoH entry, you can enter with these format below
    - For IPv4 entry: `146.185.167.43::443::DoH::https://doh.securedns.eu/dns-query`
    - For IPv6 entry: `[2a03:b0c0:0:1010::e9a:3001]::443::DoH::https://doh.securedns.eu/dns-query`
  - To adding DoT entry, you can enter with these format below
    - For IPv4 entry
	  - No alternative resolver: `146.185.167.43::853::DoT`
	  - With alternative resolver: `146.185.167.43::853::DoT::ads-dot.securedns.eu`
    - For IPv6 entry
      - No alternative resolver: `[2a03:b0c0:0:1010::e9a:3001]::853::DoT`
      - With alternative resolver: `[2a03:b0c0:0:1010::e9a:3001]::853::DoT::ads-dot.securedns.eu`

- - - - - - - - - -

### Legends
| Icon | Description |
|------|-------------|
| ***Support*** |  |
| :computer: | Generic DNS (Change DNS in your devices, router, IoT, etc. It may require DNSSEC validation on remote server for using with hosts-file blocking apps, e.g. Blokada, DNS66, ...) |
| :lock: | DNS-Over-TLS (e.g. SimpleDNSCrypt, Android Intra, Android 9+ Private DNS, ...) |
| :lock_with_ink_pen: | DNS-Over-HTTPS (Right click to copy address, capable for DoH resolvers, e.g. personalDNSFilter, Firefox, Chrome {via custom arguments}, ...) |
|  |  |
| ***Features*** |  |
| :closed_lock_with_key: | DNSSEC available for validation |
| :twisted_rightwards_arrows: | Multi-servers |
| :no_pedestrians: | Block ads and trackers |
| :children_crossing: | Family Protection (may include adult sites filtering) |
| :fire: | Thread blocking (Bots, Fraud, Malware, Spam) |
|  |  |
| ***Logging*** | Note: you can click emoji to view their terms (if available) |
|  | Unspecified |
| :negative_squared_cross_mark: | No Logging\* (Contain no sensitive info in logs e.g. No IP Address logging at all!) |
| :question: | Logging terms is unclear enough |
| :bust_in_silhouette: | Anonymous Log (e.g. Partial IP address with client country) |
| :person_with_pouting_face: | Identifiable Log (at least one of these, e.g. Full IP address :boom:, client country, devices name, browser name, hardware name, etc.) |
| :open_file_folder: | May share logs to others (e.g. Partners, Threads watcher, etc.) |
| :watch: | Logs will kept for specific time and will remove after... |
| :alarm_clock: | Logged permanently! (even they're encrypted and\/or stripped sensitive information before store them, this will be accounted for!!) |
| (`time`) | How they retain logging in specific interval before delete (format\: h=Hour, d=Day, m=Month, ?=Unknown) |

- - - - - - - - - -

### Credits
- https://github.com/DNSCrypt
- https://github.com/curl/curl/wiki/DNS-over-HTTPS
