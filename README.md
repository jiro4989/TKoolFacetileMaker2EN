TKoolFacetileMaker2 Manual
================================================================================

- 作者             : 次郎(Jiro)
- 作成日           : 2016/07/16
- 最終更新日       : 2017/03/11
- 連絡先           : [次ログ](http://jiroron666.hatenablog.com/)
- 実行ファイル名   : TKFM.jar
- 動作確認・開発環境
  - OS             : Linux Mint 18.1
  - プロセッサ     : 2.00GHz Intel Core i7-3667U
  - メモリ         : 8GB RAM
  - Javaバージョン : 1.8.0-121

![tkfmデモ](./tkfm_demo01.gif "tkfmデモ")

--------------------------------------------------------------------------------

***WARNING***

***I am Japanese and my English is NOT perfect.***

Contents
--------------------------------------------------------------------------------

Software Overview
--------------------------------------------------------------------------------

This is tool to make face tile image of RPG Maker MV and VXACE.

This helps someone to edit much stand pictures.

This tool is able to

1. connect trimmed iamges to 1 file.
1. scale up and scale down images.
1. edit images for RPG Maker MV and VXACE.

This is made by Java Programming Language.

This ought to work in Windows, Mac and Linux OS.

But I don't have Mac OS.
It means I couldn't check to work in that.

File Configuration
--------------------------------------------------------------------------------

Operation Condition
--------------------------------------------------------------------------------

Your PC has Java if you want to work this tool.

You should install Java with the following steps if you did not yet.

[Java Download](https://www.java.com/ja/download/help/download_options.xml)

Please tell me your BUG to Author Blog if you found one after you done that.

Execution
--------------------------------------------------------------------------------

Double click 'tkfm.jar'.
You should type 'java -jar tkfm.jar' if you use LinuxOS.

Usage
--------------------------------------------------------------------------------

1. Open image files that you want to connect to 1 file.
   You should click 'File' Menu and 'Open...'
   or drag and drop image files to file list.

2. Click file or select files of file list.
   Image Viewer display image that you selected when you did that.

3. Move grid panel with Mouse drag.
   Grid panel sets position to trim images.

4. Change scale of image with scroll bar of Image Viewer.

5. Click 'Insert all images'.
   Output Preview display preview image.

   'Insert all images' button sets selected images to 1 to 8 panels of Output 
   Preview.

   You should type number key (1 to 8) if you want to set images to number panel 
   of Output Preview (but not 1 panel).

6. Click 'File' Menu.
   and click 'Save' or 'Save as ...'.

   You should confirm created image.
   Work has done if no problems.

   Good job :)

Shortcut Keys
--------------------------------------------------------------------------------

| Shortcut key | Operation                                       |
|-------------:|:------------------------------------------------|
| W            | Move UP Grid panel of Image Viewer              |
| A            | Move LEFT Grid panel of Image Viewer            |
| S            | Move DOWN Grid panel of Image Viewer            |
| D            | Move RIGHT Grid panel of Image Viewer           |
| Q            | Scale down image of Image Viewer                |
| E            | Scale up image of Image Viewer                  |
| 1            | Insert selected images to Output Preview from 1 |
| 2            | Insert selected images to Output Preview from 2 |
| 3            | Insert selected images to Output Preview from 3 |
| 4            | Insert selected images to Output Preview from 4 |
| 5            | Insert selected images to Output Preview from 5 |
| 6            | Insert selected images to Output Preview from 6 |
| 7            | Insert selected images to Output Preview from 7 |
| 8            | Insert selected images to Output Preview from 8 |

FAQ
--------------------------------------------------------------------------------

### Q1. Can't execute tkfm.jar with double click

ご利用の環境にJavaがインストールされているか確認してください。また、Javaがインス
トールされていても、本ソフト作成時のJavaのバージョン以下をご利用の場合、動作しな
い場合があります。

Javaのインストール、アップデート方法については[動作条件](#動作条件)の項目を参照
してください。

### Q2. 以前は動いていたのに突然起動しなくなった

実行時に自動生成されたフォルダをすべて削除してください。ただし、これはあくまでも
一時的な対処法です。

もしそれで起動するようになったのでしたら、よろしければ作者にバグ報告していただけ
ると助かります。また、起動しなくなる前に何を行っていたかも報告していただけると、
本ソフトのバグ修正が容易になり、品質向上に役立てることができます。

### Q3. READMEのレイアウトが崩れている

仕様です。フォントが異なるとレイアウトが崩れて見えることがあります。

メモ帳などでこのドキュメントを開いているのでしたら、書式メニューのフォントからMS
ゴシック(MS Pゴシックではありません)を選択すると作者が期待している通りのレイアウ
ト表示になります。

利用規約
--------------------------------------------------------------------------------

- 配布している素材を利用したことで発生した問題に対して、私は一切の責任を負いませ
  ん。

- 著作権は私(次郎)が有しています。私が死亡して５０年経過するまで決して放棄するこ
  とはありません。

- 再配布はお控えください。

- 利用規約を事前連絡なしに変更する場合があります。その場合は最新の規約が適用され
  るものとします。

### 補足

利用できる作品

- ツクール用に作成しましたがツクール作品以外の素材作成が目的でも利用可能です。
- 有償作品、エロゲー、グロゲーでも利用可能です。
- ゲーム作品以外でも利用可能です。

利用報告

- READMEへの記載はしなくても結構です。
- 使用報告もしなくて結構です。

バージョンアップ
--------------------------------------------------------------------------------

本ソフト配布時のzipに同封のREADME.htmlをダブルクリックしてください。本ソ
フトのプログラムを公開しているGithubというサイトにジャンプします。

移動先のサイトに表示されているバージョン情報が、現在ご使用のバージョンよりも上
がっている場合は、移動先サイトの実行ファイルをダウンロードしてご利用ください。

ダウンロード方法がわからなかった場合は、本ソフトをダウンロードしたツクマテコミュ
ニティ・または作者ブログのソフト配布ページのDropboxのリンクから、最新版をダウン
ロードしてください。

その他・作者からのお願い
--------------------------------------------------------------------------------

- バグの報告は連絡先の作者ブログか、ツクマテコミュニティのツール配布のページでお
  願いします。

- 様々なユーザが利用することを想定して慎重にデバッグを行っておりますが、個人制作
  ということもあり、確認が細部にまで至っていないことがあるかもしれません。

  非常に大切なファイルなどをもし扱うようなことがある場合、予めデータをコピーして
  バックアップを取ってから利用することをおすすめします。

- 新しい機能の実装のご要望をいただいた場合、実装する場合もあるかもしれませんが、
  必ずではないことをご了承ください。

アンインストール方法
--------------------------------------------------------------------------------

本ソフトはレジストリを変更していませんので、配布時のzipフォルダと展開後のフォル
ダを実行ファイルごとゴミ箱にぶち込んでいただければアンインストールできます。

もし本ソフトの実行ファイルをフォルダの外に移動して実行した場合は、自動で生成され
る各種フォルダを削除していただければ、アンインストールは完了です。

実行時に生成されるフォルダについては[ファイル構成] (#ファイル構成)の項目を参照し
てください。

更新履歴
--------------------------------------------------------------------------------

2017/03/11: Ver2.1.1
- 英語版の作成 (Made English Version)
