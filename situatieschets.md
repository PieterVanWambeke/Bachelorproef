Pieter Van Wambeke 
Bachelorproef SBC vs. VDI:

Interview met Filip Anne, Manager IT infrastructure 4 April 2018. 
Situatieschets verschillende bedrijven waar men werkt met VDI of SBC en kijken wat de beste implementatie zou zijn.
Ik ga voor mijn Bachelorproef kijken naar 2 technologieën, server based computing en virtual desktop infrastructure deze zijn zeer gelijkaardig aan elkaar en om deze gewoon met elkaar te vergelijken ga ik kijken naar de infrastructuur van 3 bedrijven. Ik ga hierbij nagaan wat hun huidige structuur is en of dit wel de beste oplossing is, ik ga kijken of er geen beter oplossingen bestaan voor de infrastructuur van de bedrijven. Het zal voornamelijk gaan over de SBC/VDI-infrastructuur waarbij ik dan kijken naar software/hardware van Microsoft, Citrix enzovoort. De 3 bedrijven verschillen elk enorm van elkaar van infrastructuur waardoor het interessant is om na te gaan wat voor elke situatie de beste oplossing is.
De eerste klant is SLV-verkoopkantoor voor licht en lichtsystemen (SLV –EXPERIENCE LIGHT).
SLV Belgium is een snelgroeiende verlichtingsfirma gevestigd in Wommelgem. Sinds 15 jaar is het bedrijf blijven groeien. Vandaag hebben ze een team van 16 medewerkers in België. De omzet van het bedrijf is +- 12 miljoen euro per jaar en verkopen uitsluitend via een netwerk van elektrogroothandels en lichtspeciaalzaken. 
Ongeveer 90% van de medewerkers zijn roadwarriors, wat wil zeggen dat ze niet vanuit een vast kantoor werken en vaak op de baan zijn. Het bedrijf werkt hierdoor met een mobiele infrastructuur, ze gebruiken een office omgeving, ze hebben ook nood aan online pressence en unified communication (UC, gaat over IT gerelateerde communicatievormen zoals e-mail, chat, VoIP, webconferencing, schermen delen…).
SLV maakt ook gebruik van ERP-pakketten (legacy en dave). Het dave pakket is gebaseerd op een SQL-database met een Custom ontwikkelde front-end. 
Ze maken gebruik van XenApp, applicatie gerichte SBC. Met ander woorden ze gebruiken geen webapplicaties, geen Multi-ende, ook geen SaaS applicaties of infrastructuur waardoor ze wel nood hebben aan een centraal systeem dat 24/7 beschikbaar is en ook mobiel toegankelijk is. Ze maken gebruik van Citrix oplossingen door onder andere XenApp te gaan gebruiken. 
Orbid heeft alle pc’s in het bedrijf windows 10 als besturingssysteem gegeven en een Azure ad joint gemaakt. Ze maken gebruik van intune policy’s en alle technologie werkt op Microsoft 365.
Microsoft 365, is een bundel van bestaande producten onder 1 licentie en gefocust naar de business. Niet te verwarren met Office 365, dat een cloud gebaseerde omgeving is waar allerlei producten van Microsoft ter beschikking staan (zoals Outlook, Word, PowerPoint, …). Office 365 valt zelfs onder Microsoft 365.  Ook windows 10 Enterprise valt onder Microsoft 365. 
	Nog kijken naar de verschillende modellen die ze ter beschikking hebben. 
Als datacenter oplossing gebruiken ze infrastructure as a service. Ze maken gebruik van 3 VMs, 1 applicatieserver, 1 SQL-server en 1 citrix server Remote Desktop Protocol (RDP). Ook met Azure AD-joint en gebruikers hebben single sing on. 
Azure AD-joint -> een pc dat niet in de AD staat wordt altijd over een lan gehost, Microsoft heeft hiervoor een oplossing voor mobiele gebruikers. Op de Azure AD kan je pc’s dan laten joinen zonder groep policy’s of intune policy’s. 
Het enige grote probleem bij SLV is het laten afprinten van dingen. Op Azure AD kan je geen gebruik maken van een print server. Dus hiervoor moet er nog een oplossing gezocht worden. Ook zijn file servers niet gemaakt voor op de cloud te zetten waardoor dit vaak voor problemen kan zorgen. 
Evolutie is dat we meer en meer naar een fat client gaan, pc’s met windows office 365 en outlook worden zoveel mogelijk online geplaatst. 
Het is ook voor SLV niet mogelijk om een webapplicatie ter beschikking te zetten, er is geen https ter beschikking via Citrix en RDP. 


