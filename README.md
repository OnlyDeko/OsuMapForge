# osu! MapForge

Map-Generator, Feinschliff und Trainer für osu!standard – von **OnlyDeko**
([osu!-Profil](https://osu.ppy.sh/users/12630135) · [GitHub](https://github.com/OnlyDeko)).

## Download (Beta)

**[Installer für Windows herunterladen](https://github.com/OnlyDeko/OsuMapForge/releases/latest)** (Windows 10/11, 64-bit)

MapForge braucht einen Beta-Lizenzschlüssel. Den gibt es auf Anfrage per osu!-Nachricht an [OnlyDeko](https://osu.ppy.sh/users/12630135). Beim ersten Start einfügen und aktivieren, danach läuft MapForge offline. Der KI-Modus braucht eine NVIDIA-Grafikkarte (GTX 16 / RTX 20 oder neuer), alles andere läuft auf jedem PC. Mehr dazu auf [osumapforge.com](https://osumapforge.com/#kaufen).

## Cloud-Modus (experimentell)

Keine NVIDIA-Grafikkarte? Mit dem Notebook läuft die KI (Mapperatorinator) auf einer kostenlosen Google-GPU:

[![In Colab öffnen](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/OnlyDeko/OsuMapForge/blob/main/colab/MapForge_Colab.ipynb)

1. In Colab: **Laufzeit → Laufzeittyp ändern → T4-GPU**.
2. Zellen der Reihe nach ausführen. In Zelle 3 die Einstellungen einfügen – der Knopf
   „Ohne NVIDIA-Karte: Cloud (Google Colab) …“ im MapForge-Generator kopiert sie in die Zwischenablage.
3. Die fertige `.osu` in MapForge im Feinschliff mit **„+ Stufe / .osz …“** dazunehmen (gleiche Audiodatei).

> Hinweis: Laut den osu!-Ranking-Kriterien dürfen mit KI erstellte Maps nicht ranked werden.

## Danksagung

KI: [Mapperatorinator](https://github.com/OliBomby/Mapperatorinator) von OliBomby (MIT-Lizenz).
osu! ist eine Marke von ppy Pty Ltd. Dieses Projekt ist nicht offiziell mit osu! verbunden.
