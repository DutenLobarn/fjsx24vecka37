Tisdag 10/9: Workshop - Responsiv design och CSS Media Queries

Mål för dagen:
Lära sig grunderna i responsiv design och varför det är viktigt.
Förstå hur man använder CSS Media Queries för att anpassa webbplatser för olika enheter (mobil, surfplatta, desktop).

Innehåll (code along):
Genomgång av responsiv design och mobilanpassning.
Introduktion till CSS Media Queries och hur man ändrar layouten baserat på skärmstorlek.

Praktiska övningar:
Skapa en webbsida som använder media queries för att ändra layout beroende på skärmens bredd.
Övning: Sidan ska visa tre kolumner på stora skärmar och en kolumn på mobiler.

Avancerad Övning: "Interaktiv sektion och ytterligare media queries"
Mål:
Skapa en interaktiv sektion på sidan med fler stilar och media queries.
Lär dig hur man skapar responsiva bilder och text som ändrar storlek beroende på skärmens bredd.
Införa en responsiv navigation utan att använda Flexbox eller Grid.
Uppgifter:
Lägg till en bildsektion:

Skapa en sektion där en bild visas. Bilden ska vara responsiv och ändra storlek baserat på skärmens bredd.
Skriv ut en text som beskriver bilden. På mobila enheter ska texten ligga ovanför bilden, men på större skärmar ska texten vara bredvid bilden.
Gör textstorleken responsiv:

Gör så att texten i header och main ändrar storlek baserat på skärmens bredd.
Använd olika font-size för olika skärmstorlekar (exempelvis större rubriker på desktop och mindre på mobiler).
Inför en enkel navigation:

Lägg till några länkar i header för att skapa en navigation (utan dropdown-menyer).
På mobila enheter ska navigationslänkarna visas som block (en länk per rad), men på större skärmar ska de ligga i rad (horisontellt).


Mer avancerade övningar: Responsiv design med animationer och pseudo-klasser
Övning 1: Använd pseudo-klasser och animationer
Mål: Skapa en interaktiv knapp med hover-effekter, övergångar (transitions) och animationer som är anpassade för olika enheter.
Uppgifter:
Skapa en knapp i din navigation eller sektion med texten "Läs mer".
Använd pseudo-klassen :hover för att ändra färg och storlek på knappen när användaren håller musen över den.
På mobila enheter ska knappen ha ett mindre font-size och inga överdrivna animationer (för att spara prestanda).
Använd transition för att göra förändringarna smidiga (t.ex. ändra bakgrundsfärg och textstorlek över 0.3 sekunder).

Övning 2: Skapa responsiva bilder med olika upplösningar
Mål: Använd picture-elementet för att leverera olika bildfiler beroende på skärmupplösning.
Uppgifter:
Skapa en sektion där du använder picture-elementet för att visa olika bilder beroende på skärmupplösningen.
På mobiler ska en lågupplöst version av bilden visas (för att spara bandbredd).
På större skärmar ska en högupplöst version av bilden laddas in.

Övning 3: Media Queries och mörkt läge (Dark Mode)
Mål: Använd en media query för att detektera om användaren har valt mörkt läge på sin enhet och anpassa stilarna därefter.
Uppgifter:
Använd media queryn prefers-color-scheme för att skapa en design som ändras om användaren har mörkt läge aktiverat.
Ändra bakgrundsfärg, textfärg och knappstilar när enheten är inställd på mörkt läge.

Övning 4: Skapa ett responsivt modalt fönster
Mål: Skapa ett modalt fönster (popup) som kan öppnas och stängas via en knapp och som är anpassat för olika skärmstorlekar.
Uppgifter:
Skapa en knapp med texten "Visa mer" som, när den klickas, öppnar ett modalt fönster.
I det modala fönstret ska det finnas text och en stäng-knapp.
Anpassa designen för mobila enheter så att det modala fönstret täcker större delen av skärmen och centreras på större skärmar.

Övning 5: Skapa ett responsivt galleri
Mål: Skapa ett enkelt bildgalleri som anpassar antalet synliga bilder baserat på skärmstorlek utan att använda Grid eller Flexbox.
Uppgifter:
På mobila enheter ska endast en bild per rad visas, på surfplattor två bilder per rad och på desktop tre eller fler bilder.
Använd bara media queries för att justera bildstorleken och hur de visas.

Lycka till!
