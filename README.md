# Microsoft Japanese Style Guide for RedPen
[![Circle CI](https://circleci.com/gh/k--kato/redpen-ms-style-jp-validator.svg?style=svg)](https://circleci.com/gh/k--kato/redpen-ms-style-jp-validator)
[![Coverage Status](https://coveralls.io/repos/github/k--kato/redpen-ms-style-jp-validator/badge.svg?branch=master)](https://coveralls.io/github/k--kato/redpen-ms-style-jp-validator?branch=master)
[![License: Apache](http://img.shields.io/:license-apache-blue.svg?style=flat-square)](http://www.apache.org/licenses/LICENSE-2.0.html)

Microsoft Style Guides are collections of rules that define language and style conventions for specific languages. These rules usually include general localization guidelines, information on language style and usage in technical publications, and information on market-specific data formats.

## Install

You can use it by copying the `ms-style-jp-validator-0.1.3.jar` file to the RedPen library directory ($REDPEN_HOME/lib).

### macOS

```bash
/usr/local/Cellar/redpen/1.8.0/libexec/lib/
```

### Windows

```bash
c:\Program Files\redpen-cli-1.0\lib\
```

## Usage

redpen-conf.xml
```XML
<redpen-conf lang="ja" type="zenkaku2">
  <validators>
    <validator name="MSStyleJP" />
  </validators>
</redpen-conf>
```

## Language Specific Conventions


### Characters

#### Hiragana

Incorrect (-)                                     | Correct (+)                                      | Support
--------------------------------------------------|--------------------------------------------------|--------
x                                                 | 昭和 61 年 7 月 1 日 内閣告示第 1 号「現代仮名遣い」   | N/A


#### Katakana

Incorrect (-)                                     | Correct (+)                                      | Support
--------------------------------------------------|--------------------------------------------------|--------
3 ケ月, 3 ヶ月, 3 カ月, 3 ヵ月                      | 3 か月                                            | ✅
5 ケ, 5 コ                                        | 5 個                                              | ✅


##### Long vowel

Incorrect (-)                                     | Correct (+)                                      | Support
--------------------------------------------------|--------------------------------------------------|--------
x                                                 | 平成 3 年 6 月 28 日 内閣告示第 2 号「外来語 表記」   | N/A
アクセラレーター                                    | アクセラレータ                                     | ✅
バリアー                                           | バリア                                            | ✅
バザールー                                         | バザール                                          | ✅
ベアー                                            | ベア                                              | ✅
ビールー                                           | ビール                                            | ✅
キャリアー                                          | キャリア                                         | ✅
センチメートルー                                    | センチメートル                                     | ✅
クリアー                                           | クリア                                            | ✅
コンパイラー                                        | コンパイラ                                        | ✅
コネクター                                          | コネクタ                                         | ✅
コンベヤー                                          | コンベヤ                                         | ✅
メートルー                                          | メートル                                         | ✅
ミリメートルー                                      | ミリメートル                                      | ✅
アウトドアー                                        | アウトドア                                        | ✅
ピアー                                             | ピア                                             | ✅
ポリエステルー                                      | ポリエステル                                       | ✅
プレミアー                                          | プレミア                                          | ✅
プロセッサー                                        | プロセッサ                                        | ✅
プログラマー                                        | プログラマ                                        | ✅
プロペラー                                          | プロペラ                                         | ✅
ラジエーター                                        | ラジエータ                                       | ✅
ドルー                                             | ドル                                             | ✅
ドアー                                             | ドア                                             | ✅
エンジニアー                                        | エンジニア                                        | ✅
エクステリアー                                      | エクステリア                                      | ✅
フロアー                                           | フロア                                            | ✅
フォーマッター                                      | フォーマッタ                                       | ✅
フロンティアー                                      | フロンティア                                       | ✅
ギアー                                             | ギア                                             | ✅
ユーモアー                                          | ユーモア                                         | ✅
リアー                                             | リア                                             | ✅
レジスター                                          | レジスタ                                         | ✅
スケジューラー                                      | スケジューラ                                      | ✅
シニアー                                           | シニア                                           | ✅
スリッパー                                         | スリッパ                                          | ✅
ステラー                                           | ステラ                                            | ✅
タールー                                           | タール                                            | ✅
ターミネーター                                      | ターミネータ                                       | ✅
トランジスター                                      | トランジスタ                                       | ✅
インドアー                                          | インドア                                          | ✅
インテリアー                                        | インテリア                                        | ✅
ジュニアー                                          | ジュニア                                         | ✅
ボランティアー                                      | ボランティア                                      | ✅
リニアー                                            | リニア                                          | ✅
アカデミ                                           | アカデミー                                        | ✅
アドベンチャ                                        | アドベンチャー                                    | ✅
アレルギ                                           | アレルギー                                        | ✅
アスキ                                            | アスキー                                          | ✅
バルコニ                                           | バルコニー                                        | ✅
バーベキュ                                         | バーベキュー                                      | ✅
バースデ                                           | バースデー                                        | ✅
ブルーベリ                                         | ブルーベリー                                      | ✅
カロリ                                            | カロリー                                          | ✅
セレモニ                                          | セレモニー                                         | ✅
チータ                                            | チーター                                          | ✅
チンパンジ                                        | チンパンジー                                       | ✅
コーヒ                                            | コーヒー                                          | ✅
カンパニ                                          | カンパニー                                         | ✅
コンピテンシ                                      | コンピテンシー                                      | ✅
マホガニ                                          | マホガニー                                         | ✅
マーキ                                            | マーキー                                          | ✅
ムービ                                            | ムービー                                          | ✅
ミステリ                                          | ミステリー                                         | ✅
ネイチャ                                          | ネイチャー                                         | ✅
ネービ                                            | ネービー                                          | ✅
アウトロ                                          | アウトロー                                         | ✅
ペイズリ                                          | ペイズリー                                         | ✅
パンジ                                            | パンジー                                          | ✅
パスキ                                            | パスキー                                          | ✅
パススル                                          | パススルー                                         | ✅
ペッカリ                                          | ペッカリー                                         | ✅
フォトグラフィ                                     | フォトグラフィー                                    | ✅
ポリシ                                            | ポリシー                                           | ✅
プレーリ                                          | プレーリー                                         | ✅
パブリシティ                                      | パブリシティー                                      | ✅
クランベリ                                        | クランベリー                                       | ✅
デイリ                                           | デイリー                                           | ✅
ドルビ                                           | ドルビー                                           | ✅
ドリルスル                                        | ドリルスルー                                       | ✅
イージ                                           | イージー                                           | ✅
エコノミ                                         | エコノミー                                          | ✅
エナジ                                           | エナジー                                           | ✅
エネルギ                                         | エネルギー                                          | ✅
ファンシ                                         | ファンシー                                          | ✅
ファンタジ                                       | ファンタジー                                        | ✅
フロッピ                                         | フロッピー                                         | ✅
フリークエンシ                                   | フリークエンシー                                     | ✅
ギャラリ                                         | ギャラリー                                         | ✅
ハーモニ                                         | ハーモニー                                         | ✅
ヘルシ                                           | ヘルシー                                           | ✅
ヒーロ                                           | ヒーロー                                          | ✅
ホットキ                                         | ホットキー                                         | ✅
ハウツ                                           | ハウツー                                          | ✅
ラズベリ                                         | ラズベリー                                         | ✅
ランデブ                                         | ランデブー                                         | ✅
レスキュ                                         | レスキュー                                         | ✅
ロータリ                                         | ロータリー                                         | ✅
シーナリ                                         | シーナリー                                         | ✅
スクリュ                                         | スクリュー                                         | ✅
シーソ                                           | シーソー                                          | ✅
シャンプ                                         | シャンプー                                         | ✅
スプレ                                           | スプレー                                          | ✅
ストーリ                                         | ストーリー                                         | ✅
ストロベリ                                        | ストロベリー                                      | ✅
サマリ                                           | サマリー                                          | ✅
シナジ                                           | シナジー                                          | ✅
タクシ                                           | タクシー                                          | ✅
テンキ                                           | テンキー                                          | ✅
タイムリ                                         | タイムリー                                         | ✅
トレジャ                                         | トレジャー                                         | ✅
トロリ                                           | トロリー                                          | ✅
インドアトロフィ                                  | インドアトロフィー                                  | ✅
バリュ                                           | バリュー                                          | ✅
インタビュ                                       | インタビュー                                       | ✅
ベンチャ                                         | ベンチャー                                         | ✅
ジュエリ                                         | ジュエリー                                         | ✅
ビクトリ                                         | ビクトリー                                         | ✅
カンガル                                         | カンガルー                                         | ✅
ウィスキ                                         | ウィスキー                                         | ✅
ワークフロ                                       | ワークフロー                                        | ✅
ラグジュアリ                                     | ラグジュアリー                                      | ✅

#### Kanji

Incorrect (-)                                     | Correct (+)                                      | Support
--------------------------------------------------|--------------------------------------------------|--------
                                                  | 平成 22 年 11 月 30 日 内閣告示第 2 号「常用漢字表」<br/>昭和 48 年 6 月 18 日 内閣告示第 2 号「送り仮名 付け方」 | N/A

#### English letters

Incorrect (-)                                     | Correct (+)                                      | Support
--------------------------------------------------|--------------------------------------------------|--------
ＮＯＴＥ                                           | NOTE                                             | ✅


#### Spaces

Incorrect (-)                                     | Correct (+)                                      | Support
--------------------------------------------------|--------------------------------------------------|--------
第3章                                              | 第 3 章                                           | ✅
ボタンをクリックして 、 閉じます 。                    | ボタンをクリックして、閉じます。                      | ✅
45 °                                              | 45°                                               | ✅
列 A ( タイトル )                                   | 列 A (タイトル)                                    | ✅
[ 新規 ] をクリックします。                           | [新規] をクリックします。                           | ✅
「 test 」と入力します。                             | 「test」と入力します。                              | ✅
3 / 14                                            | 3/14                                              | ✅
更新しますか ?                                      | 更新しますか?                                      | ✅
更新しますか ？                                     | 更新しますか？                                      | ✅
警告 !                                             | 警告!                                             | ✅
警告 ！                                            | 警告！                                            | ✅
フォント :                                          | フォント:                                         | ✅
フォント ：                                         | フォント：                                        | ✅
その他 …                                            | その他…                                          | ✅
保存(S)                                             | 保存 (S)                                         | N/A
保存 (S)                                            | 保存(S)                                          | ✅
変換 キー                                           | 変換キー                                          | N/A
ページレイアウト                                     | ページ レイアウト                                  | N/A
「第 2 章コントロール」を参照してください。              | 「第 2 章 コントロール」を参照してください。          | N/A
3kg                                                | 3 kg                                             | N/A
50 %                                               | 50%                                              | ✅
10 mm                                              | 10mm                                             | ✅
10/13(ページ)                                       | 10/13 (ページ)                                    | ✅
保存しますか?Excelを使用して編集する場合                | 保存しますか? Excelを使用して編集する場合             | ✅
「2.1Active Directory」を参照してください。           | 「2.1 Active Directory」を参照してください。         | N/A





### Numbers

Incorrect (-)                                     | Correct (+)                                      | Support
--------------------------------------------------|--------------------------------------------------|--------
ひとつ                                             | 1 つ                                            | N/A
一回                                               | 1 回                                            | N/A
一画面                                             | 1 画面                                           | N/A
(雑誌を) 一部                                       | 1 部                                            | N/A
一月                                               | 1 月                                            | N/A
二乗                                               | 2 乗                                            | N/A
三次元                                             | 3 次元                                           | N/A
四分位数                                           | 4 分位数                                         | N/A
二十行                                             | 20 行                                           | N/A
八十桁                                             | 80 桁                                           | N/A
百五十語                                           | 150 語                                           | N/A
一時間十五分                                        | 1 時間 15 分                                     | N/A
二進法                                             | 2 進法                                           | N/A
二百五十六色                                        | 256 色                                           | N/A
もう 1 度                                          | もう一度                                         | N/A
1 部                                              | (画面 ) 一部                                      | N/A
2 項分布                                           | 二項分布                                         | N/A
最小 2 乗法                                        | 最小二乗法                                       | N/A
100 分位数                                         | 百分位数                                         | N/A
100 分率                                           | 百分率                                          | N/A
3 角形                                             | 三角形                                          | N/A
4 捨 5 入                                          | 四捨五入                                         | N/A
1 時的に                                           | 一時的に                                         | N/A

#### Measurement Units

Incorrect (-)                                     | Correct (+)                                      | Support
--------------------------------------------------|--------------------------------------------------|--------
キロメートル                                        | km                                              | ✅
メートル                                            | m                                               | ✅
デシメートル                                        | dm                                              | ✅
センチメートル                                      | cm                                              | ✅
ミリメートル，ミリ                                   | mm                                              | ✅
ヘクトリットル                                       | hL                                              | ✅
リットル                                            | L                                               | ✅
デシリットル                                         | dL                                              | ✅
センチリットル                                       | cL                                              | ✅
ミリリットル                                        | mL                                              | ✅
トン                                               | t                                               | ✅
キログラム                                          | kg                                              | ✅
lb                                                | ポンド                                           | ✅
グラム                                             | g                                               | ✅
デシグラム                                          | dg                                              | ✅
センチグラム                                        | cg                                              | ✅
ミリグラム                                          | mg                                              | ✅
in                                                | インチ                                           | ✅
ft                                                | フィート                                         | ✅
mi                                                | マイル                                           | ✅
gal                                               | ガロン                                           | ✅
テラバイト                                          | TB                                              | ✅
ギガバイト                                          | GB                                              | ✅
メガバイト                                          | MB                                              | ✅
キロバイト                                          | KB                                              | ✅
B                                                 | バイト                                           | ✅
b                                                 | ビット                                           | ✅
ビット/秒                                          | bps                                             | ✅
ギガヘルツ                                          | GHz                                             | ✅
メガヘルツ                                          | MHz                                             | ✅
キロヘルツ                                          | kHz                                             | ✅
ヘルツ                                             | Hz                                              | ✅
ドット                                             | dot                                             | ✅
ドット/インチ                                       | dpi                                             | ✅
sec                                               | 秒                                               | ✅
ms                                                | ミリ秒                                            | ✅

##### Units without a space

Incorrect (-)                                     | Correct (+)                                      | Support
--------------------------------------------------|--------------------------------------------------|--------
45 度                                             | 45°                                              | ✅
50 パーセント                                      | 50%                                              | ✅
50 %                                              | 50%                                              | ✅
50 ％                                             | 50%                                              | ✅







### Compounds

Incorrect (-)                                     | Correct (+)                                      | Support
--------------------------------------------------|--------------------------------------------------|--------
ダイアログボックス                                   | ダイアログ ボックス                                | N/A
メニュー・コマンド                                   | メニュー コマンド                                  | N/A
マルチ バイト                                       | マルチバイト                                      | N/A
ダブル クリック                                     | ダブルクリック                                     | N/A
メニューバー                                        | メニュー バー                                     | N/A
ツールバー                                          | ツール バー                                       | N/A
ログ オン                                           | ログオン                                         | N/A
チェック イン                                        | チェックイン                                     | N/A
バック アップ                                        | バックアップ                                     | N/A
シャット ダウン                                      | シャット ダウン                                   | N/A


### Modifiers

Incorrect (-)                                     | Correct (+)                                      | Support
--------------------------------------------------|--------------------------------------------------|--------
適当なオプションを選択します。                        | 適切なオプションを選択します。                        | N/A
これは完璧なソリューションです。                       | これはお勧めのソリューションです。                    | N/A
これらのコントロールはコンテンツを編集するときに非常に便利です。 | これらのコントロールはコンテンツを編集するときに便利です。 | N/A
各ファイルごとに名前を変更します。                     | ファイルごとに名前を変更します。                      | N/A
値は変更しても大丈夫です。                            | 値は変更できます。                                  | N/A
この機能の知識がない場合は…                           | この機能を初めてお使いになる場合は…                   | N/A
設定はいかなる時でも更新できます。                     | 設定はいつでも更新できます。                         | N/A
初心者でも簡単に使えます。                            | 初心者の方にも簡単にお使いいただけます。               | N/A


### Punctuation

Incorrect (-)                                     | Correct (+)                                      | Support
--------------------------------------------------|--------------------------------------------------|--------
.                                                 | 。                                                | N/A
，                                                | 、                                                | N/A
2000 ページ                                        | 2,000 ページ                                      | N/A


### Verbs

Incorrect (-)                                     | Correct (+)                                      | Support
--------------------------------------------------|--------------------------------------------------|--------
セルが見えないとき 、ダイアログ ボックスを移動させます。  | セルが見えないとき、ダイアログ ボックスを移動します。   | N/A
アプリケーションのインストールを実行します。            | アプリケーションをインストールします。                 | N/A
行を追加したり、移動したり、削除したりします。           | 行の追加、移動、または削除を行います。                | N/A
ウイルス対策プログラムやソフトウェア更新プログラムで保護されていない場合、コンピューターは安全ではありません。 | ウイルス対策プログラムやソフトウェア更新プログラムで保護されていない場合、コンピューターは危険にさらされます。 | N/A
行を追加したり、移動したり、削除したりします。           | 行の追加、移動、または削除を行います。                | N/A
Windows を立ち上げます。                             | Windows を起動します。                            | N/A


### Style

Incorrect (-)                                     | Correct (+)                                      | Support
--------------------------------------------------|--------------------------------------------------|--------
変更箇所を表示                                      | 変更箇所の表示                                     | N/A
オブジェクトの種類の選択                             | オブジェクトの種類を選択                             | N/A
アイテムの開き                                      | アイテムを開く                                     | N/A
次                                                | 次へ                                              | N/A


### Tone

Incorrect (-)                                     | Correct (+)                                      | Support
--------------------------------------------------|--------------------------------------------------|--------
データ ファイルをアプリケーションに関連付けていただきますと、~ | データ ファイルをアプリケーションに関連付けると、~  | N/A
当社, 我社                                         | 弊社                                              | ✅
~を購入してください。                                | ~をお買い求めください。                             | N/A
~を使うときには、                                   | ~をお使いいただくときには、                          | N/A
~に問い合わせてください。                            | ~にお問い合わせください。                            | N/A
ご注意ください。                                    | 注意してください。                                  | ✅
ご確認ください。                                    | 確認してください。                                  | ✅
~をお使いいただくときには、~をお買い求めください。       | ~を使用するときには、~をお買い求めください。           | N/A
~をご使用にならないようご注意ください。                | ~を使用しないようご注意ください。                     | N/A


### Frequent Errors

Incorrect (-)                                     | Correct (+)                                      | Support
--------------------------------------------------|--------------------------------------------------|--------
不正な URL                                         | 無効な URL                                        | ✅
不正な XML 形式です。                               | XML 形式が正しくありません。                         | ✅
値が不正です。                                      | 値が無効です。                                     | ✅
ファイルが不正です。                                 | ファイルが正しくありません。                         | ✅
無効なアクセスは禁止されています。                     | 不正アクセスは禁止されています。                      | N/A



# References

1. Microsoft, "Japanese Style Guide", https://www.microsoft.com/Language/en-US/StyleGuides.aspx
1. RedPen, "Extending RedPen", http://redpen.cc/docs/latest/index.html#extending
