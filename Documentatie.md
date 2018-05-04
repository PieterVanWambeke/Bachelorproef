P : Deze bachelorproef zal gaan over de toekomst van server based computing. Gaan we stilaan overschakelen naar serverless computing. Met andere woorden keren we terug naar smart endpoints/smart devices of alternatieven zoals VDI (gaat het terug naar de client)? 

S :En hoe gebeurt de dataopslag vandaag en hoe zal dit evolueren (centraal / decentraal). Ik zal dan ook kijken of services zoals RDS/Citrix nog evenveel van toepassing zullen zijn naar de toekomst toe.

-----

Vooraleer ik dit verder ga uitwerken in latex ga ik meerst wat meer informeren over het onderwerp zelf, de termen bespreken en dit docomenteren. Dan zal ik aan de slag gaan om dit te verwerken in latex en in mijn BP.

(Het onderzoek hieromtrent zal voor een later tijdstip zijn)

-----

Wat is server based computing ?

webdefinitie: 
Server Based Computing is een variant van client-server computing. Bij client-server computing worden bepaalde verwerkingstaken zoals databeheer op een centrale server uitgevoerd en andere verwerkingstaken, zoals het presenteren van de gebruikersapplicatie en printen van data, op de client. 

Dus met andere woorden, SBC is een technology waarbij applicaties geimplementeerd, gecontrolleerd en gesupport zijn op een server in plaats van op een client. SBC is ook bekend als "thin client computing".

Origineel was SBC alleen maar toetsenborden en monitoren geconecteerd aan een centraal computer of mainframe. In de jaren 80 en 90
individuele  werkstationen werden steeds beter/sterker en PCs kregen meer kracht. Hierdoor werd de centrale computer steeds minder belangrijk en werd werk gedistributeerd door op elk werkstation.


Wat is serverless computing ?

Serverless architectuur is een product van cloud computing.

Eerst waren er 3 vormern van cloud computing 

IaaS: Infrastructure as a service
PaaS: Platform as a service
SaaS: Software as a service

Later kwamen er veel "as a service" modellen erbij. Vele bedrijven hebben hun producten en services omgezet in aaS model.
Een aaS modle biedt vele mogelijkheden. Men zelf geen zorgen maken over de architectuur van het product en de prijs hangt af van de hoeveelheid data dat men verbruikt. Dankzijs APIs zijn ze makkelijk om te gebruiken en aan te passen.

Wanneer men deze services gaat gebruiken, gaan grote delen van je gebruikte applicaties ook naar de cloud service providders.
Dankzij deze services moeten ontwikkelaars geen "monolithic full stack applicaties" maken. Ze kunnen gewoon deze verschillende cloud services met elkaar verbinden, zo kunnen ze applicaties maken zonder het gebruik van servers.



-----

bronnnen:

https://www.quora.com/What-is-Serverless-Computing


https://www.techopedia.com/definition/24428/server-based-computing--sbc

-----

Wat is de huidige situatie? Waarom is men zo te werk gegaan, dus welke voorbeelden biedt de huidige generatie van server based computing-oplossingen? Waar zijn de pijnpunten? Waar moeten eventuele alternatieven dan minstens aan voldoen als ze bruikbaar moeten zijn?
 Hoeveel precies? Hoeveel bedrijven gebruiken nu SBC en hoeveel (aantal/percentage) wil overschakelen? En waar haal je die bewering vandaan? Wie zegt dat ze zullen overschakelen? Wat zijn dan precies die alternatieven en wat zouden daar dan de voordelen van zijn?

Een eerste stap kan dus zijn om de huidige situatie gedetailleerd te beschrijven. Je kan gaan praten met mensen uit Orbid, marktanalyses opzoeken, enz.
Kijken vanuit Orbid 



