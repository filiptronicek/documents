Gymnázium Thomase Manna

ROČNÍKOVÁ PRÁCE

Matematické značky - jejich význam, historie, a budoucnost

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

[**2 Jak jsme se sem dostali 4**](#jak-jsme-se-sem-dostali)

> [2.1 Řečnická doba matematické komunikace
> 4](#řečnická-doba-matematické-komunikace)
>
> [2.1.1 Mezopotámie 4](#mezopotámie)
>
> [2.1.2 Starověký Egypt 5](#starověký-egypt)
>
> [2.2 Synkopická fáze 5](#synkopická-fáze)
>
> [2.2.1 Al-Khwārizmī a algebra 6](#al-khwārizmī-a-algebra)
>
> [2.2.2 Indie a číslice 6](#indie-a-číslice)
>
> [2.2.3 Fibonacci a středověká Evropa
> 6](#fibonacci-a-středověká-evropa)

[**3 Analýza různých symbolů 6**](#analýza-různých-symbolů)

> [3.1 Typy symbolů 6](#typy-symbolů)
>
> [3.1.1 Operátory aritmetiky 7](#operátory-aritmetiky)
>
> [3.1.1.1 + a - 7](#a--)
>
> [3.1.1.2 ·, ×, ÷, :, a / 7](#a)
>
> [3.2 Podobnosti symbolů teorie množin a výrokové logiky
> 8](#podobnosti-symbolů-teorie-množin-a-výrokové-logiky)

[**4 LaTeX 8**](#latex)

[5 Závěr 8](#závěr)

[6 Seznam použitých informačních zdrojů
8](#seznam-použitých-informačních-zdrojů)

[7 Seznam příloh 12](#seznam-příloh)

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
![](media/image11.png){width="0.22058836395450568in"
height="0.20833333333333334in"}pro zápis jednotek a
![](media/image24.png){width="0.22237423447069116in"
height="0.20833333333333334in"} pro zápis desítek, což dělá jejich zápis
podstatně jednodušší na naučení^\[11\]\[12\]^. Pomocí těchto dvou číslic
dokážeme zapsat číslo až 60^\[příloha\ 2\]^ (sexagesimální soustava),
přičemž se dají velmi jednoduše zapsat i čísla mnohem větší: pokud si
čísla nějak oddělíme (čárkou, mezerou apod.), můžeme členy spočítat
následujícím vzorcem:

[![](media/image6.png){width="0.8055555555555556in"
height="0.4583333333333333in"}![](media/image6.png){width="0.8055555555555556in"
height="0.4583333333333333in"}](https://www.codecogs.com/eqnedit.php?latex=%5Csum_%7Bi%3D0%7D%5E%7Bn%7D%20d_i%20%5Ctimes%2060%5Ei#0)

kde [![](media/image15.png){width="8.333333333333333e-2in"
height="6.944444444444445e-2in"}](https://www.codecogs.com/eqnedit.php?latex=n#0)
je nejvyšší pořadová hodnota pozice,
[![](media/image23.png){width="0.1111111111111111in"
height="0.1388888888888889in"}](https://www.codecogs.com/eqnedit.php?latex=d_i#0)
je číslice na [![](media/image13.png){width="4.1666666666666664e-2in"
height="0.1111111111111111in"}](https://www.codecogs.com/eqnedit.php?latex=i#0)-té
pozici (přičemž pro nejpravější pozici platí, že
[![](media/image16.png){width="0.3472222222222222in"
height="0.1111111111111111in"}](https://www.codecogs.com/eqnedit.php?latex=i%3D0#0))
a [![](media/image1.png){width="0.19444444444444445in"
height="0.1388888888888889in"}](https://www.codecogs.com/eqnedit.php?latex=60%5Ei#0)
představuje mocninu 60 přiřazenou této pozici. Kupříkladu sexagesimální
číslo 1,35,25,30 lze vyjádřit
jako:![](media/image15.png){width="8.333333333333333e-2in"
height="6.944444444444445e-2in"} je nejvyšší pořadová hodnota pozice,
![](media/image23.png){width="0.1111111111111111in"
height="0.1388888888888889in"} je číslice na
![](media/image13.png){width="4.1666666666666664e-2in"
height="0.1111111111111111in"}-té pozici (přičemž pro nejpravější pozici
platí, že ![](media/image16.png){width="0.3472222222222222in"
height="0.1111111111111111in"}) a
![](media/image1.png){width="0.19444444444444445in"
height="0.1388888888888889in"} představuje mocninu 60 přiřazenou této
pozici. Kupříkladu sexagesimální číslo 1,35,25,30 lze vyjádřit jako:

[![](media/image32.png){width="3.6805555555555554in"
height="0.1527777777777778in"}![](media/image32.png){width="3.6805555555555554in"
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

V průběhu středověku, zhruba od 5. do 15. století, nastala ve vývoji
matematiky tzv. synkopická fáze. Tato fáze byla obdobím, kdy se
matematika postupně přesouvala z antických center do nově vznikajících
univerzit a studijních institucí. Ve středověké Evropě se během
synkopické fáze začaly objevovat nové matematické koncepty a metody,
které byly inspirovány znalostmi získanými z arabského světa a Indie.
Matematický vývoj probíhal zejména v oblasti algebry, trigonometrie a
geometrie.

### Al-Khwārizmī a algebra

Perský matematik a astronom Al-Khwārizmī (780--850 n.l.) představuje
jednu z klíčových postav synkopické fáze. Jeho dílo \"Al-Kitāb
al-Mukhtaṣar fī Ḥisāb al-Jabr wa-l-Muqābala\" (Kniha zkráceného počítání
s řešením a srovnáváním) se stalo základem pro vývoj algebry a přineslo
první systematické řešení lineárních a kvadratických rovnic. Slovo
\"algebra\" je odvozeno od arabského slova \"al-jabr\", které znamená
\"řešení\" nebo \"spojení\".

### Indie a číslice

Indická matematika přinesla významné inovace, mezi nimiž stojí za zmínku
vynález indických číslic (1, 2, 3, \...), které se později staly
základem pro dnešní **hindsko-arabskou číselnou soustavu**[^8]. Ta byla
původně složena z devíti symbolů: 1 až 9, přičemž 0 se začala používat
později, nejprve v bakhshalském rukopisu^\[16\]^.

### Fibonacci a středověká Evropa

V Evropě sehrál významnou roli ve šíření arabské matematiky italský
matematik Leonardo Fibonacci (1170--1250). Jeho kniha \"Liber Abaci\"
(Kniha počítání) z roku 1202 zpopularizovala používání arabsko-indických
číslic v Evropě a představila řadu nových matematických konceptů a
technik, jako například Fibonacciho posloupnost.

# Analýza různých symbolů

## Typy symbolů

[[Glossary of mathematical symbols -
Wikipedia]{.underline}](https://en.wikipedia.org/wiki/Glossary_of_mathematical_symbols)

V moderní matematice najdeme symbolů opravdu mnoho a proto je lepší u
nich zavést jednoduchou taxonomii. I samotných kategorií je ale pro naše
účely trochu moc a následuje výčet jejich zkrácené a upravené verze[^9]:

### Operátory aritmetiky

Mezi nejzákladnější symboly, které v oboru matematiky rozeznáváme se
řadí aritmetické operátory. Do této kategorie patří ty nejpoužívanější
symboly, se kterými se setkáváme i v ne-matematických prostředích každý
den.

#### + a -

Znaménko pluska má dva hlavní významy: jednoduché aritmetické sčítání
dvou symbolů, nebo jako denotace absence zápornosti.[^10]

Znaménko mínus značí opak sčítání, neboli odčítání. Stejně jako plus se
používá k denotaci (tentokrát přítomnosti) zápornosti. Původ těchto
znamének není zcela jasný^\[19\]^, ale jako jedno z prvních děl, které
je zmiňuje jest *Algorismus proportionum* od Mikuláše Oresma. Znaménko +
mělo v této době zkracovat latinské slovo pro spojku "a", *et*, které se
zkracovalo jen na písmeno t, připomínající dnešní značku pro sčítání.

#### ·, ×, ÷, :, a /

Symboly pro násobení (**·** a ×) jsme oba dostali v 17. století: symbol
× se prvně objevil v anonymním dodatku překladu od Edwarda Wrighta, díla
Johna Napiera o logaritmech: *Mirifici Logarithmorum Canonis
Descriptio*^\[17\]\[18\]^. *"Tečku jako symbol pro násobení zavedl G. W.
Leibniz. Dne 29. července 1698 napsal v dopise Johnu Bernoullimu:
\"Nemám rád X jako symbol pro násobení, protože se snadno zaměňuje s x;
\... často prostě spojuji dvě veličiny pomocí vložené tečky a označuji
násobení ZC \* LM. Proto při označování poměru nepoužívám jednu tečku,
ale dvě tečky, které zároveň používám pro dělení.\"" (Robertson &
O'Connor, n.d.).*

Značky pro operaci opačnou násobení, dělení, je podstatně více. Možná
první psaný zápis dělení používal značku zavřené jednoduché závorky - )
pro dělení dvou číslic[^11], i když tento zápis se jako jeden z mála
neuchytil. V Česku používáme převážně symbol **:**, který se pro dělení
prvně objevil v roce 1684[^\[18\]^]{.mark}. Více světově známý symbol
dělení, **[÷]{.mark}**[^12] [byl prvně použit v díle *Teutsche Algebra*
z roku 1659^\[18\]^]{.mark}[^13][.]{.mark} V 18. století se začal
používat symbol horizontálního i diagonálního lomítka[^14], z kterého se
vyvinuly i značky pro procenta (%), promile ([‰]{.mark}) a bazického
bodu (‱)^\[23\]^. ^\[22\]^

#### Ostatní aritmetické značky

Zbylé základní značky mocnin a odmocnin. Mocniny tak jak je značíme dnes
(superskriptem jako [![](media/image25.png){width="0.1388888888888889in"
height="0.1388888888888889in"}](https://www.codecogs.com/eqnedit.php?latex=x%5E2#0))
začal používat René Descartes v díle *La Geometrie*
(1637)[^15][^16]^\[18\]^.

Pro odmocňování používáme převážně značku
[![](media/image4.gif){width="0.125in"
height="0.16666666666666666in"}](https://latex-staging.easygenerator.com/eqneditor/editor.php?latex=%5Csqrt#0)[^17].
Před ním se jako denotace odmocnin používalo písmeno **R** a když v roce
1525 Christoph Rudolff použil poprvé znak
[![](media/image4.gif){width="0.125in"
height="0.16666666666666666in"}](https://latex-staging.easygenerator.com/eqneditor/editor.php?latex=%5Csqrt#0),
bylo to bez vodorovné čáry nad odmocninovým obsahem[^18]^\[18\]^.

Znaménko pro "plus mínus",
[![](media/image20.png){width="0.1111111111111111in"
height="0.1111111111111111in"}](https://www.codecogs.com/eqnedit.php?latex=%5Cpm#0),
vytvořil William Oughtred pro jeho spis *Clavis Mathematicae (1631)*.

### Značky číselných vztahů

Pro porovnání dvou nebo více čísel můžeme použít vztahové operátory.
Nejzákladnější znaménko z této kategorie je znaménko Tento symbol byl
zveřejněn poprvé v roce 1557 a byl popsán Robertem Recordem jako "pár
rovnoběžek".^\[24\]^

Pro popsání jakékoliv nerovnosti používáme
[![](media/image22.png){width="0.1111111111111111in"
height="0.1527777777777778in"}](https://www.codecogs.com/eqnedit.php?latex=%5Cneq#0),
pro nerovnost určující "není větší než" používáme
[![](media/image19.png){width="9.722222222222222e-2in"
height="0.1527777777777778in"}](https://www.codecogs.com/eqnedit.php?latex=%5Cngtr#0)
(a opačné [![](media/image17.png){width="9.722222222222222e-2in"
height="0.1527777777777778in"}](https://www.codecogs.com/eqnedit.php?latex=%5Cnless#0)).[^19][^20]

Za zmínku stojí samozřejmě i symboly pro větší než,
[![](media/image9.png){width="9.722222222222222e-2in"
height="8.333333333333333e-2in"}](https://www.codecogs.com/eqnedit.php?latex=%3E#0),
větší nebo rovno [![](media/image29.png){width="9.722222222222222e-2in"
height="0.125in"}](https://www.codecogs.com/eqnedit.php?latex=%5Cgeq#0),
a jejich protějšky menší než,
[![](media/image14.png){width="9.722222222222222e-2in"
height="8.333333333333333e-2in"}](https://www.codecogs.com/eqnedit.php?latex=%3C#0)
a menší nebo rovno,
[![](media/image8.png){width="9.722222222222222e-2in"
height="0.125in"}](https://www.codecogs.com/eqnedit.php?latex=%5Cleq#0).[^21]

Při počítání s měřeními z reálného světa nebo komplexnějšími
matematickými koncepty se často používá aproximace[^22]^\[25\]^.

## Podobnosti symbolů teorie množin a výrokové logiky

Teorie množin a výroková logika jsou dva základní matematické obory,
které se zabývají strukturami a způsoby, jak vyjadřovat a analyzovat
matematické tvrzení. Přestože se jedná o různé obory, existují mezi nimi
určité podobnosti v základních symbolech a operacích, konkrétně v
symbolu AND a OR.

V teorii množin se tyto operace používají pro popis interakcí mezi
množinami.

-   **Průnik** ([![](media/image31.png){width="8.333333333333333e-2in"
    > height="9.722222222222222e-2in"}](https://www.codecogs.com/eqnedit.php?latex=%5Ccup#0)
    > / AND): Průnik dvou množin A a B, značený jako A ∩ B, je množina
    > obsahující všechny prvky, které jsou součástí jak množiny A, tak
    > množiny B.

-   **Sjednocení**
    > ([![](media/image27.png){width="8.333333333333333e-2in"
    > height="9.722222222222222e-2in"}](https://www.codecogs.com/eqnedit.php?latex=%5Ccap#0)
    > / OR): Sjednocení dvou množin A a B, značené jako A ∪ B, je
    > množina obsahující všechny prvky, které jsou součástí alespoň
    > jedné z množin A nebo B.

Výroková logika, na druhou stranu, se zabývá vztahy mezi výroky
(tvrzeními) a jejich pravdivostními hodnotami. Základní operace výrokové
logiky zahrnují:

-   **Konjunkce**
    > ([![](media/image28.png){width="8.333333333333333e-2in"
    > height="9.722222222222222e-2in"}](https://www.codecogs.com/eqnedit.php?latex=%5Cwedge#0)
    > / AND): Konjunkce dvou výroků p a q, značená jako p ∧ q, je
    > pravdivá, pokud jsou pravdivé oba výroky p i q. Jinak je
    > nepravdivá.

-   **Disjunkce** ([![](media/image2.png){width="8.333333333333333e-2in"
    > height="9.722222222222222e-2in"}](https://www.codecogs.com/eqnedit.php?latex=%5Cvee#0)
    > / OR): Disjunkce dvou výroků p a q, značená jako p ∨ q, je
    > pravdivá, pokud je pravdivý alespoň jeden z výroků p nebo q.

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

4.  Wikipedia contributors. (2023, March 16). Roman numerals. In
    > Wikipedia, The Free Encyclopedia. Retrieved 15:20, April 9, 2023,
    > from
    > [[https://en.wikipedia.org/w/index.php?title=Roman_numerals&oldid=1144895332]{.underline}](https://en.wikipedia.org/w/index.php?title=Roman_numerals&oldid=1144895332)

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

14. [[Rounding -
    > Wikipedia]{.underline}](https://en.wikipedia.org/wiki/Rounding)

    a.  A [[wavy equals
        > sign]{.underline}](https://en.wikipedia.org/wiki/Approximately_equals_sign)
        > ([**[≈]{.underline}**](https://en.wikipedia.org/wiki/%E2%89%88):
        > *approximately equal to*) is sometimes used to indicate
        > rounding of exact numbers, e.g., 9.98 ≈ 10. This sign was
        > introduced by [[Alfred George
        > Greenhill]{.underline}](https://en.wikipedia.org/wiki/Alfred_George_Greenhill)
        > in
        > 1892.[^[\[1\]]{.underline}^](https://en.wikipedia.org/wiki/Rounding#cite_note-1)

    b.  

15. [[https://archive.org/details/historyofmathema031756mbp/page/n267/mode/2up]{.underline}](https://archive.org/details/historyofmathema031756mbp/page/n267/mode/2up)

16. Wikipedia contributors. (2023, April 4). 0. In *Wikipedia, The Free
    > Encyclopedia*. Retrieved 15:11, April 9, 2023, from
    > <https://en.wikipedia.org/w/index.php?title=0&oldid=1148210764>

17. Arndt, G. (2021, May 29). *The History of Mathematical Symbols*.
    > Everything Everywhere.
    > [[https://everything-everywhere.com/the-history-of-mathematical-symbols/]{.underline}](https://everything-everywhere.com/the-history-of-mathematical-symbols/)

18. Robertson, E., & O'Connor, J. (n.d.). *Earliest Uses of Symbols of
    > Operation*. Maths History; University of St Andrews. Retrieved
    > April 9, 2023, from
    > [[https://mathshistory.st-andrews.ac.uk/Miller/mathsym/operation/]{.underline}](https://mathshistory.st-andrews.ac.uk/Miller/mathsym/operation/)

19. *Minus Symbol -- All Math Symbols*. (n.d.). All Math Symbols.
    > Retrieved April 9, 2023, from
    > [[https://allmathsymbols.com/minus-symbol/#:\~:text=The%20minus%20sign%20didn%E2%80%99t%20have%20any%20origin%20since]{.underline}](https://allmathsymbols.com/minus-symbol/#:~:text=The%20minus%20sign%20didn%E2%80%99t%20have%20any%20origin%20since)

20. *Wikipedia contributors. (2023, February 14)*. Division sign. In
    > Wikipedia, The Free Encyclopedia. Retrieved 15:56, April 9, 2023,
    > from
    > [[https://en.wikipedia.org/w/index.php?title=Division_sign&oldid=1139398210]{.underline}](https://en.wikipedia.org/w/index.php?title=Division_sign&oldid=1139398210)

21. Křížek (znak úmrtí). (9. 09. 2022). Wikipedie: Otevřená
    > encyklopedie. Získáno 15:58, 9. 04. 2023 z
    > [[https://cs.wikipedia.org/w/index.php?title=K%C5%99%C3%AD%C5%BEek\_(znak\_%C3%BAmrt%C3%AD)&oldid=21660326]{.underline}](https://cs.wikipedia.org/w/index.php?title=K%C5%99%C3%AD%C5%BEek_(znak_%C3%BAmrt%C3%AD)&oldid=21660326).

22. Wikipedia contributors. (2023, April 9). Slash (punctuation). In
    > Wikipedia, The Free Encyclopedia. Retrieved 16:23, April 9, 2023,
    > from
    > [[https://en.wikipedia.org/w/index.php?title=Slash\_(punctuation)&oldid=1149001407]{.underline}](https://en.wikipedia.org/w/index.php?title=Slash_(punctuation)&oldid=1149001407).

23. Bazický bod. (20. 05. 2022). Wikipedie: Otevřená encyklopedie.
    > Získáno 16:21, 9. 04. 2023 z
    > [[https://cs.wikipedia.org/wiki/Bazick%C3%BD_bod]{.underline}](https://cs.wikipedia.org/wiki/Bazick%C3%BD_bod).

24. Robertson, E., & O'Connor, J. (n.d.). *Earliest Uses of Symbols of
    > Relation*. Maths History; University of St Andrews. Retrieved
    > April 9, 2023, from
    > [[https://mathshistory.st-andrews.ac.uk/Miller/mathsym/relation/]{.underline}](https://mathshistory.st-andrews.ac.uk/Miller/mathsym/relation/)

25. Matematické symboly a značky. (7. 02. 2023). *Wikipedie: Otevřená
    > encyklopedie*. Získáno 17:34, 9. 04. 2023 z
    > [[https://cs.wikipedia.org/w/index.php?title=Matematick%C3%A9_symboly_a_zna%C4%8Dky&oldid=22422578]{.underline}](https://cs.wikipedia.org/w/index.php?title=Matematick%C3%A9_symboly_a_zna%C4%8Dky&oldid=22422578).

# Seznam příloh

> **Příloha 1 -- Počítací značky**
>
> ![](media/image26.png){width="6.101744313210848in"
> height="1.5277777777777777in"}
>
> Benjamin D. Esham, Public domain, prostřednictvím Wikimedia Commons
>
> **Příloha 2 -- Sexagesimální soustava používaná v Mezopotámii**
>
> ![](media/image30.png){width="6.101744313210848in"
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

[^8]: [[Hindsko-arabská číselná soustava -- Wikipedie
    (wikipedia.org)]{.underline}](https://cs.wikipedia.org/wiki/Hindsko-arabsk%C3%A1_%C4%8D%C3%ADseln%C3%A1_soustava)

[^9]: Tato sekce je převážně zaměřena na symboly, se kterými je nejspíše
    čtenář již seznámen. Poučování čtenáře o novém symbolu a následném
    poukázání na jeho historii ztrácí smysl a zájem o tato historická
    data, když čtenář o symbol neměl zájem předem.

[^10]: U záporných čísel zápornost vždy určujeme znaménkem mínus
    (**-**), ale u nezáporných hodnot se většinou neudává.

[^11]: Například 24)3 = 8

[^12]: Tomuto znaku se říká *obelos*

[^13]: Tento symbol je ale kvůli jeho chybějící univerzálnosti podle
    standardu ISO 80000-2 nedoporučován.

[^14]: Značka je také známá jako *solidus* nebo diagonála.

[^15]: Mocniny jsou v tomto ohledu velmi zajímavé: neznačíme je
    symbolem, ale velikostí písma. V některých kontextech se také pro
    mocnění používá značka \^.

[^16]: Historii mocnění samotného hezky popisuje stránka [[History of
    Exponents \|
    Sutori]{.underline}](https://www.sutori.com/en/story/history-of-exponents--wNbwYExXdzFNYPh1zFUYhbDc).

[^17]: Neplést s ✓.

[^18]: Tuto vodorovnou čáru, latinsky *vinculum* přidal ve stejném díle
    jako moderní mocniny Descartes.

[^19]: Všechny tyto symboly zavedl Euler

[^20]: Sem se dají ještě zařadit symboly ≨ (ne méně, ale ne rovno) a ≩
    (ne více, ale ne rovno)

[^21]: K nim můžeme také zařadit symboly mnohem více než (≫) a mnohem
    méně než (≪), i když jejich přesný význam není úplně
    jasný[^[\[zdroj\]]{.underline}^](https://math.stackexchange.com/questions/1516976/much-less-than-what-does-that-mean).

[^22]: Česky také přibližnost
