+++
date = '2025-04-11T02:47:32+09:00'
draft = true
title = 'Coding Philosophy'
+++

## 命名

正しい名前をつける

> 「すべてに正しい名前を付けて、そして、正しい名前であることを維持する」という鉄の意志

- [きれいなソースコードを書くために必要な、たったひとつの単純な事](https://r-west.hatenablog.com/entry/20090510/1241962864)

> 最初の時点ではすべてについて「それは何？」が明確となっていて整理されたきれいなコードを書いていても、「こうすれば必要な動きになる」という修正が入っていく事で、本来の「それは何？」を表していた名前と、実際の実態が少しずつずれていく。

- [そのソースコードが汚い理由：共通した根源的な間違い](https://r-west.hatenablog.com/entry/20090516/1242489952)

## 複雑性を減らす方法

> 私は状態 (state)、結合 (coupling)、複雑性 (complexity)、コード量 (code) の順に削減することでコードを最適化する。
>
> コードがよりステートレスになるなら、結合を増やすこともいとわない
> 結合を減らすためには、コードをもっと複雑にすることもある
> コードの複雑さが軽減されるなら、コードをコピーする
> コードの重複排除をするのは状態・結合・複雑性を増さない時のみに限る

- [状態、結合、複雑性、コード量の順に最適化する](https://ohbarye.hatenablog.jp/entry/2022/01/31/state-coupling-complexity-code)
- [There’s No Such Thing as Clean Code](https://www.steveonstuff.com/2022/01/27/no-such-thing-as-clean-code)

## 良かった記事

- [ブラウザからDBに行き着くまでただまとめる](https://zenn.dev/moko_poi/articles/c2402f13a870a1)
- [Latency Numbers Every Programmer Should Know](https://colin-scott.github.io/personal_website/research/interactive_latency.html)
- [【日本人エンジニア必携】英語命名規則の決定版](https://qiita.com/hironori_narita/items/4b06db0953053d41c4a0)