Hoe zit server based computing er vandaag de dag uit en hoe nemen bedrijven dit op in hun infrastructuur ?
Het primaire doel van server based computing is om een de netwerkapparatuur en alle applicaties van een bedrijf centraal te zetten. Dus werken met centrale opslag, alle gegevens en bestanden worden op 1 locatie gezet zodat de bestanden niet verspreid geraken. Vaak met vele cloud providers zoals Dropbox, Google Drive enzovoort weet men niet waar je data staat of deze allemaal op 1 locatie staat. Door centrale opslag weet men waar de data staat ,is de onderhoud van het netwerk ook goedkoper en sneller en kan men sneller aan de applicaties en de gegevens. 
Indien men wijzigingen wil brengen hoeft dit maar op 1 locatie uitgevoerd worden. 
Vroeger werkten bedrijven nog met terminals en mainframes vandaag de dag heeft bijna iedereen een PC/laptop waardoor dit verdwijnt.
Vandaag hebben de meeste moderne netwerken een client-server technologie. Hierin heb je zowel een centrale opslag als werkstations ( meetstal personal computers ).  Het beheer van SBC is wel een stuk complexer dan in de tijd van mainframe, toen werd alles centraal beheerd en verwerkt. 
Vandaag de dag is de hardware, software en infrastructuur in een bedrijfsnetwerk een stuk complexer als in de tijd van mainframe waar bijna alles kon geautomatiseerd worden. 
De netwerktechnologie SBC zorgt er gewoon voor dat alles 100% kan worden geïnstalleerd op 1 of meerdere servers die centraal zijn opgesteld. 
Hierdoor moeten werkstations zelf geen software of programma’s hebben van gebruikers een werken deze enkel nog als een communicatiemiddel. De uitwisseling tussen deze werkstations en servers is minimaal er wordt nog enkel gebruik gemaakt van externe informatie zoals beeldscherm/toetsenbord/muis interactie. 
Door gebruik te maken van SBC verloopt alles vlotter voor gegevenswisseling en onderhoud is goedkoper. 
De gegevensbewerking op een traditionele PC gebeurt decentraal, aangezien elke PC een eigen OS en applicaties heeft.
Bij SBC delen meerdere gebruikers 1 besturingssysteem vb. windows server 2016. RDS (microsoft) voor heen terminal services. Hierdoor kunnen we de volledige desktop presenteren aan de eindgebruikers via een thin client of een laptop. Via VMware horizon heb je ook de mogelijkheid om gwn applicaties aan te bieden op smartphones en tablets.

Een VDI staat op een centrale locatie opgesteld, met VDI kunnen we meerder os en virtuele pc’s op een fysieke server zetten. 
SBC en VDI maken allebei gebruik van centralisatie en grootste verschil is dat VDI , is dat VDI gebruik maakt van een desktop OS, bij SBC is dit server besturingssystemen.
http://www.computerweekly.com/feature/Server-based-computing-gets-a-lift
http://www.brianmadden.com/podcast/A-talk-about-the-future-of-Citrix-and-the-Server-Based-Computing-Industry


 


 

https://www.arrowsict.nl/server-based-computing
https://go.vlcmtech.com/hubfs/Gartner_Modular_Servers.pdf?t=1519789696581
https://www.commitment.nl/verschil-server-based-computing-en-virtual-desktop-infrastructure/


Oplossingen SBC:

Citrix -> ….
Cisco -> ….
SBC oplossingen zoeken

---

Citrix en Microsoft in SBC
SBC-variant van client-server
Microsoft en citrix werken goed samen omtrent SBC.
Citrix was de eerste op de markt die opkwam met SBC-programma’s. 
Citrix heeft nooit echt een grote concurrent gehad op de markt van SBC en was altijd de leider zeker ook door de goede samenwerking met Microsoft. 
XenApp is de oplossing van Citrix maar nu heeft VMware ook een SBC-oplossing. 

Voordelen van SBC 
-	Lagere kosten voor IT-beheer 
-	Beter te beveiliging 
-	Lager kosten hardware 
-	Lager energieverbruik
-	Minder diefstalgevoelig
-	Zware omgevingen
-	Minder netwerkbelasting
-	Efficiënter gebruik van resources
-	Eenvoudige hardware uitbreidingen

Nadelen SBC:
-	Hogere server requirements
-	Slechtere multimedia performance
-	Minder flexibiliteit

Andere producten zoals Dell vWorkspace, Thinspace (ProPalms) TSE, desktopsites’ Konect Elite, Ericom PowerTerm WebConnect maar weinig van deze kunnnen concureren tegenover citrix.
XenApp 6.5 product was geannuleerd en de eigenschappen gingen naar XenDesktop hierdoor waren veel gebruikers niet tevreden. 
VMware Horizon 6.
Citrix heeft een minder periode gehad waarbij veel klanten kozen voor concurrenten ook door het kiezen van een nieuwe CEO en mankementen technische richting. 
Citrix heeft nog steeds zeer veel klanten onder zijn beschikking die niet zomaar gaan veranderen van kant. 

 


