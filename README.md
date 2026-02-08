# VentPro Elite v2.0 🛠️

VentPro Elite är ett specialverktyg utvecklat för ventilationsmontörer. Appen automatiserar beräkningar av kapmått för rör och kanaler vid offset-montage (S-mått) och håller ordning på beställningar direkt i mobilen.

## 🚀 Funktioner

- **Dual-Mode Kalkylator:** Växla blixtsnabbt mellan Rund (Ø) och Rektangulär (r) kanal.
- **Avancerad S-beräkning:** Hanterar förskjutningar i både sidled och höjd samtidigt.
- **Smart Kapmått (L):** Räknar ut det exakta måttet mellan sickarna efter avdrag för böjar ($90°, 60°, 45°, 30°, 15°$).
- **Varningssystem:** Indikerar visuellt om avståndet är för kort för att monteras.
- **Beställningslista:** Färgkodade snabbval för böjar, rör, montage och isolering.
- **SMS-Integration:** Kopiera hela din plocklista med en knapptryckning för smidig beställning till lager/inköpare.
- **Historik:** Sparar dina 5 senaste beräkningar lokalt i mobilen.

## 📐 Matematiken bakom

Appen använder trigonometriska funktioner för att beräkna hypotenusan och drar sedan bort böjarnas byggmått baserat på vinkel och dimension:

- **Rund:** Avdraget $a$ beräknas som $a = \tan(v/2) \cdot d$
- **Rekt:** Avdraget $a$ beräknas som $a = r \cdot \tan(v/2)$

---
*Utvecklad av ventilationsmontörer, för ventilationsmontörer.*
