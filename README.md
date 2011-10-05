# Lokka Git Themes

Git Themes plugin for Lokka.

GitHub上に置かれたテーマをその場でインストールして変更することができます。

## Installation

    $ cd LOKKA_ROOT/public/plugin
    $ git clone git://github.com/tkawa/lokka-git_themes.git

## Usage

Input Git URL & hit 'install' button.

then click the theme to apply.

## GitHubからインストールできるテーマの作り方

このプラグインでは、*.erb, *.hamlなどのテンプレートだけをインストールし、その他のCSSや画像ファイルは取得しません。
CSSや画像ファイルを反映させるためには、GitHub Pagesを有効にする必要があります。

やり方は、 "gh-pages" という名前のブランチを作成してpushするだけです。

* https://github.com/tkawa/lokkatheme-p0t

を参考にしてください。