http://searchvirtualdesktop.techtarget.com/opinion/Server-based-computing-market-blazes-as-Citrix-vs-VMware-fight-rages

Citrix XenApp en XenDesktop vs. VMware Horizon,
Citrix en VMware zijn de 2grootste huidige speler op de markt op vlak van SBC/VDI-markt, ik ga hun beide producten bekijken en vergelijken. 

https://www.citrix.nl/products/xenapp-xendesktop/compare.html

https://nl.wikipedia.org/wiki/Server_based_computing
TCO: total cost of ownership

“The TCO of an SBC deployment used to deliver all applications to users is 8% to 13% lower than that of a locked and well-managed PC deployment, and up to 44 to 47% lower than that of an unmanaged desktop deployment.”

VMware offert geen SBC-oplossing, VMware offert alleen VDI als deel van desktop offering. 

https://www.citrix.com/blogs/2009/08/21/has-citrix-abandoned-server-based-computing/

mss onderwerp veranderen naar SBC vs VDI.
http://www.resultaatgroep.nl/blog/2017/11/15/heeft-server-based-computing-nog-toekomst-deel-2/

VDI is een nieuwere vorm van centralized computing terwijl SBC de oudere versie is van centralized computing.

----

BP uitgeschreven:

(Uitleg gevraagd aan promotor, die een algemene situatieschets heeft gegeven omtrent mijn onderwerp)

Voor Server based computing zijn de meest gebruikte providers Microsoft met remote desktop/app 
En Citrix met XenApp/XenDesktop. 

De Citrix producten zijn iets complexer en meer in detail ten opzichte van Microsoftproducten met Citrix heeft men meer specialisatie opties en meer policy’s. De keuze om te kiezen voor 16 bit schermen enzovoort.  

XenApp biedt de mogelijkheid om 1 applicatie te openen en te laten draaien. De applicatie wordt dan geopend op de lokale (centrale) server. Deze applicatie draait als een andere gewone applicatie op je besturingssysteem. 

De Citrix producten zijn dan ook niet gratis ten opzichte van Microsoftproducten die ingebouwd zijn in de windows server edities. Bij remote desktop/app kan je wel extra licenties bijbetalen. Voor XenApp/XenDesktop moet je dus betalen, deze producten zijn dan over het algemeen een stuk gebruiksvriendelijker en hebben meer functies. 

Veel bedrijven/klanten blijven bij de SBC-omgeving. Hoewel er nieuwere toepassingen zijn en betere oplossingen. Zijn veel bedrijven zeker die niet IT-gericht zijn geneigd om bij hun huidige structuur te blijven. Zolang het werkt is het goed voor velen. Indien ze een vernieuwing mensen moeten ze gans de omgeving (infrastructuur, hardware) vernieuwen maar ook alle bestaande applicaties moeten verplicht worden vernieuwd dit kost natuurlijk tijd en geld. 

Indien men gebruik maakt van volledige desktopoplossingen (full desktop), heeft men wel altijd een netwerkconnectie nodig het voordeel is wel dat het goedkopere oplossingen biedt aangezien men kan overstappen naar thin-clients.

Veel hangt ook af aan de voorkeur van de klant. Er is een bedrijf waar ze maar met 5 werknemers zijn toch gebruik maken van Citrix XenApp/XenDesktop omdat ze het gebruiksvriendelijker vinden en makkelijker hanteerbaar is.

Dankzij SBC staat ook alles centraal beheerd meestal bij het bedrijf zelf, waardoor gegevens snel traceerbaar zijn en men weet waar de data staat. 

Veel klanten/bedrijven zijn ook nog niet klaar voor te migreren want migratie kost ook veel tijd en geld en moet er ook nagegaan/onderzocht worden hoelang dit gaat duren en hoeveel geld dit gaat kosten. 

Volgens mijn stagementor hebben de meeste bedrijven in Vlaanderen een eerder afwachtende houding als het aankomt op technologie vernieuwing. Ze blijven hun ding doen zolang het werkt want ze hebben de tijd/budget/zin niet om een gans nieuwe technologie laten implementeren. 

Thin clients kan je ook makkelijk laten verbinden met Azure. ( ??? ) 

