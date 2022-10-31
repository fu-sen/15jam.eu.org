## MixJuice コンテンツ サンプル

![画面表示](/screenshot.jpg)

IchigoJam BASIC の カナ は Shift_JIS の半角と同じですが、\
GitHub 上では UTF-8 で表示されています。\
そのため、ここでの MixJuice コンテンツは英文表記にしています。

### IchigoJam BASIC

次のコマンドで参照できます。

```
?"MJ GETS 15jam.ru.org/
```

実際の表示とソースを見比べて下さい。

2020年10月29日より、IchigoJam web で表示できるように、\
IchigoJam BASIC は `GETS` で表示するようになりました。

2022年11月1日より、ドメインを `15jam.eu.org` へ移し\
[GitHub Pages](https://pages.github.com/) を用いて公開しています。

現在多くの環境は https で HTTP/2 および HTTP/3 対応になったため、\
MixJuice では GETS・POSTS が機能しなくなる場合があります。\
その場合でも http を用いた GET・POST は HTTP/1.1 を用いるため、\
動作可能な場合がありますが、MixJuice・MicJack は GET・POST、\
IchigoJam web は GETS・POSTS を使用する必要があり、\
コンテンツによっては動的に出力を変化させる必要があります。

### IchigoLatte

起動直後は一度次のコマンドを実行して下さい。\
文字化けした文字列が出てきて正常です。（lash> は入力する必要ありません）

```
lash>echo > uart;cat uart
```

次のコマンドで参照できます。（GET の代わりに GETS も使用可）

```
lash>echo MJ GET 15jam.eu.org/il/> uart;cat uart > .
```

### IchigonQuest

IchigonQuest そのものは MixJuice 非対応です。\
IJUtilities を用いて変換する事で公開できます。\
上位互換の MicJack が Kidspod; のプログラム送受に対応しています。

___

## 関連サイト

* MixJuice (公式) http://mixjuice.shizentai.jp/
* IchigoJam (公式) https://ichigojam.net/
* IchigoLatte (公式) http://ichigolatte.shizentai.jp/

* イチゴジャム レシピ (公開元) https://15jamrecipe.jimdofree.com/

___

## Powered by

[GitHub Pages](https://pages.github.com/)
