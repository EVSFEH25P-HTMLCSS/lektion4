---
author: Lektion 4
date: MMMM dd, YYYY
paging: "%d / %d"
---

# Lektion 4

Hej och välkommen!

## Dagens agenda

1. Frågor och repetition
2. Introduktion till flexbox
3. Repetition av Git
4. Quiz frågor
5. Övning med handledning

---

# Fråga

När jag ska pusha mina nya ändringar, behöver jag alltid skriva "git push origin main" eller räcker det att skriva "git push"?

# Svar

Man kan skriva `git push -u origin main` för att spara "origin main". Därefter räcker det med  `git push`.

---

# Quiz frågor

1.  Vad gör `position: relative`?
2.  Vad gör `display: inline-block`?
3.  Vad gör `flex-direction`?
4.  Vad gör `justify-content: center`?
5.  Vilka två egenskaper kan kombineras för att centrera ett element helt?
6.  Vad gör `align-self`?
7.  Hur skiljer sig `gap` från `margin`?

---

# Svar quiz frågor

1. Elementet positioneras relativt till föräldern och kan flyttas genom `right, left, top, bottom` egenskaperna
2. Elementet tar upp nödvändigt utrymme och kan förstoras och förminskas genom `width, height` egenskaperna
3. Byter riktningen som flex-element renderas i (horisontellt eller vertikalt)
4. Centrerar element i en flex container på huvudaxeln
5. `justify-content` och `align-items`
6. Centrerar ett specifikt element på andra axeln
7. Margin appliceras per element, gap på container-elementet, och gap applicerar ej spacing i kanterna
