<!-- ELUCENIA technical documentation · child-pugh · es · no clinical/professional/rights approval -->

# Child-Pugh

[condiciones, fuentes y permisos](https://elucenia.org/es/herramientas/child-pugh)

## Cómo usar

Utilice la herramienta en el portal o abra index.html mediante un servidor HTTP local. Seleccione el idioma, complete los campos y calcule.

## Entradas y unidades

### Bilirrubina total

`bili`

- `1` — \< 2 mg/dL
- `2` — 2 a 3 mg/dL
- `3` — \> 3 mg/dL

### Albúmina

`alb`

- `1` — \> 3,5 g/dL
- `2` — 2,8 a 3,5 g/dL
- `3` — \< 2,8 g/dL

### INR

`inr`

- `1` — \< 1,7
- `2` — 1,7 a 2,3
- `3` — \> 2,3

### Ascitis

`ascite`

- `1` — Ausente
- `2` — Leve o controlada con diurético
- `3` — Moderada a grave o refractaria

### Encefalopatía hepática

`ence`

- `1` — Ausente
- `2` — Grados I–II (o controlada)
- `3` — Grados III–IV (o refractaria)

## Edición del método

Child–Pugh/Pugh 1973: 5 ítems 1–3, clases A 5–6/B 7–9/C 10–15

## Fórmula documentada

Cada uno de los 5 ítems vale 1–3 puntos. Total 5–15.

Clase A: 5–6 · Clase B: 7–9 · Clase C: 10–15.

## Límites y población

El Child–Pugh caracteriza la gravedad y el pronóstico de la cirrosis mediante evaluación clínica de ascitis y encefalopatía, además de análisis. Estos dos componentes dependen del juicio clínico y del tratamiento recibido; documente la condición evaluada. En esta interfaz, la coagulación usa INR, no segundos de prolongación del tiempo de protrombina. Las mortalidades de Mansour 1997 corresponden a aquella cohorte de pacientes con cirrosis sometidos a cirugía abdominal electiva o de emergencia, y no son predicciones individuales automáticas. La puntuación no sustituye la evaluación de la causa de la hepatopatía ni una regla específica de dosificación de medicamentos.

## Referencias

- [Pugh RN et al. Transection of the oesophagus for bleeding oesophageal varices. Br J Surg, 1973.](https://doi.org/10.1002/bjs.1800600817)

- [Mansour A et al. Abdominal operations in patients with cirrhosis: still a major surgical challenge. Surgery, 1997.](https://doi.org/10.1016/S0039-6060(97)90080-5)

- [Durand F, Valla D. Assessment of the prognosis of cirrhosis: Child-Pugh versus MELD. J Hepatol, 2005.](https://doi.org/10.1016/j.jhep.2004.11.015)

- [Durand/Valla2005](https://www.journal-of-hepatology.eu/article/S0168-8278%2804%2900533-1/fulltext)

## Reproducir las pruebas técnicas

Ejecute node test.cjs en el directorio raíz de este repositorio para repetir los casos sintéticos registrados. Se conservan las entradas, los resultados esperados y las tolerancias originales. Las pruebas técnicas no constituyen validación clínica.

```sh
node test.cjs
```

tool.json contiene las fuentes, la edición y el alcance de la revisión. examples.json conserva las entradas y los resultados esperados de los casos sintéticos; results.json registra los resultados obtenidos.

[Ficha y referencias](../tool.json) · [Código JavaScript](../calculator.js) · [Casos de referencia](../examples.json) · [results.json](../results.json)

## Revisión y condiciones de uso

No se ha realizado una revisión clínica independiente.

Esta interfaz es una traducción de elaboración propia, no una edición oficial o certificada. No se han realizado la revisión clínica independiente, la revisión lingüística profesional ni la autorización de derechos de los instrumentos.

Resultado de la fórmula o clasificación. La interpretación, la conducta y la aplicabilidad dependen de la evaluación profesional y de la fuente seleccionada.

## Licencia y atribución

Apache-2.0 se aplica únicamente al código de ELUCENIA. Los derechos de los instrumentos, publicaciones, traducciones y datos permanecen en manos de sus respectivos titulares. Conserve LICENSE y NOTICE.

ELUCENIA · Felipe Guedes · Copyright © 2026
