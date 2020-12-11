# 注意
こちらのリポジトリでの最新版の提供は終了しました。今後は[道南バス公式HP](https://www.donanbus.co.jp/)よりダウンロードしてください。なお、考古学のためにこのリポジトリはこのまま保存しておきます。

# GTFSとは
GTFS(General Transit Feed Specification)は、公共交通機関の時刻表データにおける統一的な表記で、Googleによって提唱されています。統一的な企画であるため、この形式でデータを提供すれば、公共交通機関のデータを利用するアプリが作成しやすくなります。

さらにこのGTFSを改良し、日本での利用に適した「標準的なバス情報フォーマット(通称: 日本版GTFS)」が国交省より提唱されています。この「日本版GTFS」は、オリジナルGTFSの上位互換となっており、日本版GTFSで作成したデータはそのままオリジナルGTFSとしても利用可能です。

# 道南バスGTFS化プロジェクトとは
道南バス市内線の時刻表を室蘭市オープンデータやOpenStreetMapを活用して[日本版GTFS](http://www.mlit.go.jp/sogoseisaku/transport/sosei_transport_tk_000067.html)に書き起こすプロジェクトです。

元データはExcel形式であるため機械判読性も高くありませんが、GTFS形式にすれば、全世界共通のフォーマットとして扱えるため、利便性が大きく向上します。

# この「日本版GTFS」ファイルについて
このバージョンは、2018年4月1日に改定された時刻表に基づいています。

なお、`feed_inf.txt`の`feed_version`はZipファイル作成時に置換していますので、ご利用時はご注意ください。

# 実装など
Python3.xで実装しています。基本的にExcelなどの生データから抽出する形をとっています。

# 利用データ (ライセンス)
- [むろらんオープンデータライブラリ](http://www.city.muroran.lg.jp/main/org2260/odlib.php) (CC BY 2.1)
- [OpenStreetMap](http://www.openstreetmap.org/) (CC BY SA 3.0)

# ライセンス
利用したデータに準拠して「CC BY SA 3.0」を適用します。

