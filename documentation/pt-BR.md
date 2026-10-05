<!-- ELUCENIA technical documentation · child-pugh · pt-BR · no clinical/professional/rights approval -->

# Child-Pugh

[condições, fontes e permissões](https://elucenia.org/pt-br/ferramentas/child-pugh)

## Como usar

Use a ferramenta no portal ou abra index.html em um servidor HTTP local. Selecione o idioma, preencha os campos e calcule.

## Entradas e unidades

### Bilirrubina total

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

- `1` — Ausente
- `2` — Leve ou controlada com diurético
- `3` — Moderada a grave ou refratária

### Encefalopatia hepática

`ence`

- `1` — Ausente
- `2` — Graus I–II (ou controlada)
- `3` — Graus III–IV (ou refratária)

## Edição do método

Child Pugh/Pugh 1973:5 itens 1–3, classes A 5–6/B 7–9/C 10–15

## Fórmula documentada

Cada um dos 5 itens vale de 1 a 3 pontos. Total de 5 a 15.

Classe A: 5–6 · Classe B: 7–9 · Classe C: 10–15.

## Limites e população

O Child–Pugh caracteriza gravidade e prognóstico da cirrose, com avaliação clínica de ascite e encefalopatia além dos exames. Esses dois componentes dependem de julgamento e do tratamento recebido; documente a condição avaliada. Nesta interface, a coagulação usa INR, e não segundos de prolongamento do tempo de protrombina. As mortalidades do estudo cirúrgico de Mansour 1997 pertencem àquela coorte de cirróticos em cirurgia abdominal eletiva ou de emergência e não são uma previsão individual automática. O escore não substitui a avaliação da causa da hepatopatia nem uma regra específica de dose de medicamento.

## Referências

- [Pugh RN et al. Transection of the oesophagus for bleeding oesophageal varices. Br J Surg, 1973.](https://doi.org/10.1002/bjs.1800600817)

- [Mansour A et al. Abdominal operations in patients with cirrhosis: still a major surgical challenge. Surgery, 1997.](https://doi.org/10.1016/S0039-6060(97)90080-5)

- [Durand F, Valla D. Assessment of the prognosis of cirrhosis: Child-Pugh versus MELD. J Hepatol, 2005.](https://doi.org/10.1016/j.jhep.2004.11.015)

- [Durand/Valla2005](https://www.journal-of-hepatology.eu/article/S0168-8278%2804%2900533-1/fulltext)

## Reproduzir os testes técnicos

Execute node test.cjs na pasta raiz deste repositório para repetir os casos sintéticos registrados. As entradas, expectativas e tolerâncias originais são preservadas. Testes técnicos não constituem validação clínica.

```sh
node test.cjs
```

tool.json contém fontes, edição e escopo de revisão. examples.json conserva as entradas e expectativas sintéticas; results.json registra os resultados obtidos.

[Ficha e referências](../tool.json) · [Código JavaScript](../calculator.js) · [Casos de referência](../examples.json) · [results.json](../results.json)

## Revisão e condições de uso

Revisão clínica independente não realizada.

Esta interface é uma tradução autoral, não uma edição oficial ou certificada. Revisão clínica independente, revisão linguística profissional e autorização de direitos de instrumentos não foram realizadas.

Resultado da fórmula ou classificação. Interpretação, conduta e aplicabilidade dependem da avaliação profissional e da fonte selecionada.

## Licença e atribuição

Apache-2.0 aplica-se somente ao código da ELUCENIA. Os instrumentos, publicações, traduções e dados mantêm os direitos dos respectivos titulares. Preserve LICENSE e NOTICE.

ELUCENIA · Felipe Guedes · Copyright © 2026
