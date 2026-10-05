<!-- ELUCENIA technical documentation · child-pugh · ja · no clinical/professional/rights approval -->

# Child-Pugh

[条件・出典・許諾](https://elucenia.org/ja/tools/child-pugh)

## 使い方

ポータルでツールを使用するか、ローカルHTTPサーバー経由でindex.htmlを開いてください。言語を選択し、項目を入力して計算してください。

## 入力項目と単位

### 総ビリルビン

`bili`

- `1` — \< 2 mg/dL
- `2` — 2 ～ 3 mg/dL
- `3` — \> 3 mg/dL

### アルブミン

`alb`

- `1` — \> 3.5 g/dL
- `2` — 2.8 ～ 3.5 g/dL
- `3` — \< 2.8 g/dL

### INR

`inr`

- `1` — \< 1.7
- `2` — 1.7 ～ 2.3
- `3` — \> 2.3

### 腹水

`ascite`

- `1` — なし
- `2` — 軽度または利尿薬で管理可能
- `3` — 中等度～重度または治療抵抗性

### 肝性脳症

`ence`

- `1` — なし
- `2` — グレードI–II（または管理可能）
- `3` — グレードIII–IV（または治療抵抗性）

## 方法の版

Child–Pugh/Pugh 1973：5項目1～3点、クラスA 5～6/B 7～9/C 10～15

## 記載された計算式

5項目を各1～3点で採点。合計5～15点。

クラス A: 5–6 · クラス B: 7–9 · クラス C: 10–15.

## 限界・対象集団

Child–Pughは、検査値に加えて腹水と肝性脳症を臨床的に評価し、肝硬変の重症度と予後を表します。この二つの項目は臨床判断と受けた治療に左右されるため、評価した状態を記録してください。この画面の凝固評価にはINRを用い、プロトロンビン時間の延長秒数は用いません。Mansour1997の死亡率は、待機的または緊急腹部手術を受けた当時の肝硬変患者コホートの値であり、個人の予測へ自動的に転用できません。スコアは肝疾患の原因評価や、個別の薬剤用量規則に代わるものではありません。

## 参考文献

- [Pugh RN et al. Transection of the oesophagus for bleeding oesophageal varices. Br J Surg, 1973.](https://doi.org/10.1002/bjs.1800600817)

- [Mansour A et al. Abdominal operations in patients with cirrhosis: still a major surgical challenge. Surgery, 1997.](https://doi.org/10.1016/S0039-6060(97)90080-5)

- [Durand F, Valla D. Assessment of the prognosis of cirrhosis: Child-Pugh versus MELD. J Hepatol, 2005.](https://doi.org/10.1016/j.jhep.2004.11.015)

- [Durand/Valla2005](https://www.journal-of-hepatology.eu/article/S0168-8278%2804%2900533-1/fulltext)

## 技術テストの再現

このリポジトリのルートディレクトリでnode test.cjsを実行すると、記録された合成ケースを再実行できます。元の入力、期待結果、許容誤差は保持されています。技術テストは臨床的検証を意味しません。

```sh
node test.cjs
```

tool.jsonには出典、版、確認範囲が記録されています。examples.jsonには合成入力と期待結果が保持され、results.jsonには実際に得られた結果が記録されています。

[記録・参考文献](../tool.json) · [JavaScriptコード](../calculator.js) · [参照ケース](../examples.json) · [results.json](../results.json)

## 確認状況と使用条件

独立した臨床レビューは実施されていません。

このインターフェースは独自に作成した翻訳であり、公式版や認証済みの版ではありません。独立した臨床レビュー、専門家による言語レビュー、評価尺度等の権利許諾の確認は実施されていません。

式または分類の結果です。解釈、対応、適用可能性は専門家による評価と選択した出典に依存します。

## ライセンスと帰属表示

Apache-2.0はELUCENIAのコードにのみ適用されます。評価尺度等、出版物、翻訳、データの権利は、それぞれの権利者に帰属します。LICENSEとNOTICEを保持してください。

ELUCENIA · Felipe Guedes · Copyright © 2026
