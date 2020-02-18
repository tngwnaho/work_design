
## 有償・無償のgeocoding apiまとめ
https://developer.ntt.com/ja/blog/b3dacc84-ee1e-43d4-85d5-6611e8449da7



## Google map
google map の利用方法と地図APIについて:
https://www.webdesignleaves.com/pr/plugins/googlemap_01.html

google map の料金体型：
月間28,000マップロードまで無償。以降は請求対象
https://developers.google.com/maps/documentation/geocoding/start?hl=ja

必要なもの：
Google アカウント(billingアカウント)



## Yahoo!ジオコーダAPI
無料で使えるけど、非商用目的じゃないと利用できない

URL:
https://developer.yahoo.co.jp/webapi/map/openlocalplatform/v1/geocoder.html

料金体系：
●基準
利用回数の計測はリクエストに付与されたアプリケーションIDを基準にしています。

●計測期間
利用回数は1日あたりで計測されます。毎日、午前0:00にすべてのアプリケーションIDのリクエスト回数は0回にリセットされ、再び計測が開始されます。

●リクエスト回数の計測方法
上限回数は通常、1アプリケーションIDごとに1日50000回です。ただし、Web APIによってはこれよりも少なく設定されていることがあります。この回数はWeb APIごとではなく、アプリケーションIDごとに計測される総リクエスト回数を基準にします。


## mapfan
URL:
http://business.mapfan.com/purpose/geocording.php

料金体系：
基本有料。
法人向けにMapFan APIを月間上限5000PVの範囲内で利用可能らしい
http://business.mapfan.com/api_free_plan/

## openstreetmap関連のapi
openstreetmapは無償で使えるが、基本的に提供されているUIも精度もあまりよくない

### leaflet
精度が悪い。。
https://github.com/Esri/esri-leaflet-geocoder/

### Nominatim
地図UIが好みにあっているのであれば、いいかも。
https://nominatim.openstreetmap.org/search.php?q=%E6%96%B0%E5%AE%BF%E3%83%9F%E3%83%A9%E3%82%A4%E3%83%8A%E3%82%BF%E3%83%AF%E3%83%BC&polygon_geojson=1&viewbox=
