# That's Text README

`That's Text` スクリプトは、AppleScript で書いたプログラム。Safari で TEXTAREA などの入力フォームを、好みの外部エディタで編集できるようにする。利用には、Automator でこのスクリプトを実行するサービスを作ること、およびシステム環境設定でサービスを駆動するショートカットキーの登録が必要とする。

`That's Text` is a AppleScript program. Using this, you can edit input forms such like TEXTAREA with your favorite external editors in Safari.

## 動作環境

今回わたしが That's Text の開発と検証を行った環境については、以下のようなものである:

* `Mac OS X` version 10.11.6 (El Capitan)
* `Safari` version 10.0.1
* `AppleScript` version 2.5 (`osascript -e "applescript's version"`)
* `Automator` version 2.6
* `システム環境設定` version 14.0
* エディタ
    * `MacVim` Custom version 8.0 (Kaoriya 20161022)
    * `Emacs` version 24.5.1
    * `Visual Studio Code` version 1.6.1

## 導入

That's Text を利用するための環境構築の作業の流れは:

1. Automator で入力なしのサービスを作成し、That's Textスクリプトをコピペする
2. 作成したサービスを、システム環境設定でキーボードショートカットに登録する

の2ステップである。

手順の詳細が必要ならば xxxx を参照のこと。

## LICENSE

Copyright (c) 2016- YAMAMOTO, Masayuki

MIT License.


