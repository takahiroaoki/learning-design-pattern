# Facade

Facade（ファサード）とは正面玄関のこと。Facadeパターンは、クラスの数が増えて使い方が複雑になったシステムについて、使い方が明確なインターフェースを提供する。こうすることで各機能が疎結合になる。プログラマは複数のFacadeをさらにまとめて新たなFacadeを作るなど、分かりやすい構成を作る必要がある。

この際、余分なクラスは別パッケージから呼び出せないようにしておくなどすれば、機能の使い方がさらに分かりやすい。このようにクラスやそのフィールドにアクセスできる範囲を明確かつ限定しておくことも、Open/Closed-Principleの一つであると言える。どこからでもアクセスできるようになっていては、修正する際にどこまで影響を確認したらよいのかわからない。