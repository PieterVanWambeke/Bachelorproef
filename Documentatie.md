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


