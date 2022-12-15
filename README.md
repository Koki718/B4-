# TeX-VScode_setup

VScodeでLaTeX環境を作成する．

まずはsettings.jsonの中身を，[これ](/settings.json)と同じように変える．ctrl+pで検索できるはず．

次に，実行するテンプレートを[ここ](/main.tex)に書いてあるものにする．(documentclassだけ揃えとけばまあ大丈夫)

さらに，実行するmain.texと同じ階層に[これ](/.latexmkrc)をおいておく．これがないとpLaTeXが実行できないみたい．

自動保存をOFF，保存するたびにコンパイルする設定にすれば，cloudlatexと同じ感じで使える．

ctrl+rでpdfリフレッシュするショートカットを設定しても良い．

そして，左下の歯車から「ユーザースニペットの構成」を選択し，[これ](/latex.json)と同じものを作成する．グローバルではなくlatexのみにしておくと良い．
これを行うことで，"includegraphics","tabular","report"でそれぞれショートカットが割り当てられる．(やってみた方がはやい)

以上で大体完了
