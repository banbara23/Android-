# Android Library Ranking
2015/8/30〜9/4の期間に、 Google Playで公開されてるアプリに使用されてるライブラリを集計してみた

## 概要
2015/8/30〜9/4の期間に、
[Google Play](https://play.google.com/store/apps)で公開されてるアプリに使用されてるライブラリを集計してみた


## 集計方法
- アプリのカテゴリ別の「人気の〜」または「無料トップ」の１〜１０位までのアプリが対象
- エミュレータにアプリをインストールし、ライセンス項目を目視で確認
- アプリにライセンス項目がなければそのアプリはスキップ（時間がなかったので）
- アプリ数は200くらい
- ライブラリ総数は766

## ライブラリ使用回数ランキング
ライブラリの使用回数をカウント

|順位|ライブラリ名|使用アプリ数|
|:-----------:|:------|:--------:|
| 1 | Gson | 23 |
| 2 | OkHttp | 22 |
| 3 | Facebook SDK | 19 |
| 4 | Jackson | 18 |
| 5 | google-breakpad | 16 |
| 5 | Picasso | 16 |
| 6 | Volley | 15 |
| 7 | ViewPagerIndicator | 14 |
| 8 | Guava | 13 |
| 9 | NineOldAndroids | 12 |
| 9 | Twitter4J | 12 |
| 10 | RxJava | 11 |
| 10 | ButterKnife | 11 |
| 11 | Apache Commons | 10 |
| 11 | JSR 305 | 10 |
| 12 | OpenSSL | 9 |
| 13 | Otto | 8 |
| 13 | Android-PullToRefresh | 8 |
| 13 | ZXing | 8 |
| 14 | Retrofit | 7 |
| 14 | DiskLruCache | 7 |
| 14 | StickyListHeaders | 7 |
| 14 | Zlib | 7　|
| 14 | RxAndroid | 7 |
| 14 | PagerSlidingTabStrip | 7 |
| 14 | Jakarta Commons Logging | 7 |
| 15 | PhotoView | 6 |
| 15 | ActionBarSherlock | 6 |
| 15 | EventBus | 6 |
| 15 | Dagger | 6 |

## アプリ別 使用ライブラリ数ランキング

|順位|アプリ名|使用ライブラリ数|
|:-----------:|:------|:--------:|
|1| Chromeブラウザ | 174|
|2| Facebook、メッセンジャー | 153|
|3| Google フォト| 47|
|4| AWA| 28|
|5| EverNote  |27|
|5| MERY  |27|
|6| Instagram |25|
|6| Path  |25|
|7| クックパッド  |24|
|7| Snapchat  |24|
|7| LINE |24|
|8| Squareレジ  |23|
|9| NARUTO-ナルト- 無料マンガ連載 |22|
|10| 家計簿Dr.Wallet  |21|
|11| 少年ジャンプ  |20|
|11| ONE PIECE 無料連載公式アプリ |20|
|12| MX Player |19|
|13| フリル - ファッションフリマアプリ  |18|
|13| OfficeSuite 8 + PDF Converter |18|
|14| Shazam  |17|
|15| フリマアプリ「メルカリ」  |16|
|16| Polaris Office |15|
|16| グノシー  |15|
|16| ツイキャス・ビューワー |15|
|17| SoundCloud  |14|
|17| Twitter| 14|
|17| WPS Office + PDF |14|
|18| ホットペッパー グルメ |13|
|18|  Tumblr |13|
|18| icoron |13|
|19| GYAO!  |12|
|19| We Heart It |12|
|20| TRILL |11|
|20| マンガボックス |11|
|20| Yahoo!ショッピング |11|
|20| スポナビ プロ野球速報2015 |11|

## 感じたこと
- オシャレなアプリでも、ライセンス画面が雑だと少しアプリイメージが下がる
- スポーツカテゴリは全体的にアプリがショボい
- ベネッセはUIがショボすぎ
- Google Mapはライセンスが長すぎて諦めた
- Photo Shop Expressはライセンスリンクをおすと、pdfで百ページ以上が表示された
- マテリアルデザインはまだ全然使われていない事も分かった（全体の２〜３割）
- カテゴリ別にアプリの雰囲気が全然違う
    - 音楽やソーシャルネットワークはオシャレ
    - スポーツと医療は古臭い

## 感想
- 初めて知るライブラリが多く、勉強になった
- 実際にアプリを触ることでUIの勉強にもなった
- AndroidなのにiOSライブラリが載ってるアプリもあって面白い
  - icoronというアプリにAFNetworkingやMBProgressHUDが…

以上です。
