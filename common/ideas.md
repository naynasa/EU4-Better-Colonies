# colonies / trade company mod eu4
## -------nya typer av colonial nations-----
### Spanien:
* autonomous/private charter? à la columbus - ger mer militär kapacitet för kolonin (och settler growth?) men gör att du som overlord kan kontrollera den mindre - lägre tariffs och färre interactions?
* viceroy/viceroyalty
* se till att spanien får bonus för att kolonisera filipinerna från mexiko (vilket de gjorde i verkligheten) istället för runt afrika
### ---övriga mechanics----
* encomienda systemet (encomenderos de som ägde encomiendas) - minimum autonomy? + nått mer 
* haciendas?
* mestisos
* "the council of the indies"
* events? - relaciones geográficas + Mit'a + corregimiento + reducciones
* kunna slå ihop / dela upp "colonial nations" för att representera power struggeln mellan de?
* royal license - möjlighet för autonom upptäckning?
* gör så att replace governor faktiskt gör något / man använder den
* lägg till local modifier i nya världen för minskad supply limit (högre attrition?)
* mercantilism - låg = + goods produced i dina subjects / trade efficiency hög = domestic tradepower + dev cost

### generella teman
* gör det svårare att helt ignorera natives (framförallt tags) - gör det betydligt viktigare att sammarbeta med lokalbefolkningen (höj naval attrition / minska koloniernas kraft i början)
* gör det svårare att ha gubbar i nya världen generellt - sjukdomar? kan också göra att "autonomy leveln" på dina colonial nations blir viktigare
* mercantilism påverkar om dina kolonier kan handla med varandra???


## General notes on history
### spanien
* spanien va fokuserade på guld/silvergruvor och inte jätteintresserade av att utveckla kolonierna? - allt silver från kolonierna gjorde också att det gick dåligt för spansk tillverkningsindustri "allt är dyrbart i spanien utom silver"
* juros - statssskuld som adeln investerade i
* stor tillgång på naturresurser minskade också utvecklingen och entreprenörskapsheten
* habsburgarna spenderade silvret väldigt liberalt och gick bankrutt flera gånger

>representation in game:
>disaster - over reliance on new world silver?
>juros estate priviledge?


i filippinerna överlevde mycket större del av lokalbefolkningen än i nya världen
Limahong - känd kinesisk pirat
man handlade mexikanskt silver mot kinesiskt silke och indiska och malaysiska ädelstenar + kryddor
de allra flesta soldaterna i filippinerna kom från kolonierna

>representation in game:
>mission / event för att kolonisera filipinerna efter mexiko - koppling till självständigheten i mexiko - typ desto mindre självständiga mexiko är desto lättare / snabbare kan man göra det och allierade i området

spanska missionärer fick i uppgrag att göra om "unreasonable people" (infödingar) i norra mexiko till "resonable people" genom att sätta de i arbets / kulturläger men tjänade stora pengar på urbefolkningens obetalda arbete se de deklarerade att ingen någonsin blivit "konverterad" utan behöll de som slavar

spanska kolonier fick inte handla med varandra

patron - bruksägare deluxe - chef för en stor ranch eller gruva som styrde en community

avlönade arbetare bytte ut slavar i mexiko?


### storbritannien
de rika delarna av nya världen var redan koloniserade så man fick nöja sig med nordamerika. Till en början försökte engelsmännen samma strategi som spanjorerna med conquistadorer men fann snabbt att nordamerika saknade de feudala maktstrukturerna som bl.a. aztekerna hade. Därför försökte de gå över till att förslava kolonisterna istället för lokalbefolkningen genom "penal colonies". Detta fungerade dock inte speciellt bra och man gick snabbt över till att göra kolonisterna till "settlers" där de fick land och visst självstyre (colonial assembly) mot att de sålde sina varor till "the virginia company"



### mexiko
kidnappning av folk för att bygga infrastruktur?

## implementation
gör om så att viceroy tillhör viceroyalty colonial nation typen istället för att bara va en reskin för spansk kultur
### 4 tiers av colonial nations (några är kulturberoende t.ex. conquestador state)
* private charter - du har i princip sålt dina kolonier till ett privat företag (heter ... company?) fungerar som trade companies?
    * lögre liberty desire?
    * begränsat antal interractions? - ska man ens kunna lägga till tarrifs?
    * -100 opinion för natives i området

* autonomous charter/dominion - conquistador state för spanien? (kolonier börjar här?)
    * kolonin styrs som en kleptokratisk autokrati av de som upptäckte den / erövrade den
    * fördelar: kan expandera snabbare? får högre force limit?
    * nackdelar för kolonin: mer unrest högre minimum autonomy?
    * nackdelar för kolonisatören: ger i princip ingen inkomst (bara treasure fleets?) kan inte höja tarrifs
    * -100 till 0 opinion för natives i området

* viceroyalty
    * mer direktstyrd av moderlandet, har en viceroy som kan bytas ut från hemlandet
    * fungerar i princip som vanliga kolonier men kan contributa till capital - har dock också högre unrest / fler disasters
    * -20 till +20 opinion för natives i området

* crown colony
    * i princip direktstyrd av moderlandet - fungerar likt en vassal
    * kan transfera tradepower och ta emot manpower från moderlandet (march interactionen)
    * har 80% starting tarrifs
    * kan endast ha en/ ett par? eller har de mycket högre unrest? ger mycket pengar men är svåra att styra många
    * -100 opinion för natives i området