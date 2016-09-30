# Oefening 1: hallo HTML!

Welkom bij de html4kids cursus. Leuk dat je meedoet! :smiley:

In deze oefening gaan we onze allereerste HTML-pagina (ook wel webpagina genoemd) maken. Wat hebben we hiervoor nodig?

1. Een (simpele) tekstverwerker om de pagina te maken. Bijvoorbeeld Kladblok/Notepad (Windows) of TextEdit (OSX).
2. Een webbrowser om het resultaat te bekijken. Bijvoorbeeld Chrome, Firefox of Internet Explorer. 

Dat is alles. Ben je klaar om te beginnen? Mooi. Daar gaan we!

## Hallo HTML!
Start de tekstverwerker en begin met een leeg bestand. Kopieer nu de volgende tekst in het bestand:

```
<html>
  <head></head>
  <body>
    Hallo HTML!
  </body>
</html>
```

Sla het bestand op, bijvoorbeeld als `hallo.html`, en onthoud de locatie. Open het bestand vervolgens met je webbrowser.

Als het goed is zie je nu zoiets als dit:

![Hallo HTML](https://raw.githubusercontent.com/schuijers/html4kids-nl/master/oplossingen/01-hallo-html.png "Hallo HTML!")

Gelukt? High five! :raised_hand:

Het werkt wel, maar waarom? Zoals je misschien al opgevallen was staan er allerlei rare woorden en tekens in ons tekstbestand zoals `<html>`, `<head>` en `</body>`. Deze woorden zie je niet terug als je de webpagina in de browser bekijken. Zijn ze wel nodig? 

## Tags
Het antwoord is: ja. De woorden die tussen `<` en `>` tekens staan worden *tags* genoemd. Dit is Engels voor *markeringen*. Met deze woorden vertellen we de browser hoe deze met de inhoud van ons tekstbestand om moet gaan.

Voor onze eerste webpagina hebben we de volgende tags gebruikt:
* `<html>` en `</html>`: hiermee vertel je de browser waar de webpagina begint en eindigt;
* `<head>` en `</head>`: hiermee vertel je de browser waar de zogenaamde *metadata* van de webpagina begint en eindigt (hier komen we later nog op terug); 
* `<body>` en `</body>`: hiermee vertel je de browser waar de daadwerkelijke (veelal zichtbare) inhoud van de webpagina begint en eindigt.

Dit zijn de enige verplichte tags die in elke webpagina aanwezig moeten zijn.
Verder bestaan er bijvoorbeeld ook tags om aan te geven of iets een paragraaf is, of iets vetgedrukt moet worden, etc. Een aantal voorbeelden van deze tags komen we in het vervolg van deze cursus nog tegen.

Tags worden meestal in paren gebruikt bestaand uit een starttag (bijvoorbeeld `<html>`) en een eindtag (bijvoorbeeld `</html>`). Een eindtag herken je aan de `/` na de `<`. Tags kunnen ook *genest* worden. Dit betekent dat je binnen een paar van start- en eindtags ook weer andere tags kan gebruiken.

In ons tekstbestand zie je bijvoorbeeld dat de start- en eindtags van `head` en `body` binnen de start- en eindtags van `html` staan:

<pre>
<b>&lt;html&gt;</b>
  &lt;head&gt;&lt;/head&gt;
  &lt;body&gt;
    Hallo HTML!
  &lt;/body&gt;
<b>&lt;/html&gt;</b>
</pre>

In principe is er geen limiet aan hoe vaak je tags binnen andere tags kan nesten. Het is alleen wel belangrijk dat je de start- en eindtags in de juiste volgorde zet. Zo moet de laatst toegevoegde starttag altijd weer als eerste afgesloten worden met een eindtag. Anders snapt de browser er niks meer van.

Goed. Genoeg gekletst over tags. Tijd voor actie! 

## Opdracht
* Vervang de tekst *'Hallo HTML!'* door bijvoorbeeld *'Hallo, ik ben [je naam]'* en kijk wat er gebeurd.

Ben je klaar? Ga dan verder met de volgende oefening.