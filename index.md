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
**なお、このウェブページはデモですので、
将来的にURLが変更される可能性があります。**

<!--
150,000で50,000で4週と考えると12週分のコマになる。
1. 授業をする　
1. 動画として残す
1. ハンズオンは code camp
-->

## LME資料

日程は現在調整中です。決まり次第確定させます。
また、Readingsは「参考になります」程度であって、
買って読んでおく必要はございません。
基本的には事前知識ゼロでOKです。

| Unit | Topic                          | Readings                                  | Date                          |
|------|--------------------------------|-------------------------------------------|-------------------------------|
| 1    | [Rと統計の入門       ][day-1]  | [Rで学ぶ統計学入門][yellow] の 1, 8, 9章  |  3/12(金) の 13:00 -- 15:00   |
| 2    | [一般化線形モデル    ][day-2]  | [Rで学ぶ統計学入門][yellow] の 10章       |  3/12(金) の 13:00 -- 15:00   |
| 3    | [一般化線形混合モデル][day-3]  | [Rで学ぶ統計学入門][yellow] の 11章       |  3/12(金) の 13:00 -- 15:00   |

以下の動画はチュートリアル当日を録画、編集したものです。
YouTube上にある詳細に目次を記述したので、
上のURLと動画を参考にしながら学習を進めてもらえれば幸いです。

<center>
<iframe width="560" height="315" src="https://www.youtube.com/embed/cwS_SVy4ZaM" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
</center>

## VWP資料

| Unit | Topic                          | Readings                                  | Date  |
|------|--------------------------------|-------------------------------------------|-------|
| 4    | [VWPと実験の流れ ][day-4]      | [ことばの実験研究の方法][nakatani] の 1章 |  N/A  |
| 5    | [VWP の機材配置と実施][day-5]  | N/A                                       |  N/A  |
| 6    | [VWP の実験結果の分析][day-6]  | N/A                                       |  N/A  |

## 動画

N/A

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
  * ~~視線計測実験のチュートリアル(中旬)~~ (資料作成のみとします。)
  * 作業報告(下旬)

## 参考資料 (subject to modification)

- [Rで学ぶ統計学入門][yellow]
- [パソコンがあればできる！ ことばの実験研究の方法][nakatani]
- [Package ‘lme4’][lme_pdf]
- [lme4: Mixed-effects models in R.][lme]
- [datacamp / datacamp-light][dc]

## Contributions

このサイトのソースコードは[GitHub][home]で管理しています。
オープンな状態なので、もし改善点や疑問点、
あるいは資料の追加があれば[Issues][issues]に投稿してください。

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

## 謝辞

本ウェブサイト及び付随する資料は東京大学による
『オンキャンパスジョブを活用した修学支援事業』
の一貫として作成しました。
[東京大学大学院 言語情報科学専攻 アカデミック・サポーター](http://ut-oncampusjob.chips.jp/)
というウェブサイトもあり、様々な事業があります。
この機会を設けてくださった大学と専攻そしてもちろん
多方面でご尽力くださった広瀬友紀教授に感謝申し上げます。
実験や統計分析に対する負担と記述的な制約を減らせれば幸いです。
また、資料を `r-wakalang` というコミュニティで共有したところ、
分かりづらい点のフィードバックもいただきました。
こちらもこの場を借りて感謝申し上げます。

<!---
### Misc.

Your Pages site will use the layout and styles from the Jekyll theme you have selected in your
[repository settings](https://github.com/kishiyamat/tutorial-lme-vwp/settings). 
The name of this theme is saved in the Jekyll `_config.yml` configuration file.

### Support or Contact

Having trouble with Pages? Check out our [documentation](https://docs.github.com/categories/github-pages-basics/) or [contact support](https://github.com/contact) and we’ll help you sort it out.
-->
