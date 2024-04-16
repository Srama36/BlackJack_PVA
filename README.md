# Blackjack 

## Úvod:  

Rozhodl jsem se vytvořit jednoduchou karetní hru Blackjack. Hra poběží v konzoli a zobrazení karet bude textové.  

 

## Co je to Blackjack:  

Blackjack je karetní hra, která se hraje proti dealerovi a cílem je dosáhnout karet s celkovou hodnotou blízkou nebo rovnající se 21, ale nepřesahující ji. Hráči mají za úkol porazit dealera, aniž by přesáhli 21 bodů. Pokud hráč přesáhne 21 bodů, ztrácí svou sázku. 

 

Rozdání karet: Každý hráč a dealer dostanou dvě karty. Většinou jsou karty hráčům rozdávány otočenými lícem nahoru, zatímco jedna z karet dealera je otočena lícem dolů a jedna lícem nahoru. 

 

Hodnoty karet: Karty 2 až 10 mají hodnotu odpovídající jejich číselné hodnotě. Karty J, Q a K mají hodnotu 10 bodů. Eso může mít hodnotu 1 nebo 11 bodů podle toho, co je pro hráče výhodnější. 

 

Rozhodování hráče: Hráči mají několik možností, jak reagovat na své karty: Hit: Požádat o další kartu. Stand: Zůstat se svými současnými kartami a nepožádat o další. Double down: Udělat další sázku (v některých pravidlech) a požádat o jednu další kartu, poté ukončit svůj tah. Split: Pokud mají hráči dvě karty se stejnou hodnotou, mohou je rozdělit do dvou samostatných rukou a hrát každou zvlášť (s další sázkou). 

 

Rozhodování dealera: Dealer hraje podle pevných pravidel stanovených kasinem. Obvykle dealer musí hitovat (požádat o další kartu), pokud má celkovou hodnotu karet 16 nebo méně, a musí stát, pokud má 17 nebo více bodů. 

 

Vyhodnocení vítěze: Po skončení tahů hráčů a dealera se porovnají celkové hodnoty jejich karet. Hráč, který má nejbližší celkovou hodnotu k 21, vyhrává hru. Pokud hráč přesáhne 21 bodů, prohrává (tzv. "bust"). Pokud dealer přesáhne 21 bodů, hráči, kteří nezkrachovali, vyhrávají. Výplata: Pokud hráč vyhraje, obvykle dostane sázku v poměru 1:1. Výjimkou je situace, kdy hráč dostane Blackjack (21 body získané z dvou prvních karet, tj. eso a karta s hodnotou 10), v takovém případě je obvykle výplata 3:2. 

 

Výplata: Pokud hráč vyhraje, obvykle dostane sázku v poměru 1:1. Výjimkou je situace, kdy hráč dostane Blackjack (21 body získané z dvou prvních karet, tj. eso a karta s hodnotou 10), v takovém případě je obvykle výplata 3:2 

 

## Jazyk: Python 

## Program: Visual Studio Code 



Start menu: Konzole zobrazí první otázku jestli: “Chcete hrát?”. Pokud hráč napíše “ano” spustí se hra. Pokud napíše “ne” konzole se vypne.  

Začátek hry: Hráči budou dány 2 karty otočené symbolovou stranou nahoru. Dealerovi bude dána 1 karta otočená symbolovou stranou nahoru a 1 karta otočená symbolovou stranou dolů.  

Hit or Stand: Hráč se může rozhodnout, jestli chce další kartu nebo ne. Pokud ano klikne na tlačítko hit, pokud ne tak klikne na tlačítko stand.  

Stand: Pokud hráč použije funkci stand tak podle toho, jestli má dealer součet karet 16 nebo menší tak dostane další kartu a pokud ne tak kartu nedostane. Následně se odhalí dealerovy karty a podle toho kdo má součet karet blíž k 21 a zároveň ne víc jak 21, tak hru vyhrál.  

Hit: Pokud hráč vybere možnost hit tak mu je přidána 1 karta symbolovou stranou nahoru. Následně dealerovi proběhne random šance pro přidání další karty. Dále se hráč znovu rozhoduje mezi Hit nebo Stand. Podle toho, kdo má součet karet blíž k 21 a zároveň ne víc jak 21, tak hru vyhrál. 

Konec hry: Po dokončení kola se hra hráče zeptá, jestli chce pokračovat. Pokud napíše “ano” pak se hra spustí. Pokud hráč napíše “ne” tak se konzole vypne. 

 

## Počty karet:  

Karty s číslem 2–10 se rovnají číslu které je na nich vyobrazené 

Karty Q, J, K, se rovnají 10 

Karta A se rovná buď 1 nebo 11 podle potřeby 

 

## Závěr:  

Blackjack je relativně komplexní hra a programování ji by mě mělo naučit základy programování v pythonu.   
