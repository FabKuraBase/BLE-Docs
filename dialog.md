# Dialog系BLEモジュール

## Co-processor
ARM® Cortex™ M0

## 開発者サイト
http://support.dialog-semiconductor.com/

## 開発に必要なハードウェア
### DA14580DEVKT-B
Dialog’s DA14580 Bluetooth® Smart Development Kit - Basic

![](image/da14580_devboard.jpg)

http://dialog-semiconductor.com/products/bluetooth-smart/smartbond-development-tools/bluetooth-smart-development-kit

| 開発キット | 購入先 | 価格|
| -- | -- | -- |
| [DA14580DEVKT-B](http://www.futureelectronics.com/en/technologies/development-tools/rf-wireless/Pages/2046391-DA14580DEVKT-B.aspx?IM=0) | Future Electronics | $99 |
| [DA14580DEVKT-B](http://www.digikey.jp/product-detail/ja/DA14580DEVKT-B/1564-1000-ND/5113983) | Digi-key|13,320円|

## 開発に必要なソフトウェア

| ツール | 提供元 |
| -- | -- |
| [Keil MDK-ARM Version 5](https://www.keil.com/download/product/) | Keil |
| [the Jlink software & documentation pack for Windows](https://www.segger.com/jlink-software.html)|segger|

## 開発に必要なドキュメント

[DA14580DEVKT-BUserGuide](http://www.cdiweb.com/datasheets/iwatt/DA14580DEVKT-BUserGuide.pdf) 


## DA14580搭載モジュール
| チップ名 | メーカー |
|--|--|
|[TypeTZ Datasheet](http://wireless.murata.com/RFM/data/lbca2hnzyz-711.pdf)|murata|
|[PAN1740](http://eu.industrial.panasonic.com/sites/default/pidseu/files/downloads/files/pan1740_flyer.pdf)|Panasonic|

### TypeTZ  Block diagram

![](typeTZ_block.png)

### PAN1740 Block diagram

![](PAN1740_block.png)

### TypeTZメモリなしでのOTA対応
> ![](typeTZ_internal_ota.png)
[Bluetooth Low Energy Module Data Sheet](http://wireless.murata.com/RFM/data/lbca2hnzyz-711.pdf) P15

### TypeTZ SPI FlashメモリでのOTA対応
>![](typeTZ_SPI_flash.png)
[Bluetooth Low Energy Module Data Sheet](http://wireless.murata.com/RFM/data/lbca2hnzyz-711.pdf) P16

### TypeTZ I2C EEPROMでのOTA対応
>![](typeTZ_i2c_eeprom.png)
[Bluetooth Low Energy Module Data Sheet](http://wireless.murata.com/RFM/data/lbca2hnzyz-711.pdf) P17

# 参考になる情報
* [PAN1740設計ガイド](http://www.mouser.jp/pdfdocs/PAN1740DesignGuideRev101.PDF)(Panasonic)
* [Bluetooth Low Energy Module Data Sheet ](http://wireless.murata.com/RFM/data/lbca2hnzyz-711.pdf)(Murata)


