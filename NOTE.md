# 機械語とアセンブラ

* 返り値はRAX
* 第1引数はRDI、第2引数はRSI
* `call`命令は次の2つを行う
  * call命令の次の命令のアドレスをスタックにプッシュ
  * call命令の引数として与えられたアドレスにジャンプ
* `ret`命令は次の2つを行う
  * スタックからアドレスをポップ
  * そのアドレスにジャンプ

コラム

* [Compiler Explorer](https://godbolt.org/z/RyNqgE)
