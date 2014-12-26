# coding rules

* gebruik enkelvoudige zelfstandige naamwoorden of naamwoordzinnen als namen voor klassen. gebruik Pascal casing voor hun spelling.
* een klasse documentatie commentaar begint met een opsomming van alle eigenschappen van de klasse zelf. Met ook de eigenschappen van individuele objecten van de klasse.
* vermeld minstens een versienummer en auteur in de klasse documentatie commentaar.
* gebruik werkwoorden of werkwoordzinnen als namen voor methodes. Gebruik camelCase voor hun spelling.
* kies methodenamen zodanig dat hun oproepen lezen als een bevel of een vraag.
* begin een klasse met de definitie van al zijn constructoren
* groepeer alle elementen van een klasse die bij een enkele eigenschap horen. begin met publieke elementen, sluit af met private. Binnen een groep met dezelfde toegangsrechten krijgen inspectoren voorrang op mutatoren.
* introduceer een getter en een setter voor elk enkelwaardig veranderbaar object, introduceer enkel een getter voor elk enkelwaardig onveranderbaar object.
* Inspectoren veranderen nooit de observeerbare staat van een object.
* Mutatoren geven nooit een resultaat terug.
* Verkies instantiemethoden boven klassemethoden.
* Gebruik statische methodes als er alleen primitieve waardes bij betrokken zijn.
* Gebruik klassemethonden als hun gedrag het zelfde moet zijn voor alle objecten van de klasse. Gebruik klassemethoden om klassevariabelen te wijzigen.
* Gebruik enkelvoudige zelstandige naamwoorden of naamwoordzinnen als formele argumenten voor een methode, gebruik camelCase om ze te schrijven.
* Begin de documentatie van een methode met een korte beschrijving (1 zin) van wat hij doet.
* Gebruik de @param tag om bij de documentatie van een methode voor elke formele parameter aan te geven wat hij doet.
* Introduceer basisinspectoren om de huidige waarde van elke eigenschap van een klasse en zijn objecten te inspecteren. Voeg de annotatie @basic toe aan hun definitie.
* voeg de annotatie @immutable toe aan inspectoren waarvan de waarde niet veranderd gedurende de loop van het programma.
* Specifieer het resultaat van afgeleide inspectoren in een of meerdere zinnen voorafgegaan door de tag @return.
* Handel alle speciale gevallen af in de definitie van een methode. 
* Specifieer veranderingen aan de staat van objecten of klassen die worden veroorzaakt voorafgegaan door de tag @post.
* als een mutator hetzelfde effect heeft als een combinatie van andere mutatoren schrijf dat dan met de annotatie @effect.
* roep klassemethode op op hun klasse, niet op een object van de klasse.

