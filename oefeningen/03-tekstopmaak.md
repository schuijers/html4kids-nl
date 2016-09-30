# Oefening 3: tekst opmaken
Nu we onze webpagina opgedeeld hebben in paragrafen en voorzien hebben van kopjes is het tijd om de tekst verder op te maken. We kunnen een aantal woorden bijvoorbeeld vetgedrukt, schuingedrukt of gemarkeerd maken.

Laten we eens zien hoe we dat doen!

## De b en strong tags
We beginnen met het vetgedrukt maken van een paar woorden. Hiervoor kun je in HTML gebruik maken van twee verschillende tags: de `b` tag en de `strong` tag.

Waarom zijn er twee tags die hetzelfde doen? Het verschil zit hem in de betekenis van de tags.

De `b` tag komt van het Engelse woord *bold* wat *vet* betekent. De `b` tag betekent dus letterlijk: maak deze tekst vetgedrukt. 

De `strong` tag heeft een heel andere betekenis. Deze tag geeft namelijk alleen aan dat bepaalde tekst belangrijk is. Deze tag zegt dus eigenlijk niks over de opmaak van de tekst. Het vetgedukt maken van tekst binnen een `strong` tag is echter wel het standaardgedrag in de meeste browsers.

Tijd om de browser te vertellen welke woorden belangrijk zijn!

We beginnen met onze eigen naam. Voeg een `<strong>` tag toe voor je naam en een `</strong>` tag toe achter je naam:

<pre>
&lt;html&gt;
  &lt;head&gt;&lt;/head&gt;
  &lt;body&gt;
    &lt;h1&gt;Welkom op mijn webpagina!&lt;/h1&gt;
    &lt;p&gt;
      Wat leuk dat je een kijkje neemt op mijn webpagina.
    &lt;/p&gt;
    &lt;hr&gt;
    &lt;h2&gt;Even voorstellen&lt;/h2&gt;    
    &lt;p&gt;
      Hallo, ik ben <b>&lt;strong&gt;Martijn&lt;/strong&gt;</b>. Ik vind het leuk om HTML te leren en om te programmeren.
    &lt;/p&gt;
    &lt;p&gt;
      Mijn lievelingssport is voetbal en mijn lievelingsdier is een hond.
    &lt;/p&gt;
  &lt;/body&gt;
&lt;/html&gt;
</pre>

Als het goed gegaan is ziet het er ongeveer zo uit:

![Strong](https://raw.githubusercontent.com/schuijers/html4kids-nl/master/oplossingen/03a-opmaak-strong.png "Strong")

Nu vergeet tenminste niemand meer hoe je heet! :wink:

### Opdracht:
Maak zelf nog twee woorden die je belangrijk vindt vetgedrukt, bijvoorbeeld de naam van je lievelingssport of je lievelingsdier.

## De i en em tags
Nu we toch bezig zijn met de opmaak kunnen we ook net zo goed wat woorden schuingedrukt maken. Net als voor vetgedrukte tekst zijn er ook hier weer twee tags die je kan gebruiken: de `i` tag en de `em` tag.

Ook voor deze twee tags geldt dat het verschil zit in de betekenis van de tags.

De `i` tag komt van het Engelse woord *italic* wat *schuin* betekent. De `i` tag betekent dus letterlijk: maak deze tekst schuingedrukt. 

De `em` tag komt wat betekenis betreft meer in de buurt van de `strong` tag. Ook deze tag geeft eigenlijk alleen aan dat bepaalde tekst belangrijk is. In dit geval is het standaardgedrag van de meeste browsers echter anders dan bij de `strong` tag. Tekst binnen een `em` tag wordt standaard schuingedrukt weergegeven.

Laten we eens wat tekst schuingedrukt maken, bijvoorbeeld de dingen die je leuk vindt:

<pre>
&lt;html&gt;
  &lt;head&gt;&lt;/head&gt;
  &lt;body&gt;
    &lt;h1&gt;Welkom op mijn webpagina!&lt;/h1&gt;
    &lt;p&gt;
      Wat leuk dat je een kijkje neemt op mijn webpagina.
    &lt;/p&gt;
    &lt;hr&gt;
    &lt;h2&gt;Even voorstellen&lt;/h2&gt;    
    &lt;p&gt;
      Hallo, ik ben &lt;strong&gt;Martijn&lt;/strong&gt;. Ik vind het leuk om <b>&lt;em&gt;HTML te leren&lt;/em&gt;</b> en om te <b>&lt;em&gt;programmeren&lt;/em&gt;</b>.
    &lt;/p&gt;
    &lt;p&gt;
      Mijn lievelingssport is &lt;strong&gt;voetbal&lt;/strong&gt; en mijn lievelingsdier is een &lt;strong&gt;hond&lt;/strong&gt;.
    &lt;/p&gt;
  &lt;/body&gt;
&lt;/html&gt;
</pre>

Onze webpagina ziet er inmiddels ongeveer zo uit:
![Emphasis](https://raw.githubusercontent.com/schuijers/html4kids-nl/master/oplossingen/03b-opmaak-em.png "Emphasis")

Dat begint ergens op te lijken!

## Bonus: de mark tag
Naast het vetgedrukt of schuingedrukt maken van tekst is het ook mogelijk om bepaalde tekst te markeren. Net als met een markeerstift.

Hiervoor kan je de `mark` tag gebruiken. Deze tag zorgt ervoor dat tekst binnen de tag een gele achtergrondkleur krijgt.

### Opdracht:
Voeg een `mark` tag toe aan je webpagina, bijvoorbeeld om het woord 'webpagina' in de `h1` tag.