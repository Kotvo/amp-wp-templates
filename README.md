# AMP-Vorlagen für Wanna Play

Eigene Vorlagen für AMP (CubeCoders) für Spiele, die AMP nicht selbst
mitbringt. Die Website legt Server daraus mit einem Klick an
(Verwaltung → Gameserver → „＋ Turnier-Server erstellen“) und richtet sie
selbst ein.

| Spiel | Dateien |
| --- | --- |
| Trackmania Nations Forever | `tmnf.kvp`, `tmnf*.json` |

Teeworlds steht nicht hier: AMP bringt eine eigene Vorlage mit, und die
Website kommt damit zurecht.

## In AMP eintragen

1. In AMP: **Configuration → Instance Deployment → Deployment Sources**
2. `Kotvo/amp-wp-templates:main` hinzufügen, **Fetch Latest** drücken.
3. Danach erscheint „Trackmania Nations Forever“ auf der Website unter
   „＋ Turnier-Server erstellen“.

Ports: 2350 und 3450 (TCP + UDP) für alle, 5000 (TCP) nur für die Website.
Der Server-Login (Dedicated-Server-Konto) kommt von
http://official.trackmania.com/tmf-playerpage.

Die Quelle der Vorlagen liegt im Repository der Website unter `tools/amp-tmnf/`.
Änderungen dort machen und hierher kopieren.
