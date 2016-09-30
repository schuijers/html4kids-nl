# Oefening 2: structuur aanbrengen

Nu je weet wat tags zijn is het tijd om er een paar toe te voegen aan onze webpagina :simple_smile:

In deze oefening beginnen we met een aantal tags waarmee je structuur aan kan brengen aan je webpagina. Wat is structuur? Denk maar eens aan een boek. Een boek bestaat uit meerdere hoofdstukken die meestal beginnen met een vetgedrukte *kop* gevolgd door één of meerdere *paragrafen*.

Laten we beginnen!

## Heading tags
Als eerste gaan we een vetgedrukte kop aan onze webpagina toevoegen. Dit doen we met een zogenaamde *heading* tag (heading is Engels voor kop). Er zijn zes verschillende heading tags die je kan gebruiken in een webpagina: `h1` t/m `h6`:

><h1>Dit is een &lt;h1&gt; tag</h1>
><h2>Dit is een &lt;h2&gt; tag</h2>
><h3>Dit is een &lt;h3&gt; tag</h3>
><h4>Dit is een &lt;h4&gt; tag</h4>
><h5>Dit is een &lt;h5&gt; tag</h5>
><h6>Dit is een &lt;h6&gt; tag</h6>

Zoals je ziet wordt de tekst bij elke volgende tag kleiner. Dit komt doordat de `h1` tag de belangrijkste heading tag is en de `h6` tag de minst belangrijke.

Maar genoeg gekletst. Laten we een paar heading tags toevoegen aan onze webpagina!

We beginnen met een `h1` tag. Voeg deze toe binnen de `body` tag, boven de huidige tekst:

<pre>
&lt;html&gt;
  &lt;head&gt;&lt;/head&gt;
  &lt;body&gt;
    <b>&lt;h1&gt;Welkom op mijn webpagina!&lt;/h1&gt;</b>
    Hallo, ik ben Martijn
  &lt;/body&gt;
&lt;/html&gt;
</pre>

Als je het bestand nu in je browser opent, dan zie je als het goed is gegaan zoiets als dit:

![Headings](https://raw.githubusercontent.com/schuijers/html4kids-nl/master/oplossingen/02a-structuur-headings.png "Headings")

Is het gelukt? Ja? Goed gedaan! :muscle:

### Opdracht:
Voeg zelf een `h2` tag toe net onder de `h1` tag. Bijvoorbeeld met als tekst: *Even voorstellen*.

## De p(aragraph) tag
Nu we een aantal heading tags hebben toegevoegd is het tijd om wat meer tekst toe te voegen aan onze webpagina. Om de tekst leesbaar te houden is het een goed idee om deze in te delen in paragrafen. Paragrafen zijn stukjes bij elkaar horende tekst met wat ruimte ertussen.

Voor paragrafen bestaat er een aparte tag: de `p` tag. We gaan twee paragrafen toevoegen aan onze webpagina.

Allereerst gaan we een paragraaf toevoegen tussen de `h1` en `h2` tags:

<pre>
&lt;html&gt;
  &lt;head&gt;&lt;/head&gt;
  &lt;body&gt;
    &lt;h1&gt;Welkom op mijn webpagina!&lt;/h1&gt;
    <b>&lt;p&gt;
      Wat leuk dat je een kijkje neemt op mijn webpagina.
    &lt;/p&gt;</b>
    &lt;h2&gt;Even voorstellen&lt;/h2&gt;    
    Hallo, ik ben Martijn
  &lt;/body&gt;
&lt;/html&gt;
</pre>

Als tweede maken we van de tekst onder de `h2` tag ook een paragraaf. Als je wilt kan je hier nog wat meer tekst toevoegen. Bijvoorbeeld:

<pre>
&lt;html&gt;
  &lt;head&gt;&lt;/head&gt;
  &lt;body&gt;
    &lt;h1&gt;Welkom op mijn webpagina!&lt;/h1&gt;
    &lt;p&gt;
      Wat leuk dat je een kijkje neemt op mijn webpagina.
    &lt;/p&gt;
    &lt;h2&gt;Even voorstellen&lt;/h2&gt;    
    <b>&lt;p&gt;
      Hallo, ik ben Martijn. Ik vind het leuk om HTML te leren en om te programmeren.
    &lt;/p&gt;</b>
  &lt;/body&gt;
&lt;/html&gt;
</pre>

Als je het goed gedaan hebt ziet het er nu ongeveer zo uit:

![Paragraphs](https://raw.githubusercontent.com/schuijers/html4kids-nl/master/oplossingen/02b-structuur-paragraphs.png "Paragraphs")

### Opdracht:
Voeg zelf nog een tweede `p` tag toe net onder de `h2` tag. Beschrijf hierin bijvoorbeeld wat je lievelingsdier of lievelingssport is.

> **Veiligheid op het internet**<br>
> Omdat je natuurlijk nooit weet wie er je webpagina bekijkt, moet je je altijd afvragen wat je wilt delen met
> een onbekende.<br>
> Het delen van telefoonnummers, adressen of de school waarop je zit is meestal geen goed idee!

## Bonus: de hr tag
Om nog duidelijker aan te kunnen geven welke tekst bij elkaar hoort kan je naast heading tags en paragraph tags ook gebruik maken van een tag die ervoor zorgt dat er een horizontale lijn verschijnt. Dit is de `hr` tag.

De `hr` tag is één van de weinig tags waarbij je geen eindtag hoeft te gebruiken. Dit komt doordat je geen andere tags binnen een `hr` tag kan plaatsen.

### Opdracht:
Voeg een `hr` tag toe net boven de `h2` tag.

<br>
Ben je klaar? Ga dan verder met de volgende oefening: [tekst opmaken](03-tekstopmaak.md).
