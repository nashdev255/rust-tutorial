# Rust Tutorial
Rustの基本文法を学び、Rustを用いたCLIツールの開発を行う。

### 参考ドキュメント

ドキュメントのリンク<br/>
[Learn Rust - Rust Programming Language](https://www.rust-lang.org/learn)

ローカルでのドキュメント参照コマンド
```:cmd
~\rust-tutorial> rustup doc
```

<br/>

### トラブルシューティング
`error: link.exe not found`と表示される。
- 原因 : Visual StudioでのC++の実行環境が整っていないことから発生する。
- 対処 : [Visual Studio ダウンロードページ](https://visualstudio.microsoft.com/ja/downloads/)からVisual Studio Build Tools 20xx(vs_BuildTools.exe)をダウンロードし、起動後「C++によるデスクトップ開発」にチェックを入れてインストールする。