Een tweede klant dat ik ga bekijken is hotelketen flanders hotel holding, daaronder valt “Auberge du pecheur”, “hotel serwir”, “gosset hotel”,”charl’s”,”Diner Privé”.
Elke vestiging heeft een eigen receptie met verschillende werkposten, ze maken gebruik van meerdere kassasystemen voor de restaurants. 
Ze hebben een gewone office omgeving met email. De meeste werknemers werken op een vaste plaats dus er is geen nood aan een mobiele oplossing. Aangezien het over hotelketen gaat moeten ze wel 24/7 beschikbaar zijn en de performantie moet ook goed zijn van de systemen. Ze werken met een legacy applicatie dat niet als SaaS werkt. SaaS is webbased zoals https, bijvoorbeeld Sharepoint is puur SaaS.
Meerdere mensen kunnen aan data via dezelfde URL binnenin de firma. IaaS is zoals VDC. PaaS is dan zoals SQL-online, database serveren waar iedereen op elk moment aankan, er is geen front-end alleen backend. 
Ze maken ook gebruik van Citrix XenDesktop als SBC/VDI-oplossing.  Voor dit bedrijf is dus een hybride oplossing een goede oplossing. 
De inrichting van het bedrijf is IaaS alle applicaties van office 365 staan lokaal op 1 server, die dan een full desktopoplossing biedt via XenDesktop. 
Ze gebruiken CRM voor commerciële activiteiten, SaaSapplicaties. 
CRM gebruiken voor commerciële activiteiten, SaaSapplicaties, ook een eigen pakket voor IaaS, ook office 365 voor email dat opnieuw SaaS is. En als on-premise infrastructuur, hebben ze nog een print server en een lokale AD.

Logica van analyse voor infrastructuur is om te kijken water in SaaS kan doen we in SaaS, al de rest doen we in PaaS wat niet in PaaS gaat doen we dan in IaaS. Dan de colocatie fysische hardware doen we in een datacenter en al de rest terug on premise. En altijd in deze volgorde. Verschil met cloud is dat cloud altijd meerdere server rond de wereld ter beschikking heeft in plaats van 1. 


3de klant heeft een private omgeving oplossing. Hier zijn 2 mogelijk klanten ter beschikking,
Callens EMK-bedrijf en Peter Siemen (Peter Siemen is net iets vriendelijker en makkelijker bereikbaar). 
Callens EMK is een productiebedrijf die bouwen werktuigmachines en die zitten in Waregem. Deze werken met grafische bestanden, planningen, werken ook met een office omgeving, outlook, file server en hebben een eigen ERP-software; Dynamics IX lokale infrastructuur en productie. 
Ze hebben alleen office 365 als SaaS al de rest is lokaal of is in eigen infrastructuur. 

Peter Siemen is een productiebedrijf voor industriële broedmachines, maar heeft eenzelfde scenario als Callens EMK. Ze zijn de enige in de branche en dus sterk groeiend in wat ze doen. 
Ze maken gebruik van RDP thin clients. 

Intern verantwoordelijk voor verschillende klanten
Peter Siemen flanders -> Filip Monbalieue
SLV -> Marco van der werf

Kijken verschillende oplossingen en toepassen op de verschillende bedrijven
Veel vragen stellen aan mensen en enquêtes 
Welke architectuur vandaag en hoe verbeteren t.o.v. vroeger.
Kijken extra is de huidige kosten/baten structuur en wat als we de verandering zouden toepassen. 
Kijken naar onderhoud nieuwe dingen zoals office 365.
En kijken binnen 5 jaar en GDPR-wetgeving. 
Interacties tussen verschillende SaaS omgevingen kan voor problemen zorgen en is niet altijd even makkelijk uit te werken. 
Als je geen lokale server hebt proberen zoveel mogelijk SaaSapplicaties te gebruiken. 
Alles naar office 365, voor crm teamleader-> opzoeken.
Zoeken naar oplossingen voor SaaS?
VERSCHILLEN PER KLANT HEEL BELANRIJKS
Zou er een oplossing voor 50-80% voor de bedrijven?
ALS JE De helft al kan zeggen standaard oplossingen. Niet alles op maat.


