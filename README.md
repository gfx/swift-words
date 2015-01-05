# Swift訳語集

Swiftの用語がかなりバラバラなので、統一のために訳語集を作りました。

絶対的なものではありませんが、Swiftの日本語記事を書く際に参考になれば幸いです。

[swift-words](https://github.com/gfx/swift-words) へのpull-requestは歓迎します。また、質問や議論は [swift-words/issues](https://github.com/gfx/swift-words/issues) で受け付けています。

## 原則

* なるべく和訳する（×ストアド・プロパティ / ◯格納プロパティ）
* すでに広く使われる用語があればそちらを優先する（× 所有物 / ◯ プロパティ, × パターンマッチング / ◯ パターンマッチ）
* キーワード・コード以外はなるべくカタカナにする（× patterns / ◯ patterns）
* カタカナ化する際、構文や概念などで原語が複数形ならカナ用語も複数形にする（◯パターンズ / ◯ジェネリクス）

## 訳語

訳語 | 原語 | 捕捉
----|------|------------
構造体 | structure |
クラス | class |
列挙型 | enumeration |
プロトコル | プロトコル |
総称 | generics | Javaで一般的な用語の「ジェネリクス」も紹介する
変異メソッド | mutating method |
パターンズ | patterns | パターンマッチや変数の初期化に使われるパターンの仕様のこと。 cf. [Patterns](https://developer.apple.com/library/ios/documentation/Swift/Conceptual/Swift_Programming_Language/Patterns.html)
格納プロパティ | stored property |
算出プロパティ | computed property |
初期化子 | initializer |
解放子 | deinitializer |
添字 | subscript |
パターンマッチ | pattern-matching | 正規表現のパターンマッチと紛らわしいのでなるべく使用は避けること cf. [Control Flow](https://developer.apple.com/library/ios/documentation/Swift/Conceptual/Swift_Programming_Language/ControlFlow.html#//apple_ref/doc/uid/TP40014097-CH9-XID_1900)
ARC | ARC | Automatic Reference Counting. 訳語は与えない
オプショナル型 | optional types | コードを表すときはT?(Tに注目する場合）またはOptional<T>（オプショナル型に注目する場合）
取り出し | unwrap | 「後置!の適用」 == 「Optional型のもつ値を取り出す」

以下は訳語が定まっていないもの。

訳語 | 原語 | 捕捉
----|------|------------
? | implicitly-unwrapped optionals | コードを表すときはT?またはImplicitlyUnwrappedOptional<T>

## Contributing

新しい訳語の追加や変更のリクエストは歓迎します。以下のガイドラインに従っていただけるとスムーズかと思います。

* 原典ないし既存の使用例へのリンク
* README.md#Contributorsへのご自身のGitHub IDの追加

## License

Copyright (c) 2015, [FUJI Goro (gfx)](https://github.com/gfx).

This document is licensed in [CC-BY](https://creativecommons.org/licenses/by/3.0/).

本記事はいかなる用途でも使用してかまいません。

## Contributors

* https://github.com/yuseinishiyama
