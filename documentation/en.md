<!-- ELUCENIA technical documentation · child-pugh · en · no clinical/professional/rights approval -->

# Child–Pugh

[conditions, sources and permissions](https://elucenia.org/en/tools/child-pugh)

## How to use

Use the tool in the portal or open index.html through a local HTTP server. Select the language, complete the fields and calculate.

## Inputs and units

### Total bilirubin

`bili`

- `1` — \< 2 mg/dL
- `2` — 2 to 3 mg/dL
- `3` — \> 3 mg/dL

### Albumin

`alb`

- `1` — \> 3.5 g/dL
- `2` — 2.8 to 3.5 g/dL
- `3` — \< 2.8 g/dL

### INR

`inr`

- `1` — \< 1.7
- `2` — 1.7 to 2.3
- `3` — \> 2.3

### Ascites

`ascite`

- `1` — Absent
- `2` — Mild or controlled with a diuretic
- `3` — Moderate to severe or refractory

### Hepatic encephalopathy

`ence`

- `1` — Absent
- `2` — Grades I–II (or controlled)
- `3` — Grades III–IV (or refractory)

## Method edition

Child–Pugh/Pugh 1973: 5 items 1–3, classes A 5–6/B 7–9/C 10–15

## Documented formula

Each of 5 items scores 1–3 points. Total 5–15.

Class A: 5–6 · Class B: 7–9 · Class C: 10–15.

## Limits and population

Child–Pugh characterizes the severity and prognosis of cirrhosis, using clinical assessment of ascites and encephalopathy as well as laboratory tests. Those two components depend on judgment and received treatment; document the condition assessed. In this interface, coagulation uses INR rather than seconds of prothrombin-time prolongation. Mortality figures from Mansour 1997 belong to that cohort of patients with cirrhosis undergoing elective or emergency abdominal surgery and are not automatic individual predictions. The score does not replace assessment of the cause of liver disease or a specific medication-dosing rule.

## References

- [Pugh RN et al. Transection of the oesophagus for bleeding oesophageal varices. Br J Surg, 1973.](https://doi.org/10.1002/bjs.1800600817)

- [Mansour A et al. Abdominal operations in patients with cirrhosis: still a major surgical challenge. Surgery, 1997.](https://doi.org/10.1016/S0039-6060(97)90080-5)

- [Durand F, Valla D. Assessment of the prognosis of cirrhosis: Child-Pugh versus MELD. J Hepatol, 2005.](https://doi.org/10.1016/j.jhep.2004.11.015)

- [Durand/Valla2005](https://www.journal-of-hepatology.eu/article/S0168-8278%2804%2900533-1/fulltext)

## Reproduce the technical tests

Run node test.cjs in the root directory of this repository to repeat the recorded synthetic cases. Original inputs, expectations and tolerances are preserved. Technical tests do not constitute clinical validation.

```sh
node test.cjs
```

tool.json contains sources, edition and review scope. examples.json retains synthetic inputs and expectations; results.json records the obtained results.

[Record and references](../tool.json) · [JavaScript code](../calculator.js) · [Reference cases](../examples.json) · [results.json](../results.json)

## Review and conditions of use

Independent clinical review has not been performed.

This interface is an authorial translation, not an official or certified edition. Independent clinical review, professional language review and instrument rights clearance have not been performed.

Formula or classification result. Interpretation, care and applicability depend on professional assessment and the selected source.

## License and attribution

Apache-2.0 applies only to ELUCENIA code. Rights to instruments, publications, translations and data remain with their respective holders. Preserve LICENSE and NOTICE.

ELUCENIA · Felipe Guedes · Copyright © 2026

## Documented results

The information below preserves the method outputs for synthetic examples. It does not constitute independent clinical validation.

### 1

Class A (5 to 6 points): compensated disease

Abdominal surgical mortality of about 10% (Mansour 1997).


### 2

Class B (7 to 9 points): significant functional impairment

Abdominal surgical mortality of about 30%; assess transplantation.


### 3

Class C (10 to 15 points): decompensated disease

Abdominal surgical mortality of about 82%; avoid elective surgery and assess transplantation.

