# Build Guide

![cocot46plus_main15](https://user-images.githubusercontent.com/88039287/171889114-53163c9f-4ef2-492d-b12b-7b6a23578bdf.jpg)


cocot46plusのビルドガイドになります。
cocot46plusは中央に34mmトラックボールを備えていることが一つの特徴です。
また親指キーの中央にロータリーエンコーダを配置しており、ホームポジションを崩すことなく両手の親指でエンコーダの操作が可能となっています。
中央奥側にはOLEDには現在のレイヤー情報、トラックボールのステータス（CPIや回転軸の角度など）を表示することができます。
その他オプションとしてアクリル積層ケースを用意しているので、お好みに合わせて実装ください。

v1のビルドガイドはこちら（[JP](v1/buildguide.md) / [EN](v1/buildguide_en.md)）を参照してください。

## 部品
### キット付属品

|![Switch_Plate](https://user-images.githubusercontent.com/88039287/171806873-68054a1a-36d1-4915-b93d-127a05854126.jpg)|![PCB_v2](https://user-images.githubusercontent.com/88039287/205923168-0d0df27b-0a3f-4af9-aba0-c3d1f32002cb.jpg)|![Bottom_Acryl_v2](https://user-images.githubusercontent.com/88039287/205923519-edbd1ccf-e472-47fe-9218-6a58ee6ed255.jpg)|![Bottom_FR4](https://user-images.githubusercontent.com/88039287/171806984-461ad017-8711-4a60-9600-2489366fadf8.jpg)|
|---|---|---|---|
|スイッチプレート（FR4）×1枚|実装済基板×1枚|ボトムプレート➀（アクリル）×1枚（販売時期によってデザインが異なる場合があります）|ボトムプレート➁（FR4）×1枚|
|![OLED_Cover](https://user-images.githubusercontent.com/88039287/171806991-c0f1b51d-bc91-48cc-b005-a78fb0f66c97.jpg)|![Spacer_8mm_v2](https://user-images.githubusercontent.com/88039287/205923668-0045b034-09db-4351-b71f-80b6741854bf.jpg)|![Spacer_3mm_FF](https://user-images.githubusercontent.com/88039287/205923846-4c8c07bf-3499-4b40-b7f3-590df1d3d88a.jpg)|![Screw_3mm](https://user-images.githubusercontent.com/88039287/170508488-f9c20e9d-b73d-4815-877d-80143e98b4a0.jpg)|
|OLEDカバープレート（FR4）×1枚|M2 スペーサー 長（メス―メス）×15本|M2 スペーサー 短（メス―メス）×4本|M2 ねじ 短×19本|
|![Screw_5.5mm](https://user-images.githubusercontent.com/88039287/170508494-bdf5d0af-b931-436f-9bb0-2520529e32d8.jpg)|![Screw_8mm](https://user-images.githubusercontent.com/88039287/170508513-d78bf413-0ffd-4d2b-af5c-ba677e04bc4d.jpg)|![ProMicro](https://user-images.githubusercontent.com/88039287/205924543-1c8691dd-91f6-43c3-93bc-d67ae7ede338.jpg)|![Spring_Pin_Header](https://user-images.githubusercontent.com/88039287/205924750-1ca4d9c8-7dff-472f-9edc-4af409c95afc.jpg)|
|M2 ねじ 中×15本|M2 ねじ 長×4本|ProMicro×1個|コンスル―×2本|
|![ADNS5050](https://user-images.githubusercontent.com/88039287/169820156-9035cbba-5442-4802-9604-11034021dc22.jpeg)|![OLED](https://user-images.githubusercontent.com/88039287/169819901-5ce452c8-a375-4aa5-b7b8-a138fdbe6984.jpeg)|![ResetSwitch](https://user-images.githubusercontent.com/88039287/169819952-702c3c93-5d5c-447f-826e-60da1ef909b2.jpeg)|![ゴム足](https://user-images.githubusercontent.com/88039287/169814183-75fbffd8-37b3-4ab7-a23b-17e0d72b70cd.jpg)|
|マウスセンサー（ADNS-5050）・レンズ×各1個|OLEDモジュール・ピンソケット・ピンヘッダ×各1個|タクトスイッチ×1個|ゴム脚×6個|
|![RotaryEncoder](https://user-images.githubusercontent.com/88039287/169816718-450c08e5-dff6-49ae-8aa3-451d7397d9e2.jpg)|![SK6812MINI-E](https://user-images.githubusercontent.com/88039287/169815407-b250e15f-a0f6-411f-9e6a-54aa07cd5fa0.jpg)|![Ballcase_34mm_v2](https://user-images.githubusercontent.com/88039287/205925687-38856b6a-9717-4b2f-9e98-5a3fbe8132b8.jpg)||
|ロータリーエンコーダ（EC12互換）×1個|ノブ×1個|ボールケース×1個（＋セラミックボール×3個）||

### キット以外に必要なもの

下記パーツは[遊舎工房](https://shop.yushakobo.jp/)、[TALP KEYBOARD](https://talpkeyboard.net/)、[Daily Craft Keyboard](https://shop.dailycraft.jp/)などで揃えることが可能です。また、22mm径ノブは[へちょあまの工房＠たねやつ支店](https://booth.pm/ja/items/3944829)での品揃えが豊富です。

|名前|数|備考|
|---|---|---|
|USB-TypeCケーブル|1本||
|キースイッチ|46個|MX互換|
|キーキャップ（1U）|46個|MX互換|
|34mmボール|1個||

各ショップの在庫状況に応じて検討ください。


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


### 1. ProMicro

  ProMicroの準備をします。写真の向きでコンスル―をはんだ付けします。  
  コンスル―には向きがあるので注意してください。コンスル―の向きについては[こちら](https://yushakobo.zendesk.com/hc/ja/articles/360044233974-%E3%82%B3%E3%83%B3%E3%82%B9%E3%83%AB%E3%83%BC-%E3%82%B9%E3%83%97%E3%83%AA%E3%83%B3%E3%82%B0%E3%83%94%E3%83%B3%E3%83%98%E3%83%83%E3%83%80-%E3%81%AE%E5%8F%96%E3%82%8A%E4%BB%98%E3%81%91%E6%96%B9%E3%82%92%E6%95%99%E3%81%88%E3%81%A6%E4%B8%8B%E3%81%95%E3%81%84)を参照ださい。  
  遊舎工房で販売のキットにはマイクロUSB版が付属していますが、USB Type-C版のProMicroにも対応しています。マイクロUSBの場合、USBコネクタがもげやすいので、適宜補強をしてからはんだ付けを行ってください。
  **Elite-Cには対応していません。ご注意ください。**

  ![cocot46plus_bg_01_1](https://user-images.githubusercontent.com/88039287/170452185-4f523c38-248c-4b8d-87d4-889d6da17bf8.jpg)

### 2. マウスセンサー（ADNS-5050）

  マウスセンサー（ADNS-5050）を基板裏面から写真の向きに設置し、表面からはんだ付けを行います。シルクの●●印と基板の●●印の位置が合うように注意してください。  
  ![cocot46plus_bg_02_1](https://user-images.githubusercontent.com/88039287/205928430-625ecfc4-35e9-42b1-a5d7-df5b4f9352da.jpg)

  センサーの脚がしっかり奥まで入った状態で、浮かないようにマスキングテープなどで固定します。  
  ![cocot46plus_bg_02_2](https://user-images.githubusercontent.com/88039287/205928575-54091156-6ef4-40b5-aeb5-85ed4f3a069a.jpg)

  表面から8本の脚をはんだ付けします。センサーに貼られているテープもこのタイミングではがしておきます。  
  テープをはがしたらセンサーを取り付け、マスキングテープなどで軽く固定しておきます。
  ![cocot46plus_bg_02_3](https://user-images.githubusercontent.com/88039287/205928856-9a40670c-a4d4-49a2-89fb-7ac671164bfb.jpg)

### 3. OLED

  OLEDピンソケットを表側から挿し、マスキングテープなどで固定します。  
  ![cocot46plus_bg_03_1](https://user-images.githubusercontent.com/88039287/170467680-c5bf1d65-fe7e-406b-a933-91ee3e93b58d.jpg)

  ![cocot46plus_bg_03_2](https://user-images.githubusercontent.com/88039287/170467910-3b9ef4bc-dfab-4c57-ae40-404f63fd76a6.jpg)

  基板裏側からピンソケットの脚4本のはんだ付けを行ってください。  
  ![cocot46plus_bg_03_3](https://user-images.githubusercontent.com/88039287/170468810-e113a686-0350-4d38-ba71-02273a7c83d9.jpg)


  OLEDモジュールにピンヘッダを通し、斜めにならないように1本ずつはんだ付けを行います。  
  ![cocot46plus_bg_03_4](https://user-images.githubusercontent.com/88039287/170474570-298a2c45-4f1e-40e6-a35a-7291a0f67d20.jpg)


### 4. タクトスイッチ

  PCB表面に、タクトスイッチ（リセットスイッチ）を取り付け、裏面からはんだ付けします。1箇所のみです。  
  ![cocot46plus_bg_04_1](https://user-images.githubusercontent.com/88039287/170474668-4fefb8fe-1c71-49c3-8657-79d88a92d53a.jpg)


### 5. ロータリーエンコーダ

  中央部分にロータリーエンコーダをはんだ付けします。ロータリーエンコーダの脚を通し、裏側からはんだ付けをしてください。  
  ![cocot46plus_bg_05_1](https://user-images.githubusercontent.com/88039287/170474731-cd817ef7-662f-4d09-a309-c73f993b37d9.jpg)

  ![cocot46plus_bg_05_2](https://user-images.githubusercontent.com/88039287/170474739-0a417432-8ab3-463f-8600-5ee963c2c427.jpg)


  全てのパーツを付け終わった状態です。  
  ![cocot46plus_bg_09_3](https://user-images.githubusercontent.com/88039287/170474753-b494944c-e7c3-4953-a648-0b03a9f9392f.jpg)

  ![cocot46plus_bg_09_4](https://user-images.githubusercontent.com/88039287/170474767-5a647ab8-ec9e-475e-a5a2-dbfa7f804846.jpg)


### 6. ボールケース

  ボールケースにセラミックボールを固定します。キット内容物以外に必要な道具は下記写真の通り、エポキシ2液混合接着剤、接着剤を取り出す容器、爪楊枝になります。  
  ![cocot46plus_bg_ballcase_01](https://user-images.githubusercontent.com/88039287/226820854-839753fa-50cc-49b4-b183-860b4672632e.jpg)

  接着剤の取り扱い説明に沿って接着液の準備を行います。  
  ![cocot46plus_bg_ballcase_02](https://user-images.githubusercontent.com/88039287/226820885-08b87789-22ed-47b8-828b-e8ba3df3491b.jpg)

  爪楊枝の先端に接着剤を少量付け、ボールケース内側の穴に塗ります。塗りすぎるとボールを嵌めた際にあふれてしまうので、窪みの内側が接着剤で薄く覆われる程度を目安としてください。  
  ![cocot46plus_bg_ballcase_03](https://user-images.githubusercontent.com/88039287/226820905-af0f3451-a6f7-4ecd-a42f-e3e1407a0052.jpg)

  ![cocot46plus_bg_ballcase_04](https://user-images.githubusercontent.com/88039287/226820925-2cb8de68-cb62-473e-a874-141fe15a1e09.jpg)

  接着剤が乾く前にボールをはめ込みます。接着剤がボールの周りにあふれてしまった場合は固まる前にきれいにふき取ってください。  
  ![cocot46plus_bg_ballcase_05](https://user-images.githubusercontent.com/88039287/226820957-14e5d2f1-9693-4ec7-9fb0-9a6081d463f8.jpg)

  3箇所すべてボールを接着すればボールケースの準備完了です。  
  ![cocot46plus_bg_ballcase_06](https://user-images.githubusercontent.com/88039287/226821043-05606c8c-6c40-4bf9-b368-8b84e1a0726b.jpg)


### 7. 組み立て

  ボトムプレート（アクリル）にネジ（中）でスペーサー（長）を固定します。  
  ![cocot46plus_bg_06_1](https://user-images.githubusercontent.com/88039287/205934015-431b887f-fd0d-40d4-b0bf-02f9964ecb81.jpg)

  ボトムプレート（FR4）をアクリルの裏側（底側）に重ね、ネジ（中）でスペーサー（短）を固定します。  
  ![cocot46plus_bg_06_2](https://user-images.githubusercontent.com/88039287/205934028-446aadb9-f03d-4a19-ae9d-2ac39559edea.jpg)

  基板上にネジ（短）でスペーサー（長）を固定します。またOLEDもピンソケットに差し込んでおきます。  
  ![cocot46plus_bg_06_3](https://user-images.githubusercontent.com/88039287/205934032-a689959e-0b9f-4001-9387-ce7409df19cc.jpg)

  スイッチプレートと基板を重ね、隅から順番にキースイッチをはめていきます。スイッチの向きに気を付けて、またスイッチの脚が曲がらないように真っすぐに差し込むようにしてください。  
  ![cocot46plus_bg_06_4](https://user-images.githubusercontent.com/88039287/205934037-4123abfe-0369-4e0a-9713-bccfb9d39769.jpg)

  全てのキースイッチを差し込んだ状態です。  
  ![cocot46plus_bg_06_5](https://user-images.githubusercontent.com/88039287/205934041-a6fbafed-bcc7-4e55-8cde-c2ce420c99fb.jpg)

  スイッチプレートをネジ（短）で固定します。  
  ![cocot46plus_bg_06_6](https://user-images.githubusercontent.com/88039287/205934044-4b17c40b-ce43-4e9d-a252-cd5f5901d65e.jpg)

  OLEDカバープレートをネジ（短）で固定します。  
  ![cocot46plus_bg_06_7](https://user-images.githubusercontent.com/88039287/205934047-374ede9c-dae8-497c-85b5-cfe5e0965f46.jpg)

  トラックボールケースに対応するボールを入れ、ネジ（長）で固定します。  
  レンズを仮固定していたマスキングテープはこのタイミングではがしてください。
  ![cocot46plus_bg_06_8](https://user-images.githubusercontent.com/88039287/205934052-3c2713a3-a65e-45e9-ba27-4bff50542380.jpg)

  ボトムプレートにバランスよくゴム脚を貼り付けます。  
  ![cocot46plus_bg_06_9](https://user-images.githubusercontent.com/88039287/205934053-211ffc1a-3bb6-4b60-98f0-48205c640b42.jpg)

  お好みのキーキャップ、ロータリーエンコーダのノブを付けて完成です！
  ![cocot46plus_bg_06_10](https://user-images.githubusercontent.com/88039287/205934057-ae4e05d5-e91a-4d3b-a659-67fa307f5c2b.jpg)


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

ソースコードは[こちら](https://github.com/aki27kbd/qmk_firmware/tree/master/keyboards/aki27/cocot46plus)を参照ください。  
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

  REMAPでカスタムキーコードを設定する場合は下記の画面からカスタムキーコードを設定可能です。
  ![CustomKeycode_rev](https://user-images.githubusercontent.com/88039287/200452631-9aac13d4-22e4-45f8-866a-a6e3093cbaf8.jpg)


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


## Links

  [【トラックボール】cocot46plus【自作キーボード】](https://www.youtube.com/watch?v=U7nu5G_PX5Y) (by 椎葉さん)  
  トラックボールの使い心地、内部構造、適合するボール色など紹介いただいています。

  [Gallery on Twitter](https://twitter.com/search?q=%23cocot46plus&src=typed_query&f=image)

## 終わりに
何かトラブルがあれば[Twitterアカウント](https://twitter.com/aki27kbd)までご連絡ください。

また、完成写真をSNSにアップいただけるととても励みになります。（アップするのがはばかられる方はDMで直接送りつけていただいても構いません。）

ハッシュタグは #cocot46plus です。
