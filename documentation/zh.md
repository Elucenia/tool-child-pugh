<!-- ELUCENIA technical documentation · child-pugh · zh · no clinical/professional/rights approval -->

# Child-Pugh

[条件、来源与许可](https://elucenia.org/zh/tools/child-pugh)

## 使用方法

在门户中使用工具，或通过本地 HTTP 服务器打开 index.html。选择语言，填写各字段，然后计算。

## 输入与单位

### 总胆红素

`bili`

- `1` — \< 2 mg/dL
- `2` — 2 至 3 mg/dL
- `3` — \> 3 mg/dL

### 白蛋白

`alb`

- `1` — \> 3.5 g/dL
- `2` — 2.8 至 3.5 g/dL
- `3` — \< 2.8 g/dL

### INR

`inr`

- `1` — \< 1.7
- `2` — 1.7 至 2.3
- `3` — \> 2.3

### 腹水

`ascite`

- `1` — 无
- `2` — 轻度或利尿剂可控制
- `3` — 中重度或难治性

### 肝性脑病

`ence`

- `1` — 无
- `2` — I–II 级（或可控制）
- `3` — III–IV 级（或难治性）

## 方法版本

Child–Pugh/Pugh 1973：5项1–3分，分级A 5–6/B 7–9/C 10–15

## 已记录的公式

5项各计1–3分。总分5–15。

级 A: 5–6 · 级 B: 7–9 · 级 C: 10–15.

## 限制与适用人群

Child–Pugh描述肝硬化的严重程度和预后，除实验室检查外，还包括腹水和肝性脑病的临床评估。这两个部分取决于临床判断和已接受的治疗；请记录被评估的状态。本界面的凝血指标使用INR，而不是凝血酶原时间延长的秒数。Mansour1997的死亡率属于当时接受择期或急诊腹部手术的肝硬化队列，不能自动用来预测个人结局。该评分不能替代肝病病因评估或特定药物的剂量规则。

## 参考文献

- [Pugh RN et al. Transection of the oesophagus for bleeding oesophageal varices. Br J Surg, 1973.](https://doi.org/10.1002/bjs.1800600817)

- [Mansour A et al. Abdominal operations in patients with cirrhosis: still a major surgical challenge. Surgery, 1997.](https://doi.org/10.1016/S0039-6060(97)90080-5)

- [Durand F, Valla D. Assessment of the prognosis of cirrhosis: Child-Pugh versus MELD. J Hepatol, 2005.](https://doi.org/10.1016/j.jhep.2004.11.015)

- [Durand/Valla2005](https://www.journal-of-hepatology.eu/article/S0168-8278%2804%2900533-1/fulltext)

## 复现技术测试

在此仓库的根目录中运行 node test.cjs，以重复已记录的合成案例。原始输入、预期结果和容差保持不变。技术测试不构成临床验证。

```sh
node test.cjs
```

tool.json 包含来源、版本和审查范围。examples.json 保留合成输入与预期结果；results.json 记录实际得到的结果。

[记录与参考文献](../tool.json) · [JavaScript代码](../calculator.js) · [参考案例](../examples.json) · [results.json](../results.json)

## 审查与使用条件

尚未开展独立临床审查。

此界面为自主编写的翻译，并非官方或认证版本。尚未完成独立临床审查、专业语言审查或工具权利授权。

公式或分类结果。解释、处理及适用性须结合专业评估和所选来源。

## 许可与署名

Apache-2.0 仅适用于 ELUCENIA 代码。工具、出版物、翻译和数据的权利仍归各自权利人所有。请保留 LICENSE 和 NOTICE。

ELUCENIA · Felipe Guedes · Copyright © 2026

## 已记录的结果

以下信息保留该方法对合成示例的输出，不构成独立的临床验证。

### 1

A 级（5 至 6 分）：代偿性疾病

腹部手术死亡率约 10%（Mansour 1997）。


### 2

B 级（7 至 9 分）：明显功能受损

腹部手术死亡率约 30%；评估移植。


### 3

C 级（10 至 15 分）：失代偿性疾病

腹部手术死亡率约 82%；避免择期手术并评估移植。

