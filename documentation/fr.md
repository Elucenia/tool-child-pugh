<!-- ELUCENIA technical documentation · child-pugh · fr · no clinical/professional/rights approval -->

# Child-Pugh

[conditions, sources et autorisations](https://elucenia.org/fr/outils/child-pugh)

## Mode d’emploi

Utilisez l’outil sur le portail ou ouvrez index.html via un serveur HTTP local. Sélectionnez la langue, remplissez les champs et lancez le calcul.

## Données d’entrée et unités

### Bilirubine totale

`bili`

- `1` — \< 2 mg/dL
- `2` — 2 à 3 mg/dL
- `3` — \> 3 mg/dL

### Albumine

`alb`

- `1` — \> 3,5 g/dL
- `2` — 2,8 à 3,5 g/dL
- `3` — \< 2,8 g/dL

### INR

`inr`

- `1` — \< 1,7
- `2` — 1,7 à 2,3
- `3` — \> 2,3

### Ascite

`ascite`

- `1` — Absent
- `2` — Légère ou contrôlée par un diurétique
- `3` — Modérée à sévère ou réfractaire

### Encéphalopathie hépatique

`ence`

- `1` — Absent
- `2` — Grades I–II (ou contrôlée)
- `3` — Grades III–IV (ou réfractaire)

## Édition de la méthode

Child–Pugh/Pugh 1973 : 5 items 1–3, classes A 5–6/B 7–9/C 10–15

## Formule documentée

Chacun des 5 items vaut 1–3 points. Total 5–15.

Classe A: 5–6 · Classe B: 7–9 · Classe C: 10–15.

## Limites et population

Le Child–Pugh caractérise la gravité et le pronostic de la cirrhose, avec une évaluation clinique de l’ascite et de l’encéphalopathie en plus des examens biologiques. Ces deux composantes dépendent du jugement clinique et du traitement reçu ; documentez l’état évalué. Dans cette interface, la coagulation utilise l’INR, et non les secondes d’allongement du temps de prothrombine. Les mortalités de Mansour 1997 concernent cette cohorte de patients cirrhotiques opérés de l’abdomen en chirurgie programmée ou en urgence ; elles ne sont pas des prévisions individuelles automatiques. Le score ne remplace ni l’évaluation de la cause de l’hépatopathie ni une règle propre à la posologie d’un médicament.

## Références

- [Pugh RN et al. Transection of the oesophagus for bleeding oesophageal varices. Br J Surg, 1973.](https://doi.org/10.1002/bjs.1800600817)

- [Mansour A et al. Abdominal operations in patients with cirrhosis: still a major surgical challenge. Surgery, 1997.](https://doi.org/10.1016/S0039-6060(97)90080-5)

- [Durand F, Valla D. Assessment of the prognosis of cirrhosis: Child-Pugh versus MELD. J Hepatol, 2005.](https://doi.org/10.1016/j.jhep.2004.11.015)

- [Durand/Valla2005](https://www.journal-of-hepatology.eu/article/S0168-8278%2804%2900533-1/fulltext)

## Reproduire les tests techniques

Exécutez node test.cjs dans le répertoire racine de ce dépôt pour reproduire les cas synthétiques enregistrés. Les données d’entrée, les résultats attendus et les tolérances d’origine sont conservés. Les tests techniques ne constituent pas une validation clinique.

```sh
node test.cjs
```

tool.json contient les sources, l’édition et le périmètre de la revue. examples.json conserve les données d’entrée et les résultats attendus des cas synthétiques ; results.json consigne les résultats obtenus.

[Fiche et références](../tool.json) · [Code JavaScript](../calculator.js) · [Cas de référence](../examples.json) · [results.json](../results.json)

## Revue et conditions d’utilisation

Aucune révision clinique indépendante n’a été effectuée.

Cette interface est une traduction réalisée par nos soins, et non une édition officielle ou certifiée. La revue clinique indépendante, la révision linguistique professionnelle et l’autorisation des droits sur les instruments n’ont pas été réalisées.

Résultat de la formule ou de la classification. L’interprétation, la conduite et l’applicabilité dépendent de l’évaluation professionnelle et de la source sélectionnée.

## Licence et attribution

Apache-2.0 s’applique uniquement au code d’ELUCENIA. Les droits sur les instruments, publications, traductions et données restent ceux de leurs titulaires respectifs. Conservez LICENSE et NOTICE.

ELUCENIA · Felipe Guedes · Copyright © 2026

## Résultats documentés

Les informations ci-dessous conservent les sorties de la méthode pour des exemples synthétiques. Elles ne constituent pas une validation clinique indépendante.

### 1

Classe A (5 à 6 points) : maladie compensée

Mortalité chirurgicale abdominale d’environ 10 % (Mansour 1997).


### 2

Classe B (7 à 9 points) : atteinte fonctionnelle significative

Mortalité chirurgicale abdominale d’environ 30 % ; évaluer la transplantation.


### 3

Classe C (10 à 15 points) : maladie décompensée

Mortalité chirurgicale abdominale d’environ 82 % ; éviter la chirurgie élective et évaluer la transplantation.

