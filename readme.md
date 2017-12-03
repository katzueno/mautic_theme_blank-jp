# Blank-JP - Mautic 用シンプル日本語用テンプレート

Mautic を使って日本語のシンプルなメール・ランディングページ用テンプレートです。

## インストール方法

スクリーンショット付きの解説を、[弊社ブログ記事](https://concrete5.co.jp/blog/mautic-blank-jp-mautic)にて掲載しています。

https://concrete5.co.jp/blog/mautic-blank-jp-mautic


- GitHub のレポジトリから [ダウンロード](https://github.com/katzueno/mautic_theme_blank-jp/archive/master.zip)
    - https://github.com/katzueno/mautic_theme_blank-jp/archive/master.zip
- ZIP ファイルを解凍
- 「mautic_theme_blank-jp-master」フォルダを **含めず** 仮想ファイルのみで ZIP ファイルを作成
- blank-jp.zip という名前に変更 
- Mautic 管理画面に管理権限の有るユーザーとしてログイン
- 右上の歯車ボタンをクリックし、右ペインメニューを出す
- メニューから「テーマ」を選択
- 右上より、ファイルを選択し、「インストール」
- 以上で Blank-JP テーマが追加されます。

## 仕様

### 特長

- フォント指定日本語フォントに最適化
- スマホ & PC で最適化できるようにシンプルなレスポンシブ実装

### フォント指定

下記のように指定しています

```
        body {
        	font-family: "游ゴシック", YuGothic, "ヒラギノ角ゴ ProN W3", "Hiragino Kaku Gothic ProN", "メイリオ", Meiryo, sans-serif;	font-size:16px;
        	font-weight:400;
        	color:#000;
        	min-height: 100%;
        	height: 100%;
        }
```

### レスポンシブ実装

- 横幅 480px 以下をスマホとして、
- それ以上は、横幅 600px として固定。table を使わず div で横幅を指定

## クレジット

- @katzueno (コンクリートファイブジャパン)

## ご意見・PR ウェルカム！

みなさんのご意見、Pull Request をどんどんお寄せ下さい。
