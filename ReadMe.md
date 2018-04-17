# このソフトウェアについて

Webから使えるテキストエディタを作りたい。

# 使い方

1. URLにアクセス
1. 何らかのアクションでテキスト内容をどこかへ保存

## 既存の方法

### ブラウザ標準

ブラウザのURL欄に以下を入力して`Enter`キー押下する。

```
data:text/html, <html contenteditable>
```

* 背景白なのが気に入らない
* 保存できない

# 開発環境

* [Raspberry Pi](https://ja.wikipedia.org/wiki/Raspberry_Pi) 3 Model B
    * [Raspbian](https://www.raspberrypi.org/downloads/raspbian/) GNU/Linux 8.0 (jessie)
        * Chromium 51.0.2704.91

# ライセンス

このソフトウェアはCC0ライセンスである。

[![CC0](http://i.creativecommons.org/p/zero/1.0/88x31.png "CC0")](http://creativecommons.org/publicdomain/zero/1.0/deed.ja)
