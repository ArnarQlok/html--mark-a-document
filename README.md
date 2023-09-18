# Årlig Tech Hackathon 2023 - HTML Övning

## Instruktioner

I den här övningen kommer du att skapa en enkel händelsesida för den årliga Tech Hackathon 2023. Du kommer att använda texten från `events.txt`-filen som innehåller evenemangets namn, datum, tid, plats, beskrivning och en lista över talare. Du kommer att behöva strukturera HTML-dokumentet med hjälp av lämpliga taggar.

1. Skapa filen `index.html` i din editor (t.ex. Visual Studio Code).
2. Börja med den grundläggande HTML-mallen.
3. Infoga texten från `eventlista.txt`-filen inuti body-taggen och strukturera HTML-dokumentet genom att märka upp varje del med lämplig HTML-tagg.
4. Utför en peer review med en klasskamrat för att kontrollera det uppmärkta dokumentet.
5. Validera även HTML-dokumentet på https://validator.w3.org/. Var resultatet felfritt, eller avslöjade det andra fel/varningar?

## Diskussionsfrågor

1. Visas HTML-dokumentet i webbläsaren som det är tänkt? Är syntaxen korrekt?
2. Ange vad som definieras som start- och sluttagg, attribut, nästlande element.
3. Ange vilka element som är block- vs. inline-element. Vad är skillnaden?
4. Diskutera vad som är HTML:s roll inom webbutveckling?
5. Vad innebär det att validera ett HTML-dokument?

## Rekommenderade taggar för detta dokument

```html
<h1> - <h4>             Rubriker och underrubriker
<p>                     Textstycke
<strong>                Stark betonad text (fetstil)
<em>                    Viktig text (kursiv) 
<ul>
     <li></li>
     <li></li>
</ul>                   Oordnad lista
<ol> 
   <li></li>
   <li></li>
<ol>                    Ordnad lista

<a href="#">Länk</a>    Länk där adressen skrivs i #
<img src="bild.jpg" alt="Bildbeskrivning för tillgänglighet, SEO">  Bild
