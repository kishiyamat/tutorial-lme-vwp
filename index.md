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
以下の技術指導を実施します。
(i) データ分析⽀援 (統計の概論)
(ii) 視線計測実験のセットアップ
形式は感染防⽌対策には万全の注意を払うため、
以下を想定しています。
(i) 必要に応じてオンラインでのワークショップ型指導
(ii) ラボ内での対⾯実習指導(1〜2名を上限とした⼩数指導)
また、成果を活かした技術資料および、
トレーニング課題(サンプル実験を含む)の作成を⾏い
オンライン媒体で共有します。

<!--
150,000で50,000で4週と考えると12週分のコマになる。
1. 授業をする　
1. 動画として残す
1. ハンズオンは code camp
-->

## シラバス

| Week | Topic                          | Readings                                  |
|------|--------------------------------|-------------------------------------------|
| 1    | [Rと統計の入門       ][week-1] | [Rで学ぶ統計学入門][yellow] の 1, 8, 9章 |
| 2    | [一般化線形モデル    ][week-2] | [Rで学ぶ統計学入門][yellow] の 10章       |
| 3    | [一般化線形混合モデル][week-3] | [Rで学ぶ統計学入門][yellow] の 11章       |
| 4    | [対照実験の役割と VWP][week-4] | [ことばの実験研究の方法][nakatani] の 1章 |
| 5    | [VWP の機材配置と実施][week-5] | TBA                                       |
| 6    | [VWP の実験結果の分析][week-1] | TBA                                       |

[yellow]: http://www.tkd-pbl.com/book/b279683.html
[nakatani]: http://www.hituzi.co.jp/hituzibooks/ISBN978-4-89476-964-9.htm
[week-1]: ./1.html
[week-2]: ./2.html
[week-3]: ./3.html
[week-4]: ./4.html
[week-5]: ./5.html
[week-6]: ./6.html

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

## 参考資料 (subject to modification)

- [Rで学ぶ統計学入門](http://www.tkd-pbl.com/book/b279683.html)
- [パソコンがあればできる！ ことばの実験研究の方法](http://www.hituzi.co.jp/hituzibooks/ISBN978-4-89476-964-9.htm)
- [Package ‘lme4’](https://cran.r-project.org/web/packages/lme4/lme4.pdf)
- [lme4: Mixed-effects models in R.](https://www.r-project.org/nosvn/pandoc/lme4.html)
- [datacamp / datacamp-light](https://github.com/datacamp/datacamp-light)


## Contributions

このサイトのソースコードは[GitHub][home]で管理しています。
オープンな状態なので、もし改善点があれば[Issues][issues]に投稿してください。

[home]: https://github.com/kishiyamat/tutorial-lme-vwp/tree/gh-pages
[issues]: https://github.com/kishiyamat/tutorial-lme-vwp/issues

<!---
### Misc.

Your Pages site will use the layout and styles from the Jekyll theme you have selected in your [repository settings](https://github.com/kishiyamat/tutorial-lme-vwp/settings). The name of this theme is saved in the Jekyll `_config.yml` configuration file.

### Support or Contact

Having trouble with Pages? Check out our [documentation](https://docs.github.com/categories/github-pages-basics/) or [contact support](https://github.com/contact) and we’ll help you sort it out.
-->
