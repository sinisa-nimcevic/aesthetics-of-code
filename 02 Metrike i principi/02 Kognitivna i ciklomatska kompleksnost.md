### H3 Kognitivna i ciklomatska kompleksnost 

Kao "esteta", principijelno se protivim statičkoj analizi koda iako ona ima svoje mesto u održavanju na duge staze, pogotovo ako govorimo o velikim timovima (recimo više od 4 člana a mogućno i više od 10). 

Statička analiza koda podrazumeva stroga pravila koja se primenjuju na tekst putem algoritama, ne bismo li iscedili neki broj, odnosno neku sumu koju arbitrarno odredimo kao "granicu" koju tolerišemo, ili da bismo usilili poštovanje nekih "najboljih praksi" bez razumevanja konteksta koda.

 Dve najčešće zastupljene metrike su pokušaji određivanja kompleksnosti koda. 

Ciklomatska kompleksnost pokušava da zbroji broj individualnih, linearnih putanja kroz kod, jer se brinemo o tome koliko je lako testirati kod, i to vodeći se najnaivnijom merom dobro testiranog koda a to je pokrivenost.

Kognitivna kompleksnost ide dalje i zanima se time koliko je lako ili teško (mada su po meni ovo skroz subjektivne odrednice) neku porciju koda shvatiti. Možemo reći da izbegavanjem ugnežđene logike dobijamo na lakoći shvatanja, dakle jedan uslov prati izvršenje jedne akcije, odnosno, favorizuje se mešavina imerativnog i deklarativnog programiranja gde će porcije unutar petlji biti navodno razumljivije, ako su deklarativna pozivanja skrivene logike, nasuprot ogoljenom mnoštvu uslova i petlji (što je donekle logično).

Moj najveći problem sa kognitivnom kompleksnošću (koja mi je i dalje draža od ciklomatičke) je što se vodi često lažnom premisom da je lakše pratiti kod koji je iscepkan na manje funkcije. Teoretski, male funkcije jesu lakše za testiranje, i ako imamo kod koji se sastoji iz mnoštva uslovima podeljenih manjih funkcija imaćemo čitko parče logike. Međutim, ovo podrazumeva da su uslovi dovoljno jednostavni da ne zahtevaju dalje gnežđenje. To opet dalje podrazumeva da, ukoliko postoji dalje gnežđenje logike, ono bude sakriveno i enkapsulirano ovim funkcijama. I treća pretpostavka, gde će ovo uglavnom pasti u vodu ako se tera do ekstrema, je da su sve funkcije tako jasno nazvane, da nam govore šta rade, bez da mi nužno zavirimo u njih. Što gotovo nikad nije slučaj, pogotovo ako tražimo neku sitnu grešku koja nije očigledna.

Pri tom, baze koda koje idu u ovom smeru (male, više puta iskorištene funkcije) mogu da budu žrtva nasilnog apstrahovanja, gde se stvaraju zajedničke porcije slične logike, blago razdvojene argumentima samo da bi se izbegla benigna duplikacija koda. Time dobijamo ponovno iskorištenje koda koji sam po sebi nije optimalan, ni funkcionalnošću ni imenom, i istovremeno, odvajamo nešto što je možda srž komponente, van vidokruga (u neku "korisnu" funkciju), da bismo dobili malu, čitku komponentu koja nam na prvi pogled ne govori ništa o sebi. Ali je paradoksalno "čitka" (?). Da ne govorim o zahtevima "starosedeoca" projekata da se ove funkcijice iznova i iznova koriste, forsirajući "učenje" projekta, što je po meni suprotno od idealnog projekta koji je toliko jasan, da nije potrebno posebno izučavanje baze koda i period mentalne adaptacije jer je većina stvari jasna na prvi pogled, prati standarde industrije i zapravo je i praktično čitka, a ne "čitka" na oko (dva različita pojma).

