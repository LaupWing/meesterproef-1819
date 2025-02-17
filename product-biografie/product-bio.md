# Product Biografie
In de productbiografie kan je mijn proces vinden voor de meesterproef van de minor webdevelopment. Naast het proces kan je mijn persoonlijke leerdoelen hier vinden en de samenwerking met mijn team. 

## Inhoud
1.  [Inleiding](#inleiding)
2.  [Leerdoelen](#leerdoelen)
    1.  [WAFS](#wafs)
        *   [Punten uit de rubric](#punten-uit-de-rubric)
    2.  [RTW](#rtw)
        *   [Punten uit de rubric](#punten-uit-de-rubric)
3.  [Logboek](#logboek)
    1.  [Week1](#week1)
        *  [Wat heb ik gedaan](#wat-heb-ik-gedaan)
        *  [Bevindingen](#bevindingen)
        *  [Wat kon beter](#wat-kon-beter)
    2.  [Week2](#week2)
        *  [2.1 Wat heb ik gedaan](#2.1-wat-heb-ik-gedaan)
        *  [2.1 Bevindingen](#2.1-bevindingen)
        *  [2.1 Wat kon beter](#2.1-wat-kon-beter)
    3.  [Week3](#week3)
        *  [3.1 Wat heb ik gedaan](#3.1-wat-heb-ik-gedaan)
        *  [3.1 Bevindingen](#3.1-bevindingen)
        *  [3.1 Wat kon beter](#3.1-wat-kon-beter)
    4.  [Week4](#week4)
        *  [4.1 Wat heb ik gedaan](#4.1-wat-heb-ik-gedaan)
        *  [4.1 Bevindingen](#4.1-bevindingen)
        *  [4.1 Wat kon beter](#4.1-wat-kon-beter)
    5.  [Week5](#week5)
        *  [Server de juiste data laten ophalen](#server-de-juiste-data-laten-ophalen)
            *  [Bijbehorende functies](#bijbehorende-functies)
        *  [Data vertalen naar visuele elementen op de website](#data-vertalen-naar-visuele-elementen-op-de-website)
            *  [EJS](#ejs)
            *  [Sockets](#sockets)
        *  [Website een applike gevoel geven](#website-een-applike-gevoel-geven)
            *  [Bijbehorende functies](#bijbehorende-functies)
            *  [Mappen Indeling JS](#mappen-indeling-js)
4.  [Zeflreflectie](#zelfreflectie)
    *   [Leerdoelen-reflectie](#leerdoelen-reflectie)
        *   [WAFS](#wafs)
            *   [Punten uit de rubric](#punten-uit-de-rubric)
        *   [RTW](#rtw)
            *   [Punten uit de rubric](#punten-uit-de-rubric)

## Inleiding
Voor de meesterproef heb ik mij ingeschreven bij Linernote. Dit project sprak mij aan, omdat het concept voornamlijk rondom het onderwerp muziek en artiesten draaide en zelf luister ik dagelijks muziek onderweg of tijdens het sporten. 

Tijdens deze meesterproef heb ik samengewerkt met May en Zekkie. En onze opdrachtgever was Joost van de Boo.

<!-- <img src="images/Linernote_Logo_White.png"> -->
![alt text](images/Linernote_Logo_White.png)

### De opdracht
De bedoeling van  de opdracht is om een website te maken waar alle social media van je favoriete artiesten worden gebundeld en weergeven om 1 platform namelijk de Linernote website. Gebruikers kunnen artiesten volgen en van die artiesten worden dan de posts in de homepagina weergeven.  
Uiteindelijk wou Joost van de Linernote website ook een echte app van maken. 

**Opsomming**
*   Artiesten social media posts
*   Uiteindelijk een echte app
*   Artiesten volgen 

## Leerdoelen
Na de debrieving gehad te hebben van Joost van de Boo ben ik gaan wezen kijken welke leerdoelen het best bij de opdracht passen. De meeste leerdoelen heb ik uit het vak WAFS gehaald, omdat de opdracht zelf gebruik word gemaakt van API's en data manipulatie. Vandaar dat ik voornamelijk mijn leerdoelen uit WAFS heb gehaald.

### WAFS
Heel veel punten uit de rubric van WAFS waren van toepassing bij het project bij Linernote. Dit komt omdat voor Linernote het een vereiste is om veel API's te callen, om informatie te halen van artiesten. Wat onze opdrachtgever ook wou is dat het concept van Linernote uiteindelijk een app word. Mijn leerdoel is hierbij ook om de website een app-like gevoel te geven. Dit probeerde ik te bereiken door de website maar 1 keer te laden en dat de verschillende pagina's worden gerenderd door middel van fetches naar onze server.

#### Punten uit de rubric
*   `Je hebt, met behulp van een micro library, routes toegepast naar een overzichts- en een detailpagina.`
*   `Je hebt andere slimme methodes gebruikt om JSON data te manipuleren`
*   `Je hebt je verdiept in de API en aan de hand van API docs de op te halen data zo efficient mogelijk opgevraagd`
*   `Ik heb geen enkele OCD source-formatting neiging als ik naar jouw code kijk. De structuur is volledig duidelijk en logisch opgezet`
*   `Het is gelukt om, met behulp van een micro library, JSON data te renderen naar HTML`


### RTW
Omdat ik de Linernote website een app-like gevoel wilt geven is het nodig om een open connectie te hebben met de server waardoor ik met gemak data kan opvragen vanuit de server. Ik heb daarom als leerdoelen het volgende uitgekozen uit het vak Real-Time Web.

#### Punten uit de rubric
*   `Je hebt methodes gecreëerd die clients in staat stelt middels jouw eigen API te communiceren met jouw server. Real time connectiviteit is op een slimme manier opgezet`

## Logboek
Hier kan je het logboek zien per week wat ik allemaal gedaan heb. Per week beschrijf ik hoe de week ging, Wat ik gedaan heb, mijn bevindingen en wat ik vond dat er beter kon in die week.

### Week 1
Onze debrief begon om half 10 in de Volkshotel. Tijdens de debrief werd kregen we te horen waarvoor de applicatie diende en welke api's de opdrachtgever voornamelijk in de applicatie wou zien. 
In de afbeelding hieronder kan je zien welke api's een must-have zijn en welke api's would-like.
![alt text](images/apis.png)


In deze eerste week heb ik ook besloten om samen met Zekkie te werken aan de Linernote App. 
We hadden in deze week de afspraak gemaakt dat Zekkie de backend zou maken, zodat mensen kunnen inloggen/account aanmaken en dat gebruikers artiesten kunnen volgen. En ik zou de api's onderzoeken hoe we informatie eruit konden halen.

Na het onderzoeken van verschillende API's in de eerste week kwamen we er al snel achter dat de instagram api niet meer beschikbaar was voor openbaar gebruik en dat de meeste api's in onze must-have list een bepaalde authenticatie voor nodig was(ook wel OAUTH genoemd). Dit zorgt ervoor dat als de gebruiker op de Linernote app wilt komen eerst meerdere keren moet inloggen voordat hij/zij op de Linernote app zelf kwam.

#### 1.1 Wat heb ik gedaan?
*   Team gemaakt(Zekkie + Loc)
*   Afspraken gemaakt wie doet wat
    *   Zekkie maakt de backend
    *   Ik onderzoek API's
*   Gezamelijk repo gemaakt
*   Api documentatie lezen(Spotify, Instagram, Ticketmaster, Youtube).
*   Ik ben begonnen met data ophalen van Spotify
*   Eerste interface versie gemaakt
    *   [Link Sourcecode](https://github.com/LaupWing/Linernote)
    *   ![alt text](images/first_prototype.gif)
*   Eerste documentatie gemaakt 
    *   [Link Readme](https://github.com/LaupWing/Linernote)

#### 1.1 Bevindingen
*   Data uit: Instagram, Spotify, Ticketmaster en Youtube is a must (Debrief)
*   Website word uiteindelijk een app (Debrief)
*   Instagram API niet beschikbaar (API onderzoek)
*   Spotify, Youtube is inloggen een vereiste (API onderzoek)
*   Meeste API's bieden een embed aan van een post, dit houd dat er een iframe word gemaakt van eenpost (API onderzoek)

#### 1.1 Wat kon beter?
*   Afspraken noteren en heel duidelijk maken wie wat doet

### Week 2
In week 2 hadden we rond 10 uur afgesproken in het volkshotel voor feedback. Na het laten zien van onze prototypes kwam Joost op het idee om de posts te kunnen liken en commenten van de artiesten. Deze like en comment systeem werkt binnen de Linernote app. Dus de likes en comments worden niet naar de platform zelf gepost maar allemaal in de Linernote app zelf. Joost wou ook een wrapper rondom de embedded posts voor styling. In deze week besloot May ook om deel te nemen aan ons groepje.

#### 2.1 Wat hebben ik gedaan?
*   Gekeken of er een wrapper rondom de embeds konden
*   Alternatieve mogelijkheden bekijken om data uit Instagram te halen
*   Opnieuwe server en frontendcode geschreven, zodat May samen met mij kon werken aan de prototype.   
*   Ticketmaster api toegepast

#### 2.1 Bevindingen
*   Joost wou een wrapper rondom embedded posts voor styling
*   Joost wou dat de gebruiker onder elke post kon commenten en liken
    *   ![comment en like](images/comment.png)
*   May is bij ons in het groepje gekomen
*   Instagram is mogelijk door scrapen van de shortcodes met puppeteeer(node package)
*   Zekkie slaat alle data op in zijn eigen backend (Dat had ik niet verwacht)

#### 2.1 Wat kon beter?
*   Afspraken noteren en heel duidelijk maken wie wat doet
*   Beter communiceren, ik vond het namelijk totaal onzin om alle data op te slaan in een database omdat ik het nut ervan niet in zag en totaal niet deel was van de opdracht zelf. Maar ik had niks daar niks over gezegd.

### Week 3
Deze week was er op een maandag een feestdag waardoor we geen feedback moment hadden met Joost. In deze week heb ik samen met May de applicatie interface gemaakt. Tijdens deze week waren en nogal onenigheden binnen ons groepje. Iedereen had een andere idee in zijn/haar gedachten voor dit product. En iedereen voerde maar zijn/haar eigen idee uit. Ik was van mening dat we gewoon de design en concept van onze opdrachtgever maar moeten aanhouden, maar May (met wie ik samen frontend taken had) had een andere mening hierover. Ik ben uiteindelijk maar meegegaan met haar mening en we werkten toen uit wat zij in haar gedachten had hoe dit product zou moeten uitzien. Verder was de database waar alle posts in worden opgeslagen bij lange na nog niet klaar, dus hadden we geen data om de homepagina te renderen. Ik besloot toen om zelf via de server api calls te maken om deze data toch te verkrijgen.

#### 3.1 Wat heb ik gedaan?
*   Samen met May de artiesten pagina gemaakt
    *   Kleine effecten toegevoegd zoals uitzoom functie in de album carousel
    *   ![comment en like](images/second_prototype.gif)
*   Verder API's onderzoeken

#### 3.1 Bevindingen
*   Samenwerken is moeilijker is dan ik gedacht had.
*   Iedereen had een andere opinie/idee over dit project

#### 3.1 Wat kon beter?
*   Communicatie en bespreken over hoe en wat

### Week 4
Tijdens deze week waren ik en May niet aanwezig bij de feedback momentje met Joost. Zekkie was er wel van ons groepje. Na dit gesprek kwamen we erachter dat de design niet goedgekeurd werd door onze opdrachtgever. De opdrachtgever wou een exacte 1 op 1 kopie van zijn design. Dit zorgde dat het werk wat we de vorige week hadden gemaakt helemaal moesten schrappen. Ook hoorde Zekkie dat het liken en commenten niet meer nodig was en dat ook moest schrappen, en ook dit zorgde ervoor dat we een week aan werk of zelfs meer moesten weggooien. 

De design van Joost bestond voornamelijk uit de post embeds van de artiesten dus data hebben van elke artiest was van uiterste belang voor de frontend, maar helaas was Zekkie nog niet klaar met het opslaan van de data van verschillende artiesten. Hierdoor hadden ik en May niet veel te doen tijdens deze week. Ik had toen zelf maar weer geprobeerd om data uit de verschillende API's te halen, zodat wij verder konden gaan. Na een poosje onderzoeken stuitte ik op de MusicBrainz API. Dit was een hele fijne ontdekking, omdat we via de Musicbrainz API makkelijk naar de artiesten hun social media konden navigeren en daar data vandaan konden halen.

#### 4.1 Wat heb ik gedaan?
*   API's data fetchen en implementeren in de frontend.
*   Frontend styling

#### 4.1 Bevindingen
*   MusicBrainz API maakt het makkelijker om de social links te krijgen van Artiesten
    *   ![comment en like](images/musicbrainz.png)
        *   In elke relation heb je een URL waar we data van konden halen.
*   Design moest exact worden nagemaakt
*   Like systeem en commenten hoefde niet meer

#### 4.1 Wat kon beter?
*   Wederom communcatie problemen

### Week 5
In de laatste week was de backend onderdeel klaar voor gebruik dus konden de mensen echt pas beginnen aan de frontend. Tijdens deze week heb ik het meest aan het project kunnen werken. Mijn goals voor deze week was:
* Server de juiste data laten ophalen
* Data vertalen naar visuele elementen op de website
* Website een app-like gevoel geven

#### Server de juiste data laten ophalen
In de `api.js` bestandje staat alle logica om de data op te halen uit verschillende api-endpoints (Merendeels word niet meer gebruikt, omdat we onze eigen database hebben). Voordat de database er was heb ik zelf geprobeerd om alle data op te halen uit de verschillende api's, dit werd gedaan door eerst naar de musicbrainz api te gaan en van daaruit alle sociale media op te halen. Na het ophalen van de social media links worden de data opgehaald van de beschikbare social media links uit music brainz. 

##### Bijbehorden Functies
`musicBrainz`
Deze functie doet als volgt:
* `artist`: haalt data op aan de hand van artiest naam
* `artistId`: haalt id op uit `artist` variabele
* `artistLinks`: haalt alle social links op uit musicbrainz
* stuurt social links terug
```javascript
const musicBrainz = {
    artistLinks: async name => {
        const artist = await getData(`http://musicbrainz.org/ws/2/artist/?query=artist:${name}&fmt=json`)
        const artistId = artist.artists[0].id
        const artistLinks = await getData(`http://musicbrainz.org/ws/2/artist/${artistId}?inc=url-rels&fmt=json`)
        return artistLinks
    },
}
```

`wikipedia`
Deze functie doet als volgt (dit is één van de vele api functie's):
* `allLinks`: haalt social links op uit de `musicBrainz.artistLinks` functie
* `getLink`: filtert de wikepdia link uit `allLinks` variabele
* `hardCodedLink`: hardcoded link voor het geval wikipedia link niet beschikbaar is
* `wikiLink`: checked of de wikipedia link aanwezig in de allLinks anders word de hardcoded link gebruikt
* `data`: haalt dat op uit de `wikiLink`
* stuurt data terug

```javascript
const wikipedia = async(name)=>{
    try{
        const allLinks  = await musicBrainz.artistLinks(removeAllNonAlpha(name))
        const getLink = allLinks.filter(searchObj('wikipedia'))
        const hardCodedLink = `https://en.wikipedia.org/api/rest_v1/page/summary/${name}`

        const wikiLink  = (getLink.length===0) ? hardCodedLink : `https://en.wikipedia.org/api/rest_v1/page/summary/${getLink[0].urlrsc.split('https://en.wikipedia.org/wiki/')[1]}`

        const data = await getData(`${wikiLink}`)
        return data.extract
    }catch{
        console.log('error wikipedia data isnt loading')
    }
}
```
#### Data vertalen naar visuele elementen op de website
Om de data te vertalen naar visuele elementen op de pagina heb gebruik gemaakt en ejs en sockets om elementen in te laden. De meeste elementen zijn gerenderd via ejs aan de serverside en slechts alleen de zoekresultaten word gerenderd met sockets.

##### ejs
Hieronder kan je de verschillende templat files vinden. Door op het bestandnaam te klikken ga je naar het desbetreffende source code. Zoals je hieronder kan zien bestaat de website voornamelijk maar uit 2 pagina's: index en de login pagina. Zodra de gebruiker ingelogd is, word alleen maar de index.ejs pagina gebruikt als basis. Als de gebruiker navigeert naar een andere gedeelte van de websites dan word de webpagina door javascript weggehaald en vervolgens de gewensde pagina ingeladen door javascript. Hierdoor lijkt de website op een onepager. Bekijk [Website een app-like gevoel geven](#Website-een-applike-gevoel-geven) voor meer info hierover.

* :open_file_folder: Views
    * :page_facing_up: [index.ejs](https://github.com/LaupWing/Linernote_finalV2/blob/master/views/index.ejs)
    * :page_facing_up: [login.ejs](https://github.com/LaupWing/Linernote_finalV2/blob/master/views/login.ejs)
    * :open_file_folder: partials
        * :page_facing_up: [artist.ejs](https://github.com/LaupWing/Linernote_finalV2/blob/master/views/partials/artist.ejs)
        * :page_facing_up: [following.ejs](https://github.com/LaupWing/Linernote_finalV2/blob/master/views/partials/following.ejs)
        * :page_facing_up: [followingList.ejs](https://github.com/LaupWing/Linernote_finalV2/blob/master/views/partials/followingList.ejs)
        * :page_facing_up: [head.ejs](https://github.com/LaupWing/Linernote_finalV2/blob/master/views/partials/head.ejs)
        * :page_facing_up: [homefeed.ejs](https://github.com/LaupWing/Linernote_finalV2/blob/master/views/partials/homefeed.ejs)
        * :page_facing_up: [nav.ejs](https://github.com/LaupWing/Linernote_finalV2/blob/master/views/partials/nav.ejs)
        * :page_facing_up: [search.ejs](https://github.com/LaupWing/Linernote_finalV2/blob/master/views/partials/search.ejs)
            * :open_file_folder: artist-partials
                * :page_facing_up: [feeds.ejs](https://github.com/LaupWing/Linernote_finalV2/blob/master/views/partials/artist-partials/feeds.ejs)
                * :page_facing_up: [filter.ejs](https://github.com/LaupWing/Linernote_finalV2/blob/master/views/partials/artist-partials/filter.ejs)
                * :page_facing_up: [related.ejs](https://github.com/LaupWing/Linernote_finalV2/blob/master/views/partials/artist-partials/related.ejs)
##### Sockets
Om de zoek feature zo soepel mogelijk te laten verlopen heb ik ervoor gekozen om een socket verbinding te gebruiken om data zo snel mogelijk van de server naar de client te brengen.
###### Bijbhorende Functies
**Clientside Code**
Deze functie hieronder word gedaan na een key up event in de input.

Deze functie doet als volgt:
* verwijderd content wanneer value gelijk aan null is
* Laat x icoontjes zien wanneer er iets word getypd
* Verstuurd socket event wanneer waarde groter is dan drie
```javascript
function getSearchResults(){
    console.log("%c searchPage- typing", consoleStyling)
    const input = document.querySelector('#search')
    if(input.value.length === 0){
        const container = document.querySelector('section.search-main')
        document.querySelector('.input-container i').classList.remove('reveal')
        removeChilds(container)
    }
    else if(input.value.length > 0){
        document.querySelector('.input-container i').classList.add('reveal')
    }
    if(input.value.length >3){
        console.log("emitting search")
        socket.emit('sending searchvalue', input.value)
    }
}
```
**Serverside Code**
Deze functie doet als volgt:
* luisterd naar een socket event
* laat data in via de `api.js` functie's
* bekijkt welke artiesten de gebruiker al volgt om een visuele indictie toe te voegen
* stuurt socket event terug met de data

```javascript
socket.on('sending searchvalue',async (value)=>{
try{
    const result        = await ourDB.nameQuery(value)
    const searchSpotify = await spotifyApi.search(result.artist,acces_token)
    const img           = searchSpotify.artists.items[0].images[0].url
    const spotifyId     = searchSpotify.artists.items[0].id
    result.img          = img
    result.spotifyId    = spotifyId

    let followed        = 'noborder'
    for(fw of following){
        if(fw.id===result.id){
            followed = 'border'
        }
    }
    socket.emit('sending artistinfo', {
        result,
        foundSomething: true,
        followed
    })            
}catch{
    socket.emit('sending artistinfo', {
        result          : 'Found nothing!',
        foundSomething  : false
    })
}
})
```

#### Website een applike gevoel geven
Om de website een meer app-like gevoel te geven heb ik ervoor gezorgd dat de gebruiker alleen maar de website hoeft te laden wanneer de gebruiker voor de eerste keer naar de website gaat. Dit houd in dat als de gebruiker navigeert naar een andere gedeelte van de website dat er niet nogmaals een pagina geladen hoeft te worden. Dit zorg ervoor dat de website een meer app-like gevoel heeft. 

##### Bijbehorden Functies
`getElement`
Deze functie doet als volgt:
* Haalt HTML elementen op
* Verwijderd huidige elementen
* Laad de HTML elementen in
* Bekijkt op welke pagina de gebruiker is
```javascript
function getElement(href){
    console.log("%c fetchHTML- Creating new elements", consoleStyling)
    const container = document.querySelector('main')
    if(href === 'javascript:void(0);')   return
    fetch(href)
        .then(data=>data.text())
        .then(body=>{
            removeChilds(container)
            container.insertAdjacentHTML('beforeend',body)
            container.classList.remove('fadeAway')
            checkWhichPage()
        })    
}
```
Doordat de webpagina's niet worden geladen maar ingeladen door middel van javascript, moest ik ervoor zorgen nadat de gebruiker op een andere webpagina dat alle juist functionaliteiten worden ingeladen. 
Je kan hierbij denken aan:
* Juiste events bij de juiste webpagina
* Wat de vorige staat was. (wanneer de gebruiker een webpagina terug wilt gaan)
* Errors voorkomen (bijv: als een gebruiker weer op hetzelfde link klikt, wat gebeurt er met de state dan?)

Om al de punten hierboven te realiseren is het van uiterst belang dat ik de mappen indeling zo goed mogelijk ga indelen, waardoor het uiteindelijk voor mij ook makkelijker word om onderdelen te veranderen. 

###### Mappen indeling JS
* :open_file_folder: js:
_Hier staan alle javascript files geladen die vanaf de login pagina al worden ingeladen_
    * :page_facing_up: [main.js](https://github.com/LaupWing/Linernote_finalV2/blob/master/static/js/main.js)
    * :page_facing_up: [resize.js](https://github.com/LaupWing/Linernote_finalV2/blob/master/static/js/resize.js)
    * :page_facing_up: [utils.js](https://github.com/LaupWing/Linernote_finalV2/blob/master/static/js/utils.js)
    * :page_facing_up: [socket.js](https://github.com/LaupWing/Linernote_finalV2/blob/master/static/js/socket.js)
    * :open_file_folder: pages:
    _Hier staan alle javascript files geladen voor specifike webpagina's binnen de index.html pagina(deze webpaginas worden ingeladen zonder de pagina te laden)_
        * :page_facing_up: [artistPage.js](https://github.com/LaupWing/Linernote_finalV2/blob/master/static/js/pages/artistPage.js)
        * :page_facing_up: [homepage.js](https://github.com/LaupWing/Linernote_finalV2/blob/master/static/js/pages/homepage.js)
        * :page_facing_up: [search.js](https://github.com/LaupWing/Linernote_finalV2/blob/master/static/js/pages/search.js)
            * :open_file_folder: error-preventing:
            _Hier staan de error preventing files in_
                * :page_facing_up: [preventError.js](https://github.com/LaupWing/Linernote_finalV2/blob/master/static/js/pages/error-preventing/preventError.js): _Errors voorkomen_
            * :open_file_folder: page-operators:
            _Hier staan alle pagina operatoren files in. Wanneer den gebruiker van pagina veranderd worden er allerlei functie's gestart die staan dus in files hieronder_
                * :page_facing_up: [feeds.js](https://github.com/LaupWing/Linernote_finalV2/blob/master/static/js/pages/page-operators/feed.js): _Posts van artiesten activeren (iframes maken)_
                * :page_facing_up: [fetchHTML.js](https://github.com/LaupWing/Linernote_finalV2/blob/master/static/js/pages/page-operators/fetchHTML.js): _Webpagina's opvragen en inladen_
                * :page_facing_up: [switchingPages.js](https://github.com/LaupWing/Linernote_finalV2/blob/master/static/js/pages/page-operators/switchingPage.js): _Wanneer er van pagina word geswitched, word er gekeken op welke pagina de gebruiker zich bevind zodat de juiste functie's worden gestart_
            * :open_file_folder: page-parts: _Hier staan de elementen die op meerder pagina's worden geladen_
                * :page_facing_up: [navigation.js](https://github.com/LaupWing/Linernote_finalV2/blob/master/static/js/pages/page-parts/navigation.js): _navigatie onderin de pagina na de inlog scherm_
                * :page_facing_up: [filter.js](https://github.com/LaupWing/Linernote_finalV2/blob/master/static/js/pages/page-parts/filter.js): _filter functinoaliteiten_
            * :open_file_folder: page-states: 
            _Hier staan de pagina states in_
                * :page_facing_up: [states.js](https://github.com/LaupWing/Linernote_finalV2/blob/master/static/js/pages/page-states/states.js): _huidige staat van de webpagina en vorige staat om de gebruiker de optie te geven om een pagina terug te gaan_

## Zelfreflectie

Ik tijdens dit project meer geleerd over in groepjes samenwerken dan dat ik mijn leerdoelen heb gerealiseerd. Tijdens dit project heb ik geleerd dat duidelijke communicatie van uiterste belang is in een groepsproject. Gedurende project hadden we te weinig communcatie waardoor er veel dingen dubbel werden gemaakt. Tevens hadden mijn teamgenoten ook veel issue met het project zelf. Iedereen had een andere opinie wat betreft het project zelf. Hierdoor waren er veel verkeerde keuzes gemaakt wat resulteerde dat we veel meer werk hadden dan dat eigenlijk nodig was.

In het begin was de backend bedoeld om ervoor te zorgen dat mensen zich konden aanmelden voor de linernote project en uiteindelijk artiesten kunnen volgen. Dit waaren de afspraken dat ik gemaakt had met mijn teamgenoot. Maar halverwege het project kwam ik erachter dat deze teamgenoot heel iets anders in gedachten had en ergens anders mee bezig was. Ik had hiervan niet veel gezegd. Wat uiteindelijk voor mij heel veel stress had gezorgd en frustratie, omdat we pas op de één van laatste dagen pas konden beginnen met frontend. Dit was een resultaat van mijn gebrek aan duidelijk communiceren.

Achteraf heb ik gelukkig wel mijn leerdoelen kunnen realiseren met veel stress. Maar dit had mij heel veel frustratie en stress gekost als ik duidelijk had gecommuniceerd.

### Leerdoelen Reflectie
#### WAFS
##### Punten uit de rubric
*   `Je hebt, met behulp van een micro library, routes toegepast naar een overzichts- en een detailpagina.`
    Door het gebruik van EJS heb ik ervoor gezorgt dat de webpagina's dynamische worden gerenderd op de server. Vervolgens heb ik door middel van javascript ervoor gezorgd dat de webpagina's worden ingeladen. Hierdoor word de webpagina niet geladen wanneer de gebruiker een andere pagina bezoekt. Doordat ik de webpagina's inlaad door middel van javascript is het belangrijk dat de juist functionaliteiten op de clientside javascript worden geladen en tevens ook dat de juiste data worden geladen op de juiste routes op de server.
    * [Klik hier voor de ejs mappenstructuur en link naar de ejs files](#ejs)
    * [Klik hier voor de js mappenstructuur en link naar de js files](#Mappen-indeling-JS)
    * Deze functie hieronder is gemaakt om de ejs templates op te halen uit de server
    ```javascript
    function getElement(href){
    console.log("%c fetchHTML- Creating new elements", consoleStyling)
    const container = document.querySelector('main')
    if(href === 'javascript:void(0);')   return
    fetch(href)
        .then(data=>data.text())
        .then(body=>{
            removeChilds(container)
            container.insertAdjacentHTML('beforeend',body)
            container.classList.remove('fadeAway')
            checkWhichPage()
        })    
    }
    ```
    *  `if(href === 'javascript:void(0);')`: Hier word er gekeken of de link bestaat uit `javascript:void(0)` voor het voorkomen van errors
    *  `fetch(href)`: Ophalen van de ejs webpagina uit de server
    *  `removeChilds(container)`: Verwijderd alle contenten uit de body
    *  `container.insertAdjacentHTML('beforeend',body)`: Voegt nieuwe content toe aan de body
    *  `checkWhichPage()`:
Deze functie hieronder bekijkt welke element aanwezig op een pagina. Aan de hand van de aanwezige element word er bepaald op welke website de gebruiker zich bevind, waardoor de juiste functie's worden gestart voor desbetreffende pagina.
    ```javascript
    function checkWhichPage(){
        console.log("%c fetchHTML- Checking Which page user is on", consoleStyling)
        preventError.turnOffLink(false)
        // If the id search excist that means that we are on the searchpage
        if(document.querySelector('input#search')){
            searchPage.events()
        }
        // If the class addNew excist that means that we are on the homepage
        if(document.querySelector('.addNew a')){
            navigation.events(document.querySelectorAll('.addNew a'))
        }
        else if(document.querySelector('section#homeFeed')){
            navigation.events(document.querySelectorAll('ul.list a'))
            console.log("%c fetchHTML- Requesting Homefeed", consoleStyling)
            homepage.requestHomeFeed()
        }
        else if(document.querySelector('.image-container-following')){
            navigation.events(document.querySelectorAll('ul.list a'))
        }
        // If the class artist-header excist that means that we are on the artistpage
        if(document.querySelector('header.artist-header')!==null){
            document.querySelector('main').classList.add("artist-page")
            artistPage.events()
        }
    }
    ```
*   `Je hebt andere slimme methodes gebruikt om JSON data te manipuleren`
*   `Je hebt je verdiept in de API en aan de hand van API docs de op te halen data zo efficient mogelijk opgevraagd`: Voordat mijn teamgenoot besloot om alle api data op te slaan, was het mijn taak om de data op te halen uit de verschillende api's. 
    * [Klik hier voor de api.js bestand](#ejs)
    * Bovenin de `api.js` bestand kan je de algemene functie's vinden die data ophaald uit een bepaalde api eindpoint ophalen. Deze functie's hebben een url nodig of url en een acces token.
    ```javascript
    function getDataWithToken({url,acces_token}){
        return fetch(url,
        {
            headers:
            {
            'Authorization': 'Bearer ' + acces_token
            }
        })
            .then(response=> response.json())
    }

    function getData(url){
        return fetch(url)
            .then(response=> response.json())
    }
    ```
    * Voorbeeldcode van 1 van de api functie's binnen `api.js` bestand:
        * Alle functie's binnen een bepaalde api worden in een object property gestopt met als naam de API bron en de functie's callen allemaal een andere endpoint
        ```javascript
        const spotifyApi ={
            search: (name, acces_token) =>{
                const config = {
                    url: `https://api.spotify.com/v1/search?q=${name}&type=artist&limit=5&offset=0`,
                    acces_token
                }
                return getDataWithToken(config)
            },
            artist: (id, acces_token)=>{
                const config = {
                    url: `https://api.spotify.com/v1/artists/${id}`,
                    acces_token
                }
                return getDataWithToken(config)
            },
            related: (id, acces_token) =>{
                const config= {
                    url: `https://api.spotify.com/v1/artists/${id}/related-artists`,
                    acces_token
                }
                return getDataWithToken(config)
            },
            topTracks: (id, acces_token) =>{
                const config = {
                    url: `https://api.spotify.com/v1/artists/${id}/top-tracks?country=NL`,
                    acces_token
                }
                return getDataWithToken(config)
            }
        }
        ``` 
*   `Ik heb geen enkele OCD source-formatting neiging als ik naar jouw code kijk. De structuur is volledig duidelijk en logisch opgezet`
    * [Klik hier voor de ejs mappenstructuur en link naar de ejs files](#ejs)
    * [Klik hier voor de js mappenstructuur en link naar de js files](#Mappen-indeling-JS)
*   `Het is gelukt om, met behulp van een micro library, JSON data te renderen naar HTML`
    * De JSON data word allemaal gerenderd in de server. De template engine dat hiervoor werd gebruikt is EJS. Zoals ik al eerder heb vermeld worden de verschillende routes opgevraagd door de client, waardoor we html data kunnen inladen de webpagina te herlanden. Deze routes hebben allemaal hun eigen geformateerde data, zodat deze data correct worden omgezet tot elementen door ejs.
    * [Klik hier de route file source code](https://github.com/LaupWing/Linernote_finalV2/blob/master/server/routes.js) 
#### RTW
##### Punten uit de rubric
*   `Je hebt methodes gecreëerd die clients in staat stelt middels jouw eigen API te communiceren met jouw server. Real time connectiviteit is op een slimme manier opgezet`