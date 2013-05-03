kmbeamer（kmaedaさん用 beamer theme 集）
=======================================

概要
----

これはkmaedaさんが普段使っている beamer 用テンプレートを汎用化しようという試みです．少しずつ進めていく予定です．

インストール
------------

[ZIP アーカイブ](https://github.com/kmaed/kmbeamer/archive/master.zip)を取得し，TEXMF ツリーの然るべき場所に展開します．例えば，W32TeX ならインストールしたディレクトリ（C:\w32tex など）にある share\texmf-local の下に tex\latex というディレクトリを作成し，そこに展開します．UNIX 系 OS をお使いの方なら，~/texmf/tex/latex というディレクトリを作成し，そこに展開するとよいと思います．

使い方
------

examples/examples_kmbeamer.dtx を latex で処理するとできるサンプルを見て下さい．日本語を出力したい場合，サンプル中にもある通り platex + dvipdfmx か lualatex + luatexja を使うとよいでしょう．

注意点
------

 * 自分が使う機能を中心にいじっていくので，使い方によっては変な出力が得られることがあるかもしれません．
 * ちょっと「濃い」ものが多いので，使用する場面に注意して下さい．

収録テーマ
---------

 * Blackboard（黒板）
 * DarkConsole（画面が黒い人用）

意見・要望など
-------------

前田一貴 (kmaeda at users.sourceforge.jp) までお願いします．GitHub 経由でも構いません．
