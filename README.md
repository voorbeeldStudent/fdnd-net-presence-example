# Visitekaartje van Jane
Mijn aantekeningen bij de talk over het visitekaartje en antwoord op de vragen (bij [Features](#features))

## Description
Hieronder ziet u een screenshot van het visitekaartje van Jane. Dit voorbeeld is tijdens een talk getoond.

![Visitekaartje](./docs/VisitekaartjeChrome.png "Visitekaartje")

In dit bestand geef ik antwoord op de vragen die tijdens de talk gesteld en klassikaal besproken zijn.

## Table of Contents

- [Visitekaartje van Jane](#visitekaartje-van-jane)
  * [Description](#description)
  * [Features](#features)

## Features

1. Kijk naar de kleur, typografie en beeldgebruik.

Wat mij opvalt is dat Jane blauwtinten gebruikt in haar kaartje. Blauw wordt gekoppeld met competentie, kwaliteit, kalmte, wijsheid, productiviteit, vertrouwen en veiligheid. Blauw is ook een mannelijke kleur, misschien dat Jane dit expres gekozen heeft omdat de Frontend wereld best mannelijk gericht is. De felle kleur aan de onderkant wordt ook wel gekoppeld met frisheid of energie.

In de afbeelding zit Jane achter haar laptop, ik denk dat ze het beeld probeert te geven dat ze heel serieus is. Ze heeft haar makeup netjes gedaan en er zitten github stickers op haar laptop (die zie je alleen als je het plaatje even apart opent). Naast de afbeelding zijn er ook unicode icoontjes van een beker gebruikt, de beker staat voor winnen en ik denk dat ze de aandacht wil trekken om te laten zien dat ze goed is in bepaalde dingen. De bekers geven haar niveau van HTML, CSS en Javascript aan, ze laat zich dus echt zien als frontender.

2. Bekijk de HTML met de Chrome Devtools Element Tab.

Om het visitekaartje heen staat een `<article>` element, dit element is bedoeld om een onafhankelijk onderdeel van een pagina in op te maken. Haar naam, 'Jane Doe', staat in een `<h1>` element in een `<header>` element, dit geeft aan dat dit de koptekst van een artikel is.
 
3. Bekijk de CSS met de Chrome Devtools Element Tab.

Afgeronde hoekjes kan je maken met behulp van `border-radius`, je geeft een waarde mee voor de grootte van de afronding. 

Schaduw kan je maken met behulp van`box-shadow` maar die vind ik nog best ingewikkeld omdat er erg veel dingen meegegeven moeten worden, CSS-tricks zegt: `box-shadow: [horizontal offset] [vertical offset] [blur radius] [optional spread radius] [color];`. Hier moet ik nog vaker naar kijken voor ik het snap.

Een kleurverloop heet in het engels een gradient en in CSS kan je met `background: linear-gradient();` een gradient instellen. Je stelt de richting en een paar kleuren in: `linear-gradient(0deg, rgba(0,239,255,1) 40%, #4e54c8 100%)`.

4. Bekijk de Javascript door het bestand in Github te openen en zoek de betekenis op van onderstaande termen:

Volgens de website van MDN is `document` een interface die een ingang biedt naar de inhoud van een webpagina die is opgebouwd in de DOM tree.

`querySelector` is een methode van `document` waarmee een HTML element opgezocht kan worden.

In javascript wordt een `function` gebruikt om met een eigen verzonnen woord meerdere regels code uitvoeren.

Een `const` is een constante, een waarde die vast staat en niet veranderd kan worden.

Elk HTML element heeft een `classList` waarin alles CSS classes staan.