Het gaat dus nog lang duren voor men gaat afstappen van SBC. Maar binnen 10-20 jaar gaat men wel veel meer geneigd zijn naar cloud oplossingen. De cloud wereld wordt ook steeds groter en groter en er komen steeds meer producten op de markt zoals Egnyte, ShareFile die cloud oplossingen bieden. 

Voor nieuwe bedrijven is dit dan meestal de beter oplossing aangezien men zo minder hardware/infrastructuur omgevingen moet omzetten waardoor men toch een pak geld spaart ook is er geen onderhoud nodig in de cloud.

VDI en SBC lopen naast elkaar, er wordt vaak beweerd dat VDI een beter oplossing is als SBC maar dit is opnieuw volledig afhankelijk van de omgeving hoe het toegepast wordt en met welke doeleinden. 

Als men honderden gebruikers nodig heeft zou men in indien men VDI gebruikt voor elke gebruiker apart een omgeving moeten opzetten dit is natuurlijk allesbehalve optimaal.

Bij SBC maakt men dan gewoon meerdere servers aan met elk een aantal gebruikers men kan dan ook makkelijk servers toevoegen of verwijderen. Het nadeel wel aan dit soort werken is als 1 iemand een fout maakt of ervoor zorgt dat server niet meer werkt, werkt deze server voor alle gebruikers niet.
 
VDI-oplossingen zijn wel meer naar de cloud gericht. ( ??? ) 
VDI werkt met windows 7,8,10 terwijl SBC met windows server werkt. 
VDI heeft ook meer geheugen nodig snel 4GB ram per VM.  

Ook met Citrix is het makkelijker om VMs aan te maken, je kan ze allemaal gelijke tijd aanmaken aan een snel tempo in plaats van ze een voor aan te maken. Dit kan veel tijd kosten zeker voor bedrijven die telkens honderden virtuele machines moeten aanmaken. Het werkt namelijk met templates waardoor dit in een snel proces kan gebeuren. 

De visie van Microsoft is wel om meer en meer over te schakelen naar apps en smart end devices. Ze zien ook dat SBC verouderd aan het geraken is en willen zoveel mogelijk toekomstgericht werken natuurlijk gaat dat niet van vandaag op morgen.  Ze willen alles in de cloud plaatsen in plaats van op een server. Alle Dynamics webbased maken. 

Natuurlijk waarom men niet alles naar de cloud wil gooien is omdat veel bedrijven nog graag hun gegevens on-premise ter beschikking willen hebben. Voornamelijk zodat ze dan meer controle hebben over de security. Men ziet toch dat men nog altijd schrik heeft om gevoelige data in de cloud te gooien.

In de cloud makkelijk prijzen bereken en goedkoper men kijkt gewoon naar het aantal gebruikers en aantal verbruikte data.

SBC/VDI makkelijk prijzen bereken kijken hoeveel gebruikers en hoeveel data men verbruikt. (???)


---

XenApp/ XenDesktop heeft remote desktop services nodig om goed te functioneren.

MRD pro’s en cons:
RDS offert een singular aanpak om applicaites op te leveren boven een windows server operationg system
http://markets.businessinsider.com/news/stocks/citrix-xenapp-and-xendesktop-services-now-available-in-oracle-cloud-marketplace-1011082514

Citrix business aanpak:

 
Men ziet da citrix een stijgend vermogen heeft.
XenApp en XenDesktop zijn nu beschikbaar in de Oracle cloud Marketplace.

Benefits of VDI:
•	Utilization of Same Image.
•	Management of a Single OS Can Reduce Costs.
•	Processing moves from individual workstations to a VDI server.
•	Troubleshooting Problems is Easier.
•	Data is More Secure.

Benefits of RDS:
•	Single point of maintenance.
•	Install once, use many.
•	Reduced licenses expense.
•	Solid Security.
•	Lower Costs.
http://www.brianmadden.com/opinion/Why-its-finally-time-for-Microsoft-to-buy-Citrix-Heres-our-full-analysis


VMware Horizon View:

Microsoft ziet VMware als een concurent. 

Net als VMware sterker aan het worden is wordt citrix steeds zwakker.
Citrix krijgt druk van elliott, werknemers die weggaan negatieve quarter-over quarter sales een lange tijd moeten zoeken voor een nieuwe CEO. Strategy dat niet altijd optimaal is.
Dus microsoft kan niet altijd vertrouwen op citrix. Een zwak citrix is slecht voor microsoft.
Microsoft en Citirx zijn al voor meer dan 25 jaar trouwe partners. Ze hebben meer dan 230k gezamenlijk klanten. 

