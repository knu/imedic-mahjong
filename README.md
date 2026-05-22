# IME用麻雀用語辞書

麻雀用語をすばやく快適に入力するための、かな漢字変換システム向け変換辞書です。チャットやメールなどで麻雀用語を入力しやすくするための辞書データです。

語の追加要望や誤りの指摘は、Issue または Pull Request でお寄せください。ただし、辞書の編纂にあたり、読みや表記には編集方針が反映されています。読み方や方言、表記揺れを際限なく収録することはできません。必要に応じて、お仲間内で通じやすい表記等に直したものを配布して利用してください。その際は下記のライセンスを遵守してください。

辞書収録用語を集めるにあたり、以下のサイトを参考にさせていただきました。各サイトの作成者のみなさまにお礼を申し上げます。

- [麻雀国語辞典](http://www.geocities.co.jp/Playtown-Denei/5222/dic.htm)
- sammaniax mahjong glossary (麻雀用語集)
- [雀のお宿［辞林］](http://www.hakata21.com/suzume/3jiri/index.html)

## ダウンロード

最新版は [GitHub Releases](https://github.com/knu/imedic-mahjong/releases/latest) からダウンロードできます。

- [ATOK形式](https://github.com/knu/imedic-mahjong/releases/latest/download/mahjong.atok.txt)
- [MS-IME形式](https://github.com/knu/imedic-mahjong/releases/latest/download/mahjong.msime.txt)
- [ことえり形式](https://github.com/knu/imedic-mahjong/releases/latest/download/mahjong.kotoeri.txt)

MS-IME形式は BOM 付き UTF-16LE / CRLF です。

開発版の元データは [mahjong.txt](./mahjong.txt) です。

## 使い方

お使いの環境に合った形式の辞書テキストをダウンロードして、各 IME の辞書登録機能で取り込んでください。ブラウザ内で辞書ファイルが開いた場合は、ファイルとして保存してから登録してください。

### Windows

Windows 標準の Microsoft IME では、MS-IME形式を使います。

IME の設定画面から辞書ツールを開き、「テキストファイルからの登録」でダウンロードした `mahjong.msime.txt` を指定してください。

ATOK では、辞書ユーティリティの一括処理で単語ファイルとして `mahjong.atok.txt` を指定して登録します。

Google 日本語入力では、辞書ツールからフォーマット「Microsoft IME」で `mahjong.msime.txt` をインポートしてください。

### macOS

標準の日本語入力では、ことえり形式を使います。日本語入力ソースに切り替え、メニューバーの入力メニューから「“日本語 - ……入力”設定を開く」を選択してください。サイドバーで対象の入力ソースを選び、「入力ソース」設定ダイアログ下部の「追加辞書」ボックスに `mahjong.kotoeri.txt` をドラッグして登録します。

ATOK ではATOK形式を使います。辞書ユーティリティの一括処理で `mahjong.atok.txt` を指定して登録してください。

Google 日本語入力ではATOK形式またはMS-IME形式が使えます。辞書ツールから `mahjong.atok.txt` をインポートしてください。

### その他

利用している IME が上記の形式に対応している場合は、対応する形式のファイルをインポートしてください。未対応の環境では、[mahjong.txt](./mahjong.txt) を元に適宜変換して利用してください。

## ライセンス

この変換辞書データは、クリエイティブ・コモンズ「表示-継承 2.1 日本」ライセンスの下で利用できます。

- [Creative Commons Attribution-Share Alike 2.1 Japan License](http://creativecommons.org/licenses/by-sa/2.1/jp/)

なお、この辞書の編集著作権は、これを利用して入力した文章には及びません。文章の著作権は、その著作者に属します。

Copyright (c) 2004-2026 Akinori MUSHA
