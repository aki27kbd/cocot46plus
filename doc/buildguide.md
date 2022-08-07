# Build Guide

![cocot46plus_main15](https://user-images.githubusercontent.com/88039287/171889114-53163c9f-4ef2-492d-b12b-7b6a23578bdf.jpg)


cocot46plusのビルドガイドになります。
cocot46plusは中央に34mmトラックボールを備えていることが一つの特徴です。
また親指キーの中央にロータリーエンコーダを配置しており、ホームポジションを崩すことなく両手の親指でエンコーダの操作が可能となっています。
中央奥側にはOLEDには現在のレイヤー情報、トラックボールのステータス（CPIや回転軸の角度など）を表示することができます。
その他オプションとしてアクリル積層ケースを用意しているので、お好みに合わせて実装ください。

## 部品
### キット付属品

|![Switch_Plate](https://user-images.githubusercontent.com/88039287/171806873-68054a1a-36d1-4915-b93d-127a05854126.jpg)|![PCB](https://user-images.githubusercontent.com/88039287/170449594-f5357de6-4e08-4077-a050-3e613a48e674.jpg) ![PCB_v2](https://user-images.githubusercontent.com/88039287/175255696-1d310e30-9058-4b14-a484-3ebb340d5741.jpg)|![Bottom_Acryl](https://user-images.githubusercontent.com/88039287/170622426-63cfeaea-aa0a-4e17-b10a-165db2cff906.jpg)|![Bottom_FR4](https://user-images.githubusercontent.com/88039287/171806984-461ad017-8711-4a60-9600-2489366fadf8.jpg)|
|---|---|---|---|
|スイッチプレート（FR4）×1枚|実装済基板×1枚（販売時期によってタブがついている場合があります）|ボトムプレート➀（アクリル）×1枚（販売時期によってデザインが異なる場合があります）|ボトムプレート➁（FR4）×1枚|
|![OLED_Cover](https://user-images.githubusercontent.com/88039287/171806991-c0f1b51d-bc91-48cc-b005-a78fb0f66c97.jpg)|![Spacer_8mm](https://user-images.githubusercontent.com/88039287/170515649-114cee4e-3dec-4465-a310-c989946c1a42.jpg)|![Spacer_6mm](https://user-images.githubusercontent.com/88039287/170515641-9056cd4a-f58b-4ec7-a39d-e395ed9dab3d.jpg)|![Spacer_3mm](https://user-images.githubusercontent.com/88039287/170515631-8b3ecdaf-416b-4bc4-814a-b78e2ecb9564.jpg)|
|OLEDカバープレート（FR4）×1枚|M2 スペーサー 8mm（メス―メス）×15本|M2 スペーサー 6mm（メス―メス）×4本|M2 スペーサー 3mm（メス―オス）×4本|
|![Screw_3mm](https://user-images.githubusercontent.com/88039287/170508488-f9c20e9d-b73d-4815-877d-80143e98b4a0.jpg)|![Screw_5mm](https://user-images.githubusercontent.com/88039287/170508494-bdf5d0af-b931-436f-9bb0-2520529e32d8.jpg)|![Screw_8mm](https://user-images.githubusercontent.com/88039287/170508513-d78bf413-0ffd-4d2b-af5c-ba677e04bc4d.jpg)|![SwitchSocket](https://user-images.githubusercontent.com/88039287/169816640-7a40ab51-2435-484f-a2ad-c020c374494e.jpg)|
|M2 ねじ 3mm×19本|M2 ねじ 5mm×15本|M2 ねじ 8mm×4本|MX互換スイッチ用PCBソケット×46個|
|![ADNS5050](https://user-images.githubusercontent.com/88039287/169820156-9035cbba-5442-4802-9604-11034021dc22.jpeg)|![SensorLED](https://user-images.githubusercontent.com/88039287/169820117-6e0fe2ec-c245-4c5a-a4a0-493fbcde3c55.jpeg)|![OLED](https://user-images.githubusercontent.com/88039287/169819901-5ce452c8-a375-4aa5-b7b8-a138fdbe6984.jpeg)|![ResetSwitch](https://user-images.githubusercontent.com/88039287/169819952-702c3c93-5d5c-447f-826e-60da1ef909b2.jpeg)|
|マウスセンサー（ADNS-5050）・レンズ×各1個|マウスセンサー用LED×1個|OLEDモジュール・ピンソケット・ピンヘッダ×各1個|タクトスイッチ×1個|
|![RotaryEncoder](https://user-images.githubusercontent.com/88039287/169816718-450c08e5-dff6-49ae-8aa3-451d7397d9e2.jpg)|![SK6812MINI-E](https://user-images.githubusercontent.com/88039287/169815407-b250e15f-a0f6-411f-9e6a-54aa07cd5fa0.jpg)|![ゴム足](https://user-images.githubusercontent.com/88039287/169814183-75fbffd8-37b3-4ab7-a23b-17e0d72b70cd.jpg)||
|ロータリーエンコーダ（EC12互換）×1個|フルカラーシリアルLED (SK6812MINI-E)×2個|ゴム足×6個||

### ボールケース付属品

|![Ballcase_34mm](https://user-images.githubusercontent.com/88039287/171815139-c530fdfb-a4dc-42fb-ba31-a66bc673ff44.jpg)|![Ballcase_25mm](https://user-images.githubusercontent.com/88039287/171815132-bf7c2f25-3ba6-4d81-811f-e86ddecdd764.jpg)|
|---|---|
|34mmボールケース（上・下）×1個|25mmボールケース（上・下）・25mmボール×1個|


### キット以外に必要なもの

下記パーツは[遊舎工房](https://shop.yushakobo.jp/)、[TALP KEYBOARD](https://talpkeyboard.net/)、[Daily Craft Keyboard](https://shop.dailycraft.jp/)などで揃えることが可能です。また、22mm径ノブは[へちょあまの工房＠たねやつ支店](https://booth.pm/ja/items/3944829)での品揃えが豊富です。

|名前|数|備考|
|---|---|---|
|MicroUSB or USB-TypeCケーブル|1本||
|ProMicro|1個||
|コンスル―（2.5mm×12ピン）|2本||
|キースイッチ|46個|MX互換|
|キーキャップ（1U）|46個|MX互換|
|ロータリーエンコーダ用ノブ|1個|最大直径22mm以下|
|34mmボール|1個|34mmボールケースを選択した場合|

各ショップの在庫状況に応じて検討ください。

※34mmボールの色に応じてセンサーの反応が悪くなる場合があります。  
※デフォルトで反応の悪いボール色も後述の[オプションMOD](https://github.com/aki27kbd/cocot46plus/blob/main/doc/buildguide.md#%E3%82%AA%E3%83%97%E3%82%B7%E3%83%A7%E3%83%B3mod)を施すことで、スムーズに反応するようになります。
※[2022/8/8追記] ver1.1以降の基板では、予め[オプションMOD](https://github.com/aki27kbd/cocot46plus/blob/main/doc/buildguide.md#%E3%82%AA%E3%83%97%E3%82%B7%E3%83%A7%E3%83%B3mod)が施された状態になっています。デフォルトのままでグリーン、ブラックなどの暗い色のボールの反応も改善されています。

|反応性|色|
|---|---|
|〇（スムーズに動作可能）|レッド、パープル、シルバー、ゴールド、グレー、イエロー、ピンク、ラベンダー|
|△（LEDの角度によって少し反応が悪くなる場合あり）|ブルー、グリーン|
|×（反応しないorカクつく）|ブラック|


### オプション部品（アクリル積層ケース）

アクリルは遊舎工房やAnymanyなどのレーザーカットサービスでお好きな色のアクリルプレートを発注することが可能です。

シリコンシートは[こちら](https://www.monotaro.com/p/3629/5253/)から購入可能です。

|名前|数|備考|
|---|---|---|
|アクリルミドルプレート（上）|1枚|アクリル積層ケース用|
|アクリルミドルプレート（下）|1枚|アクリル積層ケース用|
|シリコンシート厚さ0.5mm|1枚|アクリル積層ケース用|



## 組み立て
### 0. 部品確認

  まずはキット付属品に記載されたパーツが揃っているか確認ください。  
  その他上述の「キット以外に必要なもの」および「オプション部品」を揃えた上で組み立てに取り掛かってください。

  - タブ付きPCBの場合にはタブを割って切り離し、切断面を軽くヤスリがけしてください。
  - PCB、スイッチプレートの側面を油性マジックなどで黒く塗ると見栄えが良くなります。ぜひ試してみてください。

  上:塗装済み / 下:未塗装  
  ![cocot46plus_bg_00](https://user-images.githubusercontent.com/88039287/175265959-04c136b7-71fc-4a8b-9bb1-c0b58ec9184f.jpg)


### 1. ダイオード

  ver1.0以降は予め基板にはんだ付けされているので、ダイオードのはんだ付けは不要です。


### 2. インジケータLED

  ProMicro横の2箇所にインジケータLEDのはんだ付けを行います。4箇所あるパッドの1箇所に予備はんだを盛り、LEDの位置を固定します。PCBのシルク上の角の部分と、LEDの三角に欠けている部分の向きが揃うようにはんだ付けしてください。LEDは非常に熱に弱いので、はんだごての温度を低めに設定し、一か所はんだ付けをしたら十分時間をおいてから次のはんだ付けを行いましょう。  
  この段階で後述のファームウェアを準備し、LEDの点灯を一つずつ確認しながらはんだ付けを行うとミスの早期発見につながります。
  ※デフォルトのファームウェアでは、レイヤー0ではインジケータLEDが点灯しません。点灯確認の際はSW39もしくはSW44のパッドをピンセットなどで短絡させ、レイヤー移動した状態で確認ください。

  ![cocot46plus_bg_02_1](https://user-images.githubusercontent.com/88039287/170450128-7bccdcf2-7e3d-40a5-97e1-0080989e8aac.jpg)

  ![cocot46plus_bg_02_2](https://user-images.githubusercontent.com/88039287/170451293-cf59e7ae-fea7-4a7d-95c5-4da1931f9df6.jpg)


### 3. アンダーグロウLED

  ver1.0以降は予め基板にはんだ付けされているので、アンダーグロウLEDのはんだ付けは不要です。


### 4. ProMicro

  ProMicroの準備をします。写真の向きでコンスル―をはんだ付けします。  
  コンスル―には向きがあるので注意してください。コンスル―の向きについては[こちら](https://yushakobo.zendesk.com/hc/ja/articles/360044233974-%E3%82%B3%E3%83%B3%E3%82%B9%E3%83%AB%E3%83%BC-%E3%82%B9%E3%83%97%E3%83%AA%E3%83%B3%E3%82%B0%E3%83%94%E3%83%B3%E3%83%98%E3%83%83%E3%83%80-%E3%81%AE%E5%8F%96%E3%82%8A%E4%BB%98%E3%81%91%E6%96%B9%E3%82%92%E6%95%99%E3%81%88%E3%81%A6%E4%B8%8B%E3%81%95%E3%81%84)を参照ださい。  
  USB Type-C版のProMicroにも対応しています。マイクロUSBの場合、USBコネクタがもげやすいので、適宜補強をしてからはんだ付けを行ってください。

  ![cocot46plus_bg_04_1](https://user-images.githubusercontent.com/88039287/170452185-4f523c38-248c-4b8d-87d4-889d6da17bf8.jpg)

### 5. マウスセンサー

#### 5-1. ADNS-5050
  マウスセンサー（ADNS-5050）を基板裏面から写真の向きに設置し、表面からはんだ付けを行います。シルクの●●印と基板の●●印の位置が合うように注意してください。  
  ![cocot46plus_bg_05_1](https://user-images.githubusercontent.com/88039287/170453958-e58aca65-1f71-4da0-9e0e-cbbb40e56425.jpg)

  センサーの脚がしっかり奥まで入った状態で、浮かないようにマスキングテープなどで固定します。  
  ![cocot46plus_bg_05_2](https://user-images.githubusercontent.com/88039287/170454505-65b0aa78-7d06-4c31-b2ab-bc4f62f97776.jpg)

  表面から8本の脚をはんだ付けします。  
  ![cocot46plus_bg_05_3](https://user-images.githubusercontent.com/88039287/170454245-9da5e45f-c8a4-41ba-87e1-4c37c676beb9.jpg)

  センサーに貼られているテープを剥がし、表面からレンズを付けてマスキングテープなどで固定します。  
  ![cocot46plus_bg_05_4](https://user-images.githubusercontent.com/88039287/170454912-ce859541-987f-4614-9b10-c68802e6cfbf.jpg)

#### 5-2. センサー用LED

  マウスセンサー用LEDを取り付けます。基板裏面からLEDの脚を通します。脚の長い方を丸い穴、短い方を四角い穴に通します。  
  ![cocot46plus_bg_05_5](https://user-images.githubusercontent.com/88039287/170455005-ff9d7af7-7d88-41b9-badc-025330ba14ea.jpg)

  LEDの脚を90度曲げ、横から見た時に下の写真のような位置関係になるようにマスキングテープなどで固定します。  
  ![cocot46plus_bg_05_5_2](https://user-images.githubusercontent.com/88039287/170455581-06e7b4f3-395c-44a6-93ec-c8fb8e6215e4.jpg)

  表面からLEDの脚を2箇所はんだ付けし、余分な脚をカットします。  
  ![cocot46plus_bg_05_6](https://user-images.githubusercontent.com/88039287/170455780-9cd94127-6efa-4838-9992-78e39cf6972e.jpg)

#### 5-3. ジャンパー

  基板裏面のジャンパーの両側のパッドにはんだを盛り、ブリッジさせます。  
  ![cocot46plus_bg_05_7](https://user-images.githubusercontent.com/88039287/170455922-7b17c4ca-8e60-4abd-8a33-edb597827bff.jpg)

  ![cocot46plus_bg_05_8](https://user-images.githubusercontent.com/88039287/170455929-1655e25f-8b99-49c7-b6f9-6a1d540ee2c3.jpg)

  ここまでの作業が完了したら、ProMicroに後述のファームウェアを書き込み、動作確認を行いましょう。正しい手順を踏めている場合、全部で12個のLEDとマウスセンサー用LEDが点灯しているはずです。  
  ![cocot46plus_bg_05_9a](https://user-images.githubusercontent.com/88039287/170456116-d3602e8f-aa3c-4f3c-8777-1d4b63a35322.jpg)

  表面のレンズの前に手をかざし、マウスカーソルが動いているか確認してみてください。  
  ![cocot46plus_bg_05_9b](https://user-images.githubusercontent.com/88039287/170456125-8737a304-75ed-45ea-8600-f5e00ac87531.jpg)

### 6. MXソケット

  PCB裏面に、写真の向きでソケットをはんだ付けします。**全46箇所**はんだ付けを行ってください。

  ![cocot46plus_bg_06_1](https://user-images.githubusercontent.com/88039287/170466184-43520998-4b82-4081-b9e0-286dcfd2c209.jpg)

### 7. OLED

  OLEDピンソケットを表側から挿し、マスキングテープなどで固定します。  
  ![cocot46plus_bg_07_1](https://user-images.githubusercontent.com/88039287/170467680-c5bf1d65-fe7e-406b-a933-91ee3e93b58d.jpg)

  ![cocot46plus_bg_07_2](https://user-images.githubusercontent.com/88039287/170467910-3b9ef4bc-dfab-4c57-ae40-404f63fd76a6.jpg)

  基板裏側からピンソケットの脚4本のはんだ付けを行ってください。  
  ![cocot46plus_bg_07_3](https://user-images.githubusercontent.com/88039287/170468810-e113a686-0350-4d38-ba71-02273a7c83d9.jpg)


  OLEDモジュールにピンヘッダを通し、斜めにならないように1本ずつはんだ付けを行います。  
  ![cocot46plus_bg_07_4](https://user-images.githubusercontent.com/88039287/170474570-298a2c45-4f1e-40e6-a35a-7291a0f67d20.jpg)


### 8. タクトスイッチ

  PCB表面に、タクトスイッチ（リセットスイッチ）を取り付け、裏面からはんだ付けします。1箇所のみです。  
  ![cocot46plus_bg_08_1](https://user-images.githubusercontent.com/88039287/170474668-4fefb8fe-1c71-49c3-8657-79d88a92d53a.jpg)


### 9. ロータリーエンコーダ

  中央部分にロータリーエンコーダをはんだ付けします。ロータリーエンコーダの脚を通し、裏側からはんだ付けをしてください。  
  ![cocot46plus_bg_09_1](https://user-images.githubusercontent.com/88039287/170474731-cd817ef7-662f-4d09-a309-c73f993b37d9.jpg)

  ![cocot46plus_bg_09_2](https://user-images.githubusercontent.com/88039287/170474739-0a417432-8ab3-463f-8600-5ee963c2c427.jpg)


  全てのパーツを付け終わった状態です。  
  ![cocot46plus_bg_09_3](https://user-images.githubusercontent.com/88039287/170474753-b494944c-e7c3-4953-a648-0b03a9f9392f.jpg)

  ![cocot46plus_bg_09_4](https://user-images.githubusercontent.com/88039287/170474767-5a647ab8-ec9e-475e-a5a2-dbfa7f804846.jpg)


### 10. 組み立て

  To be updated.
  ボトムプレート（アクリル）に5mmネジで8mmスペーサーを固定します。  
  ![cocot46plus_bg_10_1](https://user-images.githubusercontent.com/88039287/171879994-45020675-e3e5-491c-94e8-8f10647011dc.jpg)

  ボトムプレート（FR4）をアクリルの裏側（底側）に重ね、5mmネジで3mmスペーサー（メス―オス）を固定します。  
  ![cocot46plus_bg_10_2](https://user-images.githubusercontent.com/88039287/171880618-86b4a8c0-8a22-49cf-9021-a2281c51c2af.jpg)

  基板上に3mmネジで8mmスペーサーを固定します。またOLEDもピンソケットに差し込んでおきます。  
  ![cocot46plus_bg_10_3](https://user-images.githubusercontent.com/88039287/171881016-c5cdf3c9-ce5d-4273-bb90-fc0c4ebfe5a9.jpg)

  スイッチプレートと基板を重ね、隅から順番にキースイッチをはめていきます。スイッチの向きに気を付けて、またスイッチの脚が曲がらないように真っすぐに差し込むようにしてください。  
  ![cocot46plus_bg_10_4](https://user-images.githubusercontent.com/88039287/171824033-ace5a500-1ddf-48ca-9bd8-ebec2124e5dd.jpg)

  全てのキースイッチを差し込んだ状態です。  
  ![cocot46plus_bg_10_5](https://user-images.githubusercontent.com/88039287/171824021-608cc69b-2f85-4d8a-adb3-41fcdd79617c.jpg)

  スイッチを差し込んだスイッチプレート&基板を、ボトムプレートの上に重ねます。トラックボール廻りの4箇所を6mmスペーサーで固定します。  
  ![cocot46plus_bg_10_6](https://user-images.githubusercontent.com/88039287/171881711-fff519e3-f4d9-43fa-91f1-e2db09ebb302.jpg)

  スイッチプレートを3mmネジで固定します。  
  ![cocot46plus_bg_10_7](https://user-images.githubusercontent.com/88039287/171882199-1ff363c5-eee2-4ed3-8c2b-51cbbfb57c04.jpg)

  OLEDカバープレートを3mmネジで固定します。  
  ![cocot46plus_bg_10_8](https://user-images.githubusercontent.com/88039287/171882865-7f5b7abf-20c2-42ec-9d7b-1b7622fae37d.jpg)

  トラックボールケースに対応するボールを入れ、8mmネジで固定します。  
  ![cocot46plus_bg_10_9](https://user-images.githubusercontent.com/88039287/171883283-fffed352-0f25-4d74-8c89-b18b8e9e8224.jpg)

  ボトムプレートにバランスよくゴム脚を貼り付けます。  
  ![cocot46plus_bg_10_10](https://user-images.githubusercontent.com/88039287/171824584-1361360a-e5be-4d3c-9e66-b0b67770ad55.jpg)

  お好みのキーキャップ、ロータリーエンコーダのノブを付けて完成です！
  ![cocot46plus_bg_10_11](https://user-images.githubusercontent.com/88039287/171824592-1894730f-27d0-466f-840b-9d848abf2791.jpg)


### 11. [オプション]アクリルミドルプレート

  オプションであるアクリル積層ケースの組み立て方についてです。
  下記パーツを揃えた上で積層ケースの組み立てにのぞんでください。

  |名前|数|備考|
  |---|---|---|
  |アクリルミドルプレート（上）|1枚|※1|
  |アクリルミドルプレート（下）|1枚|※1|
  |シリコンシート 厚さ0.5mm|1枚|[こちら](https://www.monotaro.com/p/3629/5253/)から購入可能|


  ※1 遊舎工房のアクリルプレートサービスより、[cocot46plusのミドルプレート](https://shop.yushakobo.jp/collections/services/products/keyboard_acrylic_plate?variant=43940451746023)が選択できるようになりました。こちらからアクリルカラーを選択して発注してください。  
  元データは[こちら](https://github.com/aki27kbd/cocot46plus/blob/main/doc/cocot46plus_middle.zip?raw=true)にあります。オリジナルの積層ケースを作成したい場合などに用いてください。


  シリコンシートのカッティング補助用に、[こちら](https://github.com/aki27kbd/cocot46plus/blob/main/doc/cocot46plus_middle_cutting_sheet.pdf)のシートをダウンロードし、**拡大率100%** で印刷してください。用紙に合わせて印刷してしまうとキースイッチの位置がずれてしまうのでご注意ください。
  印刷した型紙に、保護シートをはがしたシリコンシートを貼り付けます。ねじ部分は後からカットすることが難しいので、この状態で赤い部分のみカットしておきます。デザインナイフやカッターナイフ（30度刃）がカットしやすいと思います。

  赤い部分をカットし終わったら、キースイッチの位置が合うようにミドルアクリルプレート（上）をシリコンシートの上に置き、外形（青線）とキースイッチ部分（灰色線）をカットしていきます。

  ボトムプレート、ミドルプレート（下）PCB、ミドルプレート（上）、スイッチプレートの順に重ねます。

  cocot46の[ビルドガイド](https://github.com/aki27kbd/cocot46/blob/main/doc/buildguide.md#10-%E3%82%A2%E3%82%AF%E3%83%AA%E3%83%AB%E7%A9%8D%E5%B1%A4%E3%82%B1%E3%83%BC%E3%82%B9%E3%82%AA%E3%83%97%E3%82%B7%E3%83%A7%E3%83%B3)も参考に組み立ててみてください。



## ファームウェア

  [REMAP](https://remap-keys.app/catalog/JPk6Ey9xB6yrr5TDqoLh/firmware)からファームウェアのダウンロードおよびProMicroへの書き込みを行うことができます。キーマップは[こちら](https://remap-keys.app/configure)から更新可能です。  
トラックボール、LED含めて上記.hexファイルで確認いただけます。

（.hexファイルをQMK ToolboxなどでProMicroに書き込む従来の方法でも問題ありません。）


![REMAP](https://user-images.githubusercontent.com/88039287/169829273-3694b209-59a6-4906-a8a7-2debab667cdf.jpg)


組み立て段階で動作確認をする際も、REMAPのTest Matrix Modeを使うと便利です。ただし、Test Matrix Modeではロータリーエンコーダの回転は確認できないので、別途キー入力等で動作を試してください。

標準ファームウェアでは、レイヤー1と2でトラックボールの動きがスクロールに変換されるようになっています。スクロールモードになるレイヤーを変更したい場合は、keymap.cを修正してください。

ソースコードは[こちら](https://github.com/aki27kbd/qmk_firmware/tree/master/keyboards/cocot46plus)を参照ください。  
また、VIA用のjsonファイルは[こちら](https://github.com/aki27kbd/cocot46plus/blob/main/firmware/cocot46plus_via.json)を参照ください。


## カスタムキーコード

  トラックボールの操作に関していくつかカスタムキーコードを設定することが可能です。

  Value    | Keycode   |Description
  ---------|-----------|-----------
  `0x5DA7` | `CPI_SW`  |トラックボールのCPIを変更します。デフォルトのファームウェアでは、押すたびに500→750→1000→1250→500…という順番でCPIが変わります。
  `0x5DA8` | `SCRL_SW` |スクロールモードにおけるセンサーの感度を変更します。数値が大きいほどスクロール量が小さくなります。
  `0x5DA9` | `ROT_R15` |マウスセンサーのＹ軸を時計回りに15度回転させます。
  `0x5DAA` | `ROT_L15` |マウスセンサーのＹ軸を反時計回りに15度回転させます。
  `0x5DAB` | `SCRL_MO` |押されている間スクロールモードになります。
  `0x5DAC` | `SCRL_TO` |押すたびにスクロールモードとマウスモードを切り替えます。
  `0x5DAD` | `SCRL_IN` |スクロール方向を反転させます。

  REMAPでカスタムキーコードを設定する場合は下記の画面のようにCUSTOMから上の表のValueを直接入力してください。

  ![CustomKeycode](https://user-images.githubusercontent.com/88039287/169856477-84ebf6bb-9430-44f8-a650-537ab8f0a79b.jpg)


## OLED

  OLEDにはトラックボールの情報を表示することが可能です。  
  ![cocot46plus_bg_oled_1](https://user-images.githubusercontent.com/88039287/170496379-0b8dcec6-afac-48e9-b727-ad647c4a09c9.jpg)

  OLED|Description
  ---------|-----------
  Current Layer|現在のレイヤーを示します。
  Scroll Status|C:カーソル/S:スクロールモードを示します。
  CPI|カーソルモードのCPIを示します。
  Scroll Divider|スクロールモードにおけるセンサーの感度を示します。数値が大きいほどスクロール量が小さくなります。
  Rotation Angle|マウスセンサーのY軸の回転角を示します。

  手の大きさやトラックボールへの手の置き方によって、操作しやすいY軸の回転角が異なります。`ROT_R15`、`ROT_L15`キーで調整しながら自分に合った設定を探してみてください。  
  ![cocot46plus_bg_oled_2_2](https://user-images.githubusercontent.com/88039287/170499867-b430839b-f2f0-4163-afa2-c227184bd697.jpg)

  ![cocot46plus_bg_oled_3_4_5](https://user-images.githubusercontent.com/88039287/171883896-1a3b91cb-84b8-425c-b490-9affa5f42095.jpg)

## オプションMOD

  ※※[2022/8/8追記] ver1.1以降の基板では、予めこちらのオプションMODが施された状態になっています。デフォルトのままでグリーン、ブラックなどの暗い色のボールの反応も改善されています。

  デフォルトの状態では反応の悪いボール色も、少し手を加えることでスムーズに反応するようになります。

  PCB裏面のR1のスルーホール端子部分に小さめの抵抗を付けることでセンサー用LEDの明るさが増し、緑や黒などの暗い色の球でも反応するようになります。

  参考までに、ぺリックス緑球は[300Ω](https://akizukidenshi.com/catalog/g/gR-25301/)、ぺリックス黒球は[150Ω](https://akizukidenshi.com/catalog/g/gR-25151/)で動作確認できています。

  ![cocot46plus_bg_mod_1](https://user-images.githubusercontent.com/88039287/175553271-ab133f23-baa0-479b-8bf1-9814e3324789.jpg)

  ![cocot46plus_bg_mod_2](https://user-images.githubusercontent.com/88039287/175553266-1370696c-3f86-420b-bee9-94a090027a80.jpg)


## Links

  [【トラックボール】cocot46plus【自作キーボード】](https://www.youtube.com/watch?v=U7nu5G_PX5Y) (by 椎葉さん)  
  トラックボールの使い心地、内部構造、適合するボール色など紹介いただいています。

  [Gallery on Twitter](https://twitter.com/search?q=%23cocot46plus&src=typed_query&f=image)

## 終わりに
何かトラブルがあれば[Twitterアカウント](https://twitter.com/aki27kbd)までご連絡ください。

また、完成写真をSNSにアップいただけるととても励みになります。（アップするのがはばかられる方はDMで直接送りつけていただいても構いません。）

ハッシュタグは #cocot46plus です。
