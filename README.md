# Custom DAT for LycorisXI

- プライベートサーバLycorisXI用のカスタムDATファイルです。
- アイテムの説明文を変更するだけのもので、このDATを使用しなくてもゲームシステムへの影響はありません。
1. カスタムオーグメント素材となるアイテムの説明文に、そのアイテムで付与できるオーグメント内容の記載を追加
1. アイテム説明文の改ページに対応しておらず、かつ説明文が4行以上（カスタムオーグメント4枠分表示しようとすると見切れてしまう）のアイテムの説明文を改ページに対応させる

# 使用方法

- XiPivotを導入してください。
- このページの Code -> Download ZIP でDATファイルをダウンロードしてください。
- ダウンロードしたファイルを展開し、XiPivotのDATフォルダに `Windower4\addons\XiPivot\data\DATs\LycorisXI\ROM\`となるように配置してください。
- 以下のいずれかの方法でXiPivotのオーバレイに追加したDATを加えます。
  - XiPivotの設定ファイル `Windower4\addons\XiPivot\data\settings.xml`の`overlays`に`LycorisXI`を書き加える（全サーバ&キャラに適用されてしまいますので注意）
  - ゲーム内でログイン直後に`//pivot a LycorisXI`を実行（ゲーム内でメニューを開く=標準のDATが読み込まれてしまう前に実行する必要があります）
