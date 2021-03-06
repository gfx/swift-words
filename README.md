# Swift訳語集

Swiftの用語がかなりバラバラなので、統一のために訳語集を作りました。

絶対的なものではありませんが、Swiftの日本語記事を書く際に参考になれば幸いです。

[swift-words](https://github.com/gfx/swift-words) へのpull-requestは歓迎します。また、質問や議論は [swift-words/issues](https://github.com/gfx/swift-words/issues) で受け付けています。

## 原則

* すでに広く使われる用語があればそちらを優先する（× 所有物 / ◯ プロパティ, × パターンマッチング / ◯ パターンマッチ）
* なるべく和訳する（×ストアド・プロパティ / ◯格納プロパティ）
* どうしても和訳できない場合、キーワード・コード以外はなるべくカタカナにする（× patterns / ◯ パターンズ）
* カタカナ化する際、構文や概念などで原語が複数形ならカナ用語も複数形にする（◯ パターンズ / ◯ ジェネリクス）

## 訳語

訳語 | 原語 | 捕捉
----|------|------------
構造体 | structure |
クラス | class |
列挙型 | enumeration |
プロトコル | protocol |
総称 | generics | Javaで一般的な用語の「ジェネリクス」も併用してよい
破壊的メソッド | mutating method |
パターンズ | patterns | パターンマッチや変数の初期化に使われるパターンの仕様のこと。 cf. [Patterns](https://developer.apple.com/library/ios/documentation/Swift/Conceptual/Swift_Programming_Language/Patterns.html)
格納プロパティ | stored property |
算出プロパティ | computed property |
初期化子 | initializer |
解放子 | deinitializer |
添字 | subscript |
パターンマッチ | pattern-matching | 正規表現のパターンマッチと紛らわしいので注意すること cf. [Control Flow](https://developer.apple.com/library/ios/documentation/Swift/Conceptual/Swift_Programming_Language/ControlFlow.html#//apple_ref/doc/uid/TP40014097-CH9-XID_1900)
ARC | ARC | Automatic Reference Counting; 訳語は与えない
オプショナル型 | optional types | コードを表すときは `T?` (Tに注目する場合）または `Optional<T>`（オプショナル型に注目する場合）
開封 | unwrap | 単に「オプショナル型のもつ値を取り出す」でもよい
暗黙的開封オプショナル型 | implicitly-unwrapped optionals | コードを表すときは `T?` または `ImplicitlyUnwrappedOptional<T>`
値型 | value types | 構造体と列挙型のこと
参照型 | reference types | クラスのこと
属性 | attributes | `@objc` など; プロパティのことではない
同一 | identical | `===` は同一性演算子
同値 | equivalent | `==` は同値性演算子
null合体演算子 | null coalescing operator | from [wikipedia/null合体演算子](http://ja.wikipedia.org/wiki/Null%E5%90%88%E4%BD%93%E6%BC%94%E7%AE%97%E5%AD%90)

以下は訳語が定まっていないもの。

訳語 | 原語 | 捕捉
----|------|------------

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
* https://github.com/koher
