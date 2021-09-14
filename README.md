# Bolt
Acrylic layer case file for Bolt - A 40% ergo qmk keyboard by LAZYDESIGNERS  
**** Important: Please use those files with your own discretion. No guarantee that it works****  
本项目是LAZYDESIGNERS的Bolt套件的亚克力层叠外壳图纸。
开源CAD图纸请谨慎使用。LAZYDESIGNERS不做任何保证。

![logo](http://lazydesigners.cn/wp-content/uploads/2021/09/boltlogo-01-01.jpg)

The acrylic Bolt is a project that LAZYDESIGNER started in May 2020. 
The goal is to try ergo like layout with arrow keys.  
Historic version:
* The first version is a prototype kit sharing with some friends.
* The second version has been on sale in Auguest 2020. The layout has been adjusted. The PCB is yellow and with hotswap socket. The kit uses stainless steel plate and a piece of stainless steel as a weight. 30 kits are made in total for that version.
* After that, some users requested solder PCB, and hoped for lower price. So the third version has been made. The PCB needs solder and no RGB leds by default. The kit uses anodized aluminum plate to add compatiblity to more switches but still keep the stainless steel weight. 50 kits were made in total.

All sets of CAD file of Bolt was open on the website lazydesigners.cn for users to customize. After Bolt clones were made by some ppl，and those clone users turned to us for customer service, we pulled off those files. 

亚克力Bolt是LAZYDESIGNERS于2020年5月正式完成设计并开始制作的一款套件。目的是为了测试ergo形态并具备方向键的40配列是否具有可用性。  
历史版本：
* 第一个版本是与朋友分享的测试原型。
* 第二个版本是正式出售版本。修改了配列，PCB是黄色阻焊，热插拔。定位板是镜面不锈钢并有一块不锈钢底板作为配重。 一共出货30套。
* 之后有些用户要求焊接定位板并希望进一步降低售价，所以第三个版本修改为黑色阻焊的焊接PCB，并默认不带RGB灯珠。定位板为了增加更多轴的适应性改为阳极铝，并保留了不锈钢板作为配重。一共50套。 

为了方便用户定制更换，我们将全套图纸开放在我们的网站lazydesigners.cn上。当我们发现有些用户购买了使用我们图纸仿制并声称是Bolt的产品，并在不知情的情况下向我们寻求售后之后，我们从网站上撤下了图纸。  

About the design of Bolt:
* It's solely designed by LAZYDESIGNERS from scratch. 
* Not a single Alice keyboard file has been used when designing Bolt. So It's not related to any Alice keyboard versions. 
* It's using Atmega32U4 AU MCU, with 13 RGB Leds in total, 9 for underglow, 4 for logo lighting. (Optional on solder version)
* All Bolt kits have metal plate and stainless steel bottoms as weights to make the acrylic kits more practical to function as daily keyboards.

关于亚克力Bolt的设计：
* 所有设计由LAZYDESIGNERS自主单独完成。
* 没有使用任何Alice的开源图纸，所以Bolt跟Alice任何版本之间并无关联。
* 使用 Atmega32U4 AU作为主控，一共13颗RGB灯珠，9颗作为底灯，4颗logo灯。（焊接版本为可选）
* 所有Bolt套件都具备金属定位板和不锈钢配重以保证日常使用下有比较好的打字体验。

**** Important: Please fully read the instrution below before you want to do anything with these files! ****  
请注意：请在使用图纸之前完整阅读图纸使用指南

Instrution of using files for building a Bolt:
图纸使用指南  
Acrylic layers:
| No | Layer | Standard thickness |
| :----:|  :----: | :----: |
| 1 | Top layer | 5mm |
| 2 | Second layer | 3mm |
| 3 | Port layer | 5mm |
| 4 | Support layer | 5mm |
| 5 | Bottom layer | 3mm |
| 6 | Two feet layers | 5mm |  

* All those layers are mirrored in the dwg file, which means you are actually looking them from the bottom. It will have a better surface of each layer after laser cut.
* In some area, the standard thickness is different to the actual thickness of acrylic layer. In China, 5mm thickness moudling acrylic plate has an actual thickness between 4.5-4.8mm. 3mm thickness moudling acrylic plate has an actual thickness between 2.7-2.8mm.
* The top layer and the second layer are above the plate. The total height will add to 7.2mm, which just cover the lowest edge of some profile keycaps. 3X3mm could also be used if you want to fully cover the keycaps.
* Port layer is the key part of the layer case. Due to the size of the holes for screw studs, this layer could become deformed after laser cut. Please check it with the laser cut manufacturer first.
* If you want to change the port layer to 3mm thickness, you have to use two. Then you can change support layer to 3mm too.
* Bottom layer can be replaced be a metal plate as a weight. The OG Bolt has both.
* Actually the feet layers can be change to any thickness you prefer. 

Acrylic layers:
| No | Layer | Standard thickness |
| :----:|  :----: | :----: |
| 1 | 顶层Top layer| 5mm |
| 2 | 次顶层Second layer | 3mm |
| 3 | 插口层Port layer | 5mm |
| 4 | 支撑层Support layer | 5mm |
| 5 | 底层Bottom layer | 3mm |
| 6 | 脚垫层Two feet layers | 5mm |  

* 图纸中所有层是镜像的，视角是从底部看。这样激光切割时候表面会平整些。
* 很多地区亚克力厚度尺寸是与实际尺寸是有差别的。比如在中国，5mm浇筑板尺寸大约是4.5mm到4.8mm左右，3mm亚克力浇筑板实际厚度2.7mm到2.8mm。
* 顶层和次顶层是定位板之上的层。按层叠浇筑板实际高度大约7.2毫米，基本能够到原厂键帽下缘。你也可以使用3层3mm厚的亚克力板。
* 插口层是关键的一层。由于螺丝孔的尺寸较大，这层切割时候会产生变形。切割前请与切割厂商确认这个问题。
* 如果你想把插口层变为3mm厚度，你需要两层插口层，这样的话你可以把支撑层改为3mm厚度。
* 底层可以直接改为金属板的配重。Bolt本身既有亚克力板也有不锈钢配重。
* 脚垫层可以根据需要更改任意厚度。

Bottom CAD file is for metal weight.

About the plate:
There are 4 RGB LEDs for logo lighting on Bolt OG PCB. Place a piece of white paper under the bolt logo area of the plate as a diffuse part. 
原始Bolt PCB上有4个RGB灯珠作为logo灯。请在plate下方贴一张白纸作为匀光件。