-	Kijken naar toekomst SBC 
-	Kijken grote marktspelers en producten
-	Kijken naar stabiliteit van deze houders en waarom hun producten goed zijn en naar de toekomst gericht 
-	Welke marktspelers het sterkst staan
The hedge fund elliott managment owned 7% van citrix sinds 2015.
http://www.citrixguru.com/2017/04/10/microsoft-dont-buy-citrix/
http://www.synextra.co.uk/citrix-vs-rds-2016-best-hosted-desktop/


----

BP uitgeschreven:

(Uitleg gevraagd aan promotor, die een algemene situatieschets heeft gegeven omtrent mijn onderwerp)

Voor Server based computing zijn de meest gebruikte providers Microsoft met remote desktop/app 
En Citrix met XenApp/XenDesktop. 

De Citrix producten zijn iets complexer en meer in detail ten opzichte van Microsoftproducten met Citrix heeft men meer specialisatie opties en meer policy’s. De keuze om te kiezen voor 16 bit schermen enzovoort.  

XenApp biedt de mogelijkheid om 1 applicatie te openen en te laten draaien. De applicatie wordt dan geopend op de lokale (centrale) server. Deze applicatie draait als een andere gewone applicatie op je besturingssysteem. 

De Citrix producten zijn dan ook niet gratis ten opzichte van Microsoftproducten die ingebouwd zijn in de windows server edities. Bij remote desktop/app kan je wel extra licenties bijbetalen. Voor XenApp/XenDesktop moet je dus betalen, deze producten zijn dan over het algemeen een stuk gebruiksvriendelijker en hebben meer functies. 

Veel bedrijven/klanten blijven bij de SBC-omgeving. Hoewel er nieuwere toepassingen zijn en betere oplossingen. Zijn veel bedrijven zeker die niet IT-gericht zijn geneigd om bij hun huidige structuur te blijven. Zolang het werkt is het goed voor velen. Indien ze een vernieuwing mensen moeten ze gans de omgeving (infrastructuur, hardware) vernieuwen maar ook alle bestaande applicaties moeten verplicht worden vernieuwd dit kost natuurlijk tijd en geld. 

Indien men gebruik maakt van volledige desktopoplossingen (full desktop), heeft men wel altijd een netwerkconnectie nodig het voordeel is wel dat het goedkopere oplossingen biedt aangezien men kan overstappen naar thin-clients.

Veel hangt ook af aan de voorkeur van de klant. Er is een bedrijf waar ze maar met 5 werknemers zijn toch gebruik maken van Citrix XenApp/XenDesktop omdat ze het gebruiksvriendelijker vinden en makkelijker hanteerbaar is.

Dankzij SBC staat ook alles centraal beheerd meestal bij het bedrijf zelf, waardoor gegevens snel traceerbaar zijn en men weet waar de data staat. 

Veel klanten/bedrijven zijn ook nog niet klaar voor te migreren want migratie kost ook veel tijd en geld en moet er ook nagegaan/onderzocht worden hoelang dit gaat duren en hoeveel geld dit gaat kosten. 

Volgens mijn stagementor hebben de meeste bedrijven in Vlaanderen een eerder afwachtende houding als het aankomt op technologie vernieuwing. Ze blijven hun ding doen zolang het werkt want ze hebben de tijd/budget/zin niet om een gans nieuwe technologie laten implementeren. 

Thin clients kan je ook makkelijk laten verbinden met Azure. ( ??? ) 

Het gaat dus nog lang duren voor men gaat afstappen van SBC. Maar binnen 10-20 jaar gaat men wel veel meer geneigd zijn naar cloud oplossingen. De cloud wereld wordt ook steeds groter en groter en er komen steeds meer producten op de markt zoals Egnyte, ShareFile die cloud oplossingen bieden. 

Voor nieuwe bedrijven is dit dan meestal de beter oplossing aangezien men zo minder hardware/infrastructuur omgevingen moet omzetten waardoor men toch een pak geld spaart ook is er geen onderhoud nodig in de cloud.

VDI en SBC lopen naast elkaar, er wordt vaak beweerd dat VDI een beter oplossing is als SBC maar dit is opnieuw volledig afhankelijk van de omgeving hoe het toegepast wordt en met welke doeleinden. 

