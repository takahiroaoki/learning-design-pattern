# Interpreterパターン

interpreterパターンは、プログラミング言語を使って新たなミニ言語を作りたい時などに適用できる。例えば正規表現やバッチ処理言語など。

BNFに忠実にNodeを書いていくことで、ミスの起こりづらいインタプリタを作ることができる。

自分が修論で使ったNetlogoも裏はJavaで書かれていたと聞いたことがあるがinterpreterパターンだったかも？