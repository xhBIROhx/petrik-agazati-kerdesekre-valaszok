Petrik 2024 ágazati kérdésekre válaszok
========================

## csoportmunka -> 1
1. Mi a teendő merge conflict esetén?
    * eldönteni melyik verziót akarjuk megtartani, vagy manuálissan átnézni a változtatásokat
2. Mikor jön létre merge conflict?
    * ha egyszerre két különböző változtatást akarunk alkalmazni
3. Melyik Git parancs segítségével tudod egy feature branch változásait alkalmazni a master branch-re?
    * git checkout master **VAGY** git switch master
    * git merge feature
4. Milyen funkciót látnak el a branch-ek?
    * verzió kezelést, illetve párhuzamos munkát
5. Melyik Git parancs segítségével hozhatsz létre lokális repositoryt?
    * git init
6. Melyik Git parancs segítségével másolhat le egy komplett kódbázist egy távoli kódtárból?
    * git clone
7. Melyik Git parancs segítségével töltheti fel a változásokat távoli kódtárba?
    * git push
8. Melyik Git parancs segítségével könyvelhet el változásokat a kódbázison?
    * git commit
9. Az alábbiak közül mire használható a MS Teams? (2 helyes válasz van)
    * ezt sajnos mindenki tudja
10. Milyen problémákat old meg a verziókezelés? (Kettő jó válasz van!)
    * hibák eredetének visszakeresése
    * verzió visszapörgetése
    * csoportmunka egyszerűsítése

## Elektronika -> 1
11. A(z) ……………………..az az áramköri elem (alkatrész), amely villamos tér létrehozásával elektromos töltést képes tárolni.
    * kondenzátor
12. A NOT kapu minimálisan ennyi tranzisztor felhasználásával építhető meg:
    * 1
13. Az OR kapu minimálisan ennyi tranzisztor felhasználásával építhető meg:
    * 2
14. Az AND kapu minimálisan ennyi tranzisztor felhasználásával építhető meg:
    * 2
15. Melyik logikai kapu ad mindkét bemenetén 1-es esetén 1-es kimenetet?
    * and, or, xand = xnor
16. Melyik logikai kapunak van egy logikai bemenete?
    * not
17. Bit tárolására használható eszköz
    * flip-flops, latches
18. Ha egy áramkört úgy állítunk össze, hogy benne nincs elágazás, akkor az ellenállásokat …………. kapcsoltuk a feszültségforrásra.
    * sorosan
19. Olyan berendezést, amelynek hatására egy áramkörben tartósan elektromos áram folyik
    * áramforrás
20. Milyen lenne az ideális feszültségmérő ellenállása?
    * végtelen, mintha ott se lenne.
21. Melyik logikai kapu ad mindkét bemenetén 0-ás esetén 1-es kimenetet?
    * xnor = xand, nand, nor, 
22. Mely feladatok ellátására tipikus alkatrész egy kondenzátor? (Két jó válasz van)
    * egyenáram előállítása
    * regulálás (zavarok filterelése)
        * áramkihagyás esetén kiegészítés
        * hirtelen nagy energia esetén elosztja azt.
    * késleltetés / időzítés