Als men honderden gebruikers nodig heeft zou men in indien men VDI gebruikt voor elke gebruiker apart een omgeving moeten opzetten dit is natuurlijk allesbehalve optimaal.

Bij SBC maakt men dan gewoon meerdere servers aan met elk een aantal gebruikers men kan dan ook makkelijk servers toevoegen of verwijderen. Het nadeel wel aan dit soort werken is als 1 iemand een fout maakt of ervoor zorgt dat server niet meer werkt, werkt deze server voor alle gebruikers niet.
 
VDI-oplossingen zijn wel meer naar de cloud gericht. ( ??? ) 
VDI werkt met windows 7,8,10 terwijl SBC met windows server werkt. 
VDI heeft ook meer geheugen nodig snel 4GB ram per VM.  

Ook met Citrix is het makkelijker om VMs aan te maken, je kan ze allemaal gelijke tijd aanmaken aan een snel tempo in plaats van ze een voor aan te maken. Dit kan veel tijd kosten zeker voor bedrijven die telkens honderden virtuele machines moeten aanmaken. Het werkt namelijk met templates waardoor dit in een snel proces kan gebeuren. 

De visie van Microsoft is wel om meer en meer over te schakelen naar apps en smart end devices. Ze zien ook dat SBC verouderd aan het geraken is en willen zoveel mogelijk toekomstgericht werken natuurlijk gaat dat niet van vandaag op morgen.  Ze willen alles in de cloud plaatsen in plaats van op een server. Alle Dynamics webbased maken. 

Natuurlijk waarom men niet alles naar de cloud wil gooien is omdat veel bedrijven nog graag hun gegevens on-premise ter beschikking willen hebben. Voornamelijk zodat ze dan meer controle hebben over de security. Men ziet toch dat men nog altijd schrik heeft om gevoelige data in de cloud te gooien.

In de cloud makkelijk prijzen bereken en goedkoper men kijkt gewoon naar het aantal gebruikers en aantal verbruikte data.

SBC/VDI makkelijk prijzen bereken kijken hoeveel gebruikers en hoeveel data men verbruikt. (???)




Pieter Van Wambeke – Orbid
Het eerste gedeelte gaat er een uitgebreide literatuurstudie worden opgemaakt waarin ik de begrippen SBC en VDI ga verklaren en met elkaar ga vergelijken. Hierbij zal ik ook de grote markspelers en producten bekijken op vlak van SBC en VDI en deze ook met elkaar vergelijken.
Ook kan ik nog kijken naar cloud oplossingen die vandaag bestaan voor VDI en SBC
Het 2de gedeelte ga ik mijn literatuurstudie toepassen op een reële casus. Ik ga mijn opgenomen kennis uitvoeren op 3 bedrijven die klant zijn bij het bedrijf Orbid waar ik stageloop. Ik ga kijken naar de huidige infrastructuur van deze bedrijven die SBC/VDI gericht zijn, kijken naar de problemen en wat er beter zou kunnen, waarom ze deze infrastructuur gebruiken en kijken naar welke producten ze gebruiken.
Het 3de gedeelte ga ik een algemeen besluit maken van VDI/SBC en in welke situaties nu best wat gebruikt wordt. 
De bedoeling van die onderzoek is om een beter beeld te verkrijgen op SBC/VDI en in welke situaties welke technologie nu het best past en hoe die in de praktijk wordt uitgevoerd.
Ook om een verschil van kwaliteit/functies/prijs te bekijken. 

Situatieschets bedrijven:

Interview met Filip Monbalieu vrijdag 13 april 2018
Flanders hotel holding:

