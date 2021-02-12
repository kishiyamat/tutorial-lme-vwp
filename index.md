---
layout: default
title: A Tutorial on LME and VWP
description: 線形混合効果モデル・視線計測実験のオンラインチュートリアルサイト
---

## 背景と概要

近年盛んに⼼理⾔語学分野で⽤いられている視線計測実験は、
[専攻](http://gamp.c.u-tokyo.ac.jp/)の学⽣の関⼼を多く集めていますが、
個⼈で装置にアクセスして技術を習得することは困難です。
そこで統計分析/視線計測実験の経験を持つ
[申請者](https://github.com/kishiyamat)がその知識を活かし、
パンデミック収束後多くの学⽣がプロジェクトを開始できるよう、
(i) データ分析 と
(ii) 視線計測実験のセットアップ/実施
を技術指導します。

なお感染防⽌に万全の注意を払うため、
形式は必要に応じて以下を想定しています。

(i) オンラインでのワークショップ型指導  
(ii) ラボ内での対⾯実習指導 (1--2名を上限とした⼩数指導)

また成果を活かした技術資料および、
トレーニング課題(サンプル実験を含む)の作成を⾏い
オンライン媒体で共有します。

<!--
150,000で50,000で4週と考えると12週分のコマになる。
1. 授業をする　
1. 動画として残す
1. ハンズオンは code camp
-->

## シラバス

日程は現在調整中です。決まり次第確定させます。
また、Readingsは「参考になります」程度であって、
買って読んでおく必要はございません。
基本的には事前知識ゼロでOKです。

| Unit | Topic                          | Readings                                  | Date                          |
|------|--------------------------------|-------------------------------------------|-------------------------------|
| 1    | [Rと統計の入門       ][day-1]  | [Rで学ぶ統計学入門][yellow] の 1, 8, 9章  | [3/12, 3/13 (調整中)][tonton] |
| 2    | [一般化線形モデル    ][day-2]  | [Rで学ぶ統計学入門][yellow] の 10章       | [3/12, 3/13 (調整中)][tonton] |
| 3    | [一般化線形混合モデル][day-3]  | [Rで学ぶ統計学入門][yellow] の 11章       | [3/12, 3/13 (調整中)][tonton] |
| 4    | [対照実験の役割と VWP][day-4]  | [ことばの実験研究の方法][nakatani] の 1章 |   恐らくゼミの時間 (調整中)   |
| 5    | [VWP の機材配置と実施][day-5]  | TBA                                       |   恐らくゼミの時間 (調整中)   |
| 6    | [VWP の実験結果の分析][day-1]  | TBA                                       |   恐らくゼミの時間 (調整中)   |

## 今後の予定

* 2020年12月
  * サイトの大枠作成開始(中旬)
* 2021年1月
  * サイトの大枠作成完了(上旬)
  * 統計解析のチュートリアルの資料作成開始(上旬)
* 2021年2月
  * 統計解析のチュートリアルの資料完成(上旬)
  * 視線計測実験のチュートリアルの資料作成開始(上旬)
  * 統計解析のチュートリアルのアナウンス(中旬)
* 2021年3月
  * 視線計測実験のチュートリアルの資料完成(上旬)
  * 統計解析のチュートリアル(上旬)
  * 視線計測実験のチュートリアル(中旬)
  * 作業報告(下旬)

## 参考資料 (subject to modification)

- [Rで学ぶ統計学入門][yellow]
- [パソコンがあればできる！ ことばの実験研究の方法][nakatani]
- [Package ‘lme4’][lme_pdf]
- [lme4: Mixed-effects models in R.][lme]
- [datacamp / datacamp-light][dc]


## Contributions

このサイトのソースコードは[GitHub][home]で管理しています。
オープンな状態なので、もし改善点があれば[Issues][issues]に投稿してください。

[lme]: https://www.r-project.org/nosvn/pandoc/lme4.html
[lme_pdf]: https://cran.r-project.org/web/packages/lme4/lme4.pdf
[dc]: https://github.com/datacamp/datacamp-light
[home]: https://github.com/kishiyamat/tutorial-lme-vwp/tree/gh-pages
[issues]: https://github.com/kishiyamat/tutorial-lme-vwp/issues
[yellow]: http://www.tkd-pbl.com/book/b279683.html
[nakatani]: http://www.hituzi.co.jp/hituzibooks/ISBN978-4-89476-964-9.htm
[day-1]: ./1.html
[day-2]: ./2.html
[day-3]: ./3.html
[day-4]: ./4.html
[day-5]: ./5.html
[day-6]: ./6.html
[tonton]: http://tonton.amaneku.com/list.php?id=20210131034707_wvCq57

<!---
### Misc.

Your Pages site will use the layout and styles from the Jekyll theme you have selected in your [repository settings](https://github.com/kishiyamat/tutorial-lme-vwp/settings). The name of this theme is saved in the Jekyll `_config.yml` configuration file.

### Support or Contact

Having trouble with Pages? Check out our [documentation](https://docs.github.com/categories/github-pages-basics/) or [contact support](https://github.com/contact) and we’ll help you sort it out.
-->
