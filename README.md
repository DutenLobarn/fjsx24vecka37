Onsdag 11/9: Workshop - Semantisk HTML, CSS


Praktiska övningar:
Omvandla en befintlig HTML-sida till en mer semantisk struktur genom att använda rätt element.
Lägg till grundläggande CSS för att förbättra layouten (t.ex. centrera innehållet, ändra avstånd, typsnittsstyling).


Utgångspunkt:
HTML-kod utan semantiska element:
html
Kopiera kod
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>My Webpage</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      margin: 0;
      padding: 0;
      background-color: #f4f4f4;
    }

    div {
      padding: 20px;
      margin: 10px;
    }

    .header {
      background-color: #333;
      color: white;
      text-align: center;
    }

    .content {
      background-color: white;
    }

    .footer {
      background-color: #333;
      color: white;
      text-align: center;
    }
  </style>
</head>
<body>

  <div class="header">
    <h1>Welcome to My Webpage</h1>
    <p>Home | About | Contact</p>
  </div>

  <div class="content">
    <h2>About Me</h2>
    <p>This is some information about me. I am a web developer who loves creating websites.</p>
  </div>

  <div class="footer">
    <p>Footer information goes here</p>
  </div>

</body>
</html>

Studenternas uppgift:
Omvandla strukturen till en semantisk HTML-struktur genom att byta ut <div>-taggar mot mer meningsfulla element som <header>, <nav>, <section>, och <footer>.
Lägg till CSS för att centrera innehållet, förbättra layouten, och ändra typsnittsstyling.