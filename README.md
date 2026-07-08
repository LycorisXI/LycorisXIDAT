# Custom DAT for LycorisXI

- プライベートサーバLycorisXI用のカスタムDATファイルです。
- アイテムの説明文を変更するだけのもので、このDATを使用しなくてもゲームシステムへの影響はありません。
1. カスタムオーグメント素材となるアイテムの説明文に、そのアイテムで付与できるオーグメント内容の記載を追加
1. アイテム説明文の改ページに対応しておらず、かつ説明文が4行以上（カスタムオーグメント4枠分表示しようとすると見切れてしまう）のアイテムの説明文を改ページに対応させる
1. サーバ特有のカスタマイズされたアイテムの説明（装備性能や食事効果など）として変更された内容を表示する

# 使用方法

## 新規導入時
- Windower4用の[XiPivot](https://github.com/HealsCodes/XIPivot/releases/tag/v0.4.7)を導入してください。
- XiPivotのDAT配置用フォルダ`Windower4\addons\XiPivot\data\DATs`に、フォルダ`LycorisXI`を作成します。
- [Release](https://github.com/LycorisXI/LycorisXIDAT/releases/)から最新のリリースの`LycorisXI-CustomDAT.zip`をダウンロードします。
- ダウンロードしたファイルを展開し、中身の`ROM`フォルダをXiPivotのDAT用フォルダ内に`Windower4\addons\XiPivot\data\DATs\LycorisXI\ROM`となるように配置してください。
- 以下のいずれかの方法でXiPivotのオーバレイに追加したDATを加えます。
  - XiPivotの設定ファイル `Windower4\addons\XiPivot\data\settings.xml`の`overlays`に`LycorisXI`を書き加える（全サーバ&キャラに適用されてしまいますので注意）
  - ゲーム内でログイン直後に`//pivot a LycorisXI`を実行（ゲーム内でメニューを開く=標準のDATが読み込まれてしまう前に実行する必要があります）

## 更新時
- [Release](https://github.com/LycorisXI/LycorisXIDAT/releases/)から最新のリリースの`LycorisXI-CustomDAT.zip`をダウンロードします。
- ダウンロードしたファイルを展開し、中身の`ROM`フォルダを`Windower4\addons\XiPivot\data\DATs\LycorisXI\ROM`に上書きしてください。
