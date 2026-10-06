<!-- ELUCENIA technical documentation · child-pugh · it · no clinical/professional/rights approval -->

# Child-Pugh

[condizioni, fonti e autorizzazioni](https://elucenia.org/it/strumenti/child-pugh)

## Come usare

Usi lo strumento nel portale oppure apra index.html tramite un server HTTP locale. Selezioni la lingua, compili i campi ed esegua il calcolo.

## Dati di ingresso e unità

### Bilirubina totale

`bili`

- `1` — \< 2 mg/dL
- `2` — 2 a 3 mg/dL
- `3` — \> 3 mg/dL

### Albumina

`alb`

- `1` — \> 3,5 g/dL
- `2` — 2,8 a 3,5 g/dL
- `3` — \< 2,8 g/dL

### INR

`inr`

- `1` — \< 1,7
- `2` — 1,7 a 2,3
- `3` — \> 2,3

### Ascite

`ascite`

- `1` — Assente
- `2` — Lieve o controllata con diuretico
- `3` — Moderata-grave o refrattaria

### Encefalopatia epatica

`ence`

- `1` — Assente
- `2` — Gradi I–II (o controllata)
- `3` — Gradi III–IV (o refrattaria)

## Edizione del metodo

Child–Pugh/Pugh 1973: 5 item 1–3, classi A 5–6/B 7–9/C 10–15

## Formula documentata

Ciascuno dei 5 item vale 1–3 punti. Totale 5–15.

Classe A: 5–6 · Classe B: 7–9 · Classe C: 10–15.

## Limiti e popolazione

Il Child–Pugh caratterizza la gravità e la prognosi della cirrosi, con valutazione clinica di ascite ed encefalopatia oltre agli esami di laboratorio. Questi due componenti dipendono dal giudizio clinico e dal trattamento ricevuto; documenta la condizione valutata. In questa interfaccia, la coagulazione usa l’INR, non i secondi di prolungamento del tempo di protrombina. Le mortalità di Mansour 1997 si riferiscono a quella coorte di cirrotici sottoposti a chirurgia addominale elettiva o d’urgenza e non sono previsioni individuali automatiche. Il punteggio non sostituisce la valutazione della causa dell’epatopatia né una regola specifica di dosaggio dei farmaci.

## Riferimenti

- [Pugh RN et al. Transection of the oesophagus for bleeding oesophageal varices. Br J Surg, 1973.](https://doi.org/10.1002/bjs.1800600817)

- [Mansour A et al. Abdominal operations in patients with cirrhosis: still a major surgical challenge. Surgery, 1997.](https://doi.org/10.1016/S0039-6060(97)90080-5)

- [Durand F, Valla D. Assessment of the prognosis of cirrhosis: Child-Pugh versus MELD. J Hepatol, 2005.](https://doi.org/10.1016/j.jhep.2004.11.015)

- [Durand/Valla2005](https://www.journal-of-hepatology.eu/article/S0168-8278%2804%2900533-1/fulltext)

## Riprodurre i test tecnici

Esegua node test.cjs nella cartella principale di questo repository per ripetere i casi sintetici registrati. Gli input, i risultati attesi e le tolleranze originali sono conservati. I test tecnici non costituiscono validazione clinica.

```sh
node test.cjs
```

tool.json contiene le fonti, l’edizione e l’ambito della revisione. examples.json conserva gli input e i risultati attesi dei casi sintetici; results.json registra i risultati ottenuti.

[Scheda e riferimenti](../tool.json) · [Codice JavaScript](../calculator.js) · [Casi di riferimento](../examples.json) · [results.json](../results.json)

## Revisione e condizioni d’uso

Non è stata effettuata una revisione clinica indipendente.

Questa interfaccia è una traduzione realizzata dagli autori, non un’edizione ufficiale o certificata. Non sono state eseguite la revisione clinica indipendente, la revisione linguistica professionale né la verifica delle autorizzazioni relative ai diritti sugli strumenti.

Risultato della formula o classificazione. Interpretazione, condotta e applicabilità dipendono dalla valutazione professionale e dalla fonte selezionata.

## Licenza e attribuzione

Apache-2.0 si applica solo al codice di ELUCENIA. I diritti su strumenti, pubblicazioni, traduzioni e dati restano ai rispettivi titolari. Conservi LICENSE e NOTICE.

ELUCENIA · Felipe Guedes · Copyright © 2026

## Risultati documentati

Le informazioni seguenti conservano gli output del metodo per esempi sintetici. Non costituiscono una validazione clinica indipendente.

### 1

Classe A (5 a 6 punti): malattia compensata

Mortalità chirurgica addominale di circa il 10% (Mansour 1997).


### 2

Classe B (7 a 9 punti): compromissione funzionale significativa

Mortalità chirurgica addominale di circa il 30%; valutare il trapianto.


### 3

Classe C (10 a 15 punti): malattia scompensata

Mortalità chirurgica addominale di circa l’82%; evitare la chirurgia elettiva e valutare il trapianto.

