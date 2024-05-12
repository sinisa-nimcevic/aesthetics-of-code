## H2 Uvod 

Više puta suočen sa raspravama tokom spajanja koda u glavnu granu - naišao sam na potrebu da kristalizujem šta lično smatram lepim (do prihvatljivim) kodom, ne bih li uspeo da poduprem moje (ne)odobravanje nekog pristupa konkretnim argumentima.

Uzeo sam na sebe zadatak da napišem estetski vodič za pisanje koda koji (imam osećaj) nedostaje. Estetika je sama po sebi grana filozofije koja se bavi lepotom i formiranjem "ukusa". Kodirani algoritam, iako je sa nama nešto manje od 2 veka (i eksponencijalno je sve prisutniji u poslednjim decenijama) kao da nije pustio svoje korenje u tlo estetike, i ostaje mahom gledan kao "funkcija iznad forme".

Priznajem da je kodirani algoritam uvek i nužno, uputstvo za izvršavanje zadatka prvenstveno namenjeno mašini, i njegova estetika (ukoliko objektivno postoji) uvek pada na daleko drugo ili treće mesto. Međutim u ovoj knjizi ću pokušati da dokučim (kako vama tako i sebi), lepotu koja može da se krije iza baze koda koja je podložna čestim promenama, i stoga mora biti pisana tako da olakša programeru rad(!). Održavanje baze koda je uvek lakše ukoliko pruža određeni užitak, a osim ako ste neka vrsta mazohiste, užitak u održavanju će doći (između ostalog i) iz percepcije lepote.

Takođe važna napomena - trudiću se da govorim u generalnim terminima primenjivim na bilo koji tip programiranja, iako je moje iskustvo skoro isključivo vezano za javascript programiranje te neke primedbe možda neće biti validne za druge programske jezike i njihove kontekste. Srećom, javascript je kao i većina popularnih programskih jezika C derivat pa se nadam da će većina iskustva/zapažanja biti prenosiva uz minimalne primedbe.

Kod kao izraz

Ono što se često sreće u sferi razvoja softvera, je emotivna reakcija na kritiku koda. Programer je spreman da proizvodu prispoji daleko manje od optimalnog rešenja, ne bi li odbranio svoje uloženo vreme i ideju. Ova emotivna reakcija me je svaki put podsetila, (iako nije isključiva za taj slučaj) na umetnika koji brani svoj rad, svoj neki plod ljubavi. Naravno, mnogi ljudi dolaze na posao samo da odrade svoje sate i nastave život, ali ipak, volim da verujem da čak i najhladniji "profesionalac" dobija određen osećaj zadovoljstva stavljanjem tačke na i, i to stavljanjem tačke baš na njemu svojstven način. Kodiranje jeste lični izraz.

Ukoliko ne govorimo o delu baze koda, gde primat uzimaju performanse, programeri su (s pravom) radi da nude rešenja koja su njima, kako poznata, tako i estetski prijatna. Zato i umeju da kritiku shvate lično. 

Estetski doživljaj koda

Zadržimo se na trenutak na slučaju gde se bira estetski prijatno rešenje, nasuprot možda najpoznatijem. Dakle, iako autor ima "u rukavu" rešenje koje često primenjuje, okolnosti dozvoljavaju varijaciju koja mu pruža estetsku satisfakciju i on stvara emotivnu vezu sa ovom odlukom.

Lep kod je često sinonim i za čist kod, čitljiv kod, ali ću o silama koje vode različita rešenja, i tenzijama između njih pričati u narednim poglavljima, pa se ne bih olako zaustavljao na lepom, odnosno čistom kao jedinim atributima estetičnog koda. Ono što ovde želim da zakucam je i "opravdanje" ove knjige, a to je uopšte postojanje estetske dimenzije kodiranog algoritma.

Estetska vrednost, makar bila i čisto dekorativna, podrazumeva neku vrstu "umetnosti", kao svoj objekat. Kao što već rekoh, kodirani algoritam je uvek prvenstveno funkcionalan, a tek zatim, i tek ako govorimo o kodu koji je potrebno iznova i iznova čitati i menjati, i tek i samo tek ukoliko je dobro napisan, ujedno i "estetičan". Lagan za oko.

Pozvao bih se, kao na najubedljiviji argument, na intuitivni, apriori sud. Ukoliko imate praksu kodiranja, pročitali ste prošli pasus i nadam se klimnuli glavom kada sam opisao kod kao, dobar odnosno dobro napisan, i kao lep. Skoro etička dimenzija gde kod u svojoj svrsi može biti dobar ili loš prilikom njegove percepcije, govori o dubini te naše percepcije. Mi se suočavamo ne samo sa nizom instrukcija za mašinu, mi se suočavamo predmetom koji na više slojeva (efikasnost, čitljivost, uticaj na sekciju neposrednog koda - samo da zagrebem površinu), može da ima vrline, i i tek kako, mane. Mi nedvojbeno govorimo o predmetu, koji za "uživaoca" ima estetsku vrednost - ali zanimljivo, ta estetska vrednost, dodeljuje se u trenutku kada kod čitamo s namerom da ga razumemo i menjamo, a vraća se u zapećak kada se kod izvršava na mašini.

