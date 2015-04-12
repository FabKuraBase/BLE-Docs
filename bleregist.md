# Bluetooth認証

## Bluetooth SIGについて
自社製品およびサービスに Bluetooth 技術を使用、自社商品とサービスの提供に Bluetooth ブランドを活用、または
Bluetooth 技術を使用する製品を再ブランド化または再販売する企業は、Bluetooth SIGへ加入しなければならない。<br>

Bluetooth SIG のアダプターメンバーとして、直ちに以下を獲得できる

* Bluetooth 無線技術を使って製品を開発する許可
* Bluetooth ワードマークと Bluetooth Smart および Bluetooth Smart Ready ロゴを認証されて登録された製品で使用する許可
* 多種多様な業界の何千社もの Bluetooth SIG メンバーと交流し協力する機会
* プロファイルチューニングスイート供与(試験ツールやテスト仕様)

## Bluetooth認証

Bluetooth搭載のハードウェアを製品化した場合、認証登録(デザイン登録、プロダクト登録)が必要。
売り上げ1億円以上だと8000ドル、設立2年以内で売り上げ1億円以下だと、2500ドルで手続きできる。
Bluetooth関連製品を開発をする場合、BT SIG のメンバーシップになる必要があるが、個人では登録きないので、法人もしくは団体で登録する。

もしBluetoothの認証登録をせずに製品を出荷してしまった場合、BT SIGから警告がいくかもしれない。刑事ではなく、民事等での損害賠償等の可能性も考えられる。

* [認証および登録プロセス](https://www.bluetooth.org/ja-jp/test-qualification/qualification-overview)<br>
* [認証および登録料金](https://www.bluetooth.org/ja-jp/test-qualification/qualification-overview/fees)

一般的に、Bluetooth搭載のハードウェアを製品化し、それが開発者向けではない場合、認証に$8000がかかる。売上1億円以下で設立2年以内の会社には、$2500で、2回まで認証が受けられる特例が設けられている。

## Q2) 開発者向けにBLE開発ボードを作った場合はどうなるか？

開発者が開発評価用に使うなら認証登録はいらない。一方で、最終ユーザに届く可能性がある場合は、認証登録が必要になる。

## Q3) iBeaconを開発した場合はどうなるか？

はじめて登録する場合は、デザイン登録、プロダクト登録が必要となる。Declaration Feeは発生する。

## Q4) BLEモジュールを使ったハードウェアで、ケースを変えた場合はどうなるか？

### Case1
デザイン認証が異なるモジュールを使う場合は、Declaration Feeは発生
### Case2
デザイン認証が同じでも、新たにBT SIG標準プロファイルを追加した派生モデルをプロドダクト登録する場合は、Declaration Feeは発生
### Case3
デザイン認証が同じで、新たに独自のカスタマイズプロファイルを追加する場合は、派生モデルとして、Declaration Feeは発生しない
### Case4
デザイン認証が同じで、プロファイルを追加する場合、派生モデルとして、Declaration Feeは発生しない

## Q5) 一度、認証登録したハードのFirmwareをUpdateした場合はどうなるか？

Update内容に、新たにBT SIG標準プロファイルの追加がない場合は、問題ない。

## Q6) Bluetoothモジュールを使っている場合は、どのような場合、認証登録が必要になるか？

Bluetoothモジュールを使っている場合でも、新しいハードウェアを開発する場合は、デザイン登録、プロダクト登録が必要となる。

# 用語集
| 用語 | 意味 |
| -- | -- |
| BTQF | BT認証をおこなっているBT SIG認定の機関。 |
|BQB | Bluetooth Qualification Bodyの略。Bluetoothのロゴ認証システムの公認判定者。ロゴの取得を申請してきたメーカに対して，その合否を判定する役割を果たす。|
|デザイン認証 | 「チップ＋スタック＋PCB／アンテナ」あるいは、「（それらを含んだ）モジュール」の認証|
|プロダクト認証 | 認証されたデザインを利用した最終製品としての認証。BT SIGの標準プロファイルを利用する場合は、そのプロファイルを「プロファイル・サブシステム」として、認証する（これは、BT SIGより無料でダウンロードできるPTS:Profiule Tunning Suiteを使って自分でテストして、ログを提出する。　独自プロファイルは（GATTベースプロファイル）認証は不要です。|
|QDID|各モジュールのデザイン認証番号（プロダクト登録に必要）|
| PTS| Profile Tuning Suiteの略。標準のプロファイル試験パッケージ|



# 各社モジュールのQDID(デザイン登録ID)
| Chip名 | QDID |
| -- | -- |
| [nRF51x22_QF with updated Sx10 stack](https://www.bluetooth.org/tpg/QLI_viewQDL.cfm?qid=22009) | 51744 |
|[nRF51x22 with Sx10 stack](https://www.bluetooth.org/tpg/QLI_viewQDL.cfm?qid=21495) | 49155 |
| [BLE113 Bluetooth Smart Module](https://www.bluetooth.org/tpg/QLI_viewQDL.cfm?qid=21015)|46266|
| BLE112-A, BLE112-N, BLE112-E|[35451]((https://www.bluetooth.org/tpg/QLI_viewQDL.cfm?qid=18943) |
|DA14580|[56907](https://www.bluetooth.org/tpg/QLI_viewQDL.cfm?qid=22759), [52690](https://www.bluetooth.org/tpg/QLI_viewQDL.cfm?qid=22409), [52696](https://www.bluetooth.org/tpg/QLI_viewQDL.cfm?qid=22410)|

# 国内のBTQF認定機関

* UL
http://site.ul.com/
* テュフ ラインランド ジャパン
http://www.tuv.com/jp/japan/home.jsp
* アリオン株式会社
http://www.allion.co.jp/about.html
* 太陽誘電
http://www.yuden.co.jp/jp/
* Paltek
http://www.paltek.co.jp/