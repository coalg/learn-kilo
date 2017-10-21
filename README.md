## すごいテキストエディタ楽しく作ろう！ (Kilo)

Kiloというテキストエディタがあります。

> [Kilo: A text editor in less than 1000 LOC with syntax highlight and search.](https://github.com/antirez/kilo)

C言語で書かれており、コードは1000行程度、教育的ながら構文ハイライトを備えており、実用的な題材です。

本稿ではKiloを読んで写経した様子を解説していきます。わたしテキストエディタ作れるよ！という感じになれたらいいですね。

もっとも、すでに解説があるため、それらを参照しながらやっていきます。楽に楽を重ねていくスタイルです。

本稿は[Build Your Own Text Editor](http://viewsourcecode.org/snaptoken/kilo)の翻訳形式となっています。ところどころ原文飛ばしたり、文章をかなり変更したりしていますが、技術的な意味は捉え損ねないようにやっているつもりです。

ソースコードのライセンスは[BSD 2-clause](https://github.com/antirez/kilo/blob/master/LICENSE)であり、Build Your Own Text Editorのライセンスは[CC BY 4.0](https://creativecommons.org/licenses/by/4.0/)となっています。翻訳のライセンスはあとで決めます。今のところはAll rights reservedです。

kiloには日本語の[解説も存在します](http://news.mynavi.jp/series/kilo/001/)。これについても適宜参照して文章を補完できればと思っています。
