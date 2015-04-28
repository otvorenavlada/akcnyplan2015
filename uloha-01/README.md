# Úloha č. 1

**Úloha**: Vypracovať aktualizovaný zoznam všetkých datasetov orgánov uvedených ako zodpovedných vrátane rozpočtových a príspevkových organizácií v ich pôsobnosti spolu s plánom ich postupného zverejňovania na portáli otvorených dát.
<br>
**Zodpovední**: ministri, predsedníčka Úradu geodézie, kartografie a katastra SR, predsedníčka Štatistického úradu SR, predsedníčka Úradu pre verejné obstarávanie
<br>
**Termín**: 30. apríl 2015

## Vysvetlenie

Táto úloha nadväzuje na uplynulý Akčný plán OGP (na roky 2012-2013). V ňom bola úloha "Vypracovať zoznam všetkých datasetov vrátane technickej špecifikácie a plán ich postupného zverejnenia na portáli otvorených dát." Tento zoznam datasetov sa v minulom období posielal na Úrad splnomocnenca vlády pre rozvoj občianskej spoločnosti (ÚSVROS) a bol [zverejnený na jeho webe](http://www.otvorenavlada.gov.sk/datasety-statnej-spravy/) aj na [portáli otvorených dát](http://data.gov.sk/dataset/zoznam-datasetov-statnej-spravy).

V novom akčnom pláne (na rok 2015) nastali tieto zmeny:

- Úloha sa rozširuje o rozpočtové a príspevkové organizácie v pôsobnosti zodpovedných organizácií (tzn. zodpovedná organizácia neodošle informáciu len o "svojich" datasetoch, ale aj o datasetoch, ktoré spravujú organizácie v jej pôsobnosti).
- Tiež sa mení spôsob zasielania: očakáva sa, že organizácie zoznam datasetov **nahrajú priamo na portál otvorených dát** a nebudú ich posielať cez ÚSVROS.

Prečo tieto zmeny? Organizácie verejnej správy by mali **poznať svoj "dátový inventár", tento zverejňovať a priebežne aktualizovať**. Je žiaduce, aby záznamy v ňom, ktoré nepodliehajú utajeniu, boli verejne dostupné a aktualizované. Preto je flexibilnejšie mať plnú kontrolu, aktualizovať údaje priamo na [data.gov.sk](http://data.gov.sk/) a neposielať ich cez tretiu stranu (ÚSVROS). Pri priamom prístupe je jednoduchšie dáta opraviť či doplniť bez zbytočného zdržania.

Taktiež sa ukázalo, že viaceré rezorty nemajú prehľad o tom, aké všetky dáta sa vlastne v organizáciách v ich pôsobnosti nachádzajú. Vytvorenie dátového inventára spolu s plánom zverejňovania má byť krokom, aby sa tento stav zlepšil. Dáta, ktoré sú v jednotlivých rezortoch "ukryté", môžu byť totiž **užitočné ako pre verejnosť, tak aj pre rezort samotný**.

Dňa 15.3.2015 vstúpilo do platnosti novelizované znenie [Výnosu MF SR o štandardoch pre ISVS č. 55/2014 Z. z.](http://www.zakonypreludi.sk/zz/2014-55). K nemu uvádzame niekoľko poznámok:

- § 2 definuje dataset, pod ktorým sa rozumie "ucelená a samostatne použiteľná skupina súvisiacich údajov vytvorených a udržiavaných na určitý účel a uložených spoločne podľa rovnakej schémy". V [tomto paragrafe](http://www.zakonypreludi.sk/zz/2014-55#p2) sú aj ďalšie definície, ktoré je dobré poznať.
- § 51 až 53 hovoria o poskytovaní otvorených údajov. Toto sú na Slovensku záväzné technické štandardy.
- Príloha č. 9 k Výnosu obsahuje zoznam povinných metaúdajov datasetu s otvorenými údajmi.

Úloha aktualizovať dátový inventár bola zadaná pred účinnosťou nového znenia Výnosu MF SR o štandardoch. Plnú technologickú implementáciu Výnosu má realizovať **nový portál data.gov.sk** (vyvíjaný v rámci projektu **eDemokracia a otvorená vláda**), ktorý by mal byť spustený v priebehu roka 2015. Tento Výnos (ku ktorému v čase vydania ešte nie je metodické usmernenie) už teraz dávame do pozornosti. Samotné publikovanie dát by už malo byť v súlade s ním, pokiaľ to bude technicky možné.

## Postup riešenia

Očakáva sa, že zodpovedné organizácie zaktualizujú informácie o svojich datasetoch a do zoznamu doplnia **aj datasety v organizáciách vo svojej pôsobnosti**. Pre vypracovanie odporúčame **[stiahnuť si a vyplniť šablónu](https://raw.githubusercontent.com/otvorenavlada/akcnyplan2015/master/uloha-01/sablona.zip)**, ktorej štruktúra vychádza z Akčného plánu OGP na roky 2012-2013. Minimálna štruktúra je nasledovná (v prípade potreby je možné doplniť aj iné údaje, napr. poznámku):

- **ID datasetu** (akékoľvek jedinečné pomenovanie -- napr. skratka a pod. -- alebo poradové číslo)
- **Názov datasetu**
- **Výstižný krátky popis**
- **Správca datasetu** (kontakt na správcu, napr. organizácia, sekcia, odbor, meno garanta -- ak je to možné a vhodné: e-mail, telefónne číslo). Nejde o štatutárneho zástupcu inštitúcie, ale o osobu, ktorá je zodpovedná za aktuálnosť datasetu.
- **Povinná inštitúcia** (napr. názov priamo riadenej organizácie)
- **Stav elektronizácie** (napr. "neštruktúrovaný text v textovom procesore", "tabuľkové údaje"). Ak je rozdiel medzi aktuálnym stavom elektronizácie a plánovaným stavom elektronizácie v budúcnosti (napr. sa pripravuje nový informačný systém, do ktorého sa idú dáta migrovať), uveďte túto informáciu.
- **Formát, v ktorom sú údaje uložené** (napr. "xlsx", "databáza MySQL" a pod.)
- **Odhadnutý rozsah údajov** (napr. počet objektov v dátovom zdroji, objem údajov)
- **Údaj o čase vzniku, aktuálnosti, alebo spôsobe či frekvencii aktualizácie údajov**
- **Bližšia špecifikácia obsahu** (napr. aké dátové zdroje sa v datasete nachádzajú, aká je štruktúra dát a pod.)
- **Zverejniteľnosť** (napr. "už zverejnené", "možné zverejniť v celom rozsahu", "možné zverejniť len po anonymizácii", "možné zmeniť až po úprave" + popis úpravy, "možné zverejniť len v agregovanej podobe" a pod.)
- **Odôvodnenie** (odôvodnenie, resp. bližšie vysvetlenie zverejniteľnosti -- v prípade už publikovaného obsahu sa uvedie URL adresa). V prípade, že nie je možné dataset zverejniť v plnej miere (napr. kvôli tomu, že obsahuje osobné údaje), ale je potrebné čiastočne ho anonymizovať, resp. publikovať len agregované údaje a pod., napíšte prosím vysvetlenie.
- **Plán zverejnenia** (dátum dokedy budú údaje publikované)

Uprednostniť by sa mali tieto typy dát: 1) tie, ktoré organizácia sama vníma ako zmysluplné a zároveň je ich publikovanie technicky nenáročné; a 2) dáta, o ktoré je zo strany verejnosti najväčší záujem (s tým môže pomôcť [úloha č. 3, prieskum dopytu](../uloha-03)).

**Poznámky**:

- V jednom datasete (napr. "obchodný register") môže byť viacero dátových zdrojov (napr. rôzne API, databázové tabuľky a pod.). Najdôležitejšie je uviesť údaje na úrovni detasetu a dátové zdroje spomenúť tam, kde to má význam.
- Úloha hovorí o "všetkých" datasetoch. Ak by sa chápala ad absurdum, znamenalo by to ešte aj uvádzanie zoznamu čistiacich prostriedkov v každej zo stoviek verejných organizácií. Vytváranie nezmyselných zoznamov pravdaže nie je cieľom. Je potrebné sústrediť sa na **všetky podstatné datasety, ktoré sa týkajú činnosti organizácie** alebo také datasety, ktoré môžu byť aj z iného dôvodu zaujímavé.
- V prípade nejasností ÚSVROS rád poskytne konzultáciu.

Keď zodpovedná organizácia skompletizuje takúto tabuľku, de facto vytvorí akýsi "nultý dataset" ("dataset so zoznamom datasetov"). Tento by sa mal zverejniť presne takým postupom [**ako akýkoľvek iný dataset, na portáli otvorených dát data.gov.sk**](http://data.gov.sk/). K tomuto môžu byť nápomocné poznámky k [úlohe č. 2](../uloha-02).
