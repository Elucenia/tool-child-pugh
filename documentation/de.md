<!-- ELUCENIA technical documentation · child-pugh · de · no clinical/professional/rights approval -->

# Child-Pugh

[Bedingungen, Quellen und Berechtigungen](https://elucenia.org/de/werkzeuge/child-pugh)

## Verwendung

Verwenden Sie das Werkzeug im Portal oder öffnen Sie index.html über einen lokalen HTTP-Server. Wählen Sie die Sprache, füllen Sie die Felder aus und berechnen Sie das Ergebnis.

## Eingaben und Einheiten

### Gesamtbilirubin

`bili`

- `1` — \< 2 mg/dL
- `2` — 2 bis 3 mg/dL
- `3` — \> 3 mg/dL

### Albumin

`alb`

- `1` — \> 3,5 g/dL
- `2` — 2,8 bis 3,5 g/dL
- `3` — \< 2,8 g/dL

### INR

`inr`

- `1` — \< 1,7
- `2` — 1,7 bis 2,3
- `3` — \> 2,3

### Aszites

`ascite`

- `1` — Nicht vorhanden
- `2` — Leicht oder mit Diuretikum kontrolliert
- `3` — Mäßig bis schwer oder refraktär

### Hepatische Enzephalopathie

`ence`

- `1` — Nicht vorhanden
- `2` — Grade I–II (oder kontrolliert)
- `3` — Grade III–IV (oder refraktär)

## Fassung der Methode

Child–Pugh/Pugh 1973: 5 Items 1–3, Klassen A 5–6/B 7–9/C 10–15

## Dokumentierte Formel

Jedes der 5 Items zählt 1–3 Punkte. Gesamt 5–15.

Klasse A: 5–6 · Klasse B: 7–9 · Klasse C: 10–15.

## Grenzen und Population

Child–Pugh beschreibt Schweregrad und Prognose der Leberzirrhose anhand der klinischen Beurteilung von Aszites und Enzephalopathie sowie Laborwerten. Diese beiden Komponenten hängen vom klinischen Urteil und der erhaltenen Behandlung ab; dokumentieren Sie den beurteilten Zustand. In dieser Oberfläche wird die Gerinnung anhand der INR und nicht anhand der Verlängerung der Prothrombinzeit in Sekunden erfasst. Die Mortalitätsangaben von Mansour 1997 beziehen sich auf jene Zirrhosekohorte mit elektiver oder notfallmäßiger Bauchoperation und sind keine automatischen individuellen Vorhersagen. Der Score ersetzt weder die Ursachenklärung der Lebererkrankung noch eine spezifische Regel zur Medikamentendosierung.

## Referenzen

- [Pugh RN et al. Transection of the oesophagus for bleeding oesophageal varices. Br J Surg, 1973.](https://doi.org/10.1002/bjs.1800600817)

- [Mansour A et al. Abdominal operations in patients with cirrhosis: still a major surgical challenge. Surgery, 1997.](https://doi.org/10.1016/S0039-6060(97)90080-5)

- [Durand F, Valla D. Assessment of the prognosis of cirrhosis: Child-Pugh versus MELD. J Hepatol, 2005.](https://doi.org/10.1016/j.jhep.2004.11.015)

- [Durand/Valla2005](https://www.journal-of-hepatology.eu/article/S0168-8278%2804%2900533-1/fulltext)

## Technische Tests reproduzieren

Führen Sie node test.cjs im Stammverzeichnis dieses Repositorys aus, um die dokumentierten synthetischen Fälle zu wiederholen. Ursprüngliche Eingaben, erwartete Ergebnisse und Toleranzen bleiben erhalten. Technische Tests stellen keine klinische Validierung dar.

```sh
node test.cjs
```

tool.json enthält Quellen, Ausgabe und Umfang der Überprüfung. examples.json bewahrt die synthetischen Eingaben und erwarteten Ergebnisse; results.json dokumentiert die tatsächlich erhaltenen Ergebnisse.

[Eintrag und Referenzen](../tool.json) · [JavaScript-Code](../calculator.js) · [Referenzfälle](../examples.json) · [results.json](../results.json)

## Überprüfung und Nutzungsbedingungen

Eine unabhängige klinische Prüfung wurde nicht durchgeführt.

Diese Benutzeroberfläche ist eine selbst erstellte Übersetzung und keine offizielle oder zertifizierte Ausgabe. Eine unabhängige klinische Überprüfung, eine professionelle sprachliche Prüfung und eine Klärung der Rechte an den Instrumenten wurden nicht durchgeführt.

Ergebnis der Formel oder Klassifikation. Interpretation, Vorgehen und Anwendbarkeit hängen von der fachlichen Beurteilung und der ausgewählten Quelle ab.

## Lizenz und Urheberangaben

Apache-2.0 gilt nur für den ELUCENIA-Code. Die Rechte an Instrumenten, Veröffentlichungen, Übersetzungen und Daten verbleiben bei den jeweiligen Rechteinhabern. Bewahren Sie LICENSE und NOTICE auf.

ELUCENIA · Felipe Guedes · Copyright © 2026
