# Das wandernde Labyrinth

Ein atmosphärisches First-Person-Gedächtnis-Labyrinth im Browser.

1. **Einprägen** – Draufsicht mit Start (Pfeil = Blickrichtung), Ausgang und leuchtenden Kristallen; Countdown.
2. **Karte verschwindet** – keine Minimap, nur noch die Ich-Perspektive.
3. **Erinnern & Anpassen** – Wände öffnen und schließen sich in festen Intervallen (spürbar am Grollen), der Ausgang bleibt immer erreichbar.

**Starten:** `index.html` im Browser öffnen (keine Installation, Three.js liegt in `vendor/`).
Steuerung: WASD/Pfeiltasten, Maus, Shift rennen, Q/E drehen, Esc Pause. Touch: links Joystick, rechts umsehen.

| Level | Größe | Einprägen | Veränderung alle | Kristalle |
|---|---|---|---|---|
| 1 | 6×6 | 10 s | 45 s | 5 |
| 5 | 10×10 | 7 s | 28 s | 3 |
| 10 | 15×15 | 4 s | 18 s (4 Wände) | 0 |

Mit jedem Level außerdem: mehr Kreuzungen/Schleifen, weniger lange Geraden, schwächere Bereichsfarben, dichterer Nebel, weniger Licht.
