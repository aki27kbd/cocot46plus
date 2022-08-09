# Build Guide

![cocot46plus_main15](https://user-images.githubusercontent.com/88039287/171889114-53163c9f-4ef2-492d-b12b-7b6a23578bdf.jpg)


This is a build guide for cocot46plus.
One feature of cocot46plus is that it has a 34mm trackball in the center.
It also has a rotary encoder in the center between the thumb keys, allowing the encoder to be operated with both thumbs without disrupting the home position.
The OLED at the top can display current layer information and trackball status (CPI, rotary axis angle, etc.).
Other options include an acrylic laminated case, which can be mounted according to your preference.

## Parts
### Kit Accessories

|![Switch_Plate](https://user-images.githubusercontent.com/88039287/171806873-68054a1a-36d1-4915-b93d-127a05854126.jpg)|![PCB](https://user-images.githubusercontent.com/88039287/170449594-f5357de6-4e08-4077-a050-3e613a48e674.jpg) ![PCB_v2](https://user-images.githubusercontent.com/88039287/175255696-1d310e30-9058-4b14-a484-3ebb340d5741.jpg)|![Bottom_Acryl](https://user-images.githubusercontent.com/88039287/170622426-63cfeaea-aa0a-4e17-b10a-165db2cff906.jpg)|![Bottom_FR4](https://user-images.githubusercontent.com/88039287/171806984-461ad017-8711-4a60-9600-2489366fadf8.jpg)|
|---|---|---|---|
|Switch plate (FR4) x 1 piece|Pre-mounted PCB x 1 piece(may have tabs depending on the sales period)|Bottom plate➀ (Acrylic) x 1 piece(design may vary depending on the sales period)|Bottom plate➁ (FR4) x 1 piece|
|![OLED_Cover](https://user-images.githubusercontent.com/88039287/171806991-c0f1b51d-bc91-48cc-b005-a78fb0f66c97.jpg)|![Spacer_8mm](https://user-images.githubusercontent.com/88039287/170515649-114cee4e-3dec-4465-a310-c989946c1a42.jpg)|![Spacer_6mm](https://user-images.githubusercontent.com/88039287/170515641-9056cd4a-f58b-4ec7-a39d-e395ed9dab3d.jpg)|![Spacer_3mm](https://user-images.githubusercontent.com/88039287/170515631-8b3ecdaf-416b-4bc4-814a-b78e2ecb9564.jpg)|
|OLED cover plate (FR4) x 1 piece|M2 spacer 8mm (female - female) x 15pcs|M2 spacer 6mm (female - female) x 4pcs|M2 spacer 3mm (female - male) x 4pcs|
|![Screw_3mm](https://user-images.githubusercontent.com/88039287/170508488-f9c20e9d-b73d-4815-877d-80143e98b4a0.jpg)|![Screw_5mm](https://user-images.githubusercontent.com/88039287/170508494-bdf5d0af-b931-436f-9bb0-2520529e32d8.jpg)|![Screw_8mm](https://user-images.githubusercontent.com/88039287/170508513-d78bf413-0ffd-4d2b-af5c-ba677e04bc4d.jpg)|![SwitchSocket](https://user-images.githubusercontent.com/88039287/169816640-7a40ab51-2435-484f-a2ad-c020c374494e.jpg)|
|M2 Screw 3mm x 19pcs|M2 Screw 5mm x 15pcs|M2 Screw 8mm x 4pcs|Kailh MX Hotswap sockets x 46pcs|
|![ADNS5050](https://user-images.githubusercontent.com/88039287/169820156-9035cbba-5442-4802-9604-11034021dc22.jpeg)|![SensorLED](https://user-images.githubusercontent.com/88039287/169820117-6e0fe2ec-c245-4c5a-a4a0-493fbcde3c55.jpeg)|![OLED](https://user-images.githubusercontent.com/88039287/169819901-5ce452c8-a375-4aa5-b7b8-a138fdbe6984.jpeg)|![ResetSwitch](https://user-images.githubusercontent.com/88039287/169819952-702c3c93-5d5c-447f-826e-60da1ef909b2.jpeg)|
|Mouse sensor (ADNS-5050) and lens x 1 piece|LED for mouse sensor x 1 piece|OLED module, pin socket and pin header x 1 piece|Tact switch x 1 piece|
|![RotaryEncoder](https://user-images.githubusercontent.com/88039287/169816718-450c08e5-dff6-49ae-8aa3-451d7397d9e2.jpg)|![SK6812MINI-E](https://user-images.githubusercontent.com/88039287/169815407-b250e15f-a0f6-411f-9e6a-54aa07cd5fa0.jpg)|![Rubber Feet](https://user-images.githubusercontent.com/88039287/169814183-75fbffd8-37b3-4ab7-a23b-17e0d72b70cd.jpg)||
|Rotary encoder (EC12 compatible) x 1 piece|RGB LED (SK6812MINI-E) x 2 pcs|Rubber feet x 6 pcs||

### Ball Case Accessories

|![Ballcase_34mm](https://user-images.githubusercontent.com/88039287/171815139-c530fdfb-a4dc-42fb-ba31-a66bc673ff44.jpg)|![Ballcase_25mm](https://user-images.githubusercontent.com/88039287/171815132-bf7c2f25-3ba6-4d81-811f-e86ddecdd764.jpg)|
|---|---|
|34mm ballcase (top and bottom) x 1 piece|25mm ballcase (top and bottom) and 25mm ball x 1 piece|


### Additional required parts

The following parts can be obtained from [Yousha Kobo](https://shop.yushakobo.jp/), [TALP KEYBOARD](https://talpkeyboard.net/), [Daily Craft Keyboard](https://shop.dailycraft.jp/), etc. 22mm diameter knobs are available at [Hechoamano Kobo @ Taneyatsu Branch](https://booth.pm/ja/items/3944829).

|Name|Number|Remarks|
|---|---|---|
|MicroUSB or USB-TypeC cable|1 piece||
|ProMicro or compatible microcontroller|1 piece||
|Header pins(2.5mm x 12pin)|2 pcs||
|46 switches|46pcs|MX compatible||
|46 keycaps (1U)|46pcs|MX compatible
|1 rotary encoder knob|1piece|22mm max. diameter or less
|34mm trackball|1piece|34mm ball case if selected|

*Sensor performance depends on the color of the trackball.  
*To improve the sensor performance of other ball colors [a small modification](#Optional-mod) is available.
*[Added on 8/8/2022] For boards with ver1.1 or later, please add the [following mod](#Optional-mod). The default performance is still the same, but the response of balls with darker colors such as green, black, etc. is also improved.

|Reactivity|Color|
|---|---|
|0 (smooth operation possible)|Red, Purple, Silver, Gold, Gray, Yellow, Pink, Lavender|
|△(The angle of the LED may make it a little less responsive)|Blue, Green||
|× (No response or stutter)|Black|


### Optional parts (acrylic case)

Acrylic plates can be ordered with laser cutting services such as Yusha Kobo or Anymany for acrylic plates in your favorite colors.

Silicon sheets can be purchased from [here](https://www.monotaro.com/p/3629/5253/).

|Name|Number|Remarks|
|---|---|---|
|Acrylic middle plate (top)|1|for acrylic case
|Acrylic middle plate (bottom)|1|for acrylic case
|Silicon sheet 0.5mm thick|1|for acrylic case



## Assembly
### 0. Parts Check

  First, check that all the parts listed in the kit accessories are present.  
  Please prepare the kit with the above-mentioned "Additional required parts" and "optional parts" before starting the assembly.

  - If the PCB has tabs, break off the tabs and file the cut surface lightly.
  - Paint the sides of the PCB and switch plate black with an oil-based marker to make them look better. Please give it a try.

  Top: painted / Bottom: unpainted  
  ![cocot46plus_bg_00](https://user-images.githubusercontent.com/88039287/175265959-04c136b7-71fc-4a8b-9bb1-c0b58ec9184f.jpg)


### 1. Diodes

  Since ver1.0 or later, the diodes come pre-soldered on the board, so soldering the diodes is not necessary.


### Indicator LEDs

  Solder the indicator LEDs in two places beside the microcontroller. LEDs are very sensitive to heat, so set the soldering iron to a low temperature and wait long enough after soldering one pin before soldering the next.  
  At this stage, prepare the firmware described below and check the LEDs one by one as you solder, to confirm the leds are properly soldered at an early stage.
  With the default firmware, the indicator LEDs do not light up on the base layer. When checking the lighting, short the SW39 or SW44 pads with tweezers, to perform a layer switch and check the leds.

  ![cocot46plus_bg_02_1](https://user-images.githubusercontent.com/88039287/170450128-7bccdcf2-7e3d-40a5-97e1-0080989e8aac.jpg)

  ![cocot46plus_bg_02_2](https://user-images.githubusercontent.com/88039287/170451293-cf59e7ae-fea7-4a7d-95c5-4da1931f9df6.jpg)


### 3. Underglow LED

  Since ver1.0 or later, the underglow LEDs come pre-soldered on the board, so soldering the underglow LEDs is not necessary.


### 4. Microcontroller

  Prepare the microcontroller. Solder the header pins in the orientation shown in the photo. In this case we are using spring loaded header pins. Note that these have an orientation. For more information about the direction of these pins, see [here](https://yushakobo.zendesk.com/hc/ja/articles/360044233974-%E3%82%B3%E3%83%B3%E3%82%B9%E3%83%AB%E3%83%BC-%E3%82%B9%E3%83%97%E3%83%AA%E3%83%B3%E3%82%B0%E3%83%94%E3%83%B3%E3%83%98%E3%83%83%E3%83%80-%E3%81%AE%E5%8F%96%E3%82%8A%E4%BB%98%E3%81%91%E6%96%B9%E3%82%92%E6%95%99%E3%81%88%E3%81%A6%E4%B8%8B%E3%81%95%E3%81%84)).  
  The USB Type-C version of a ProMicro is also supported. In case of micro USB, please reinforce the USB connector before soldering as it is prone to breaking off.

  ![cocot46plus_bg_04_1](https://user-images.githubusercontent.com/88039287/170452185-4f523c38-248c-4b8d-87d4-889d6da17bf8.jpg)

### 5. mouse sensor

#### 5-1. ADNS-5050
  Place the mouse sensor (ADNS-5050) from the backside of the board in the orientation shown in the photo and solder from the topside. Be careful to align the ●● mark on the silkscreen with the ●● mark on the board.  
  ![cocot46plus_bg_05_1](https://user-images.githubusercontent.com/88039287/170453958-e58aca65-1f71-4da0-9e0e-cbbb40e56425.jpg)

  With the sensor legs firmly in place, secure them with masking tape or other means so that they stay in place.  
  ![cocot46plus_bg_05_2](https://user-images.githubusercontent.com/88039287/170454505-65b0aa78-7d06-4c31-b2ab-bc4f62f97776.jpg)

  Solder the 8 legs from the topside.  
  ![cocot46plus_bg_05_3](https://user-images.githubusercontent.com/88039287/170454245-9da5e45f-c8a4-41ba-87e1-4c37c676beb9.jpg)

  Remove the tape on the sensor, place the lens from the topside and fix it with masking tape, etc.  
  ![cocot46plus_bg_05_4](https://user-images.githubusercontent.com/88039287/170454912-ce859541-987f-4614-9b10-c68802e6cfbf.jpg)

#### 5-2. Sensor LED

  Attach the LED for the mouse sensor. Pass the legs of the LED through the backside of the board. Pass the long leg through the round hole and the short leg through the square hole.  
  ![cocot46plus_bg_05_5](https://user-images.githubusercontent.com/88039287/170455005-ff9d7af7-7d88-41b9-badc-025330ba14ea.jpg)

  Bend the LED legs 90 degrees and fix them with masking tape or similar so that they are positioned as shown in the photo below when viewed from the side.  
  ![cocot46plus_bg_05_5_2](https://user-images.githubusercontent.com/88039287/170455581-06e7b4f3-395c-44a6-93ec-c8fb8e6215e4.jpg)

  Solder two LED legs from the topside and trim the legs with flush cutters.  
  ![cocot46plus_bg_05_6](https://user-images.githubusercontent.com/88039287/170455780-9cd94127-6efa-4838-9992-78e39cf6972e.jpg)

#### 5-3. Jumpers

  Bridge the pads on the back side of the board.
  ![cocot46plus_bg_05_7](https://user-images.githubusercontent.com/88039287/170455922-7b17c4ca-8e60-4abd-8a33-edb597827bff.jpg)

  ![cocot46plus_bg_05_8](https://user-images.githubusercontent.com/88039287/170455929-1655e25f-8b99-49c7-b6f9-6a1d540ee2c3.jpg)

  Once you have completed this step, flash the firmware mentioned below and check the operation. If you have followed the steps correctly, a total of 12 LEDs and the LED for the mouse sensor should be lit.  
  ![cocot46plus_bg_05_9a](https://user-images.githubusercontent.com/88039287/170456116-d3602e8f-aa3c-4f3c-8777-1d4b63a35322.jpg)

  Hold your hand in front of the lens on the top side and check if the mouse cursor is moving.  
  ![cocot46plus_bg_05_9b](https://user-images.githubusercontent.com/88039287/170456125-8737a304-75ed-45ea-8600-f5e00ac87531.jpg)

### 6. MX sockets

  Solder the sockets on the back side of the PCB as shown in the picture. **Solder in all 46 locations**.

  ![cocot46plus_bg_06_1](https://user-images.githubusercontent.com/88039287/170466184-43520998-4b82-4081-b9e0-286dcfd2c209.jpg)

### 7. OLED

  Insert the OLED pin socket from the front side and secure it with masking tape.  
  ![cocot46plus_bg_07_1](https://user-images.githubusercontent.com/88039287/170467680-c5bf1d65-fe7e-406b-a933-91ee3e93b58d.jpg)

  ![cocot46plus_bg_07_2](https://user-images.githubusercontent.com/88039287/170467910-3b9ef4bc-dfab-4c57-ae40-404f63fd76a6.jpg)

  Solder the four pin socket legs from the backside of the board.  
  ![cocot46plus_bg_07_3](https://user-images.githubusercontent.com/88039287/170468810-e113a686-0350-4d38-ba71-02273a7c83d9.jpg)

  Pass the pin headers through the OLED module and solder one by one so that they are not slanted.  
  ![cocot46plus_bg_07_4](https://user-images.githubusercontent.com/88039287/170474570-298a2c45-4f1e-40e6-a35a-7291a0f67d20.jpg)


### 8. Tact switch

  Insert the tact switch (reset switch) from the top side of the PCB and solder from the back side.  
  ![cocot46plus_bg_08_1](https://user-images.githubusercontent.com/88039287/170474668-4fefb8fe-1c71-49c3-8657-79d88a92d53a.jpg)




### 9. Rotary Encoder

  Solder the rotary encoder to the lower center section. Solder the rotary encoder from the back side.  
  ![cocot46plus_bg_09_1](https://user-images.githubusercontent.com/88039287/170474731-cd817ef7-662f-4d09-a309-c73f993b37d9.jpg)

  ![cocot46plus_bg_09_2](https://user-images.githubusercontent.com/88039287/170474739-0a417432-8ab3-463f-8600-5ee963c2c427.jpg)


  All parts are finished being attached.  
  ![cocot46plus_bg_09_3](https://user-images.githubusercontent.com/88039287/170474753-b494944c-e7c3-4953-a648-0b03a9f9392f.jpg)

  ![cocot46plus_bg_09_4](https://user-images.githubusercontent.com/88039287/170474767-5a647ab8-ec9e-475e-a5a2-dbfa7f804846.jpg)


### 10. Assembly

  To be updated.
  Secure the 8mm spacer to the bottom plate (acrylic) with 5mm screws.  
  ![cocot46plus_bg_10_1](https://user-images.githubusercontent.com/88039287/171879994-45020675-e3e5-491c-94e8-8f10647011dc.jpg)

  Place the bottom plate (FR4) over the back side (bottom side) of the acrylic plate and secure the 3mm spacer (female-male) with 5mm screws.  
  ![cocot46plus_bg_10_2](https://user-images.githubusercontent.com/88039287/171880618-86b4a8c0-8a22-49cf-9021-a2281c51c2af.jpg)

  Secure the 8mm spacer on the board with 3mm screws. Also insert the OLED into the pin socket.  
  ![cocot46plus_bg_10_3](https://user-images.githubusercontent.com/88039287/171881016-c5cdf3c9-ce5d-4273-bb90-fc0c4ebfe5a9.jpg)

  Place the switch plate and the board on top of each other and insert the key switches starting from the corners. Be careful to orient the switches and also make sure to insert them straight so that the switch legs do not bend.  
  ![cocot46plus_bg_10_4](https://user-images.githubusercontent.com/88039287/171824033-ace5a500-1ddf-48ca-9bd8-ebec2124e5dd.jpg)

  All keyswitches are inserted.  
  ![cocot46plus_bg_10_5](https://user-images.githubusercontent.com/88039287/171824021-608cc69b-2f85-4d8a-adb3-41fcdd79617c.jpg)

  Place the switch plate & board with the switches inserted on top of the bottom plate. Place 6mm spacers on the 4 places around the trackball.  
  ![cocot46plus_bg_10_6](https://user-images.githubusercontent.com/88039287/171881711-fff519e3-f4d9-43fa-91f1-e2db09ebb302.jpg)

  Secure the switch plate with 3mm screws.  
  ![cocot46plus_bg_10_7](https://user-images.githubusercontent.com/88039287/171882199-1ff363c5-eee2-4ed3-8c2b-51cbbfb57c04.jpg)

  Secure the OLED cover plate with 3mm screws.  
  ![cocot46plus_bg_10_8](https://user-images.githubusercontent.com/88039287/171882865-7f5b7abf-20c2-42ec-9d7b-1b7622fae37d.jpg)

  Put the corresponding ball in the trackball case and secure it with 8mm screws.  
  ![cocot46plus_bg_10_9](https://user-images.githubusercontent.com/88039287/171883283-fffed352-0f25-4d74-8c89-b18b8e9e8224.jpg)

  Attach the rubber feet to the bottom plate as shown.  
  ![cocot46plus_bg_10_10](https://user-images.githubusercontent.com/88039287/171824584-1361360a-e5be-4d3c-9e66-b0b67770ad55.jpg)

  Put on the keycaps of your choice, a rotary encoder knob, and you're done!!!
  ![cocot46plus_bg_10_11](https://user-images.githubusercontent.com/88039287/171824592-1894730f-27d0-466f-840b-9d848abf2791.jpg)


### 11. [Optional] Acrylic middle plate

  This section describes how to assemble the optional acrylic stacked case.
  Please prepare the following parts before assembling the acrylic case.

  |Name|Number|Remarks|
  |---|---|---|
  |1 Acrylic middle plate (top)|1|*1|
  |Acrylic middle plate (bottom)|1|*1|
  |1 silicon sheet 0.5mm thick|1|[click here](https://www.monotaro.com/p/3629/5253/)


  1 From Yuusha Kobo's acrylic plate service, [cocot46plus middle plate](https://shop.yushakobo.jp/collections/services/products/keyboard_acrylic_plate?variant=43940451746023) can be selected. Please select a color from here and place an order.  
  The original files can be found [here](https://github.com/aki27kbd/cocot46plus/blob/main/doc/cocot46plus_middle.zip?raw=true). Please use it when you want to create your own acrylic case.


  For cutting the silicone sheet, download the sheet from [here](https://github.com/aki27kbd/cocot46plus/blob/main/doc/cocot46plus_middle_cutting_sheet.pdf) and print it out at **100% scale**.
  Please note that if you print according to the file, the position of the key switch will be misaligned.
  Attach the silicon sheet with the protective sheet peeled off to the printed pattern paper. Since it is difficult to cut the screw part later, cut only the red part at this state. An exacto knife (30 degree blade) should be helpful here.

  After finishing cutting the red part, place the middle acrylic plate (top) on the silicon sheet so that the key switches are aligned, and cut the outer shape (blue line) and the key switch part (gray line).

  Layer the bottom plate, middle plate (bottom) PCB, middle plate (top), and switch plate in this order.

  Please refer to [Build Guide](https://github.com/aki27kbd/cocot46/blob/main/doc/buildguide.md#10-%E3%82%A2%E3%82%AF%E3%83%AA%E3%83%AB%E7%A9%8D%E5%B1%A4%E3%82%B1%E3%83%BC%E3%82%B9%E3%82%AA%E3%83%97%E3%82%B7%E3%83%A7%E3%83%B3) of cocot46.



## Firmware

  You can download and flash the firmware to the microcontroller from [REMAP](https://remap-keys.app/catalog/JPk6Ey9xB6yrr5TDqoLh/firmware). The keymap can be updated from [HERE](https://remap-keys.app/configure).  
The above .hex file including trackballs and LEDs can be found here.

(You can also write the .hex file to the microcontroller using QMK Toolbox or other tools.)


![REMAP](https://user-images.githubusercontent.com/88039287/169829273-3694b209-59a6-4906-a8a7-2debab667cdf.jpg)


REMAP's Test Matrix Mode can be used to check if all keys are working as intended. However, since rotary encoder rotation cannot be checked in the Test Matrix Mode, please test the operation by key input, etc. separately.

In the standard firmware, the trackball movement is converted to scrolling in layers 1 and 2. If you want to change the layer for the scroll mode, please modify keymap.c.

See [here](https://github.com/aki27kbd/qmk_firmware/tree/master/keyboards/cocot46plus) for the source code.  
Also, please refer to [here](https://github.com/aki27kbd/cocot46plus/blob/main/firmware/cocot46plus_via.json) for the json file for VIA.



## Custom key codes

  It is possible to set several custom key codes for trackball operation.

  Value | Keycode |Description
  ---------|-----------|-----------
  `0x5DA7` | `CPI_SW`  |Changes the CPI of the trackball. The default firmware changes the CPI in the order 500 -> 750 -> 1000 -> 1250 -> 500... each time it is pressed.
  `0x5DA8` | `SCRL_SW` |Changes the sensitivity of the sensor in scroll mode. The higher the value, the smaller the amount of scrolling.
  `0x5DA9` | `ROT_R15` |Turns the Y axis of the mouse sensor 15 degrees clockwise.
  `0x5DAA` | `ROT_L15` |Rotate the Y axis of the mouse sensor 15 degrees counterclockwise.
  `0x5DAB` | `SCRL_MO` |Enables scroll mode for as long as it is pressed.
  `0x5DAC` |Toggles between scroll mode and mouse mode each time it is pressed.
  `0x5DAD` |Inverts the scroll direction.

  To set a custom key code in REMAP, enter the Value in the table above directly from CUSTOM as shown in the image below.

  ![CustomKeycode](https://user-images.githubusercontent.com/88039287/169856477-84ebf6bb-9430-44f8-a650-537ab8f0a79b.jpg)


## OLED

  OLED can display trackball information.  
  ![cocot46plus_bg_oled_1](https://user-images.githubusercontent.com/88039287/170496379-0b8dcec6-afac-48e9-b727-ad647c4a09c9.jpg)

  OLED|Description
  ---------|-----------
  Current Layer|Indicates the current layer.
  Scroll Status|Indicates C:Cursor/S:Scroll Mode.
  CPI|Indicates CPI in cursor mode.
  Scroll Divider|Indicates the sensitivity of the sensor in scroll mode. The higher the value, the smaller the scroll amount.
  Rotation Angle|This value indicates the rotation angle of the mouse sensor's Y axis.

  A comfortable Y-axis angle depends on the size of your hand and the way you place your hand on the trackball. Use the `ROT_R15` and `ROT_L15` keys to adjust it and find the setting that suits you best.  
  ![cocot46plus_bg_oled_2_2](https://user-images.githubusercontent.com/88039287/170499867-b430839b-f2f0-4163-afa2-c227184bd697.jpg)

  ![cocot46plus_bg_oled_3_4_5](https://user-images.githubusercontent.com/88039287/171883896-1a3b91cb-84b8-425c-b490-9affa5f42095.jpg)

## Optional mod

  **[Added on 8/8/2022] The boards after ver1.1 have these optional mods applied beforehand. The response of balls with darker colors such as green and black is also improved with the default.

  Ball colors that do not respond well in the default state will respond smoothly with a little modification.

  Attaching a smaller resistor to the R1 through-hole terminal on the backside of the PCB increases the brightness of the LED for the sensor and makes it react even with dark colored balls such as green and black.

  For reference, we have confirmed the operation of the Perix green bulb with [300Ω](https://akizukidenshi.com/catalog/g/gR-25301/) and the Perix black bulb with [150Ω](https://akizukidenshi.com/catalog/g/gR-25151/). We have confirmed that they work.

  ![cocot46plus_bg_mod_1](https://user-images.githubusercontent.com/88039287/175553271-ab133f23-baa0-479b-8bf1-9814e3324789.jpg)

  ![cocot46plus_bg_mod_2](https://user-images.githubusercontent.com/88039287/175553266-1370696c-3f86-420b-bee9-94a090027a80.jpg)


## Links

  [[Trackball] cocot46plus [Homemade keyboard]](https://www.youtube.com/watch?v=U7nu5G_PX5Y) (by Mr. Shiiba)  
  The site introduces the trackball, its internal structure, and compatible ball colors.

  [Gallery on Twitter](https://twitter.com/search?q=%23cocot46plus&src=typed_query&f=image)

## End

If you have any trouble, please contact us at our [Twitter account](https://twitter.com/aki27kbd).

Also, it would be very encouraging if you could upload photos of your work on social networking sites. (If you don't feel comfortable uploading your photos, you can send them directly to us via DM.)

The hashtag is #cocot46plus.