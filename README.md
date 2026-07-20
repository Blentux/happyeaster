# Easter Eco-Runner (Three.js Voxel Game Concept)

Dieses Projekt ist ein interaktiver Prototyp im Voxel-Look, der einen pädagogischen Ansatz beinhaltet. Die Idee entstand rund um das Thema Ostern und Umweltschutz.

# Das Spielkonzept (Vision)
Der Spieler steuert den Osterhasen durch verschiedene Level (Gärten), um Ostereier zu sammeln. Gleichzeitig muss herumliegender Müll aufgesammelt werden, um die Umwelt zu entlasten. 

* **Pädagogischer Ansatz:** Je weiter der Spieler fortschreitet, desto sauberer und blühender werden die Gärten. Das Spiel schafft so Awareness für Umweltschutz.
* **Belohnungssystem:** Mit den gesammelten Ostereiern können im In-Game-Shop kosmetische Gegenstände und Hasen-Skins freigeschaltet werden.
* **Zukunftsvision:** Langfristig ist ein Online-Modus vorstellbar, um gemeinsam mit Freunden zu spielen.

# Tech-Stack & Implementierung
* **Core:** HTML5, CSS3, Vanilla JavaScript
* **3D-Engine:** Three.js (`WebGLRenderer`)
* **Art-Style:** 3D-Voxel-Modelle

# Technische Highlights & Herausforderungen
Da es sich um ein Voxel-basiertes Projekt handelt, lag der Fokus stark auf der Performance-Optimierung:
* **Kollisionsabfrage:** Implementierung einer Collision Detection, um das Einsammeln von Items sowie die Levelgrenzen zu steuern.
* **Asset-Größe:** Durch den Voxel-Look sind die `.glb`-Dateien extrem klein, was zu minimalen Ladezeiten führt.
