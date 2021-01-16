---
layout: default
title: A Tutorial on LME and VWP
description: 線形混合効果モデル・視線計測実験のオンラインチュートリアルサイト
---

## 背景と概要

近年盛んに⼼理⾔語学分野で⽤いられている視線計測実験は、
[専攻](http://gamp.c.u-tokyo.ac.jp/)の多くの学⽣の関⼼を集めていますが、
個⼈レベルで装置にアクセスして技術を習得することは難しい状況です。
そこで視線計測実験に⼗分な経験を持つ
[申請者](https://github.com/kishiyamat)(恐縮です)がその知識を活かし、
パンデミック収束後多くの学⽣がプロジェクトを開始できるよう、
感染防⽌対策には万全の注意を払いながら、
実験のセットアップ・データ分析⽀援を、
必要に応じてオンラインでのワークショップ型指導と、
ラボ内での対⾯実習指導（1〜2名を上限とした⼩数指導）を組み合わせた技術指導を⾏いつつ、
その成果を活かした技術資料および、
トレーニング課題（サンプル実験を含む）の作成を⾏いオンライン媒体で共有します。

## Readings & Textbooks

- [Rで学ぶ統計学入門](http://www.tkd-pbl.com/book/b279683.html)
- [パソコンがあればできる！ ことばの実験研究の方法](http://www.hituz動機i.co.jp/hituzibooks/ISBN978-4-89476-964-9.htm)
- [Package ‘lme4’](https://cran.r-project.org/web/packages/lme4/lme4.pdf)
- [lme4: Mixed-effects models in R.](https://www.r-project.org/nosvn/pandoc/lme4.html)
<!--
150,000で50,000で4週と考えると
12週分のコマになる(あれ、期末なしの普通の授業では)。
-->

<div data-datacamp-exercise data-lang="r">
<code data-type="pre-exercise-code">
    # This will get executed each time the exercise gets initialized
    b = 6
</code>
<code data-type="sample-code">
    # Create a variable a, equal to 5
    # Print out a
</code>
<code data-type="solution">
    # Create a variable a, equal to 5
    a <- 5
    # Print out a
    print(a)
</code>
<code data-type="sct">
    test_object("a")
    test_function("print")
    success_msg("Great job!")
</code>
<div data-type="hint">Use the assignment operator (<code><-</code>) to create the variable <code>a</code>.</div>
</div>


## シラバス

1. Rを用いた統計の基礎
    1. 統計を学ぶ大切さ(1.5h)
    1. 相関と回帰分析(1.5h)
    1. 一般化線形モデル(3h)
    1. 一般化線形混合モデル(3h)
1. VWP
    1. 対照実験の役割(3h)
    1. VWP の概要と構成(3h)
    1. あｓｄ(3h)

## 今後の予定

* 2020年12月
  * 本サイト作成(中旬)
  * 統計解析のチュートリアルの資料作成開始(下旬)
* 2020年1月
  * 統計解析のチュートリアルの資料完成(中旬)
  * 統計解析のチュートリアルのアナウンス(下旬)
  * 視線計測実験のチュートリアルの資料作成(下旬)
* 2020年2月
  * 統計解析のチュートリアル(中旬)
  * 視線計測実験のアナウンス(下旬)
* 2020年3月
  * 視線計測実験のチュートリアル(中旬)
  * 作業報告(下旬)

## チュートリアル資料

* [線形混合効果モデル](./lme.html)
* [視線計測実験](./vwp.html)

## 参考資料

- [datacamp / datacamp-light](https://github.com/datacamp/datacamp-light)

適宜更新


<!---
### Misc.

Your Pages site will use the layout and styles from the Jekyll theme you have selected in your [repository settings](https://github.com/kishiyamat/tutorial-lme-vwp/settings). The name of this theme is saved in the Jekyll `_config.yml` configuration file.

### Support or Contact

Having trouble with Pages? Check out our [documentation](https://docs.github.com/categories/github-pages-basics/) or [contact support](https://github.com/contact) and we’ll help you sort it out.
-->
