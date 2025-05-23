本リポジトリは既に終了済の[国土数値情報のファイル形式に関する意見募集](https://github.com/furuhashilab/next-ksj-formats) に有用な情報が集まったので、その後の地理空間情報データ形式に関する状況変化のメモ用に **青山学院大学古橋研究室として非公式にFork** しました。

非公式リポジトリの [Issues](https://github.com/furuhashilab/next-ksj-formats/issues) は開放しておりますので、気になる議論など自由にお使いください。


---
[意見募集は令和7年2月28日までで終了しました。多くのご意見をお寄せいただき、ありがとうございました。](https://github.com/furuhashilab/next-ksj-formats)

# 【終了】国土数値情報のファイル形式に関する意見募集
現在の国土数値情報は、Shape 形式・GML 形式・GeoJSON 形式の大きく3 つのファイル形式でデータを整備・提供していますが、時代にあった新しいファイル形式での提供へ移行していくことを検討しています。

そこで、ユーザーの皆様から、国土数値情報のファイル形式について意見を募集します。

本レポジトリでは、国土数値情報として提供してほしいファイル形式について、具体的なご意見を募集します。

意見募集や投稿方法の詳細は、[地理空間情報課ラボのページ](https://www.mlit-gis-lab.jp/ksj/)をご覧ください。

## サンプルデータ
国土数値情報の中でもダウンロードの多い以下の３形式のデータのサンプルファイルを提供します。

* 全国のデータを１ファイルにまとめ、属性名はコードではなく、日本語としています（例：L01_007 → 年度）。

* [国土数値情報ダウンロードサービスコンテンツ利用規約](https://nlftp.mlit.go.jp/ksj/other/agreement.html)に従ってご利用ください。

### L01-24_地価公示データ_2024年(令和6年)版 （ポイント）
[GeoJSON 形式](https://public-data.geolonia.com/mlit-ksj-vector-2024/sample-data/L01-24/L01-24.geojson) 148MB

[FlatGeobuf 形式](https://public-data.geolonia.com/mlit-ksj-vector-2024/sample-data/L01-24/L01-24.fgb) 47.7MB

[GeoParquet 形式](https://public-data.geolonia.com/mlit-ksj-vector-2024/sample-data/L01-24/L01-24.parquet) 4.46MB

[GeoArrow 形式](https://public-data.geolonia.com/mlit-ksj-vector-2024/sample-data/L01-24/L01-24.arrow) 14.9MB

[PMTiles 形式](https://public-data.geolonia.com/mlit-ksj-vector-2024/sample-data/L01-24/L01-24.pmtiles) 36.3MB　[PMTiles Viewerで見る](https://pmtiles.io/?url=https://public-data.geolonia.com/mlit-ksj-vector-2024/sample-data/L01-24/L01-24.pmtiles#map=13.29/35.68753/139.75305)

[GeoPackage 形式](https://public-data.geolonia.com/mlit-ksj-vector-2024/sample-data/L01-24/L01-24.gpkg) 35.4MB

参考：[国土数値情報ダウンロードサイト「地価公示データ」](https://nlftp.mlit.go.jp/ksj/gml/datalist/KsjTmplt-L01-2024.html)

### N03-20240101_行政区域データ_2024年(令和6年)版 （ポリゴン）
[GeoJSON 形式](https://public-data.geolonia.com/mlit-ksj-vector-2024/sample-data/N03-20240101/N03-20240101.geojson) 463MB

[FlatGeobuf 形式](https://public-data.geolonia.com/mlit-ksj-vector-2024/sample-data/N03-20240101/N03-20240101.fgb) 252MB

[GeoParquet 形式](https://public-data.geolonia.com/mlit-ksj-vector-2024/sample-data/N03-20240101/N03-20240101.parquet) 219MB

[GeoArrow 形式](https://public-data.geolonia.com/mlit-ksj-vector-2024/sample-data/N03-20240101/N03-20240101.arrow) 229MB

[PMTiles 形式](https://public-data.geolonia.com/mlit-ksj-vector-2024/sample-data/N03-20240101/N03-20240101.pmtiles) 207MB　[PMTiles Viewerで見る](https://pmtiles.io/?url=https://public-data.geolonia.com/mlit-ksj-vector-2024/sample-data/N03-20240101/N03-20240101.pmtiles#map=3.79/38.46/132.29)

[GeoPackage 形式](https://public-data.geolonia.com/mlit-ksj-vector-2024/sample-data/N03-20240101/N03-20240101.gpkg) 263MB

参考：[国土数値情報ダウンロードサイト「行政区域データ」](https://nlftp.mlit.go.jp/ksj/gml/datalist/KsjTmplt-N03-2024.html)


### W05_河川データ_2009年度～2006年度(平成21年度～平成18年度) （ライン）
[GeoJSON 形式](https://public-data.geolonia.com/mlit-ksj-vector-2024/sample-data/W05/W05-Stream.geojson) 633MB

[FlatGeobuf 形式](https://public-data.geolonia.com/mlit-ksj-vector-2024/sample-data/W05/W05-Stream.fgb) 300MB

[GeoParquet 形式](https://public-data.geolonia.com/mlit-ksj-vector-2024/sample-data/W05/W05-Stream.parquet) 243MB

[GeoArrow 形式](https://public-data.geolonia.com/mlit-ksj-vector-2024/sample-data/W05/W05-Stream.arrow) 244MB

[PMTiles 形式](https://public-data.geolonia.com/mlit-ksj-vector-2024/sample-data/W05/W05-Stream.pmtiles) 73.2MB　[PMTiles Viewerで見る](https://pmtiles.io/?url=https://public-data.geolonia.com/mlit-ksj-vector-2024/sample-data/W05/W05-Stream.pmtiles#map=9.85/35.702/139.7491)

[GeoPackage 形式](https://public-data.geolonia.com/mlit-ksj-vector-2024/sample-data/W05/W05-Stream.gpkg) 349MB

参考：[国土数値情報ダウンロードサイト「河川データ」](https://nlftp.mlit.go.jp/ksj/gml/datalist/KsjTmplt-W05.html)

※「河川データ」は、ラインデータとポイントデータが提供されていますが、サンプルファイルにはラインデータのみを格納しています。
