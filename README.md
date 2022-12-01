## robosys202x
## このリポジトリにはplusコマンドが含まれています。
![tesst](https://github.com/takuma0114/robosys202x/actions/workflows/test.yml/badge.svg)

## インストール方法
```
$ git clone https://github.com/takuma0114/robosys202x.git
$ cd robosys202x
```

## 内容
標準入力から読み込んだ数字から計算をして標準出力する。

## 使用方法
```
$　seq n | ./plus 
```
* 標準入力を行う際に上記に従い変数nに好きな数を入力する

## 使用例
```
$ seq 5 | ./plus
  15
```

## 必要なソフトウェア
* python: 3.7～3.10
  * テスト済み

## 動作確認済み環境です
* Ubuntu 22.04.1LTS

## 著作権とソフトウェアライセンスについて
* このソフトウェアパッケージは，3条項BSDライセンスの下，再頒布および使用が許可されます。
* このパッケージのコードは，下記のスライド（CC-BY-SA 4.0 by Ryuichi Ueda）のものを，教育目的で本人の許可を得て自身の著作としたものです。
* https://github.com/ryuichiueda/my_slides/tree/master/robosys_2022
* © 2022 Takuma Abe
