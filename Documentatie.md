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




 


