




GNU IceCat

https://github.com/losuler/icecat

https://software.opensuse.org//download.html?project=home%3Alosuler%3Aicecat&package=icecat

https://github.com/muslayev/icecat-win64


ungoogled-chromium
https://github.com/Eloston/ungoogled-chromium

https://ungoogled-software.github.io/ungoogled-chromium-binaries/

https://software.opensuse.org/download/package?package=ungoogled-chromium&project=home:ungoogled_chromium

* If you have the `.deb` packages:

	```sh
	# dpkg -i ungoogled-chromium_*.deb ungoogled-chromium-common_*.deb
	```

* If you are using OBS:
  - OBS (Debian Buster)
    ```sh
    # echo 'deb http://download.opensuse.org/repositories/home:/ungoogled_chromium/Debian_Buster/ /' | sudo tee /etc/apt/sources.list.d/home-ungoogled_chromium.list > /dev/null
    # curl -s 'https://download.opensuse.org/repositories/home:/ungoogled_chromium/Debian_Buster/Release.key' | gpg --dearmor | sudo tee /etc/apt/trusted.gpg.d/home-ungoogled_chromium.gpg > /dev/null
    # sudo apt update
    # sudo apt install -y ungoogled-chromium
    ```
  - OBS (Debian Sid)
    ```sh
    # echo 'deb http://download.opensuse.org/repositories/home:/ungoogled_chromium/Debian_Sid/ /' | sudo tee /etc/apt/sources.list.d/home-ungoogled_chromium.list > /dev/null
    # curl -s 'https://download.opensuse.org/repositories/home:/ungoogled_chromium/Debian_Sid/Release.key' | gpg --dearmor | sudo tee /etc/apt/trusted.gpg.d/home-ungoogled_chromium.gpg > /dev/null
    # sudo apt update
    # sudo apt install -y ungoogled-chromium
    ```
    
      * RPM repository
    - OBS (Fedora 33)
      ```sh
      # dnf config-manager --add-repo https://download.opensuse.org/repositories/home:wchen342:ungoogled-chromium-fedora/Fedora_33/home:wchen342:ungoogled-chromium-fedora.repo
      # dnf install ungoogled-chromium
      ```
    - OBS (Fedora 32)
      ```sh
      # dnf config-manager --add-repo https://download.opensuse.org/repositories/home:wchen342:ungoogled-chromium-fedora/Fedora_32/home:wchen342:ungoogled-chromium-fedora.repo
      # dnf install ungoogled-chromium
      ```
 

-------------------

