Gymnázium Thomase Manna

ROČNÍKOVÁ PRÁCE

Matematické značky -- jejich význam, historie, a budoucnost

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

[1 Úvod 3](#úvod)

[1.1 Cíl práce 3](#cíl-práce)

[2 Jak jsme se sem dostali 4](#jak-jsme-se-sem-dostali)

> [2.1 Řečnická doba matematické komunikace
> 4](#řečnická-doba-matematické-komunikace)
>
> [2.1.1 Mezopotámie 4](#mezopotámie)
>
> [2.1.2 Starověký Egypt 5](#starověký-egypt)
>
> [2.1.3 Značení v Řecku 5](#značení-v-řecku)
>
> [2.2 Synkopická fáze 6](#synkopická-fáze)
>
> [2.2.1 Al-Chorezmí a algebra 7](#al-chorezmí-a-algebra)
>
> [2.2.2 Indie a číslice 7](#indie-a-číslice)
>
> [2.2.3 Fibonacci a středověká Evropa
> 7](#fibonacci-a-středověká-evropa)
>
> [2.2.4 Modernější Řecko 7](#modernější-řecko)
>
> [2.2.5 Čínský zápis 8](#čínský-zápis)
>
> [2.3 Symbolická fáze 8](#symbolická-fáze)

[3 Analýza různých symbolů 10](#analýza-různých-symbolů)

> [3.1 Operátory aritmetiky 10](#operátory-aritmetiky)
>
> [3.1.1 + a - 10](#a--)
>
> [3.1.2 ·, ×, ÷, :, a / 10](#a)
>
> [3.1.3 Ostatní aritmetické značky 11](#ostatní-aritmetické-značky)
>
> [3.2 Značky číselných vztahů 11](#značky-číselných-vztahů)
>
> [3.3 Značky logiky 12](#značky-logiky)
>
> [3.3.1 Podobnosti se symboly teorie množin
> 12](#podobnosti-se-symboly-teorie-množin)
>
> [3.3.2 Ostatní logické symboly 13](#ostatní-logické-symboly)
>
> [3.4 Ostatní značky 13](#ostatní-značky)
>
> [3.5 Matematické konstanty 14](#matematické-konstanty)
>
> [3.5.1 π 14](#π)
>
> [3.5.2 e 14](#e)
>
> [3.5.3 ɸ 15](#ɸ)
>
> [3.6 Znaky číselných oborů 15](#znaky-číselných-oborů)

[4 LaTeX 16](#latex-latech)

> [4.1 Původ a účel LaTeXu 16](#původ-a-účel-latexu)
>
> [4.2 Vlastnosti LaTeXu 16](#vlastnosti-latexu)
>
> [4.3 Výhody použití LaTeXu pro matematický zápis
> 17](#výhody-použití-latexu-pro-matematický-zápis)

[5 Závěr 18](#závěr)

> [5.1 Budoucnost značení matematiky 18](#budoucnost-značení-matematiky)
>
> [5.2 Další čtení 19](#další-čtení)
>
> [5.3 Poděkování 19](#poděkování)

[6 Seznam použitých informačních zdrojů
20](#seznam-použitých-informačních-zdrojů)

[7 Seznam příloh 29](#seznam-příloh)

#   {#section .unnumbered}

# Citační styl a protokol pro poznámky pod čarou

Ještě před úvodem bych rád uvedl formát této práce pro zamezení možného
zmatku. Formát je inspirován otevřenou encyklopedií Wikipedie, která
vnímá dva typy poznámek pod čarou: **poznámky** a **reference**.
Poznámky text v mé práci doplňují -- jsou tu vysvětlivky, humorné
příspěvky a zasazování do kontextu. Reference zase k textovým pasážím
přidávají zdroje a dávají informacím v něm kredibilitu[^1]. Reference se
značí číslem s horním indexem a korespondují s jejich ordinálním pořadím
v seznamu [[Zdrojů]{.underline}](#seznam-použitých-informačních-zdrojů);
například první zdroj v seznamu zdrojů se podle tohoto protokolu značí
jako^\[1\]^. Podobně je také v práci odkazováno na přílohy:
^\[příloha\ 1\]^.

# Úvod

Pro psanou komunikaci[^2] používá většina západního světa stejný zápis
písmen -- to tedy nadstavbu latinky, která nese název "humanistické
písmo". Používá ji asi 2,5 miliardy mluvčích^\[1\]^ a v naší kultuře ji
považujeme za samozřejmost. Co možná ale dokáže překvapit je skutečnost,
že na světě existuje styl zápisu výrazů a vztahů mezi nimi, který je
celosvětově zcela univerzální: matematická notace.

Matematická notace je univerzální jazyk nejen matematiky, ale i vědy a
inženýrství. Tento styl zapisování je tzv. exaktní, což znamená, že
nenechává místo pro interpretaci[^3], narozdíl od přirozených jazyků.

# Cíl práce

Cílem práce je přiblížit čtenáři pojem matematických značek, včetně
popsání jejich historie, jejich částečnou kategorizací a analýzu
některých z nich. Zároveň čtenáři poskytne náhled do digitálního
zpracování tohoto jazyka vědy a jeho nynějšího distribučního média.

# Jak jsme se sem dostali

Matematiku zapisuje lidská rasa už velmi dlouho. Zároveň v její historii
najdeme dobu, kdy různorodé matematické koncepty již vyžadovaly
komunikaci staletí před jejich prvním zápisem.

## Řečnická doba matematické komunikace

Matematika v dobách antického Řecka, starověkých Babyloňanů či počátků
civilizace v Číně (obecně před 1000 př. n.l.) se komunikovala místo
grafiky rétorikou. V této době ještě neexistuje nic jako teoretický
problém, protože koncepty v matematice jsou využívány jen na řešení
praktických problémů: například geometrie začíná v počítání rozměrů a
vzdáleností a algebra nachází své počátky v aritmetických
problémech[^4]^\[3\]\[7\]^.

Později v této době se matematika také začala zapisovat. Začátky zápisu
čísel vůbec přiřazujeme rytí značek do kamene či dřeva, kde každá z
čárek představovala jednu jednotku. Tato praktika byla používána v mnoha
kulturách a byla napříč nimi velmi podobná[^5] -- to zajisté přispívá k
tomu, že čárky používáme na některých místech dodnes (například pro
počítání skóre na amatérských sportovních zápasech, nebo ve
stereotypickém prostředí pro vězně, kteří si tak značkují počet dnů,
které ve vězení již strávili). ^\[příloha\ 1\]^

### Mezopotámie

Asi 2000 let př. n. l. začali obyvatelé tamější Mezopotámie zapisovat
číslice tzv. klínopisem[^6]. Tento systém používá místo našich
tradičních desíti číslic jenom dvě:
![](media/image3.png){width="0.22058836395450568in"
height="0.20833333333333334in"}pro zápis jednotek a
![](media/image1.png){width="0.22237423447069116in"
height="0.20833333333333334in"} pro zápis desítek, což dělá jejich zápis
podstatně jednodušší na naučení^\[11\]\[12\]^. Pomocí těchto dvou číslic
dokážeme zapsat číslo až 60^\[příloha\ 2\]^ (sexagesimální neboli
šedesátková soustava), přičemž se dají velmi jednoduše zapsat i čísla
mnohem větší: pokud si čísla nějak oddělíme (čárkou, mezerou apod.),
můžeme členy spočítat následujícím vzorcem:

$d_{i} \times 60^{i}$

kde $n$ je nejvyšší pořadová hodnota pozice, $d_{i}$ je číslice na
$i$-té pozici (přičemž pro nejpravější pozici platí, že $i\  = \ 0$) a
$60^{i}$ představuje mocninu 60 přiřazenou této pozici. Kupříkladu
sexagesimální číslo 1, 35, 25, 30 lze vyjádřit jako:

$1\  \times \ 60^{3}\  + \ 35\  \times \ 60^{2}\  + \ 25\  \times 60^{1}\  + \ 30\  \times 60^{0}\  = \ 343\ 530$
[^7]

Tento vzorec vyjadřuje babylonskou sexagesimální poziční soustavu a lze
jej použít k převodu libovolného sexagesimálního čísla na jeho dekadický
ekvivalent.

### Starověký Egypt

Ještě dříve než v Mezopotámii, se kolem 3. tisíciletí před Kristem
začala matematika zapisovat ve Starověkém Egyptě. Zde používali
dekadický neboli desítkový systém, ve kterém měli speciální
hieroglyfické symboly nejen pro celá čísla (10, 100, 1000, 10 000 a 100
000), ale i pro zlomky (½, ⅓, ⅔, ¼ a ⅕ )^\[5\]\[13\]^.

### Značení v Řecku

Jako jedno z prvních písmenných zápisů v Řecku se používalo dosud
nerozluštěné Lineární písmo A^\[47\]^ a již rozluštěné Lineární písmo
B^\[48\]^. Tyto zápisy používaly symboly dle následující
tabulky:^\[49\]^

  -----------------------------------------------------------------------
  Symbol                Číslo (des. soustava)
  --------------------- -------------------------------------------------
  \|                    1

  --                    10

  ◦                     100

  ¤                     1 000

  ☼                     10 000
  -----------------------------------------------------------------------

Tento systém později nahradily akrofonické attické číslice, které začaly
používat písmena řecké abecedy pro číselnou reprezentaci. Systém
fungoval velmi podobně k systému římských číslic (dokonce poněkud
jednodušeji): máme k dispozici písmena pro čísla začínající pětkou či
jedničkou a můžeme je kombinovat pro arbitrární počty:^\[49\]^

  -----------------------------------------------------------------------
  Symbol                Číslo (des. soustava)
  --------------------- -------------------------------------------------
  Ι                     1

  Π                     5

  Δ                     10

  ΠΔ                    50

  H                     100

  ΠΗ                    500

  X                     1 000

  ΠΧ                    5 000

  Μ[^8]                 10 000

  ΠΜ                    50 000
  -----------------------------------------------------------------------

## Synkopická fáze

V průběhu středověku, zhruba do 10. století našeho letopočtu, nastala ve
vývoji matematiky tzv. synkopická fáze. Tato fáze byla obdobím, kdy se
matematika postupně přesouvala z antických center do nově vznikajících
univerzit a studijních institucí. Ve středověké Evropě se během
synkopické fáze začaly objevovat nové matematické koncepty a metody,
které byly inspirovány znalostmi získanými z arabského světa a Indie.
Matematický vývoj probíhal zejména v oblasti algebry, trigonometrie a
geometrie.

### Al-Chorezmí a algebra

Perský matematik a astronom Al-Chorezmí (780--850 n.l.) představuje
jednu z klíčových postav synkopické fáze. Jeho dílo *[Hisáb al-džabr
wa-l-muqábala]{.mark}* se stalo základem pro vývoj algebry a přineslo
první systematické řešení lineárních a kvadratických rovnic. Slovo
\"algebra\" je odvozeno od arabského slova \"al-jabr\", které znamená
\"řešení\" nebo \"spojení\".^\[54\]^

### Indie a číslice

Indická matematika přinesla významné inovace, mezi nimiž stojí za zmínku
vynález indických číslic (1, 2, 3, \...), které se později staly
základem pro dnešní **hindsko-arabskou číselnou soustavu**. Ta byla
původně složena z devíti symbolů: 1 až 9, přičemž 0 se začala používat
později, nejprve v bakhshalském rukopisu^\[16\]^.

### Fibonacci a středověká Evropa

V Evropě sehrál významnou roli v šíření arabské matematiky italský
matematik Leonardo Fibonacci (1170--1250). Jeho kniha \"Liber Abaci\"
(Kniha počítání) z roku 1202 zpopularizovala používání hindsko-arabských
číslic v Evropě a představila řadu nových matematických konceptů a
technik, jako například Fibonacciho posloupnost.

### Modernější Řecko

Před tím, než se v Řecku objevily arabské číslice (kolem 15. století),
byl systém attických číslic nahrazen za iónský[^9], který používal
řeckou abecedu pro substituci všech jednotek[^10], desítek a stovek. To
znamená, že tento systém využil všech 27 písmen tehdejší abecedy a mohl
si velmi jednoduše poradit s čísly pod jeden tisíc.

Zápis vyšších čísel byl také možný: jednotky se často používaly jako
násobek tisíců (tisíc definovala čárka[^11] před nimi): "$͵\alpha$" byl
tisíc jeden, "$͵$ $\beta$" tisíce dva.^\[51\]^

### Čínský zápis

Čínský matematický zápis má bohatou historii a systém *huāmǎ* se stále
používá pro uvádění cen na trzích a v tradičních fakturách. Čínská
matematika vznikla kolem 11. století př. n. l. a přinesla významné
objevy, jako jsou záporná a desetinná čísla, dvojková soustava, algebra,
geometrie, nebo trigonometrie[^12].

Starověká čínská matematika se zaměřovala především na praktické
aplikace, například na zdokonalení zemědělského kalendáře. Pokroky byly
dosaženy v oblasti vývoje algoritmů a algebry, kdy čínská algebra
dosáhla svého vrcholu ve 13. století, což byla doba, ve které Zhu Shijie
předvedl svou metodu čtyř neznámých[^13].^\[3\]^

Ačkoli se čínská matematika a starověká středomořská matematika
pravděpodobně vyvíjely nezávisle, díky známé kulturní výměně docházelo k
určité výměně myšlenek. Například znalost Pascalova trojúhelníku
existovala v Číně již několik století před Pascalem.^\[3\]^

Za dynastie Sung (960-1279)^\[52\]^ se v Číně začala rozvíjet
trigonometrie, přičemž byl kladen důraz na sférickou trigonometrii v
kalendářní vědě a astronomických výpočtech. Vlivnými matematiky a
astronomy, kteří přispěli k rozvoji trigonometrie v Číně, byli Šen Kua a
Kuo Šou-ťing. Ve 13. století se do čínské matematické vědy začlenily
práce a učení arabských misionářů, kteří do Číny přinesli znalosti
sférické trigonometrie.^\[3\]^

^\[příloha\ 3\]^

## Symbolická fáze

Po synkopické fázi se nacházíme ve stejné fázi, která pokračuje do 21.
století. V této době matematického "novověku" se shledáváme s
prvopočátky a pokračování matematického zápisu, který používáme dodnes.
V průběhu této přes milénium-dlouhé doby se v oblasti matematiky
vytvořily stovky[^14] různých objevů a převratů, které jsou pro naši
dobu klíčové.[^15]

# Analýza různých symbolů

V moderní matematice najdeme symbolů opravdu mnoho, a proto je lepší u
nich zavést jednoduchou taxonomii. I samotných kategorií je ale pro naše
účely trochu moc a následuje výčet jejich zkrácené a upravené
verze[^16].

## Operátory aritmetiky

Mezi nejzákladnější symboly, které v oboru matematiky rozeznáváme, se
řadí aritmetické operátory. Do této kategorie patří ty nejpoužívanější
symboly, se kterými se setkáváme i v ne-matematických prostředích každý
den.

### + a -

Znaménko pluska má dva hlavní významy: jednoduché aritmetické sčítání
dvou symbolů, nebo jako denotace absence zápornosti[^17].

Znaménko mínus značí opak sčítání -- odčítání. Stejně jako plus se
používá k denotaci (tentokrát přítomnosti) zápornosti. Původ těchto
znamének není zcela jasný^\[19\]^, ale jako jedno z prvních děl, které
je zmiňuje, jest *Algorismus proportionum* od Mikuláše Oresma.
Znaménko + mělo v této době zkracovat latinské slovo pro spojku "a",
*et*, které se zkracovalo jen na písmeno t, připomínající dnešní sčítací
značku.

### ·, ×, ÷, :, a /

Symboly pro násobení (**·** a ×) jsme oba dostali v 17. století: symbol
× se prvně objevil v anonymním dodatku překladu od Edwarda Wrighta díla
Johna Napiera o logaritmech: *Mirifici Logarithmorum Canonis
Descriptio*^\[17\]\[18\]^. *"Tečku jako symbol pro násobení zavedl G. W.
Leibniz. Dne 29. července 1698 napsal v dopise Johnu Bernoullimu:
\"Nemám rád X jako symbol pro násobení, protože se snadno zaměňuje s x;
\... často prostě spojuji dvě veličiny pomocí vložené tečky a označuji
násobení* $ZC \cdot \ LM$*. Proto při označování poměru nepoužívám jednu
tečku, ale dvě tečky, které zároveň používám pro dělení.\"" (Cajori,
1928/2013, s. 267)*

Značky pro operaci opačnou násobení, dělení, je podstatně více. Možná
první psaný zápis dělení používal značku zavřené jednoduché závorky --
)[^18], i když tento zápis se jako jeden z mála neuchytil. V Česku
používáme převážně symbol **:**, který se pro dělení prvně objevil v
roce 1684[^\[18\]^]{.mark}. Více světově známý symbol dělení,
**[÷]{.mark}**[^19] [byl prvně použit v díle *Teutsche Algebra* z roku
1659^\[18\]^]{.mark}[^20][.]{.mark} V 18. století se začal používat
symbol horizontálního i diagonálního lomítka[^21], z kterého se vyvinuly
i značky pro procenta (%), promile ([‰]{.mark}) a bazického bodu
(‱)^\[23\]^. ^\[22\]^

### Ostatní aritmetické značky

Zbylé základní značky jsou značky mocnin a odmocnin. Mocniny tak jak je
značíme dnes (superskriptem jako $x^{2}$) začal poprvé používat René
Descartes v díle *La Geometrie* (1637)[^22][^23]^\[18\]^.

Pro odmocňování používáme převážně značku $$[^24]. Před ní se jako
denotace odmocnin používalo písmeno **R** a když v roce 1525 Christoph
Rudolff použil poprvé znak $$, bylo to bez vodorovné čáry nad
odmocninovým obsahem[^25]^\[18\]^.

Znaménko pro "plus mínus",
[![](media/image4.png){width="0.1111111111111111in"
height="0.1111111111111111in"}](https://www.codecogs.com/eqnedit.php?latex=%5Cpm#0),
vytvořil William Oughtred pro jeho spis *Clavis Mathematicae (1631)*.

## Značky číselných vztahů

Pro porovnání dvou nebo více čísel můžeme použít vztahové operátory.
Nejzákladnější znaménko z této kategorie je znaménko =. Tento symbol byl
zveřejněn poprvé v roce 1557 a byl popsán Robertem Recordem jako "pár
rovnoběžek".^\[24\]^

Pro popsání jakékoliv nerovnosti používáme $\neq$[^26]; pro nerovnost
určující "není větší než" používáme ≯ (a opačné ≮).[^27]

Za zmínku stojí samozřejmě i symboly pro větší než, ＞, větší nebo rovno
≥, a jejich protějšky menší než, ＜ a menší nebo rovno, ≤.[^28]

Při počítání s měřeními z reálného světa nebo komplexnějšími
matematickými koncepty[^29] se často používá aproximace[^30]^\[25\]^. Ta
se obecně značí znaménkem $\approx$, které značí, že si jsou dvě čísla
skoro rovná[^31]. S aproximací souvisí i zaokrouhlování (≐), přičemž
schválně snižujeme přesnost čísla pro jednodušší nakládání s ním[^32].

Pokud si opravdu nevíte rady a chcete, aby vaše rovnice platila za
pomocí jenom jednoho znaku, můžete použít ⪑, či ⪒ (méně než, více než,
nebo rovno a více než, méně než, nebo rovno).[^33]

## Značky logiky

Pro logické výroky používáme v matematice logické značky. Tyto symboly
můžeme používat nejen přímo v logice, ale i třeba v geometrii (symboly
$\exists$ pro "existuje", $\forall$ pro "pro všechny"[^34]).

### Podobnosti se symboly teorie množin

Podobnosti symbolů napříč matematikou nenajdeme v kontrastu s výrokovou
logikou jen u geometrie. Symboly podobné, nikoliv stejné, můžeme najít v
teorii množin.

-   **Průnik** ($\cap$ / *AND*): Průnik dvou množin A a B, značený jako
    > A $\cap$ B, je množina obsahující všechny prvky, které jsou
    > součástí jak množiny A, tak množiny B.

-   **Sjednocení** ($\cup$ / *OR*): Sjednocení dvou množin A a B,
    > značené jako A $\cup$ B, je množina obsahující všechny prvky,
    > které jsou součástí alespoň jedné z množin A nebo B.

Výroková logika se na druhou stranu zabývá vztahy mezi výroky
(tvrzeními) a jejich pravdivostními hodnotami. Základní operace výrokové
logiky zahrnují:

-   **Konjunkci** ($\land$ / *AND*): Konjunkce dvou výroků p a q,
    > značená jako $p\  \land q$, je pravdivá, pokud jsou pravdivé oba
    > výroky p i q. Jinak je nepravdivá.

-   **Disjunkci** ($\vee$ / *OR*): Disjunkce dvou výroků p a q, značená
    > jako $p\  \vee q$, je pravdivá, pokud je pravdivý alespoň jeden z
    > výroků p nebo q.

### Ostatní logické symboly

V knize *Die formalen Regeln der intuitionistischen Logik* zavedl Arend
Heyting pro logickou negaci znak ¬^\[30\]\[31\]^, který je pro
jednodušší zápis v některých kontextech zaměňován za vlnovku (˜) nebo
vykřičník (!)[^35]^\[6\]^.

Pokud máme výrok, který vede k jinému výroku, používáme znaky jako
⇒[^36] (implikace, pokud A je pravda, B také), ∴ (symbol pro "takže":
$x + 1 = 10\ \therefore\ x\  = 9$^\[38\]^), nebo jeho obrácenou formu, ∵
(protože)[^37].

Symboly logiky jsou velmi hojně užívané i v rozsáhlých knižních dílech,
jako je například *Principia Mathematica* od Alfreda N. Whiteheada a
Bertranda Russella. Toto třísvazkové dílo používá symbolickou logiku pro
stovky důkazů, z kterých jeden je důkaz výroku $1\  + 1 = 2$. Autoři k
němu ironicky dodávají, že "Výše uvedené tvrzení je občas užitečné"
(Whitehead & Russell, 1910/2005, s. 86). V této trilogii se také poprvé
objevují symboly $p$ a $q$ pro zapisování konceptů jako je podmíněná
pravděpodobnost.

## Ostatní značky

Do této kategorie řadím značky, které se sice používají často, ale patří
do oborů, pro které to platí jen pro málo symbolů.

Příkladem z těch obecnějších je suma (Σ), kterou v roce 1755 začal
používat Euler^\[26\]^, podobně jako značky nerovnostních vztahů, o
kterých jsme se bavili pár kapitol zpátky.

Znak pro prázdnou množinu, ∅, je jeden z těch nejnovějších (zaveden až v
roce 1939). Před tím, než jsme ho dostali, se prázdné množiny zapisovaly
jako {}^\[26\]^.

Za zapisováním konceptu nekonečna stojí John Wallis, který pro něj v 50.
letech 17. století použil tzv. lemniskátu[^38] -- populárně nazývanou
"ležatou osmičkou": ∞. Důvod k využití zrovna tohoto symbolu není jistě
známý, ale jedna z populárních teorií tvrdí, že je to prostá adaptace
symbolu římského čísla pro číslo jeden tisíc: CIƆ nebo jednoduše
CƆ[^39]^\[39\]\[40\]^.

Pokud chceme znázornit, že prvek náleží nebo nenáleží nějaké množině,
používáme symbol ∈ a jeho opak ∉, které se používají od konce 19.
století.^\[26\]^

## Matematické konstanty 

Někdy reprezentujeme i speciální čísla matematiky symboly, protože je
pro některé nemožné zapsat jejich plný číselný rozvoj.

### π

Ludolfovo číslo, zapisované minuskulou řeckého písmena pí[^40] vyjadřuje
poměr obvodu kruhu k jeho průměru. Jeho přibližná hodnota v desítkové
soustavě je 3,14 a proto se každého 14. března slaví mezinárodní den
𝛑[^41]. Toto řecké písmeno bylo poprvé použito podle naší dnešní
definice v roce 1706 Williamem Jonesem.^\[44\]^ 𝛑 je používáno kvůli
tomu, že je prvním písmenem pro slovo "obvod" v řečtině,
περίμετρος^\[43\]^.

### $e$

Pro zapisování Eulerova čísla se používá malé písmeno E. Je základem
přirozených logaritmů a jeho přibližná hodnota činí 2,71828.^\[45\]^

Písmeno sice zavedl Euler, ale neoznačuje první písmeno jeho příjmení:
přesný původ písmena není známý.^\[44\]^

### ɸ

Malé řecké fí, nazývané také "zlatý řez" označuje poměr, který *"vznikne
rozdělením úsečky na dvě části tak, že poměr větší části k menší je
stejný jako poměr celé úsečky k větší části"* (Přispěvatelé projektů
Wikimedia, 2023). Tento poměr se dá vyjádřit jako následující rovnice:

$\varphi\  = \ 1 + \frac{1 +}{2}$ ^\[46\]^

Původ používání fí pro označení zlatého řezu je sporný. Některé zdroje
uvádějí, že se \"fí\" začalo používat na počátku 20. století na počest
řeckého sochaře Feidia, který zlatý řez hojně používal ve svých
dílech.^\[44\]\[46\]^

## Znaky číselných oborů 

I když čísla byla označována již dříve, od konce 19. století používáme
naše moderní jednopísmenné zkratky pro různé číselné obory, psané
převážně zdvojeným písmem[^42]. Tyto zkratky začaly písmenem ℕ (dříve
J^\[42\]^) pro přirozená čísla a písmenem ℚ pro čísla racionální (obě
zavedeny 1895^\[26\]^). V roce 1930 jsme dostali ℤ pro čísla celá a o
devět let později přišlo písmeno ℂ pro čísla komplexní (ze všech
nejspíše nejméně používané[^43]).^\[26\]^

# LaTeX *\[latech\]*

Digitální doba přinesla v oblasti matematického zápisu významný pokrok a
inovace. Jedním z nejrozšířenějších nástrojů pro vytváření, formátování
a prezentaci matematických výrazů a symbolů v digitálním prostředí je
LaTeX. Cílem této kapitoly je proniknout do konceptu digitální notace se
zaměřením na LaTeX, prozkoumat jeho vznik, funkce a výhody.

## Původ a účel LaTeXu

LaTeX je systém pro zápis vytvořený Leslie Lamportem na počátku 80. let
20. století^\[29\]^. Je postaven na písmolijectví TeX, které navrhl
Donald Knuth s cílem vytvářet dokumenty profesionální kvality, které
dodržují nejvyšší typografické standardy.^\[28\]^ LaTeX byl speciálně
navržen pro zpracování složitých matematických zápisů a měl autorům
usnadnit vytváření dobře formátovaných dokumentů, zejména těch, které
obsahují značné množství matematických symbolů a výrazů.

##  Vlastnosti LaTeXu

LaTeX je v podstatě značkovací jazyk, který uživatelům umožňuje vytvářet
dokumenty s vysokou úrovní kontroly nad formátováním a prezentací. Mezi
jeho klíčové vlastnosti patří např.:

a.  Syntaxe založená na příkazech: LaTeX používá řadu příkazů k
    > definování prvků v dokumentu. Příkazy obvykle začínají zpětným
    > lomítkem (\\), za kterým následuje název příkazu a volitelné
    > parametry uzavřené primárně ve složených závorkách. Například $$
    > jde v LaTeXu zapsat jako \\sqrt{2}.

b.  Modulární struktura: Dokumenty LaTeXu jsou uspořádány do logických
    > jednotek nazývaných prostředí, které jsou definovány pomocí
    > dvojice příkazů (\\begin a \\end). Tato modulární struktura
    > umožňuje lepší organizaci a snadnější správu složitých dokumentů.

c.  Balíčky a makra: Uživatelé mohou vytvářet vlastní makra nebo
    > importovat existující balíčky a rozšiřovat tak funkčnost LaTeXu,
    > díky čemuž je vysoce přizpůsobitelný různým potřebám. Toto
    > umožňuje uživatelům LaTeXu zapisovat nejen matematiku, ale i
    > složité chemické sloučeniny[^44] nebo elektrické obvody[^45].

d.  Správa bibliografie: LaTeX nabízí účinné nástroje pro správu
    > bibliografických odkazů a citací, včetně systémů BibTeX a
    > BibLaTeX.^\[27\]^

##  Výhody použití LaTeXu pro matematický zápis

LaTeX nabízí oproti tradičním textovým procesorům několik výhod, pokud
jde o práci s matematickým zápisem:

a.  Přesnost a konzistence: Syntaxe LaTeXu založená na příkazech
    > umožňuje přesnou a konzistentní kontrolu nad formátováním a
    > prezentací matematických výrazů. Zápisová syntaxe LaTeXu je
    > zabudována v mnoha populárních online nástrojích, a proto není
    > nutné se učit pro každé prostředí nový "jazyk".

b.  Profesionální vzhled: LaTeX vytváří vysoce kvalitní výstupy, které
    > splňují přísné typografické standardy profesionálních publikací.

c.  Škálovatelnost: Dokumenty LaTeXu lze snadno převádět do různých
    > formátů, jako jsou PDF, HTML a XML, což usnadňuje sdílení a
    > publikování práce.

d.  Spolupráce: Soubory LaTeX jsou prosté textové dokumenty, což
    > zjednodušuje spolupráci a kontrolu revizí.

# Závěr

V průběhu této práce jsme se zaměřili na matematickou notaci jako
univerzální jazyk, který je základním prvkem vědy a inženýrství.
Prozkoumali jsme historii matematických značek, dostali jsme se i k
jejich kategorizaci a analýze. Dále jsme se zabývali digitálním
zpracováním matematické notace a jejím nynějším šířením.

Historie matematických značek nám ukázala, že matematická notace má
hluboké kořeny, které sahají až do starověkých civilizací. V průběhu
staletí se matematická notace vyvíjela a zpřesňovala, což vedlo k její
dnešní formě, která je celosvětově univerzální a exaktní.

Kategorizace matematických značek nám poskytla ucelený přehled o různých
typech symbolů, které se používají v matematickém zápisu. Ukázalo se, že
matematická notace je velmi rozmanitá, ale zároveň logicky uspořádaná a
ucelená.

Analýza vybraných matematických značek přinesla vhled do důležitých
konceptů, které formují základy matematiky a vědy. Zdůraznila také,
jakým způsobem matematická notace zjednodušuje a zefektivňuje komunikaci
vědeckých a matematických myšlenek.

Digitální zpracování matematické notace a její distribuce
prostřednictvím moderních médií umožňuje rychlejší a efektivnější přenos
informací. To má zásadní dopad na vývoj vědy, technologií a celkového
pokroku lidské civilizace.

V konečném důsledku je matematická notace základním kamenem vědecké
komunikace a hraje klíčovou roli ve všech oborech, které využívají
matematiku. Porozumění a zvládnutí matematické notace je tedy nezbytné
pro úspěch ve vědeckých a inženýrských disciplínách. Osobně doufám, že
tato práce poskytla čtenáři ucelený a zajímavý vhled do světa
matematických značek a jejich významu pro komunikaci a pokrok v různých
oblastech lidského poznání.

## Budoucnost značení matematiky

Podle mých pozorování nebude v budoucnu velká potřeba symboly měnit nebo
k nim přidávat. Možná se v oboru matematiky objeví nějaká zcela
nezmapovaná věda, které koncepty si nedokážeme ani představit, ale
myslím si, že pokud budeme do naší matematické sady značky přidávat,
bude to proto, že budeme potřebovat velmi komplexní koncepty abstrahovat
(stejně jako jsme abstrahovali násobení ze sčítání a mocnění z
násobení).

## Další čtení

Při psaní této práce jsem narazil na mnoho různých témat, na které už v
ní nebyl prostor. Zde je z nich výtažek:

-   **Polský zápis**: alternativní metoda zapisování matematických
    > výrazů. Článek na anglické Wikipedii, [[Polish
    > notation]{.underline}](https://en.wikipedia.org/wiki/Polish_notation),
    > o něm referuje do hloubky.

-   Různá nekonečna: při psaní o symbolu ∞ jsem narazil na video od
    > Michaela Stevense, [[How To Count Past
    > Infinity]{.underline}](https://youtu.be/SrU9YDoXE88), ve kterém
    > vysvětluje různé typy nekonečen. Ve videu [[The Banach--Tarski
    > Paradox]{.underline}](https://youtu.be/s86-Z-CbaHA) o nich mluví
    > dále.

-   Kniha *A History of Mathematical Notations* od Floriána Cajoriho,
    > která v tomto oboru slouží jako jedna z těch klíčových, je zdroj s
    > mnohem více symboly a jejich původy.

-   Matematická logika: vědní disciplína, která stojí na podstatě
    > matematiky a zdůvodňuje její základní pravidla. Symbolická logika
    > (která s matematickou logikou úzce souvisí), zmíněná v odstavci o
    > knize *Principia Mathematica*, má podle mého svou krásu a kromě
    > toho, že je celá dostupná online, je i hezky shrnutá v podkapitole
    > videa od Dereka Mullera, [[Math\'s Fundamental
    > Flaw]{.underline}](https://youtu.be/HeQX2HjkcNo?t=693).

-   Povídání o čínském zapisování čísel bylo enormně zkráceno. Na
    > anglické Wikipedii je o něm rozsáhlý článek: [[Chinese numerals --
    > Wikipedia]{.underline}](https://en.wikipedia.org/wiki/Chinese_numerals).

-   V kapitole o [[Indii v synkopické
    > fázi]{.underline}](#indie-a-číslice) je zmínka o začátcích
    > hindsko-arabských číslic. Ideálně by toho o nich zde bylo více,
    > ale moc hezký článek o něm má česká Wikipedie: [[Hindsko-arabská
    > číselná
    > soustava]{.underline}](https://cs.wikipedia.org/wiki/Hindsko-arabsk%C3%A1_%C4%8D%C3%ADseln%C3%A1_soustava).

## Poděkování

Na závěr bych taky chtěl vyjádřit můj osobní dík následujícím lidem, bez
kterých by v této podobě práce nevznikla:

-   panu **Bc. Adriánovi Majorosovi** -- vedoucímu práce, který poskytl
    > neocenitelné množství zpětné vazby a nápadů (je tu podle jednoho z
    > jeho nápadů i celá kapitola, [[Podobnosti se symboly teorie
    > množin]{.underline}](#podobnosti-se-symboly-teorie-množin))

-   **Floriánu Cajorimu** a jeho dílům mapujícím vznik a zánik
    > všemožných matematických symbolů

    -   také **Jeffu Millerovi** za zmapování jeho děl a jejich
        > obohacení o moderní pochopitelnost. Pan Miller vytvořil portál
        > pro Univerzitu St. Andrews ve Skotsku, která sloužila jako
        > primární zdroj mé práce.

-   panu **Dereku Alexandru Mullerovi, Michaelovi Davidovi Stevensovi**
    > a panu **Danielovi Ivanovi Flaigovi** za nadchnutí do
    > problematiky.

-   paní **Mgr. Jindře Glogrové** za poskytnutí nápadů ke zpracovaným
    > tématům práce.

#  Seznam použitých informačních zdrojů

1.  Latinka. (7. 11. 2022). *Wikipedie: Otevřená encyklopedie*. Získáno
    > 12:07, 11. 02. 2023 z
    > [[https://cs.wikipedia.org/w/index.php?title=Latinka&oldid=21849674]{.underline}](https://cs.wikipedia.org/w/index.php?title=Latinka&oldid=21849674).

2.  Miller, J. (n.d.). *Earliest Uses of Various Mathematical Symbols*.
    > Maths History; School of Mathematics and Statistics University of
    > St Andrews, Scotland. Retrieved April 16, 2023, from
    > [[https://mathshistory.st-andrews.ac.uk/Miller/mathsym/]{.underline}](https://mathshistory.st-andrews.ac.uk/Miller/mathsym/)

3.  Wikipedia contributors. (2023, February 10). History of mathematical
    > notation. In *Wikipedia, The Free Encyclopedia*. Retrieved 08:43,
    > April 11, 2023, from
    > [[https://en.wikipedia.org/w/index.php?title=History_of_mathematical_notation&oldid=1138568632]{.underline}](https://en.wikipedia.org/w/index.php?title=History_of_mathematical_notation&oldid=1138568632)

4.  Wikipedia contributors. (2023, March 16). Roman numerals. In
    > Wikipedia, The Free Encyclopedia. Retrieved 15:20, April 9, 2023,
    > from
    > [[https://en.wikipedia.org/w/index.php?title=Roman_numerals&oldid=1144895332]{.underline}](https://en.wikipedia.org/w/index.php?title=Roman_numerals&oldid=1144895332)

5.  Wikipedia Contributors. (2019, September 18). Ancient Egyptian
    > mathematics. Wikipedia; Wikimedia Foundation.
    > [[https://en.wikipedia.org/wiki/Ancient_Egyptian_mathematics]{.underline}](https://en.wikipedia.org/wiki/Ancient_Egyptian_mathematics)

6.  Wikipedia contributors. (2023, March 27). Glossary of mathematical
    > symbols. In *Wikipedia, The Free Encyclopedia*. Retrieved 19:17,
    > April 9, 2023, from
    > [[https://en.wikipedia.org/w/index.php?title=Glossary_of_mathematical_symbols&oldid=1146912113]{.underline}](https://en.wikipedia.org/w/index.php?title=Glossary_of_mathematical_symbols&oldid=1146912113)

7.  Wikipedia contributors. (2023, April 9). Timeline of mathematics. In
    > *Wikipedia, The Free Encyclopedia*. Retrieved 19:18, April 9,
    > 2023, from
    > [[https://en.wikipedia.org/w/index.php?title=Timeline_of_mathematics&oldid=1148958986]{.underline}](https://en.wikipedia.org/w/index.php?title=Timeline_of_mathematics&oldid=1148958986)

8.  Wikipedia contributors. (2023, April 5). Tally marks. In *Wikipedia,
    > The Free Encyclopedia*. Retrieved 19:19, April 9, 2023, from
    > [[https://en.wikipedia.org/w/index.php?title=Tally_marks&oldid=1148299491]{.underline}](https://en.wikipedia.org/w/index.php?title=Tally_marks&oldid=1148299491)

9.  Matematika. (19. 11. 2022). *Wikipedie: Otevřená encyklopedie*.
    > Získáno 19:20, 9. 04. 2023 z
    > [[https://cs.wikipedia.org/w/index.php?title=Matematika&oldid=21909601]{.underline}](https://cs.wikipedia.org/w/index.php?title=Matematika&oldid=21909601).

10. Sklářová, E. (2009). Historie matematiky ve vztahu k vyučování
    > matematiky na 2. stupni ZŠ. *Pedagogická Fakulta Masarykovy
    > Univerzity*.
    > [[https://is.muni.cz/th/gzc4v/diplomova_prace_sklarova.pdf]{.underline}](https://is.muni.cz/th/gzc4v/diplomova_prace_sklarova.pdf)

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

14. Wikipedia contributors. (2023, April 1). Rounding. In Wikipedia, The
    > Free Encyclopedia. Retrieved 18:29, April 9, 2023, from
    > [[https://en.wikipedia.org/w/index.php?title=Rounding&oldid=1147749195]{.underline}](https://en.wikipedia.org/w/index.php?title=Rounding&oldid=1147749195)

15. [[https://archive.org/details/historyofmathema031756mbp/page/n267/mode/2up]{.underline}](https://archive.org/details/historyofmathema031756mbp/page/n267/mode/2up)

16. Wikipedia contributors. (2023, April 4). 0. In *Wikipedia, The Free
    > Encyclopedia*. Retrieved 15:11, April 9, 2023, from
    > <https://en.wikipedia.org/w/index.php?title=0&oldid=1148210764>

17. Arndt, G. (2021, May 29). *The History of Mathematical Symbols*.
    > Everything Everywhere.
    > [[https://everything-everywhere.com/the-history-of-mathematical-symbols/]{.underline}](https://everything-everywhere.com/the-history-of-mathematical-symbols/)

18. Miller, J. (n.d.). *Earliest Uses of Symbols of Operation*. Maths
    > History; University of St Andrews. Retrieved April 9, 2023, from
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

24. Miller, J. (n.d.). *Earliest Uses of Symbols of Relation*. Maths
    > History; University of St Andrews. Retrieved April 9, 2023, from
    > [[https://mathshistory.st-andrews.ac.uk/Miller/mathsym/relation/]{.underline}](https://mathshistory.st-andrews.ac.uk/Miller/mathsym/relation/)

25. Matematické symboly a značky. (7. 02. 2023). *Wikipedie: Otevřená
    > encyklopedie*. Získáno 17:34, 9. 04. 2023 z
    > [[https://cs.wikipedia.org/w/index.php?title=Matematick%C3%A9_symboly_a_zna%C4%8Dky&oldid=22422578]{.underline}](https://cs.wikipedia.org/w/index.php?title=Matematick%C3%A9_symboly_a_zna%C4%8Dky&oldid=22422578).

26. Wikipedia contributors. (2023, March 5). Table of mathematical
    > symbols by introduction date. In Wikipedia, The Free Encyclopedia.
    > Retrieved 18:02, April 9, 2023, from
    > [[https://en.wikipedia.org/w/index.php?title=Table_of_mathematical_symbols_by_introduction_date&oldid=1143096798]{.underline}](https://en.wikipedia.org/w/index.php?title=Table_of_mathematical_symbols_by_introduction_date&oldid=1143096798)

27. *Bibliography management with biblatex*. (n.d.). Overleaf. Retrieved
    > April 9, 2023, from
    > [[https://cs.overleaf.com/learn/latex/Bibliography_management_with_biblatex]{.underline}](https://cs.overleaf.com/learn/latex/Bibliography_management_with_biblatex)

28. Wikipedia contributors. (2023, March 29). TeX. In *Wikipedia, The
    > Free Encyclopedia*. Retrieved 19:00, April 9, 2023, from
    > [[https://en.wikipedia.org/w/index.php?title=TeX&oldid=1147287358]{.underline}](https://en.wikipedia.org/w/index.php?title=TeX&oldid=1147287358)

29. LaTeX. (21. 02. 2021). *Wikipedie: Otevřená encyklopedie*. Získáno
    > 19:01, 9. 04. 2023 z
    > [[https://cs.wikipedia.org/w/index.php?title=LaTeX&oldid=19512927]{.underline}](https://cs.wikipedia.org/w/index.php?title=LaTeX&oldid=19512927).

30. Conifold, & Brother, B. (2022, August 6). *mathematics -- What is
    > the origin of the negation ( ¬ ) operator from logic?* History of
    > Science and Mathematics Stack Exchange.
    > [[https://hsm.stackexchange.com/a/14661]{.underline}](https://hsm.stackexchange.com/a/14661)

31. Miller, J. (n.d.). *Earliest Uses of Symbols of Set Theory and
    > Logic*. Maths History; University of St Andrews. Retrieved April
    > 9, 2023, from
    > [[https://mathshistory.st-andrews.ac.uk/Miller/mathsym/set/]{.underline}](https://mathshistory.st-andrews.ac.uk/Miller/mathsym/set/)

32. Wikipedia contributors. (2023, April 12). List of logic symbols. In
    > Wikipedia, The Free Encyclopedia. Retrieved 09:09, April 15, 2023,
    > from
    > [[https://en.wikipedia.org/w/index.php?title=List_of_logic_symbols&oldid=1149469874]{.underline}](https://en.wikipedia.org/w/index.php?title=List_of_logic_symbols&oldid=1149469874)

33. *11 things you never knew about mathematical symbols*. (2021, July
    > 30). Mathematics; University of Waterloo.
    > [[https://uwaterloo.ca/math/eleven-things-math-symbols]{.underline}](https://uwaterloo.ca/math/eleven-things-math-symbols)

34. Lista symboli matematycznych. (2023, marzec 26). *Wikipedia, wolna
    > encyklopedia*. Dostęp 09:35, kwiecień 15, 2023, Dostępny w
    > Internecie:
    > [[https://pl.wikipedia.org/w/index.php?title=Lista_symboli_matematycznych&oldid=69961529]{.underline}](https://pl.wikipedia.org/w/index.php?title=Lista_symboli_matematycznych&oldid=69961529)

35. Whitehead, A. N., & Russell, B. (2005). *Principia mathematica, by
    > Alfred North Whitehead \... and Bertrand Russell.* (p. 86). Ann
    > Arbor, Michigan: University of Michigan Library.
    > [[https://quod.lib.umich.edu/u/umhistmath/aat3201.0002.001]{.underline}](https://quod.lib.umich.edu/u/umhistmath/aat3201.0002.001)
    > (Original work published 1910)

36. Veritasium. (2021, May 22). *This is Math's Fatal Flaw*. YouTube.
    > [[https://www.youtube.com/watch?v=HeQX2HjkcNo]{.underline}](https://www.youtube.com/watch?v=HeQX2HjkcNo)

37. Miller, J. (n.d.). *Earliest Uses of Symbols in Probability and
    > Statistics*. Maths History; University of St Andrews. Retrieved
    > April 9, 2023, from
    > [[https://mathshistory.st-andrews.ac.uk/Miller/mathsym/stat/]{.underline}](https://mathshistory.st-andrews.ac.uk/Miller/mathsym/stat/)

38. Wikipedia contributors. (2023, February 18). Therefore sign. In
    > *Wikipedia, The Free Encyclopedia*. Retrieved 06:50, February 18,
    > 2023, from
    > [[https://en.wikipedia.org/w/index.php?title=Therefore_sign&oldid=1140063065]{.underline}](https://en.wikipedia.org/w/index.php?title=Therefore_sign&oldid=1140063065)

39. *Infinity Symbol and Roman Numerals*. (n.d.). Roman Numerals.
    > Retrieved April 15, 2023, from
    > [[https://www.romannumerals.org/blog/infinity-symbol-and-roman-numerals-2]{.underline}](https://www.romannumerals.org/blog/infinity-symbol-and-roman-numerals-2)

40. *Why is infinity an 8? -- WittyQuestion.com*. (2020, November 26).
    > WITTYQUESTION.com.
    > [[https://witty-question.com/why-is-infinity-an-8/]{.underline}](https://witty-question.com/why-is-infinity-an-8/#:~:text=The%20most%20accepted%20theory%20for%20the%20chpice%20of)

41. *Seznam často užívaných symbolů*. (n.d.). Mendelu.cz; Mendelova
    > univerzita v Brně. Retrieved April 15, 2023, from
    > [[https://is.mendelu.cz/eknihovna/opory/zobraz_cast.pl?cast=9110]{.underline}](https://is.mendelu.cz/eknihovna/opory/zobraz_cast.pl?cast=9110)

42. Rudin, W. (1976). *Principles of Mathematical Analysis* (3rd ed.).
    > McGraw-Hill. ISBN 978-0-07-054235-8.

43. Pí (číslo). (28. 03. 2023). *Wikipedie: Otevřená encyklopedie*.
    > Získáno 09:38, 16. 04. 2023 z
    > [[https://cs.wikipedia.org/w/index.php?title=P%C3%AD\_(%C4%8D%C3%ADslo)&oldid=22583512]{.underline}](https://cs.wikipedia.org/w/index.php?title=P%C3%AD_(%C4%8D%C3%ADslo)&oldid=22583512).

44. Miller, J. (n.d.). *Earliest Uses of Symbols for Constants*. Maths
    > History; University of St Andrews. Retrieved April 9, 2023, from
    > [[https://mathshistory.st-andrews.ac.uk/Miller/mathsym/constants/]{.underline}](https://mathshistory.st-andrews.ac.uk/Miller/mathsym/constants/)

45. Eulerovo číslo. (23. 02. 2023). *Wikipedie: Otevřená encyklopedie*.
    > Získáno 09:42, 16. 04. 2023 z
    > [[https://cs.wikipedia.org/w/index.php?title=Eulerovo\_%C4%8D%C3%ADslo&oldid=22485298]{.underline}](https://cs.wikipedia.org/w/index.php?title=Eulerovo_%C4%8D%C3%ADslo&oldid=22485298).

46. Zlatý řez. (28. 02. 2023). *Wikipedie: Otevřená encyklopedie*.
    > Získáno 09:53, 16. 04. 2023 z
    > [[https://cs.wikipedia.org/w/index.php?title=Zlat%C3%BD\_%C5%99ez&oldid=22502229]{.underline}](https://cs.wikipedia.org/w/index.php?title=Zlat%C3%BD_%C5%99ez&oldid=22502229).

47. Lineární písmo A. (17. 10. 2021). *Wikipedie: Otevřená
    > encyklopedie*. Získáno 10:36, 16. 04. 2023 z
    > [[https://cs.wikipedia.org/w/index.php?title=Line%C3%A1rn%C3%AD_p%C3%ADsmo_A&oldid=20554096]{.underline}](https://cs.wikipedia.org/w/index.php?title=Line%C3%A1rn%C3%AD_p%C3%ADsmo_A&oldid=20554096).

48. Lineární písmo B. (2. 12. 2021). *Wikipedie: Otevřená encyklopedie*.
    > Získáno 10:36, 16. 04. 2023 z
    > [[https://cs.wikipedia.org/w/index.php?title=Line%C3%A1rn%C3%AD_p%C3%ADsmo_B&oldid=20690040]{.underline}](https://cs.wikipedia.org/w/index.php?title=Line%C3%A1rn%C3%AD_p%C3%ADsmo_B&oldid=20690040).

49. Alegsa, L. (2021, June 21). *Řecké číslice*. AlegsaOnline.com.
    > Retrieved April 16, 2023, from
    > [[https://cs.alegsaonline.com/art/40638]{.underline}](https://cs.alegsaonline.com/art/40638)

50. Yolkowski, J. (2014, September 15). *Greek Ionic Numerals*. Math
    > Lair. Retrieved April 16, 2023, from
    > [[https://mathlair.allfunandgames.ca/ionic.php]{.underline}](https://mathlair.allfunandgames.ca/ionic.php)

51. Wikipedia contributors. (2023, January 27). Greek numerals. In
    > *Wikipedia, The Free Encyclopedia*. Retrieved 12:23, April 16,
    > 2023, from
    > [[https://en.wikipedia.org/w/index.php?title=Greek_numerals&oldid=1135872001]{.underline}](https://en.wikipedia.org/w/index.php?title=Greek_numerals&oldid=1135872001)

52. Britannica, T. Editors of Encyclopaedia (n. d.). *Song dynasty*.
    > *Encyclopedia Britannica*.
    > [[https://www.britannica.com/topic/Song-dynasty]{.underline}](https://www.britannica.com/topic/Song-dynasty)

53. Florian Cajori. (2013). *A history of mathematical notations* (p.
    > 267). Dover Publications, Inc.
    > [[https://monoskop.org/images/2/21/Cajori_Florian_A_History_of_Mathematical_Notations_2_Vols.pdf]{.underline}](https://monoskop.org/images/2/21/Cajori_Florian_A_History_of_Mathematical_Notations_2_Vols.pdf)
    > (Original work published 1928)

54. Al-Chorezmí. (24. 01. 2023). *Wikipedie: Otevřená encyklopedie*.
    > Získáno 16:29, 17. 04. 2023 z
    > [[https://cs.wikipedia.org/w/index.php?title=Al-Chorezm%C3%AD&oldid=22377040]{.underline}](https://cs.wikipedia.org/w/index.php?title=Al-Chorezm%C3%AD&oldid=22377040).

# Seznam příloh

> **Příloha 1 -- Počítací značky**
>
> ![](media/image2.png){width="6.101744313210848in"
> height="1.5277777777777777in"}
>
> Benjamin D. Esham, Public domain, prostřednictvím Wikimedia Commons
>
> **Příloha 2 -- Sexagesimální soustava používaná v Mezopotámii**
>
> ![](media/image5.png){width="6.101744313210848in"
> height="3.611111111111111in"}
>
> Josell7, [[CC BY-SA
> 4.0]{.underline}](https://creativecommons.org/licenses/by-sa/4.0),
> prostřednictvím Wikimedia Commons
>
> **Příloha 3 -- Čínské tyčové číslice**
>
> ![undefined](media/image6.png){width="6.101744313210848in"
> height="2.0277777777777777in"}
>
> By cmglee -- Own work, CC BY-SA 4.0,
> [[https://commons.wikimedia.org/w/index.php?curid=66097284]{.underline}](https://commons.wikimedia.org/w/index.php?curid=66097284)

[^1]: Alespoň to jest jejich účel; ozdrojovaný text nespolehlivými
    zdroji není zdaleka žádná výhra.

[^2]: Tím je myšlena komunikace s použitím složitějších symbolů než
    piktogramů jako jsou dopravní značky nebo emotikony.

[^3]: V jiných slovech: romantickou poezii v ní nenapíšete.

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

[^8]: Zde je zajímavý rozdíl mezi římským a řeckým systémem: M v římské
    soustavě reprezentuje 1 000, přičemž zde reprezentuje 10 000. M v
    římském pojetí totiž pochází z latinského *mille* a v řeckém ze
    slova *μύριοι* (nesčetný).

[^9]: V některých kontextech je používán dodnes^\[51\]^

[^10]: Vyjma nuly

[^11]: Doopravdy to není čárka, ale *levá keraia*^\[49\]^ a má v znakové
    soustavě Unicode svůj vlastní znak: *U+0375*

[^12]: "Objevy", protože informace se ještě tak rychle celosvětově
    nešířily, takže různé matematické koncepty byly objeveny na více
    místech nezávisle na sobě.

[^13]: [[Jade Mirror of the Four Unknowns --
    Wikipedia]{.underline}](https://en.wikipedia.org/wiki/Jade_Mirror_of_the_Four_Unknowns)

[^14]: Příklady různých důležitých poznatků z této doby jsou na
    [[Wikipedii]{.underline}](https://en.wikipedia.org/w/index.php?title=Timeline_of_mathematics#Symbolic_stage).
    Jenom v tomto článku jich je vyjmenováno 246.

[^15]: Ano, ironii o tom, že ta nejzajímavější doba má jen jeden
    odstavec chápu, nicméně se v další kapitole zabýváme skoro jenom s
    ní. Časové a pravidlové meze této práce nám na tuto éru bohužel
    nedaly čas.

[^16]: Tato sekce je převážně zaměřena na symboly, se kterými je
    nejspíše čtenář již seznámen. Poučování čtenáře o novém symbolu a
    následném poukázání na jeho historii ztrácí smysl a zájem o tato
    historická data, když čtenář o symbol neměl zájem předem. Významně
    zde chybí znaky týkající se pravděpodobnosti, kalkulu, lineární
    algebry, trigonometrie a geometrie.

[^17]: U záporných čísel zápornost vždy určujeme znaménkem mínus
    (**-**), ale u nezáporných hodnot se většinou neudává.

[^18]: Například 24)3 = 8.

[^19]: Tomuto znaku se říká *obelos*.

[^20]: Tento symbol je ale kvůli jeho chybějící univerzálnosti podle
    standardu ISO 80000-2 nedoporučován.

[^21]: Značka je také známá jako *solidus* nebo diagonála.

[^22]: Mocniny jsou v tomto ohledu velmi zajímavé: neznačíme je
    symbolem, ale velikostí písma. V některých kontextech se také pro
    mocnění používá značka \^.

[^23]: Historii mocnění samotného hezky popisuje stránka [[History of
    Exponents \|
    Sutori]{.underline}](https://www.sutori.com/en/story/history-of-exponents--wNbwYExXdzFNYPh1zFUYhbDc).

[^24]: Neplést s ✓.

[^25]: Tuto vodorovnou čáru, latinsky *vinculum* přidal odmocninám ve
    stejném díle jako formát pro moderní mocniny Descartes.

[^26]: Pro podobné účely můžeme použít i znaménka "více, nebo méně než"
    -- ≷, a také "méně, nebo více než" -- ≶.

[^27]: Sem se dají ještě zařadit symboly ≨ (ne méně, ale ne rovno) a ≩
    (ne více, ale ne rovno).

[^28]: K nim můžeme také zařadit symboly mnohem více než (≫) a mnohem
    méně než (≪), i když jejich přesný význam není úplně
    jasný[^[\[zdroj\]]{.underline}^](https://math.stackexchange.com/questions/1516976/much-less-than-what-does-that-mean).
    Tyto symboly nám většinou říkají, že jedno číslo se nezanedbatelně
    liší od toho druhého a většinou tak spadají pod jinou řádovou
    velikost.

[^29]: Aproximace se může hodit při pracování s iracionálními čísly
    (třeba 𝞹 nebo ℇ) a odmocninami (například √2)

[^30]: Česky také přibližnost.

[^31]: Značka vznikla v roce 1892 a zavedl ji Alfred George Greenhill.
    ^\[14\]^

[^32]: Za tento symbol můžeme poděkovat německému matematikovi Antonovi
    Steinhauserovi, který ho použil v roce 1875 v knize *Lehrbuch der
    Mathematik*.

[^33]: Samozřejmě je tento symbol používán velmi střídmě.

[^34]: V Polsku se místo ∀ někdy používá ⋀ a ⋁ místo ∃^\[34\]^.

[^35]: Vykřičníkem je míněno vykřičník před číslem či výrokem. Vykřičník
    za výrokem se používá pro faktoriál.

[^36]: Šipka s dvěma rovnoběžkami byla zavedena v roce 1954 Nicholasem
    Bourbakim. Před ní se uvedla v roce 1922 šipka jednoduchá (→).

[^37]: I když symbol ∴ byl poprvé publikován v roce 1659^\[31\]^,
    použití těchto dvou značek bylo před jejich formalizováním v 19.
    století velmi inkonzistentní^\[33\]^.

[^38]: Lemniskáta je heslo, které se neobjevuje ve slovníku spisovného
    jazyka českého a je odvozeno od jeho použití na různých místech na
    internetu -- [[Bernoulliho
    lemniskáta]{.underline}](http://fyzikalniolympiada.cz/cd/matematika/krivky/kuzelos/bernoulli.htm),
    [[lemniskáta -- ABZ.cz: slovník cizích
    slov]{.underline}](https://slovnik-cizich-slov.abz.cz/web.php/slovo/lemniskata),
    [[Lemniskáta \| Slovník cizích
    slov]{.underline}](https://www.infoz.cz/lemniskata/).

[^39]: Podle autora této práce také lemniskátě napomáhá, že když půjdete
    po jejích křivkách, nikdy neskončíte -- takže váš tah prstem či
    tužkou bude nekonečný.

[^40]: Jeho majuskula, 𝚷, se používá pro zápis součinu.

[^41]: [[Den pí --
    Wikipedie]{.underline}](https://cs.wikipedia.org/wiki/Den_p%C3%AD)

[^42]: Toto platí hlavně pro mezinárodní scénu. V České republice
    používáme častěji nezdvojenou notaci.

[^43]: Je důležité zmínit, že toto nejsou všechny číselné obory. O
    dalších se můžete dočíst v článku [[Glossary of mathematical symbols
    --
    Wikipedia]{.underline}](https://en.wikipedia.org/wiki/Glossary_of_mathematical_symbols#Blackboard_bold)

[^44]: K těm jednodušším slouží balíček mhchem a k těm složitějším
    balíček chemfig (mimo jiné)

[^45]: Dokumentaci k balíčku circuitikz, který slouží k zápisu
    elektrických obvodů, lze najít zde: [[CircuiTikZ 1.6.1 --
    manual]{.underline}](https://texdoc.org/serve/circuitikz/0)
