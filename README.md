# Bootstrap Portfolio Projekt

##  Beskrivning
Detta projekt är en responsiv portfolio-webbplats skapad med HTML, Bootstrap och Sass (SCSS).  
Syftet är att demonstrera hur moderna verktyg och ramverk kan användas för att effektivisera webbutveckling.

---

##  Tekniker som används
- HTML5
- Bootstrap 5 (CSS-ramverk)
- Sass (SCSS preprocessor)
- Git & GitHub (versionshantering)

---

##  Responsiv design
Webbplatsen använder Bootstrap grid-system för att skapa en layout som anpassar sig efter skärmstorlek:

- Mobil: 1 kolumn  
- Surfplatta: 2 kolumner  
- Desktop: 3 kolumner  

---

##  Bootstrap-komponenter
Följande komponenter används:
- Navbar
- Cards
- Buttons

Dessa komponenter gör det möjligt att snabbt bygga en modern och användarvänlig design.

---

##  Sass (SCSS)
Projektet använder Sass för att förbättra strukturen och återanvändbarheten i CSS.

### Funktioner som används:
- Variabler (färger och typsnitt)
- Nesting (nästlad kodstruktur)
- Mixins (återanvändbar styling)

Exempel:
```scss
$primary-color: #0d6efd;

@mixin hover-effect {
  transform: scale(1.05);
}