Flanders hotel holding is een van de bedrijven die onderzocht zullen worden voor deze bachelorproef. Het bedrijf is een klant van Orbid. 
Flanders hotel holding bestaat uit 5 deel bedrijven, het eerste is “Auberge du pecheur” in Sint-Martens Latem wat een hotel is. Het 2de is hotel “Serwir” in Sint-Niklaas, het 3de “Gosset hotel” in Groot-Bijgaarden, het 4de is “charl’s” dat een bar/brasserie/vakantielogies is en het laatste is “Diner Privé catering” wat een traiteurdienst is. 
Dus het gaat voornamelijk om een bedrijf met meerdere hotels. Het IT-gedeelte van dit bedrijf is beperkt maar moet altijd beschikbaar zijn aangezien de hotels altijd de mogelijkheid moeten bieden voor boekingen/reservaties/annulering te maken. Er moet dus een beschikbare service zijn die 24/7 moet draaien. De uptime is 99.9 procent
Situatiebeschrijving flanders hotel holding infrastructuur.
De volledige infrastructuur van flanders hotel holding staat in de cloud ter beschikking, het is volledig cloud based. Het is dus een IaaS klant (Infrastructure as a service), 
Ze maken gebruik van vContainer dat een onderdeel is van Belgacom Proximus (Proximus de Belgische telefoonmaatschappij). 
https://www.userfull.be/src/Frontend/Files/userfiles/files/Producten/Cloud/Brochure%20Proximus%20Cloud%20vContainer%20-%20NL.pdf
De cloud vContainer is een van de cloud oplossingen die Proximus biedt. Het is een oplossing die vele voordelen biedt.
-	Minder investigeren in on-premise infrastructuur.
-	Meer flexibiliteit, betaal de hoeveelheid data dat je verbruikt.
-	Beter bereikbaarheid doordat alles centraal staat opgeslagen.
-	Beter veiligheid, datacenters van Proximus zijn zeer goed beveiligd en uitgerust. 
-	Focus op VW core
-	Green IT
De Belgacom Proximus vContainer is gebouwd op een infrastructuur die gehost wordt in het Belgacom datacenter. Vanaf verschillende sites liggen er connecties naar het datacenter.
Cloud opslag betekent niet dat er geen on-premise infrastructuur meer is, je data staat nog altijd gewoon opgeslagen in een/meerdere datacenter op hardware. Maar deze hardware staat niet meer on-premise lokaal in het bedrijf beschikbaar.
Bijvoorbeeld Orbid maakt gebruikt van een Orbid Cloud voor oplossingen te bieden aan klanten. Deze Orbid Cloud staat ter beschikking in een datacenter van Interoute in Merelbeke. Orbid huurt een deel af van het datacenter om zelf te gebruiken. Indien er probleem zou vallen met het datacenter komt de data ter beschikking op een andere Interoute datacenter ofwel in Parijs of in Amsterdam. 
De bedoeling van cloudopslag is dat het altijd en overal ter beschikking zal moeten blijven ook al valt er iets voor in het datacenter, daarmee is back-up heel belangrijk. Security staat ook heel hoog in deze datacenters, veel mensen/klanten denken vaak als hun data in de cloud staat die minder veilig is maar vaak is het meestal het tegenovergestelde. 

Alle applicaties dat ze gebruiken staan dus in het Proximus datacenter en kunnen ter beschikking gesteld worden met Citrix XenApp.
Citrix XenApp dat al eerder besproken is biedt dus enkel applicaties ter beschikking en geen volledige desktop. Dus ze werken dus met een SBC-infrastructuur en niet VDI, alles staat ook centraal beheerd in de cloud.
Als een gebruiker inlogt op een bepaalde site kunnen ze gebruik maken van XenApp om aan de nodige applicatie(s) te geraken. 
Waarom gebruik ze liever XenApp in plaats van XenDesktop in deze situatie of geen andere mogelijkheden.
Ten eerste is XenApp een betere technologie als het aankomt op vlak van printing. En over het algemeen is er een beter gebruik bij XenApp als bij XenDesktop. 