23. Mi igaz az univerzális logikai kapuáramkörökre?
    * ![ilyen nincs](https://i.imgur.com/V2L1cAP.png)
24. A(z) ……………………. háromrétegű félvezető eszköz, amelyet túlnyomórészt gyenge villamos jelek erősítésére, továbbá jelek kapcsolására vagy feszültségstabilizálás céljára alkalmaznak.
    * tranzisztor
25. Milyen mértékegység tartozik leginkább az ellenálláshoz?
    * Ohm
26. Mely feladatok ellátására tipikus alkatrész egy ellenállás? (Két jó válasz van)
    * Áram írányítás
    * Áram/feszültség limitálás
27. Milyen számrendszert használunk leggyakrabban digitális elektronikában?
    *  base2 = binary = kettes (akárhogy írhatja)
28. Melyik az alapvető különbség az AND és az OR kapuk között?
    * chat gpt: Az AND kapu akkor ad 0-t ha bármelyik bemente 0. Az OR kapu akkor ad 1-et ha bármelyik bemente 1.
29. Mi az a Flip-flop?
    * két stabil állapottal rendelkező memória alkatrész(?)
    * Bit tárolására használható eszköz
30. Mely feladatok ellátására tipikus alkatrész egy relé? (Két jó válasz van)
    * nagy áram kapcsolására
    * áram folyásának korlátozására
31. Mely feladat ellátására tipikus alkatrész egy tranzisztor?
    * gyenge villamos jelek erősítésére
    * jelek kapcsolására
    * feszültségstabilizálás
32. Egy 4,5V-os elemmel szeretnénk világítani, mi kell még hozzá? (Két jó válasz van)
    * led
    * kapcsoló
    * vezető
33. Melyik állítás jellemzi az ESD fogalmát?
    * Electrostatic Discharge / elektrosztatikus kisülés

## Hálózat_alap -> 1
### 1/37 not worth
34. Egy játékprogram fejlesztése során meg kell valósítania a többjátékos módot. Első lépésben a szoftver működő szervert keres a hálózaton, hogy csatlakozhasson ehhez.Milyen szállítási rétegbeli protokollt, és milyen címzést használna ezeknél a felderítő üzeneteknél? **WHERE VÉGE**
     * UDP protokolt,
     * broadast cimzest

35. Tanulmányozza a képernyőképet! Az alábbiak közül milyen forgalmat fog rögzíteni a program? V1.png **IS THAT A MOTHER FUCKING ULTRAKILL REFERENCE**
36. Tanulmányozza a képernyőképet! Az alábbiak közül melyik állítás igaz az éppen vizsgált keretre? V2.png **I'M CRYING AND SHAKING RN FR**
    
37. Egy számítógép sikeresen pingel a helyi hálózaton kívülre, de nem tud hozzáférni semmilyen webes szolgáltatáshoz. Mi a legvalószínűbb oka ennek a problémának?
     * Valoszínűleg nem működik a dns nevfeloldas
38. Melyik felsorolt technológia gyűrű topológiájú?
     * Token Ring
     * FDDI (Fiber Distributed Data Interface)
     * SONET/SDH (Synchronous Optical Networking/Synchronous Digital Hierarchy)
  
39. Mennyi a Fast Ethernet adatátviteli sebessége?
     * 100Mbit/s
40. Egy számítógép IP-címe dinamikusan konfigurált, értéke pedig 169.254.17.65. Mire következtethet ebből az információból?
    * a  169.254.17.65 egy APIPA (Automatic Private IP Addressing) IP cim, amit akkor kap a szamitogep, amikor nem eri el a dhcp servert
   
41. Melyik állítás igaz a webszerver alkalmazásra? V7.png2
42. Az alábbiak közül melyik állítás igaz a webszerver alkalmazásra? V8.png
43. Tanulmányozza az alábbi képet, amelyen az ipconfig parancs kimenete látható!     
44. A felhasználó Minecraft szervert indított a számítógépén, és átengedte azt a tűzfalon. Ezután egy távoli hálózatból megpróbált csatlakozni hozzá egy kliens a fent látható IP-címe ha_01.png **NINCS BEFEJEZVE**
45. Mi a különbség a 802.3 és a 802.11 szabványok között?
     * a kozvetito kozeg
     * .3 -> ethernet (vezetekes) akar 100Gbit/s
     * .11 -> wi-fi alacsonyabb elerheto maximalis atviteli sebesseg
     * 
46. Melyik IPv6-os cím hibás/nem felhasználható?
     * igazabol itt arra kell figyelni, hogy :: csak egyszer lehet benne
     * ha a ket kettospont kozott nincs karakter, akkor ott nullák vannak
  
47. Melyik feladat NEM tartozik az OSI modell fizikai rétegéhez?
      * Adatcsomagok irányítása
48. Az alábbi fogalmak közül melyek azok, amik az OSI modell azonos rétegéhez tartoznak?
     | OSI Réteg            | Fogalmak                               |
     |----------------------|----------------------------------------|
     | Fizikai réteg        | Hálózati adapter (NIC), Bit szintű adatátvitel, Fizikai csatlakozók és kábelek, Jelzés (signaling) |
     | Adatkapcsolati réteg | MAC cím, Ethernet, Keretezés (framing), Hozzáférés-vezérlés (media access control) |
     | Hálózati réteg       | IP cím, Útválasztás (routing), Router, ICMP |
     | Szállítási réteg     | TCP, UDP, Portok, Adatfolyam vezérlés (flow control) |
     | Viszonyréteg         | Ülésszintű kapcsolat (session management), Szinchronizáció, Session control protocols |
     | Megjelenítési réteg  | Adatformázás, Titkosítás, Adattömörítés |
     | Alkalmazási réteg    | HTTP, FTP, SMTP, DNS |

49. Mi az a PDU?
     * Protocol Data Unit
     * adott protokoll legkisebb egysége, amit rétegek között továbbítanak
50. Milyen topológia szerint épül fel a vezetékes hálózat ebben az iskolában? (BMSZC-Petrik)
       * extended star -> kiterjesztett csillag
51. Mik azok a protokollok?
     * szabályok és eljárások rendszere
     * elősegítik a különböző eszközök és rendszerek közötti hatékony kommunikációt és együttműködést
52. Miért használ két portot is (20, 21) az FTP?
     * 21: control port
     * 20: data port
     * lehetővé teszi az FTP működését egy tűzfal mögött
53. Milyen címosztályba tartozik, az alábbi IP cím? 10.0.7.2
    * private ip adress (10.0.0.0-10.255.255.255)
54. Melyik szervezet ad közre lokális hálózati szabványokat, mint pl. 802.3, 802.11, 802.15, stb.
     * IEEE (Institute of Electrical and Electronics Engineers)
55. Tanulmányozza az alábbi képet! Mit eredményez a fenti parancs? ha_02.png
56. Tanulmányozza az alábbi képet, amelyen egy forgalomirányító aktuális konfigurációjának részlete látható! Mit állapíthat meg ez alapján? ha_03.png 
57. Minek a portja a 80-as?
     * http webserver
58. Mi az előnye, ha szabványokat használunk protokollok fejlesztése és megvalósítása során?
     * Kompatibilitás
     * Rugalmas fejlesztés
     * Költségmegtakarítás
     * megbízhatóság
59. Milyen szolgáltatást nyújt az UDP?
    * gyors, de hibaellenorzes es vissazigazolas nelkulit
60. Melyik eszközt nevezzük integrált szolgáltatású eszköznek?
     * több funkciót egyetlen hardvereszközben kombinál
61. Az OSI modell melyik rétegéhez tartozik a „Switch”?
     * Adatkapcsolati -> data link layer
62. A hálózati átvitel során alkalmazott redundancia…
    * ...segít megelőzni az adatvesztést vagy sérülést 
63. Az alábbiak közül melyik nem lehet alhálózati maszk?
     * formatum 255.255.255.255
     * atirva binaryba nem folytonosak az 1 esek
64. Miért használunk az Interneten kétféle címzési rendszert is (MAC-címeket, és IP-címeket)?
    * másik osi layeren mukodnek
65. Mi lehet az oka annak, ha két eszköz nem tudja pingelni egymást, pedig van közöttük működő hálózati kapcsolat?
    * nem megfelelő ip címzés
66. Szoftverfejlesztőként egy azonnali üzenetküldő alkalmazást kell írnia. Az alábbiak közül melyik portot használná a megvalósítás során?
    * Port 5222
    * 49152 és 65535 között
67. Mire lehet használni a WireShark programot?
     * Hálózati forgalom elemzése
68. Mire következtethet abból, ha egy web-oldalt ezzel a linkkel lehet megnyitni:"http://tikos.com/lista.html:8080"
     * arra, hogy nem csak ez az egy oldal fut a gépen
69. Az alábbiak közül melyik állítás IGAZ?
70. Tekintse az alábbi adatokat:  
    "A" hálózati kártya MAC-címe: D0-37-45-68-6D-5D  
    "B" hálózati kártya MAC-címe: D0-37-45-69-FF-5D  
    "C" hálózati kártya MAC-címe: D0-37-40-68-6D-5D  
    "D" hálózati kártya MAC-címe: D0-37-45-68-6F-5D  
    Mire következtethet ezekből az adatokból?
     * ugyan az a cég gyártja őket
71. Melyik az a vezeték nélküli átviteli mód, amely legfeljebb néhány méter távolságban lévőeszközök összekötésére alkalmas, és legalább 1 mb/s-os átviteli sebességet biztosít?
     * Bluetooth
## Hálózat_eszközök -> 1
72. Melyik kábeltípus lenne a legalkalmasabb egy hálózati csatolóval rendelkező nyomtató fali aljzathoz csatlakoztatására?
    * patch kábel; hajlíthatóbb, strapabíróbb
73. Mit csinál az arp-a parancs?
    * [link](https://man.archlinux.org/man/arp.8.en), de TL;DR: Address Resolution Protocol, módosíthatja vagy kiírhatja a számítógép belső cachjében tárolt MAC address és IP address kapcsolatokat.
74. Melyik eszköz tölt be átjáró szerepkört, és teszi lehetővé az állomások számára, hogy távoli IP-hálózatokba küldhessenek adatokat?
    * router
75. Árnyékolt csavart érpár jelölése:
    * az Shielded Twisted Pair (STP) jelenti azt hogy "Árnyékolt csavart érpár". Viszont árnyékolva van az FTP is, csak az páronként van árnyékolva, még a S/FTP páronként és egyben is árnyékolt.
76. A vezeték anyagának tekintetében melyik a kakukktojás: optikai kábel, CAT3 UTP, STP, koaxális?
    * optikai kábel. Mert üveg, a többi réz
77. Mik vannak egy forgalomirányító irányítótáblájában?
    * "Összetartozó alhálózatok és kimenő interfészek"
78. Mi a különbség az egyenes- és a keresztkötésű kábel között?
    * "A keresztkötésű kábel a küldő és fogadó érpárakat megcseréli."
79. A rendszergazda egy munkaállomás beállításakor elírta az alapértelmezett átjáró IP-címét. Mi igaz ebben az esetben?
    * "Az állomás bizonyos gépeket elér a hálózatán."
    * az állomás csak a lokális hálózatán lévő eszközöket éri el
80. Hány ér található egy UTP-kábelben?
    * 8
81. Milyen színű ér NINCSEN egy UTP-kábelben?
    * A következők vannak:
        *  kék (-fehér)
        *  narancs (-fehér)
        *  barna (-fehér)
        *  zöld (-fehér)
82. Miben különbözik egy egyenes (straight-through) és a rollover kábel?
    * straight -> nem egy szinten lévő eszközök összekötésére **pc-switch router-switch**
    * rollover -> egy szinten lévő egyszközök összekötésére **pc-pc**
83. Hány ütközési tartományt képez egy kapcsolóból és a beledugott 4 PC-ből álló hálózat?
    * 4
84. Melyik kábellel NEM lehet két eszköz között hálózati kapcsolatot létrehozni (vagyis sávon kívüli)?
    * amikkel lehet:
        * lan (utp, stp, ftp, patch, stb.), koax, optika, technikailag USB
85. Melyik fogalom jelenti a kapcsoló feldolgozási képességét az alapján, hogy másodpercenként mennyi adatot képes feldolgozni?
    * továbbítási/kapcsolási sebesség
        * A "továbbítási sebesség" határozza meg egy kapcsoló feldolgozási képességeit, meghatározva, hogy mennyi adatot képes feldolgozni másodpercenként. A belépő szintű kapcsolók alacsonyabb továbbítási sebességgel rendelkeznek, mint a vállalati szintű kapcsolók.
86. Tanulmányozza az alábbi képet! Milyen két hálózati eszközt egyesít a fenti szerszám? ha_04.png
87. Milyen célcímet tartalmaz egy ARP kérés keret?
    * "FFFF.FFFF.FFFF"
        * Az ARP-kérés célja, hogy megtaláljuk az Ethernet LAN-on a célállomás MAC-címét. Az ARP egy második rétegbeli szórást küld minden eszköz számára az adott hálózati szegmensen. A keret tartalmazza a célállomás IP-címét, valamint az FFFF.FFFF.FFFF broadcast MAC-címet is. Az az állomás, amelynek az IP-címe megegyezik az ARP kérésben levő címmel, egyedi címzéses üzenetben válaszolni fog, amely tartalmazza a MAC-címét. Így az eredeti küldő megkapja a céljának összetartozó IP-cím és MAC-cím párosát, folytathatja az üzenetének beágyazását.
88. Tanulmányozza az alábbi képet! Milyen kábel látható ezen? ha_05.png
89. „6swB” kapcsoló 12-es portjára UTP-kábellel egy számítógépet csatlakoztattunk. Melyik állítás igaz az alábbiak közül. V6.png
90. Melyik állítás igaz a „6swB” jelű kapcsolóról? V5.png
91. Melyik állítás igaz az éppen tesztelt kábelről? V4.png
92. Melyik állítás igaz a számítógép fizikai adapterére? V3.png **SPOILER!!**
93. Tanulmányozza az alábbi képet, amin egy vezeték nélküli forgalomirányító grafikus felülete látható! Melyik állítás igaz a lentiek közül? ha_06.png

## Hálózatbiztonság -> 1
94. Melyik két módszert használhatjuk arra, hogy a kapcsolónk kevésbé legyen sérülékeny az olyan támadásokra, mint a MAC-cím elárasztás, CDP támadás vagy Telnet támadás? (Két jó válasz van.)
    * *ez egy szar kérdés.*
        * mac cím elárasztás az DDoS
            * erőforrás figyelés és kapcsolatok figyelése, anti spam
        * CDP az basically a cisco config-hoz hozzáférés
            * CDP kikapcsolása
            * CDP password mögé helyezése
            * CDP letiltása nem LAN portokon
        * Telnet az sniffing
            * tikosítás a megoldás **(ssh használata)**
95. Biztonsági okokból a hálózati rendszergazdának biztosítania kell, hogy a helyi számítógépek ne tudják pingelni egymást. Ennek eléréséhez mit kell módosítania?
    * subnet mask-ot
96. Mi lehet egy példa a fizikai biztonság megvalósítására?
    * [kys](http://ethical.inf.elte.hu/wiki/Fizikai_biztons%C3%A1g#Fizikai_biztons.C3.A1g)
97. Mi a célja egy hálózati felderítéses támadásnak?
    * megtalálni az összes behatolási pontot, lehetséges hibákat
98. Milyen probléma merül fel, ha TELNET protokollt használunk egy hálózati eszközhöz való távoli hozzáférésre?
    * nem titkosított a kommunikáció, olyan mint egy http oldal. le lehet hallgatni.
99. Milyen körülmények között ideális behatolás tesztet végrehajtani egy hálózaton?
    * minden? huh? ez nem alap teszt? eh valszeg:
    * Amikor minden szolgáltatás ki van építve, de még nem létfontosságú vagy publikus.
100. Milyen vírus- vagy támadás fajta: a támadó telefonon felhívja a cég egy alkalmazottját és rendszergazdának kiadva magát elkéri tőle a jelszavát?
     * Social engineering
101. Melyek a biztonságos hálózati kommunikáció elemei? (Két helyes válasz van)
102. Melyik támadás - Distributed Denial of Service – támadás?
     * DDoS, több gépről egyszerre egy szervert akarnak spam módon hasznáni. Ezzel azt érik el, hogy a rendes felhasználók nem kerülnek sorra a kiszolgálásban, az az nem kapnak szolgáltatást a szervertől
103. Hibásan implementált protokollverem, vagy protokollhiányosságok miatt a már felépült, illetve kezdeményezett kapcsolatokat egy harmadik személy idegen csomagokat csempész bele. Melyik támadási módszerről beszélünk?
     * man in the middle attack
104. Mi a puffer túlcsordulás támadás leggyakoribb célpontja?
     * böngészőben elmentett jelszavak, de böngésző
105. A hálózat biztonságnál, védekezés során melyik az általánosan és jól használható módszer?
106. Mit csinálnak a „Portscanek”?
     * megkeresik a nyitott portokat
107. Mi a célja a hálózatbiztonsági naplózás funkciónak?
     * logging, minden ami történik a gépen ki van írva (loggolva) fileokba. Azért nagyon hasznos, mert minden változtatás, minden felhasználó kiszolgálása és kérelmei, minden futó program lépése visszanézhető. Ha figyeljük élőben meg lehet előzni a problémát, ha viszont már megtörtént a probléma vissza tudjuk nézni, hogy pontossan miért. Célja: tudni mi történik a serveren, részletessen, lépésenként.
108. Melyik összetevőt tervezték arra, hogy megvédjen a számítógépre irányuló és onnan érkező illetéktelen kommunikációtól?
     * firewall
109. Hogyan védekezhetünk a „Snifferek” ellen?
     * az információkat kódolt formában küldjük át a hálózaton
110. Hogyan akadályozhatja meg a felhasználó, hogy mások lehallgassák a hálózati forgalmat, amikor a számítógépet nyilvános Wi-Fi hot spoton üzemelteti?
     * VPN-el titkosítjuk a commuikánciónkat
111. Ha az adatokat helyi merevlemezen tárolják, melyik módszer védi az adatokat a jogosulatlan hozzáféréstől?
     * titkosítás, csak kulcsal lehet hozzá férni
         * az operációs rendszerben is kellene hogy legyen olyan, hogy nincs olvasási engedélyed adott fileokhoz

## Hardver -> 2
112. Nevezze meg a(z) 9. számmal jelölt csatlakozó helyet! 01hardver.jpg
113. Ezek közül melyik a legnagyobb felbontás?
114. Miben adhatjuk meg a szkennerek felbontását?
     * DPI, dots per inch
115. Mi jellemzi az additív színkezelési eljárást? (RGB) (2 jó váalsz)
116. Mi a CMOS memória feladata az alaplapon?
     * idő múlásának követése
     * Alap bios beallitasok megjegyzése
117. Nevezze meg a(z) 14. számmal jelölt csatlakozó helyet! 01hardver.jpg
118. Melyik alkatrész felelős az adatok hosszú távú tárolásáért és visszahozásáért a számítógépből?
     * storage devices (Pl: HDD, SSD)
119. Nevezze meg a(z) 1. számmal jelölt csatlakozó helyet! 01hardver.jpg
120. Nevezze meg a(z) 3. számmal jelölt csatlakozó helyet! 01hardver.jpg
121. Melyik alkatrész biztosítja a CPU és a különböző alkatrészek közötti kommunikációt az alaplapon?
     * hídak, északi híd az speckó cpu
122. Melyik alkatrész felelős a grafikus információk megjelenítéséért a monitoron?
     * videokártya
123. Melyik állítás igaz a mátrix nyomtatóra? (2 jó válasz)
     * "A mátrix nyomtatók hasonló elven működnek, mint ahogy ezt ismerjük az írógépeknél. Azonban a nyomtató 9 vagy egészen 24 tűvel rendelkezik, melyek mátrixba vannak rendezve. A nyomtatási feladat megadását követően a tűk a festékszalagon keresztül ráütnek a papírra, így szöveg vagy egyszerű grafika jön létre."
124. Mely eszközök csatlakoznak az Északi-hídra? (2 jó válasz vam)
     * cpu
     * ram
     * PCIe, gpu, agp
125. Jelölje a beviteli eszközöket! (2 jó válasz)
     * a beviteli ezközök, (minden amivel adatot ADSZ): egér, billentyűzet 
126. Nevezze meg a(z) 13. számmal jelölt csatlakozó helyet! 01hardver.jpg
127. Milyen információ olvasható le a képről? 03hardver.jpg
128. Az LGA foglalatnál
     * az LGA-nél a foglalaton vannak a pinek
     * ![vigyázz ez a CPU nem foglalat](https://i.imgur.com/iRhDIfv.png)
129. A PS2 mini redundant
     * mini - kicsi
     * redundant - amikor több van és az egyik teljessen tökremehet, még mindig el fogja a munkát látni a másik
     * ps2 - mérete
130. A BIOS (2 jó válasz)
     * Kezdeti rendszerindítás végrehajtója
     * Beállítások konfigurálója
131. Melyik eszközre igaz: alátámasztást és fizikai védelmet biztosít a hardverelemeknek?
     * Rack szekreny
132. Mik a tápegység feladatai és jellemzői? (2 jó válasz)
     * elátja a számítógép eszközeit árammal
     * átalakítja a váltó fali áramot egyenárammá
133. Melyik a leggyorsabb átviteli sebességű?
134. Milyen csatlakozót lát a képen? 02hardver.jpg
135. Melyik a leggyorsabb az alábbiak közül?
136. Mely állítások jellemzik a ROM-ot? (1 jó válasz)
     * Read only memory, csak olvasni lehet
137. Mi a ZIF foglalat és mi a jelentősége?
     * zero insertion force, nem kell erőltetni hogy beleilleszkednek a foglalatba (esetleg a cpu)
     * kevésebb eséllyel sérűl meg
138. Melyik állítás igaz a lézernyomtatóra? (2 jó válasz)
     * nem szárad be
     * toner port használ
     * gyorsak
139. Hol tárolódnak a PC-n működés (futás) közben a futó programok?
     * RAM
       * de igazából gecire mindenhol, cpu cache, gpu VRAM, swap, és van amikor adatot írva tárolunk (HDD,SSD), akár cloudban is.
140. *Mi* a *cache* a különböző hardvereknél?
     * gyorsabb és kisebb ram
141. Jelölje a perifériákat! (2 jó válasz)
142. Melyik NEM INPUT / OUTPUT periféria? (2 jó válasz)
     * ami csak az egyiket tudja(?) pl.: monitor, egér, billentyűzet
143. Melyik állítások igazak? (2 jó válasz)
144. Melyik adathordozó írható csak egyszer? (2 jó válasz)
     * CD
     * DVD
       * ezek is többször írhatód, de erre gondolt a költő valszeg
145. Mi a különbség a DVD és a CD között?
     * dvd nagyobb tarhely
     * dvd gyorsabban írható/olvasható
     * dvd újabb
146. Az SSD-k jellemzői: (2 jó válasz)
     * gyorsabb
     * kevesbe megbizhato mint a hdd
     * nem mechanikus
147. A CPU részei: (2 jó válasz)
     * Cu és Alu
148. Mire használhatjuk a SODIMM RAM-ot?
     * Laptopokban, és minipckben
     * sima ram, csak kisebb form-factor
149. Mennyi lehet jellemzően egy DDR3 RAM modul tárolókapacitása?
     * 512Mb-128Gb között (olcsón 16Gb max)
150. Mi az alaplap feladata egy PC-ben?
     * összekötni és kommunikáltatni az alkatrészeket
     * illetve árammal ellátni
151. Az alábbiak közül melyik rövidítés nem a megjelenítéshez kapcsolódó technológia?
152. Melyik PC-s bővítőkártya biztosítja az adatok hibatűrését?
     * raid card
153. Tanulmányozzuk az ábrát! Egy technikus egy második SATA-merevlemezt telepít. Az alaplap melyik részét fogja használni a SATA-kábel csatlakoztatásához? vhardver01.png
     * altalaban a nem backportos oldalán egy alaplapnak, vertically a kozepe alatt
     * a SATA portoknál ?????????
154. Melyik alkatrész felelős a tápegység és a számítógép egyéb alkatrészei közötti áramellátásért?
     * Alaplap/vezetékek
155. Hol állítható be egy számítógépen, hogy ne merevlemezről, hanem optikai meghajtóról töltsön be? (2 jó válasz)
     * Bios Boot menu, így lehet új OS-t feltelepíteni

## Karbantartás -> 1
156. Mit rögzít az eseménynapló? (Két helyes válasz lehetséges)
     * Minden szamitógéppel törtenő dolgot, annak időpontját, kategoriáját, veszélyességi fokozatátá
157. A megelőző karbantartás mely tevékenységeket foglalja magába? (két jó válasz van)
     * Adatmentés, backup
     * tisztítás és ellenőrzés
158. Az ügyfél azt jelzi, hogy laptopján a fájlok mentése és másolása közben egyre gyakrabban kap írási/olvasási hibaüzeneteket. Az alább felsoroltak közül melyik műveletet célszerű egy technikusnak legelőször elvégezni?
     * amennyiben hdd van a gepben, toredezettsegmentesitse
     * adathordozó (hdd, ssd) lecserélése, hogy megtudjuk hardware vagy software hiba
159. Nyomtatók megelőző karbantartásakor mi az első lépés?
     * tintapatron-szint ellenőrzése
160. Egy felhasználó arról számol be, hogy a az idő a laptop minden indulásakor helytelenül jelenik meg (késik). Mi lehet a probléma?
     * lemerült a cmos battery
161. Melyik eljárás ajánlott egy számítógép belsejének tisztításakor?
     * levegővel körbefújni
162. Melyik eszköz a legalkalmasabb a PC portalanítására?
     * kompresszor, sűrített levegő, kézi ventillátoros fújó bigyó
163. Milyen körülmények közt szerelheted szét a tápegységet javítás céljából?
     * SEMMILYEN KÖRÜLMÉNYEK KÖZÖTT SEM
         * valószínűleg ez a helyes válasz, de ha áramtalanítva, leföldelve és kitisztítva van, és értesz ahhoz amit csinálsz akkor lehet.
164. Mi a helyes eljárás LCD/TFT nyomtató tisztításakor? ***egyaltalan mi a faszom az***
      * a képernyő, gyengéd letörlése egy finom microfiber törlővel
      * ha nem elég akkor víz, alkohol vagy ecet
165. Melyik nem a szoftveres megelőző karbantartási folyamat része?
     * RÉSZEI:
         * Frissítések telepítése
         * Víruskeresés
         * Hardverdiagnosztika
166. Mi a tervszerű megelőző karbantartás elsődleges célja?
     * nem lesznek váratlan meghibásodások
     * a problémák felfedezése és kiküszöbölése mielőtt az megtörténik
167. Mi igaz a CPU pasztázásra?
     * A paszta segít a CPU es a hűtő közötti mikro repedéseket kitölteni
168. Mit kell tennie egy technikusnak, mielőtt számítógépet kezd szerelni?
     *  Kikapcsolni és áramtalanítani azt
169. Mit kell tennünk a RAM alaplapba való beszerelése előtt?
     * Kikapcsolni és áramtalanítani a rendszert
         * előfordulhat, hogy itt gondol olyanokra mint pl.: ellenőrizzük hogy a CPU és a MB tud-e annyi RAMot kezelni, hogy ugyan az a socket típus legyen, kiporolni a csatlakozót
170. Mi az elsődleges előnye egy számítógép megelőző karbantartásának?
     * nem lesznek váratlan meghibásodások
     * a problémák felfedezése és kiküszöbölése mielőtt az megtörténik
171. Mely tevékenység a Windows üzemeltetés és karbantartás egyik legfontosabb eszköze? **Remélem sok pénzt kapott ezért a suli #ad**
     * Windows Update

## ModernIT -> 3
172. A IaaS felhőszolgáltatói modellben
     * AKA: Infrastructure as a service
     * tárhely, server, webhost. Megadja az egész infrastrukturát ami egy adott célra (legtöbbször webserver) kell
173. Mire NEM képes az alábbiak közül a mesterséges intelligencia?
     * ezt sajnos mindenki tudja
174. Milyen kicsi lehet napjainkban egy integrált áramkör?
     * nagyon, akár pár száz vagy pár tiz nm is. De ezt telleg nem lehet megválaszolni, attól függ mire használod
     * 3 nanométeres tranzisztorok a legkissebbbek jelenleg
175. Melyek a virtualizáció és automatizálás következményei az adatközpontban? (Két jóválasz van)
     * Nagyobb rugalmasság és skálázhatóság
     * Költséghatékonyság
     * gyorsaság
176. Mik a felhőszolgáltatások előnyei? (2 jó válasz van)
     * Költséghatékonyság
     * Skálázhatóság és Rugalmasság
     * Gyors telepítés és időmegtakarítás
     * Biztonság
177. A PaaS felhőszolgáltatói modellben
     * AKA: Platform as a service
     * a szolgáltató teljes fejlesztési és üzemeltetési környezetet biztosít
         * Egy kész platformot ad, hogy te testre szabd és használd.
178. A hypervisor
     * google: "A hypervisor is a software that you can use to run multiple virtual machines on a single physical machine"
     * virtualizacios rendszer
179. Melyik fogalmat írja le? "A hálózati struktúra nem csak „embereket köt össze”, hanem dolgokat, eszközöket is. Az „okos eszközök” kommunikálnak egymással, pl. a klasszikus példa szerint a mosógép akkor indul el, amikor az elektromos hálózat terhelésétől függően a legolcsóbb az áram." **NEM VOLT BEFEJEZVE A *KURVA* KÉRDÉS**
     * IoT, Internet of Things
180. A 2-es típusú hyperizor (2 helyes válasz van)
     * szoftwaresen futtat virtuális számítógépeket
     * alacsonyabb teljesítményú, mint lv1
     * rugalmas, egyszerű
181. Mik a virtuális szerver használatának előnyei? (2 helyes válasz van)
     * erőforrások hatékonyabb limitálása
     * költségcsökkentés
     * biztonság
182. Melyek a virtualizáció előnyei? (Két jó válasz van)
     * rugalmas skálázhatóság
     * költségcsökkentés
     * biztonság
     * egyszerűbb Rendszerkarbantartás
     * nem foglal feleslegesen helyet a szerverterem
     * nem kell a hely 0/24 es biztonságára figyelni
183. Melyik felhőmodellre igaz: Legismertebb modell, a hétköznapi emberek számára is elérhető, viszont az erőforrások a szolgáltatást biztosító vállalat tulajdonában vannak?
     * SaaS
184. A SaaS felhőszolgáltatói modellben
     * software as a service
     * szolgáltatásként biztosított szoftver *pl:* ***netflix, youtube***

## Oprendszer - > 3
185. Melyik partíciót használja a Windows operációs rendszer a számítógép indításához?
     * a boot partíciót **SPOILER: minden OS-nek van boot-ja**
186. Mit jelent a lemezpartíció kifejezés?
     * az adathordozó egy önálló logikai egysége
187. Amikor egy felhasználó változtatásokat hajt végre a Windows beállításaiban, hol tárolódnak ezek a módosítások? **IGEN IGEN AZAZ WINDOWS #ad**
     * registryben
188. Mi NEM tartozik a virtuális gép előnyei közé?
     * nagyobb erőforrás igény
     * nehezebb low level tevekenysegek vegzese
189. Az NTFS (2 jó válasz) **#AD #AD #AD**
     * "New Technology File System"
     * Naplózós fájlrendszer, korrupciót meg tud előzni (határokon belül) azzal, hogy nyomonköveti a változtatásokat
     * windows által használt
         * van egy rakat csak lekövetésre kitalált "feature" benne, pl.: ADS
190. Igaz vagy hamis? A particionálás egy fájlrendszert hoz létre a partíción a fájlok tárolására.
     * **hamis**
191. A fájl: (2 jó válasz)
     * logikailag összefügg
     * sokféle kiterjesztése lehet
     * mentett adat
     * **file name** + **.** + **kiterjesztes**
     * kiterjesztés célja: minden filet egyből a saját programja tudjon megnyitni
192. Egy alkalmazás frissítését követően a számítógép nem működik megfelelően. Melyik Windowsban alkalmazható lehetőség használható a rendszer egy korábbi állapotba történő visszaállítására?
     * biztonsági mentés visszaállítása
     * recovery, update roll-back
193. Mi tudható meg az alapvető rendszerinformációból?
     * **(msinfo32.exe)**
     *  operációs rendszer verzió
     * rendszer adatai
     * ram mérete
     * processzor neve
     * pagefile helye
194. Mivel jelzi a felhasználó, hogy elfogadja egy alkalmazás végfelhasználói szerződését (EULA-t)?
     * a telepítés közben elfogadja
195. Melyik eszköz alkalmas a fontos Windows rendszerfájlok ellenőrzésére és a sérült állományok kicserélésére?
     * windows telepítőlemez, vagy SFC
196. Melyik alkatrész gyártójának weblapját keresse fel a szakember a számítógép BIOS frissítésével kapcsolatban?
     * alaplap
197. Barátja arról számolt be, hogy egy új és ingyenes navigációs applikációt töltött le az App Store Áruházból a táblagépére. Milyen típusú operációs rendszer futhat a táblagépén? **#AD #AD #AD**
     * IOS
198. Leggyakrabban hogyan juthatunk hozzá egy szoftver frissítéseihez?
     * a szoftver keszítőinek weboldaláról, vagy az alkalmazás boltból/kezelőből
199. Egy technikus szeretné ellenőrizni egy Windows operációs rendszert futtató számítógépen, hogy a hálózati kártya megfelelően van-e telepítve. Melyik segédprogramot kell használnia az alább felsoroltak közül? **ez actually valid wtf**
     * eszközkezelő

## Projektmenedzsment -> 1
### 1/30 not worth
200. Az alábbiak közül milyen típusú kapcsolati idő adható meg a MS Project programban?
201. Minek a definíciója ez: "a projekt fontosabb fázisainak kezdetét vagy befejezését jelző tevékenység"?
202. Egy zenei album rögzítése projekt esetén melyik lesz a munka típusú erőforrás:
203. Milyen típusú erőforrásokat vehetünk fel egy projektnél? (3 helyes megoldás)
204. Mikor érdemes egy projektben mérföldkövet felvenni?
205. Milyen kapcsolatot alkalmaz alapértelmezés szerint a MS Project program?
206. A MS Project program mely nézetében láthatjuk a tevékenységeket és az időt is?
207. A projektben egy anyag típusú erőforrásra teljesül, hogy (2 helyes megoldás)
208. Melyik a projektciklus szakaszai közül az utolsó szakasz?
209. Jelölje az igaz állításokat! MS projectben a projekt adatainál (2 helyes megoldás)
210. Egy projekt erőforrás költségei: (3 helyes megoldás)
211. Mi minden projekt alapvető célja?
212. Mely projekt nem tartozik a projektek teljesítésében résztvevők közé?
213. Mi a célja a piaci, illetve értékesítés-orientált projekteknek?
214. Melyik nem SWOT-analizis eleme?
215. Melyik erőforrást nem adják meg projekt erőforrás szükségletének meghatározásakor?
216. Mit jelent a probléma-fa?
217. Mi a feladata a Projektirányító testületnek?
218. Mi a feladata a Projektirányító testületnek?
219. Kik a Projektmanagerek?
220. Melyik projektszereplő leírása ez: "legfontosabb feladata az, hogy biztosítsa a projekt céljainak elérést, a projektfeladatok elvégzését, megadott költségkereten és határidőn belül"
221. Melyik NEM a SWOT elemzés része?
222. Mely negatív hatású sikertényező az alábbiak közül?
223. Az alábbiak közül melyek a projekt megvalósításának lépései?
224. Melyik fogalmat jellemzi: Egy olyan tényező, amely meghatározza az adott projekt határait. Nem csak azt mondja meg, hogy mi lesz elvégezve, hanem, hogy mi nem.
225. Melyik NEM a mágikus projektháromszög része?
226. Kik a Projekt támogatók?
227. A projekt téma időtáv szerint lehet: Két helyes válasz lehetséges)
228. Mi a projektmenedzsment fogalma?
229. Válassza ki a helyes megoldást! „A mágikus projektháromszög” peremfeltételei…


 #

sources: **(ha mar a kedves petrikes** *(nem csak)* **tanarok csak lopni tudnak.)**
* http://szakmasztar.hu/wp-content/uploads/2019/02/2019-Informatikai-rendszer%C3%BCzemeltet%C5%91-megold%C3%A1s.pdf
* http://szakmasztar.hu/wp-content/uploads/2018/01/2018-Informatikai-rendszer%C3%BCzemeltet%C5%91-megold%C3%A1s.pdf
* https://szakmasztar.hu/wp-content/uploads/2020/01/Informatikai-rendszer%C3%BCzemeltet%C5%91-2020_Megold%C3%A1s.pdf
* https://pdfcoffee.com/fejezet-5-ethernet-pdf-free.html
* http://ethical.inf.elte.hu/wiki/Fizikai_biztons%C3%A1g#Fizikai_biztons.C3.A1g
* http://w3.tmit.bme.hu/halozatbiztonsag/Halozatbiztonsag-10.doc
* https://magyarepitestechnika.hu/index.php/epites-it/digitalis-fogalomtar/
* https://www.goconqr.com/en/quiz/2700908/halozat-11
* https://jumpshare.com/s/4CX5QaHGC8z1alNfOtyD