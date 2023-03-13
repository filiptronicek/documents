Gymnázium Thomase Manna

ROČNÍKOVÁ PRÁCE

Matematické symboly - jejich význam, historie, a budoucnost

Filip Troníček

  -----------------------------------------------------------------------
  Vedoucí práce:  Bc. Adrián Majoros
  --------------- -------------------------------------------------------
  Ročník:         7\.

  Školní rok:     2022/2023
  -----------------------------------------------------------------------

**Obsah**

[0 Citační styl a protokol pro poznámky pod čarou
2](#citační-styl-a-protokol-pro-poznámky-pod-čarou)

[**1 Úvod 3**](#úvod)

[**1.1 Cíl práce 3**](#cíl-práce)

[**2 Jak jsme se sem dostali 3**](#jak-jsme-se-sem-dostali)

> [2.1 Řečnická doba matematické komunikace
> 3](#řečnická-doba-matematické-komunikace)
>
> [2.1.1 Mezopotámie 4](#mezopotámie)
>
> [2.1.2 Starověký Egypt 5](#starověký-egypt)
>
> [2.2 Synkopická fáze 5](#synkopická-fáze)

[**3 Analýza různých symbolů 5**](#analýza-různých-symbolů)

> [3.1 Podobnosti symbolů teorie množin a výrokové logiky
> 5](#podobnosti-symbolů-teorie-množin-a-výrokové-logiky)

[**4 LaTeX 5**](#latex)

[5 Závěr 5](#závěr)

[6 Seznam použitých informačních zdrojů
5](#seznam-použitých-informačních-zdrojů)

[7 Seznam příloh 8](#seznam-příloh)

#   {#section .unnumbered}

# Citační styl a protokol pro poznámky pod čarou

Ještě před úvodem bych rád uvedl formát této práce pro zamezení možného
zmatku. Formát je inspirován otevřenou encyklopedií Wikipedie, která
vnímá dva typy poznámek pod čarou: **poznámky** a **reference**.
Poznámky text v mé práci doplňují - jsou tu vysvětlivky, humorné
příspěvky a zasazování do kontextu. Reference zase text ozdrojovávají a
dávají informacím v něm kredibilitu[^1]. Reference se značí super
skriptem a korespondují s jejich ordinálním pořadím v seznamu
[[Zdrojů]{.underline}](#seznam-použitých-informačních-zdrojů); například
první zdroj v seznamu zdrojů se podle tohoto protokolu značí
jako^\[1\]^. Podobně je také v práci odkazováno na přílohy:
^\[příloha\ 1\]^.

# Úvod

Pro psanou komunikaci[^2] používá většina západního světa stejný zápis
písmen - to tedy nadstavbu latinky, která nese název "humanistické
písmo". Používá jí 2,5 miliardy mluvčích^\[1\]^ a v naší kultuře ji
považujeme za samozřejmost. Co možná ale dokáže překvapit je skutečnost,
že na světě existuje styl zápisu konceptů a vztahů mezi nimi, který je v
něm zcela univerzální: matematická notace.

Matematická notace je univerzální jazyk nejen matematiky, ale i vědy a
inženýrství. Je exaktní, což znamená, že nenechává místo pro
interpretaci[^3].

# Cíl práce

Cílem práce je přiblížit čtenáři pojem matematických symbolů, včetně
popsání jejich historie, jejich částečnou kategorizací a analýze
některých z nich. Zároveň čtenáři poskytne náhled do digitálního
zpracování tohoto jazyka vědy a jeho nynější distribuční média.

# Jak jsme se sem dostali

Matematiku zapisuje lidská rasa už velmi dlouho. Zároveň v její historii
najdeme dobu, kdy různorodé matematické koncepty již vyžadovaly
komunikaci staletí před jejich prvním zápisem.

## Řečnická doba matematické komunikace

Matematika v dobách antického Řecka, starověkých Babyloňanů či počátků
civilizace v Číně (obecně před 1000 př. n.l.) se komunikovala místo
grafiky rétorikou. V této době ještě neexistuje nic jako teoretický
problém, koncepty v matematice jsou využívány jenom na řešení problémů,
se kterými se zrovna potýkají: například geometrie začíná v počítání
rozměrů a vzdáleností a algebra nachází své počátky v aritmetických
problémech[^4]^\[3\]\[7\]^.

Později v této době se matematika i začala zapisovat. Začátky zápisu
čísel vůbec přiřazujeme rytí značek do kamene či dřeva, kde každá z
čárek představovala jednu jednotku. Tato praktika byla používána v mnoha
kulturách a byla napříč nimi velmi podobná[^5] - to zajisté přispívá k
tomu, že čárky používáme na některých místech dodnes (například pro
počítání skóre na amatérských sportovních zápasech, nebo ve
steterotipickém vězení pro vězně, kteří si tak značkují počet dnů, které
ve vězení již strávili). ^\[příloha\ 1\]^

### Mezopotámie

Asi 2000 let př. n. l. začali obyvatelé tamější Mezopotámie zapisovat
číslice tzv. klínopisem[^6]. Tento systém používá místo našich
tradičních desíti číslic jenom dvě:
![](media/image5.png){width="0.22058836395450568in"
height="0.20833333333333334in"}pro zápis jednotek a
![](media/image6.png){width="0.22237423447069116in"
height="0.20833333333333334in"} pro zápis desítek, což dělá jejich zápis
podstatně jednodušší na naučení^\[11\]\[12\]^. Pomocí těchto dvou číslic
dokážeme zapsat číslo až 60^\[příloha\ 2\]^ (sexagesimální soustava),
přičemž se dají velmi jednoduše zapsat i čísla mnohem větší: pokud si
čísla nějak oddělíme (čárkou, mezerou apod.), můžeme členy spočítat
následujícím vzorcem:

[![](media/image9.png){width="1.371560586176728in"
height="0.794501312335958in"}](https://www.codecogs.com/eqnedit.php?latex=%5Csum_%7Bi%3D0%7D%5E%7Bn%7D%20d_i%20%5Ctimes%2060%5Ei#0)

kde [![](media/image4.png){width="8.333333333333333e-2in"
height="6.944444444444445e-2in"}](https://www.codecogs.com/eqnedit.php?latex=n#0)
je nejvyšší pořadová hodnota pozice,
[![](media/image3.png){width="0.1111111111111111in"
height="0.1388888888888889in"}](https://www.codecogs.com/eqnedit.php?latex=d_i#0)
je číslice na [![](media/image1.png){width="4.1666666666666664e-2in"
height="0.1111111111111111in"}](https://www.codecogs.com/eqnedit.php?latex=i#0)-té
pozici (přičemž pro nejpravější pozici platí, že
[![](media/image10.png){width="0.3472222222222222in"
height="0.1111111111111111in"}](https://www.codecogs.com/eqnedit.php?latex=i%3D0#0))
a [![](media/image2.png){width="0.19444444444444445in"
height="0.1388888888888889in"}](https://www.codecogs.com/eqnedit.php?latex=60%5Ei#0)
představuje mocninu 60 přiřazenou této pozici. Kupříkladu sexagesimální
číslo 1,35,25,30 lze vyjádřit jako:

[![](media/image11.png){width="3.6805555555555554in"
height="0.1527777777777778in"}](https://www.codecogs.com/eqnedit.php?latex=1%20%5Ctimes%2060%5E3%20%2B%2035%20%5Ctimes%2060%5E2%20%2B%2025%20%5Ctimes%2060%5E1%20%2B%2030%20%5Ctimes%2060%5E0%20%3D%20343530#0)[^7]

Tento vzorec vyjadřuje babylonskou sexagesimální poziční soustavu a lze
jej použít k převodu libovolného sexagesimálního čísla na jeho dekadický
ekvivalent.

### Starověký Egypt

Ještě dříve než v Mezopotámii, kolem 3. tisíciletí před Kristem se
začala matematika zapisovat ve Starověkém Egyptě. Zde používali
dekadický neboli desítkový systém, ve kterém měli speciální
hieroglyfické symboly nejen pro celá čísla 10, 100, 1000, 10 000 a 100
000, ale i pro zlomky ½, ⅓, ⅔, ¼ a ⅕ ^\[5\]\[13\]^.

## Synkopická fáze

# Analýza různých symbolů

## Podobnosti symbolů teorie množin a výrokové logiky

# LaTeX

# Závěr

Závěr přehledně shrnuje hlavní myšlenku a zjištěné skutečnosti práce,
případně navrhuje další možnosti práce s tématem.

#  Seznam použitých informačních zdrojů

1.  Latinka. (7. 11. 2022). *Wikipedie: Otevřená encyklopedie*. Získáno
    > 12:07, 11. 02. 2023 z
    > [[https://cs.wikipedia.org/w/index.php?title=Latinka&oldid=21849674]{.underline}](https://cs.wikipedia.org/w/index.php?title=Latinka&oldid=21849674).

2.  [[Earliest Uses of Various Mathematical
    > Symbols]{.underline}](https://mathshistory.st-andrews.ac.uk/Miller/mathsym/)

3.  [[History of mathematical notation -
    > Wikipedia]{.underline}](https://en.wikipedia.org/wiki/History_of_mathematical_notation)

    a.  Matematické symboly mají různý původ a historii. Některé z nich
        > jsou řecká a latinská písmena, která se používají už od
        > starověku. Jiné, jako plus, mínus, krát a děleno, vypadají
        > jako obyčejné značky na papíře. Přesto jsou symboly v
        > matematice v podstatě pokyny, které řídí tuto oblast vědy².

    b.  Nejstarší důkazy o psané matematice pocházejí od starověkých
        > Sumerů a jejich systému měření z roku 3000 př. n. l. Od roku
        > 2500 př. n. l. Sumerové psali na hliněné tabulky násobilku a
        > zabývali se geometrickými cvičeními a dělením. Nejstarší stopy
        > babylonských číslic také pocházejí z tohoto období.

    c.  Symboly, které známe a používáme dnes, nebyly vytvořeny až
        > do 15. století. První použití plusového znaménka bylo v roce
        > 1489 německým matematikem Johannesem Widmannem. Plusové
        > znaménko jen představuje písmeno „t", které bylo zkratkou
        > latinského slova „et", což znamená „a". Podobně Widmann byl
        > prvním člověkem, který použil mínusové znaménko.

4.  [[Roman numerals -
    > Wikipedia]{.underline}](https://en.wikipedia.org/wiki/Roman_numerals)

5.  Wikipedia Contributors. (2019, September 18). Ancient Egyptian
    > mathematics. Wikipedia; Wikimedia Foundation.
    > [[https://en.wikipedia.org/wiki/Ancient_Egyptian_mathematics]{.underline}](https://en.wikipedia.org/wiki/Ancient_Egyptian_mathematics)

6.  [[Glossary of mathematical symbols -
    > Wikipedia]{.underline}](https://en.wikipedia.org/wiki/Glossary_of_mathematical_symbols)

7.  [[Timeline of mathematics -
    > Wikipedia]{.underline}](https://en.wikipedia.org/wiki/Timeline_of_mathematics)

8.  [[Tally marks -
    > Wikipedia]{.underline}](https://en.wikipedia.org/wiki/Tally_marks)

9.  [[Matematika --
    > Wikipedie]{.underline}](https://cs.wikipedia.org/wiki/Matematika)

10. [[MASARYKOVA UNIVERZITA Historie matematiky ve vztahu k vyučování
    > matematiky na 2. stupni
    > ZŠ]{.underline}](https://is.muni.cz/th/gzc4v/diplomova_prace_sklarova.pdf)

11. O'Connor, J. J., & Robertson, E. F. (2000, prosinec). *Babylonian
    > numerals*. Maths History.
    > [[https://mathshistory.st-andrews.ac.uk/HistTopics/Babylonian_numerals/]{.underline}](https://mathshistory.st-andrews.ac.uk/HistTopics/Babylonian_numerals/)

12. Wikipedia contributors. (2022, November 19). Babylonian cuneiform
    > numerals. In Wikipedia, The Free Encyclopedia. Retrieved 21:13,
    > March 13, 2023, from
    > [[https://en.wikipedia.org/w/index.php?title=Babylonian_cuneiform_numerals&oldid=1122741956]{.underline}](https://en.wikipedia.org/w/index.php?title=Babylonian_cuneiform_numerals&oldid=1122741956)

13. O'Connor, J. J., & Robertson, E. F. (2000, prosinec). *Egyptian
    > numerals*. Maths History.
    > [[https://mathshistory.st-andrews.ac.uk/HistTopics/Egyptian_numerals/]{.underline}](https://mathshistory.st-andrews.ac.uk/HistTopics/Egyptian_numerals/)

# Seznam příloh

> **Příloha 1 -- Počítací značky**
>
> ![](media/image7.png){width="6.101744313210848in"
> height="1.5277777777777777in"}
>
> Benjamin D. Esham, Public domain, prostřednictvím Wikimedia Commons
>
> **Příloha 2 -- Sexagesimální soustava používaná v Mezopotámii**
>
> ![](media/image8.png){width="6.101744313210848in"
> height="3.611111111111111in"}
>
> Josell7, [[CC BY-SA
> 4.0]{.underline}](https://creativecommons.org/licenses/by-sa/4.0),
> prostřednictvím Wikimedia Commons

[^1]: Alespoň to jest jejich účel; ozdrojovaný text nespolehlivými
    zdroji není zdaleka žádná výhra.

[^2]: Tím je myšlena komunikace s použitím složitějších symbolů než
    piktogramů jako jsou dopravní značky nebo emotikony

[^3]: V jiných slovech: romantickou poezii v ní nenapíšete

[^4]: Pro naše účely je tento příklad asi nejpředstavitelnější:
    matematika byla nutná pro počítání v obchodu a vyměňování zboží a
    dalších každodenních záležitostech.

[^5]: Jedna jednotka byla vždy takřka stejná, ale při zapisování více
    než jedné mají různé kultury rozdílné přístupy k zjednodušení jejich
    čtení. Například v Evropě a jižní Africe funguje systém počítacích
    značek jejich zapisováním svisle, vedle sebe a při každém násobku
    pětky využijeme čárku na přeškrtnutí předchozích čtyř, což velmi
    zjednodušuje sčítání do čísel.

[^6]: Někdy jen "klínové písmo"

[^7]: [[Příklad na Woflram
    Alphě]{.underline}](https://www.wolframalpha.com/input?i=1+%C3%97+60%5E3+%2B+35+%C3%97+60%5E2+%2B+25+%C3%97+60%5E1+%2B+30+%C3%97+60%5E0)
