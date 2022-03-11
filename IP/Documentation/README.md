# Table of contents
1 [Distributed Software System](#DistributedSoftwareSystem)

2 [Distributed Communication](#DistributedCommunication)

3 [Quality Assurance](#QualityAssurance)

4 [Data Persistency](#DataPersistency)

5 [Front-End Development](#Front-EndDevelopment)

6 [Back-End Development](#Back-EndDevelopment)


# 1. Distributed Software System	<a name="DistributedSoftwareSystem"></a>

Wat is een distributed software system?
Een gedistribueerd  softwaresysteem is een softwaresysteem dat bestaat uit meerdere softwarecomponenten die zich op meerdere computers (servers) bevinden, maar als één systeem worden uitgevoerd

Wat is het verschil tussen een monoliet en een gedistribueerd softwaresysteem?
Een monoliet softwaresysteem draait binnen één softwaretoepassing  waarbij de gebruikersinterface en datatoegangscode vanuit één platform worden gecombineerd tot één programma.

Welke voordelen biedt een gedistribueerd softwaresysteem?
Een toename van servers betekent een snellere run-time (minder wachten) en de mogelijkheid om specifieke taken toe te wijzen aan een server.

Leg uit waarom uw architectuur wordt gedistribueerd
Nog doen!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!

Wat zijn de belangrijke architecturale principes en technieken bij het ontwikkelen van een gedistribueerd softwaresysteem?

Nog doen!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!

# 2. Distributed Communication <a name="DistributedCommunication"></a>	

Wat is een techniek die kan worden gebruikt om berichten naar andere componenten in een gedistribueerde systeem te verzenden?

Wat is een techniek die kan worden gebruikt om een Observer- of publish-subscribe-patroon in een gedistribueerde systeem te implementeren?

Wat is REST?
REST staat voor Representational state transfer en is een software architectuur voor gedistribueerde software systemen.  REST wordt gebruikt voor het ontwerpen van een API (Application Programming Interface). Met een REST(full) API worden API’s bedoeld die de HTTP-standaard accepteren. 

Wat is een Websocket?
Een websocket is net zoals een API een connectie tussen twee computers maar heeft als groot verschil dat deze connectie maar één keer aangeroepen wordt. Bij een API wordt de connectie na het versturen verbroken terwijl bij een websocket deze open blijft. Als een websocket voor het eerst verbonden wordt maakt deze een ‘’Handshake’’ aan. Deze handshake bepaalt de locatie en de poort voor de verbinding. De verbinding gaat pas weg als een van de computers wegvalt.  
Een websocket is handig voor programma’s die real time updates nodig hebben zoals chat applicaties of games. Het is voor deze programma’s onhandig om telkens een API te gebruiken met HTTP omdat ze steeds weer nieuwe data moeten inladen.

Wat is een API?
Een API (Application Programming Interface) is een connectie tussen twee computer(-programma’s) en maakt het mogelijk om services aan te vragen (bijvoorbeeld het versturen of opvragen van data). Een API wordt vaak vergeleken met een Ober in een restaurant. De klant (Client) bepaalt op een menu wat hij wilt eten en geeft zijn order door aan de ober (API), De ober brengt de order door naar de keuken (Database) die op zijn beurt het eten geeft aan de ober zodat deze het eten naar de klant kan brengen. De connectie tussen de twee computers wordt na elke doorgave vebroken.

Can you name some architectural styles that can be considered a distributed software architecture?

Wat is Swagger?
Swagger is een tool om API’s te testen en te documenteren.

# 3. Quality Assurance	<a name="QualityAssurance"></a>	
# 4. Data Persistency 	<a name="DataPersistency"></a>	

Wat is datapersistentie?
Data persistence is het opslaan van data in non-volatile geheugen. Non-volatile geheugen behoudt de waarden, ook zonder stroom. Denk maar aan een USB-stick. 
Wat zijn enkele veelgebruikte soorten databases?
NoSQL, Relationele databases en cloud databases.
Wat is een ORM?
Object-Relational Mapping is een techniek voor het opslaan, wijzigen, verwijderen en ophalen van gegevens voor een object georiënteerd programma in een relationele database.
Welke ORM's zijn beschikbaar?

Welke ORM heb je gebruikt in je softwareapplicatie?
Wat is een entiteitsmanager?
Wat is het verschil tussen eager en lazy loading en wanneer gebruik je welke?
Hoe definieerde je 1-1; 1-N; N-M relaties in je ORM code?

# 5. Front-End Development <a name="Front-EndDevelopment"></a>	

Javascript heeft veel verschillende frameworks daarom heb ik onderzoek gedaan naar de drie meest gebruikte frameworks op het moment en deze vergeleken. 

<img src="https://user-images.githubusercontent.com/99740736/157831992-05f094a0-7420-4919-9a56-e54706f85d7c.png">


Na het onderzoek de matrix ingevuld  te hebben blijkt React de beste keuze te zijn voor de front-end framework. React is de meest populaire framework op het moment en heeft als grootste pluspunt dat het gemakkelijk te leren zou moeten zijn.

# 6. Back-End Development <a name="Back-EndDevelopment"></a>	

Wat is de definitie van software back-end?
Back-end software is de software die draait op de server en ervoor zorgt dat de front-end de benodigde data heeft om te kunnen functioneren.

Wat is een applicatieframework?
Een framework is een platform voor de ontwikkeling van software. Het bestaat meestal uit een (grote) verzameling bibliotheken en tools die kunnen worden gebruikt om veel standaardwerk van de ontwikkelaar weg te nemen en om functies en oplossingen te bieden voor veelvoorkomende situaties. Een raamwerk helpt de ontwikkeling te versnellen en heeft als doel de onderhoudbaarheid te verbeteren.

Wat zijn enkele veelgebruikte application frameworks?
Voor .Net: Core en Framework.
Voor Java: Spring, Jetty, Java EE

Waarom is het framework dat ik heb gekozen geschikt voor mijn toepassing?
.Net Core word is een nieuwere framework en bied ook ondersteuning voor andere platforms zoals Linux of macOS. Dit is de juiste keuze voor mijn project zodat het project op elk platform ondersteund zal worden.




## 1.1	Wat is het C4 model?

Om inzicht te creëren over dit project en de software wordt er gebruik gemaakt van de C4 methode. Deze methode is ontworpen om de architectuur van software duidelijk over te kunnen brengen aan zowel technisch als niet-technische belangstellenden bij het project. De methode bestaat uit 4 lagen of levels van diagrammen waarbij ieder net iets technischer over de software gaat dan de vorige.
De levels zijn:
•	C1 System Context diagram (weinig tot geen technische kennis nodig om diagram te begrijpen, beschrijft globaal wat het systeem doet.)
•	C2 Container diagram (begrijpelijk voor belangstellenden met weinig technische kennis.)
•	C3 Component diagram (begrijpelijk voor belangstellenden met technische kennis, bevat informatie over microservices en componenten van het systeem.)
•	C4 Code diagram (is alleen begrijpelijk voor belangstellenden met hoge technische kennis. Dit diagram gaat dieper op de code in en toont hoe de code geïmplementeerd zal worden.) 


## 1.2	C1 system context diagram

![image](https://user-images.githubusercontent.com/99740736/157423239-14772b3b-f224-40e3-9b57-5469b91e2d84.png)


## 1.3	C2 container diagram
 
![image](https://user-images.githubusercontent.com/99740736/157425021-e4ab7d7c-6030-406b-9830-1254c10ffacd.png)

