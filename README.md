# js-tutorial
This is my own tutorial for JavaScript coding.

## まとめ一覧
> ## 第一部: [基本文法](https://jsprimer.net/basic/)
> ### [コメント](https://jsprimer.net/basic/comments/#conclusion)
> この章では、ソースコードに説明を書けるコメントについて学びました。
> 
> - `//`以降から行末までが一行コメント
> - `/*`と`*/`で囲まれた範囲が複数行コメント
> - HTML-likeコメントは後方互換性のためだけに存在する
> 
> ### [変数と宣言](https://jsprimer.net/basic/variables/#summary)
> この章では、JavaScriptにおける変数を宣言するキーワードとしてconst、let、varがあることについて学びました。
>
> - constは、再代入できない変数を宣言できる
> - letは、再代入ができる変数を宣言できる
> - varは、再代入ができる変数を宣言できるが、いくつかの問題が知られている
> - 変数の名前（識別子）には利用できる名前のルールがある
> 
> varはほとんどすべてのケースでletやconstに置き換えが可能です。 constは再代入できない変数を定義するキーワードです。再代入を禁止することで、ミスから発生するバグを減らすことが期待できます。 このため変数を宣言する場合には、まずconstで定義できないかを検討し、できない場合はletを使うことを推奨しています。
> 
> [値の評価と表示](https://jsprimer.net/basic/read-eval-print/#conclusion)
> 略
> 
> [データ型とリテラル](https://jsprimer.net/basic/data-type/#data-type-summary)
> この章では、データ型とリテラルについて学びました。
> 
> - 7種類のプリミティブ型とオブジェクトがある
> - リテラルはデータ型の値を直接記述できる構文として定義されたもの
> - プリミティブ型の真偽値、数値、文字列、nullはリテラル表現がある
> - オブジェクト型のオブジェクト、配列、正規表現にはリテラル表現がある
> - プリミティブ型のデータでもプロパティアクセスができる
> 
> > JavaScriptが最初にNetscapeで実装された際に`typeof null === "object"`となるバグがありました。このバグを修正するとすでにこの挙動に依存しているコードが壊れるため、修正が見送られ現在の挙動が仕様となりました。 詳しくは[https://2ality.com/2013/10/typeof-null.html](https://2ality.com/2013/10/typeof-null.html)を参照。

## References
- js-primer
  - [Github](https://github.com/asciidwango/js-primer)
  - [Web site](https://jsprimer.net/)