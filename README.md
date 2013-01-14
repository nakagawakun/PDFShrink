PDFShrink
=========

 画像ファイルで構成されたPDFの各ページの画像の解像度を調整し、Sony Reader等のE-inkを使った端末で読みやすくするためのものです。

動作環境
--------

 Mac OS X 10.7 以降で動作します。
 Mac OS X 10.8.2 / MacBook Air mid 2011, Mac mini late 2012 にて動作確認。

使い方
------

 PDFファイルをドラッグ&ドロップすると、PDFの中身が表示されます。
 File > Export > Compacted PDF... を選択し、保存ダイアログでファイル名を指定すると、各ページの解像度を指定されたサイズに収まるように縮小して新しいPDFファイルに保存します。
 バージョン 1.2 より、PDF だけでなく、CBZ や mobi といった形式での出力にも対応しました。mobi での出力には Amazon.com が提供している KindleGen が必要です。

解像度の変更
------------

 PDFShrink > Preferences を選択し、最大の幅(maxWidth)と高さ(maxHeight)を指定します。
 バージョン 1.1 より、電子書籍リーダーを選択すると最適な解像度を自動的に設定できるようになりました。
 PDFを表示させた際の最適な解像度は、検索して調べたものがほとんどで、Kindle Paperwhite 以外は実機では確認していません。誤りなどがありましたら下記の連絡先まで連絡いただければと思います。

JPEG画質(圧縮率)の変更
----------------------

 バージョン 1.2 より、JPEG 画像の画質(圧縮率)を変更できるようになりました。
 PDFShrink > Preferences を選択し、画質(JPEG quality)を指定します。

mobi の出力
-----------

 バージョン 1.2 より、Kindle で用いられる mobi という形式での出力に対応しました。
 Amazon.com が提供する KindleGen というツールをダウンロードして利用します。展開後、「kindlegen」というファイルを PDFShrink と同じフォルダに保存してください。別のディレクトリに保存したものを利用する場合は、設定から変更してください。
 PDFShrink > Preferences を選択し、kindlegen のパス(Path to kindlegen)を指定します。

 KindleGen のダウンロード先
 http://www.amazon.com/gp/feature.html?ie=UTF8&docId=1000765211

 mobi での出力の際には、書名や著者名、ページめくりの方向を指定することが可能です。
 書名と著者名は PDF のプロパティに設定されていればそれを、設定されていなければファイル名から取得を試みます。

その他
------

 PDFファイルを開いた状態で、ページの追加や削除、入れ替えをおこなうこともできます。

免責事項
--------

 このソフトウェアを利用したことによるいかなる損害も、作者はその責任を負いません。

連絡先
------

 何かありましたら、 amatubu@mac.com までご連絡ください。
 また、最新バージョンは、
 http://amatubu.skr.jp/
 にて配布します。

2013.1.14 naoki iimura