Welke software gebruiken ze nog?
Ze maken gebruik van een hotelsoftwarepakket genaamd IDPMS wat hun belangrijkste pakket is. Deze software wordt niet ondersteund vanuit Orbid. 
Daarnaast gebruiken ze nog een automatisch batchsysteem die alle medewerkers dan gebruiken voor in-en uit te batchen deze is dan op zijn beurt gekoppeld aan hun registratie. Zodat men makkelijk de gewerkte uren van alle werknemers kan nakijken en controleren. 
Buiten dat maken ze ook nog gebruik van een kassasysteem en een applicatiesysteem. Ook nog een e-mail/files applicaties, marketingapplicaties. 
Daarbuiten hebben ze ook nog een website ter beschikking deze is apart gehost volledige buiten de Proximus server. 
Het totaalaantal gebruikers strijkt neer op +- 25 mensen.
De technische setup is dat ze gebruik maken van 1 citrix server die dan geïnstalleerd staat op de Proximus vContainer. Ook maken ze gebruik van een citrix management en applicatie server (dit is de omgeving waar de gebruikers op aanloggen).
Deze servers draaien bijna constant en kan men niet zomaar herstarten of aan passen. Aangezien alles permanent ter beschikking moet blijven draaien deze server 24/7 en kan men deze niet zomaar uitschakelen. 
Alles werkt ook met windows server en niet met OS zoals windows 8 of 10. 
Probleem is dat de servers soms wat overbelast geraken waardoor ze nu naar oplossingen aan het kijken zijn bij Orbid voor het op te splitsen van de server naar 2 XenApp server en een afzonderlijke managementserver.
De vraag die dan nog gesteld moet worden is of VDI in dit bedrijf en in deze situatie beter zou zijn of een verbetering zou zijn ten opzichte van de huidige structuur. 
Ik heb de vraag gesteld aan Filip Monbalieu gij zegt dat het zeker zou kunnen om over te schakelen naar een VDI-oplossing maar het geen verbetering zou zijn ten opzichte van de huidige structuur.
Er is ook geen goede reden in het bedrijf zelf om over te schakelen naar VDI ze zijn zelf geen IT gericht bedrijf en legen een groot deel van de verantwoordelijkheid bij Orbid. En vanuit het oogpunt van Orbid is SBC beter dan VDI. 
Er wordt lokaal ook weinig aan IT gedaan buiten de marketingafdeling dan, het is zoals eerder vermeld dan ook geen IT gericht bedrijf de IT-infrastructuur is enkel voor bedrijf te helpen en in goede banen te leiden.
De klant betaalt elke maand een fixed price tegenover Orbid, Orbid stelt dus alles samen van prijzen voor de klant en probeert een zo goed mogelijk prijs voor te schotelen aan de klant. 
Aangezien ze zelf geen lokale hardware/infrastructuur hebben is Orbid ook aan het kijken of er geen beter cloud oplossing is voor het bedrijf zoals overschakelen naar Interoute VDC. Interoute is het bedrijf dat samenwerkt ook met Orbid. Het is het datacenter van Orbid waar ook de Orbid cloud zit. Men kijkt voornamelijk naar deze overschakeling op vlak van security, storage en permissies. Of om van Proximus naar Proximus te gaan. Want een Vcontainer is niet altijd even secure en er zijn in het verleden al meerdere fouten opgetreden op vlak van security met Vcontainer.
Voor mijn stage heb ik ook meerder malen met Interoute VDC gewerkt. Het is online omgeving waar je makkelijk VMs kan aanmaken en virtuele netwerken met windows/Linux servers kan aanmaken. 
Het bedrijf Orbid is een tussenpunt voor de klant, het is een tussenpunt tussen de bedrijven die de software/hardware leveren en het bedrijf dat effectief de software/hardware gebruikt.
Proximus en explores zijn andere bedrijven die ook een invloed hebben op de software gebruik van Flanders hotel holding.
In totaal gebruiken ze maar 6 Citrix VMs en ze hebben geen interne iT-support in de HDD.
PeterSime:

PeterSime is een productie/ontwikkeling bedrijf in Olsene in Oost-Vlaanderen. Ze zijn de wereldleiders op vlak van het maken van incubators en hatcheries. In vergelijking met de andere bedrijven is dit een veel grootschaliger bedrijf dan de andere 2. 
Peter Siemen productie/ontwikkeling:
1 hoofdsite Olsene – Oost -Vlaanderen
Aantal satellietensites dat zijn voornamelijk salesmensen heel klein
Daar zit er een IT-manager, junior team van Orbid 2* per week, senior team 2* per maand.
Onlangs overgeschakeld naar laatste versie van Ax2012 (axapta) , broerjte van microsfot dynamics.
-	ERP
Bron van alle infor bij beter simon.
CRM online
SharePoint online en office 365 
Zijn van plan voor skype for business. 
BI/Planning met axapta.
Remote xenapp citrix server based,
Geen VDI

Intern werken, xenapp remotedekstop enkel voor Ax2012.
4 xenapps servers
4 remote dekstop servers
Met elke afzonderelijk manamgnet server voor die farms
250 users,  die hebben hun eigen infrastructuur.
48 acces points wirelees vervangen.
Veel applicaties lokal, dagelijks mee mee bezig voor optimalisatie maar basis setup. 
Back up op tape 
Veel onderhoudswerk
Goekopere oplossing on-premise ipv cloud, veel vm’s. werken met vlans 
Geen desktop maar applicatie windows geen virtual desktop. 








 