-[uBlock Origin](https://github.com/gorhill/uBlock)
-[Trace-Online Tracking](https://github.com/jake-cryptic/AbsoluteDoubleTrace/)
-[Disconnect](https://github.com/disconnectme/disconnect)
-[Decentraleyes](https://git.synz.io/Synzvato/decentraleyes)
-[OneTab](https://www.one-tab.com/)

-[Adguard Filters](https://github.com/AdguardTeam/AdguardFilters)


------Trace-------

gitlab訪問失敗，Trace擴展'Proxy IP Header Spoofing'臨時關閉即可。

先裝Disconnect、Decentraleyes再裝uBlock Origin。

--------uBlock Origin使用adguard規則--------

-[AdGuard filters](https://kb.adguard.com/en/general/adguard-ad-filters)

Ad Blocking
Enabled: AdGuard Base filter
https://raw.githubusercontent.com/AdguardTeam/FiltersRegistry/master/filters/filter_2_English/filter.txt

Privacy
Enabled: AdGuard Tracking Protection filter
https://raw.githubusercontent.com/AdguardTeam/FiltersRegistry/master/filters/filter_3_Spyware/filter.txt

Social Widgets
Enabled: AdGuard Social Media filter
https://raw.githubusercontent.com/AdguardTeam/FiltersRegistry/master/filters/filter_4_Social/filter.txt

Annoyances
Enabled: AdGuard Annoyances filter
https://raw.githubusercontent.com/AdguardTeam/FiltersRegistry/master/filters/filter_14_Annoyances/filter.txt

Security
Enabled: Online Malicious URL Blocklist
https://gitlab.com/curben/urlhaus-filter/-/raw/master/urlhaus-filter-ag-online.txt

Other
Enabled: Filter unblocking search ads and self-promotion
https://raw.githubusercontent.com/AdguardTeam/FiltersRegistry/master/filters/filter_10_Useful/filter.txt

Language-specific
Enabled: AdGuard Russian filter

Russian filter
https://raw.githubusercontent.com/AdguardTeam/FiltersRegistry/master/filters/filter_1_Russian/filter.txt

Japanese filter
https://raw.githubusercontent.com/AdguardTeam/FiltersRegistry/master/filters/filter_7_Japanese/filter.txt

Chinese filter
https://raw.githubusercontent.com/AdguardTeam/FiltersRegistry/master/filters/filter_224_Chinese/filter.txt

German filter 
https://raw.githubusercontent.com/AdguardTeam/FiltersRegistry/master/filters/filter_6_German/filter.txt

French filter
https://raw.githubusercontent.com/AdguardTeam/FiltersRegistry/master/filters/filter_16_French/filter.txt

Dutch filter 
https://raw.githubusercontent.com/AdguardTeam/FiltersRegistry/master/filters/filter_8_Dutch/filter.txt

Spanish/Portuguese filter 
https://raw.githubusercontent.com/AdguardTeam/FiltersRegistry/master/filters/filter_9_Spanish/filter.txt

Turkish filter
https://raw.githubusercontent.com/AdguardTeam/FiltersRegistry/master/filters/filter_13_Turkish/filter.txt

Custom

DNS filter 
https://raw.githubusercontent.com/AdguardTeam/FiltersRegistry/master/filters/filter_15_DnsFilter/filter.txt

Mobile ads filter
https://raw.githubusercontent.com/AdguardTeam/FiltersRegistry/master/filters/filter_11_Mobile/filter.txt

I don't care about cookies
https://www.i-dont-care-about-cookies.eu/abp/

AdGuard Experimental filter
https://raw.githubusercontent.com/AdguardTeam/FiltersRegistry/master/filters/filter_5_Experimental/filter.txt



# --------adguard規則列表--------

EasyList
https://easylist.to/easylist/easylist.txt

ABPindo
https://raw.githubusercontent.com/ABPindo/indonesianadblockrules/master/subscriptions/abpindo.txt

Bulgarian list
https://stanev.org/abp/adblock_bg.txt

EasyList China
https://easylist-downloads.adblockplus.org/easylistchina.txt

EasyList Czech and Slovak
https://raw.githubusercontent.com/tomasko126/easylistczechandslovak/master/filters.txt

EasyList Dutch
https://easylist-downloads.adblockplus.org/easylistdutch.txt

EasyList Germany
https://easylist.to/easylistgermany/easylistgermany.txt

EasyList Hebrew
https://raw.githubusercontent.com/easylist/EasyListHebrew/master/EasyListHebrew.txt

EasyList Italy
https://easylist-downloads.adblockplus.org/easylistitaly.txt

EasyList Lithuania
https://raw.githubusercontent.com/EasyList-Lithuania/easylist_lithuania/master/easylistlithuania.txt

Latvian List
https://notabug.org/latvian-list/adblock-latvian/raw/master/lists/latvian-list.txt

Liste AR
https://easylist-downloads.adblockplus.org/Liste_AR.txt

Liste FR
https://easylist-downloads.adblockplus.org/liste_fr.txt

ROList
https://www.zoso.ro/pages/rolist.txt

RU AdList
https://easylist-downloads.adblockplus.org/advblock+cssfixes.txt

EasyPrivacy
https://easylist.to/easylist/easyprivacy.txt

Icelandic ABP List
https://adblock.gardar.net/is.abp.txt

AdBlockID
https://raw.githubusercontent.com/realodix/AdBlockID/master/output/adblockid.txt

Greek AdBlock Filter
https://www.void.gr/kargig/void-gr-filters.txt

Fanboy's Annoyances
https://easylist-downloads.adblockplus.org/fanboy-annoyance.txt

Fanboy's Social Blocking List
https://easylist-downloads.adblockplus.org/fanboy-social.txt

Web Annoyances Ultralist
https://raw.githubusercontent.com/yourduskquibbles/webannoyances/master/ultralist.txt

Thai Ads Filters
https://adblock-thai.github.io/thai-ads-filter/subscription.txt

Hungarian filter
https://raw.githubusercontent.com/hufilter/hufilter/master/hufilter-adguard.txt

Peter Lowe's Blocklist
https://pgl.yoyo.org/adservers/serverlist.php?hostformat=adblockplus&mimetype=plaintext

Xfiles
https://raw.githubusercontent.com/gioxx/xfiles/master/filtri.txt

Adblock Warning Removal List
https://easylist-downloads.adblockplus.org/antiadblockfilters.txt

Online Malicious URL Blocklist
https://gitlab.com/curben/urlhaus-filter/-/raw/master/urlhaus-filter-ag-online.txt

Spam404
https://raw.githubusercontent.com/Spam404/lists/master/adblock-list.txt

RU AdList: Counters
https://easylist-downloads.adblockplus.org/cntblock.txt

RU AdList: BitBlock
https://easylist-downloads.adblockplus.org/bitblock.txt

ABPVN List description Vietnamese adblock filter list.
https://raw.githubusercontent.com/abpvn/abpvn/master/filter/abpvn.txt

Fanboy's Enhanced Tracking List
https://secure.fanboy.co.nz/enhancedstats.txt

Official Polish filters for AdBlock, uBlock Origin & AdGuard
https://raw.githubusercontent.com/MajkiIT/polish-ads-filter/master/polish-adblock-filters/adblock.txt

Polskie Filtry Ciasteczkowe
https://raw.githubusercontent.com/MajkiIT/polish-ads-filter/master/cookies_filters/adblock_cookies.txt

Estonian List
https://adblock.ee/list.php

ChinaList+EasyList
http://sub.adtchrome.com/adt-chinalist-easylist.txt

CJX's Annoyance List
https://raw.githubusercontent.com/cjx82630/cjxlist/master/cjx-annoyance.txt

Polskie Filtry Społecznościowe
https://raw.githubusercontent.com/MajkiIT/polish-ads-filter/master/adblock_social_filters/adblock_social_list.txt

Adblock-Persian list
https://ideone.com/plain/K452p

Fanboy's Swedish
https://www.fanboy.co.nz/fanboy-swedish.txt

Fanboy Anti-Facebook List
https://www.fanboy.co.nz/fanboy-antifacebook.txt

Fanboy's Vietnamese description Fanboy's Vietnamese
https://www.fanboy.co.nz/fanboy-vietnam.txt

List-KR
https://raw.githubusercontent.com/List-KR/List-KR/master/filter.txt

xinggsf
https://raw.githubusercontent.com/xinggsf/Adblock-Plus-Rule/master/ABP-FX.txt

I don't care about cookies
https://www.i-dont-care-about-cookies.eu/abp/

Fanboy's Spanish/Portuguese
https://fanboy.co.nz/fanboy-espanol.txt

EasyList Spanish
https://easylist-downloads.adblockplus.org/easylistspanish.txt

KAD - Przekręty
https://raw.githubusercontent.com/PolishFiltersTeam/KAD/master/KAD.txt

Adblock List for Finland
https://raw.githubusercontent.com/theel0ja/finnish-easylist-addition/master/Finland_adb.txt

ROLIST2
https://www.zoso.ro/pages/rolist2.txt

Iranian filter
https://gitcdn.xyz/repo/farrokhi/adblock-iran/master/filter.txt

road-block
https://raw.githubusercontent.com/tcptomato/ROad-Block/master/road-block-filters.txt

Polskie Filtry Elementów Irytujących
https://raw.githubusercontent.com/PolishFiltersTeam/PolishAnnoyanceFilters/master/PPB.txt

Polish Anti Adblock Filters
https://raw.githubusercontent.com/olegwukr/polish-privacy-filters/master/anti-adblock.txt

Fanboy's Anti-thirdparty Fonts
https://fanboy.co.nz/fanboy-antifonts.txt

BarbBlock
https://paulgb.github.io/BarbBlock/blacklists/adblock-plus.txt

EasyList Cookie List
https://www.fanboy.co.nz/fanboy-cookiemonster.txt

NoCoin Filter List
https://raw.githubusercontent.com/hoshsadiq/adblock-nocoin-list/master/nocoin.txt

Frellwit's Swedish Filter
https://raw.githubusercontent.com/lassekongo83/Frellwits-filter-lists/master/Frellwits-Swedish-Filter.txt

YousList
https://raw.githubusercontent.com/yous/YousList/master/youslist.txt

AlleBlock
https://alleblock.pl/alleblock/alleblock.txt

EasyList Polish
https://easylist-downloads.adblockplus.org/easylistpolish.txt

Polski Antyirytujący Dodatek Specjalny
https://raw.githubusercontent.com/PolishFiltersTeam/PolishAntiAnnoyingSpecialSupplement/master/polish_rss_filters.txt

Dandelion Sprout's Nordic Filters
https://raw.githubusercontent.com/DandelionSprout/adfilt/master/NorwegianExperimentalList%20alternate%20versions/NordicFiltersAdGuard.txt

Filter unblocking search ads and self-promotion
https://raw.githubusercontent.com/AdguardTeam/FiltersRegistry/master/filters/filter_10_Useful/filter.txt

AdGuard Mobile Ads filter
https://raw.githubusercontent.com/AdguardTeam/FiltersRegistry/master/filters/filter_11_Mobile/filter.txt

AdGuard Turkish filter
https://raw.githubusercontent.com/AdguardTeam/FiltersRegistry/master/filters/filter_13_Turkish/filter.txt

AdGuard Annoyances filter
https://raw.githubusercontent.com/AdguardTeam/FiltersRegistry/master/filters/filter_14_Annoyances/filter.txt

AdGuard DNS filter
https://raw.githubusercontent.com/AdguardTeam/FiltersRegistry/master/filters/filter_15_DnsFilter/filter.txt

AdGuard French filter
https://raw.githubusercontent.com/AdguardTeam/FiltersRegistry/master/filters/filter_16_French/filter.txt

AdGuard Russian filter
https://raw.githubusercontent.com/AdguardTeam/FiltersRegistry/master/filters/filter_1_Russian/filter.txt

AdGuard Chinese filter
https://raw.githubusercontent.com/AdguardTeam/FiltersRegistry/master/filters/filter_224_Chinese/filter.txt

AdGuard Base filter
https://raw.githubusercontent.com/AdguardTeam/FiltersRegistry/master/filters/filter_2_English/filter.txt

AdGuard Tracking Protection filter
https://raw.githubusercontent.com/AdguardTeam/FiltersRegistry/master/filters/filter_3_Spyware/filter.txt

AdGuard Social Media filter
https://raw.githubusercontent.com/AdguardTeam/FiltersRegistry/master/filters/filter_4_Social/filter.txt

AdGuard Experimental filter
https://raw.githubusercontent.com/AdguardTeam/FiltersRegistry/master/filters/filter_5_Experimental/filter.txt

AdGuard German filter
https://raw.githubusercontent.com/AdguardTeam/FiltersRegistry/master/filters/filter_6_German/filter.txt

AdGuard Japanese filter
https://raw.githubusercontent.com/AdguardTeam/FiltersRegistry/master/filters/filter_7_Japanese/filter.txt

AdGuard Dutch filter
https://raw.githubusercontent.com/AdguardTeam/FiltersRegistry/master/filters/filter_8_Dutch/filter.txt

AdGuard Spanish/Portuguese filter
https://raw.githubusercontent.com/AdguardTeam/FiltersRegistry/master/filters/filter_9_Spanish/filter.txt

=======

-[Anti-Adblock Killer](https://reek.github.io/anti-adblock-killer/#filterlist)
-[anti-adblock-killer](https://github.com/reek/anti-adblock-killer)
-[Anti-Adblock Killer](https://xuhaiyang1234.gitlab.io/AAK-Cont/)
-[AK-Cont](https://gitlab.com/xuhaiyang1234/AAK-Cont/tree/master/FINAL_BUILD)

https://gitlab.com/xuhaiyang1234/AAK-Cont/-/raw/master/FINAL_BUILD/aak-cont-list-ubo.txt

https://gitlab.com/xuhaiyang1234/AAK-Cont/-/raw/master/FINAL_BUILD/aak-cont-list-notubo.txt

https://raw.githubusercontent.com/reek/anti-adblock-killer/master/anti-adblock-killer-filters.txt

======

-[粉糖圓 tw .ttf .otf](https://github.com/FenTangYuan/fentangyuan)
