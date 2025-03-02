# Rakuen日本語化MOD

これは[翻訳MOD](https://github.com/JoaoFelipe/rakuen-translation)を用いて[Rakuen](https://store.steampowered.com/app/559210/Rakuen/)を日本語化するMODです。

## パッチノート

### 2022/04/21:

- キサブロウの病室の掲示板を調べるとエラーが発生する不具合を修正しました。

## 動作確認済み環境

- Windows 10
- Linux Mint 19.1

Macは環境が用意できず、動作確認ができていません。詳しくは `トラブルシューティング` の項を参照してください。

## 初回インストール方法

1. 次のURLからパッチをダウンロードする: https://github.com/izayoi256/rakuen-translation/archive/ja.zip
2. パッチファイルを解凍して、`rakuen-translation-ja`の中身をRakuenのインストール先に上書きする (デフォルトは`C:\Program Files (x86)\Steam\steamapps\common\Rakuen` )
3. `translation_patch.exe` を実行する

これで完了です。ゲームを起動するとタイトル画面に言語メニューが追加されているので、日本語を選択してください。

## アップデート方法

MODを既にインストール済みで、不具合修正等を反映する場合はこちらの手順を行なってください。

1. 次のURLからパッチをダウンロードする: https://github.com/izayoi256/rakuen-translation/archive/ja.zip
2. パッチファイルを解凍して、`rakuen-translation-ja`の中身をRakuenのインストール先に上書きする (デフォルトは`C:\Program Files (x86)\Steam\steamapps\common\Rakuen` )

## 文字化け回避

Linux環境で、日本語を選択した以降にゲームを起動するとタイトル画面の文字が `□` に文字化けする現象を確認しています。(Mac環境でも発生するかもしれません)

タイトル画面の上から3番目の言語メニューを選択すると直ります。

根本的な修正ができないため、お手数ですが起動のたびに上記の操作をしてください。

(直せる方はプルリクエストを送っていただけると助かります)

## トラブルシューティング

### Linuxユーザーの場合

翻訳MODの記載

> mkxpエンジンによるテストも正常に通っているのでプレイ可能です。
> 
> インストール手順でtranslation_patch.exeではなくtranslation_patch.elfを実行してください。

### Macユーザーの場合

翻訳MODの記載

> マシンを持っていないためテストができていません。Macもmkxpエンジンを利用しているため、恐らくプレイ可能だと思います。 (詳しくはLinuxユーザーの場合の回答を参照)
> 
> ですが、翻訳パッチをインストールするにはtools/translation_patch.cをビルドしてコンパイルする必要があります。
> 
> (もしMacをお持ちでしたら、コンパイル済みバージョンのプルリクエストを是非送ってください)

## 注意事項

- 原作サイドからの要請等により、予告なく当プログラムを非公開とする場合があります。
- 原作のアップデート等により、当プログラムが正常に動作しなくなる可能性があります。
- 当プログラムを使用することで発生した損害について、作者は一切責任を負いません。
