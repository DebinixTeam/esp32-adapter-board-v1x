![prototyping solderable board](./images/dimensions-of-esp32-adapter-board.png)

# The Amazing ESP32 Adapter Board v1.x

 This adapter board is used to create a `nautical precision barometer` with an unique pressure history function. This project is well documented in this [instructable](https://www.instructables.com). 

## Specification for `The Amazing ESP32 Adapter Board v1.x`

This adapter board is fabricated as two layer board with the dimensions 5.4"x6.6" (137.16 x 167.64 mm).

| parameter | imperial | metric |
| -----------|-------|------|
| board material | FR4 | FR4 |
| board thickness | 63 mil | 1.6 mm |
| M3 mounting holes | 1/8" | 3.2 mm |
| header hole diameter | 39.4 mil | 1.0 mm |
| surface finish | HASL (with lead) | HASL (with lead) |
| copper layer thickness | 1.4 mil | 35 um |
| board color | green | green |
| board text | white | white |
| board weight | 2.82 oz | 80 gram |

## Fabrication of the board by yourself

This project is open-source, so that you will find KiCad PCB board design files and gerbers in this repository. Therefore, feel free to modify these files to fit your specific need.

You can directly upload files in the `fabrication/gerbers` folder to PCB prototype services like [OSHPark](https://oshpark.com), [EUROcircuits](https://www.eurocircuits.com/), [JLCPCB](https://jlcpcb.com/), or [PCBWay](https://www.pcbway.com/?adwgc=666&campaignid=172480651&adgroupid=8787904531&feeditemid=&targetid=kwd-96217560494&loc_physical_ms=9077376&matchtype=p&network=g&device=c&devicemodel=&creative=347469560617&keyword=pcbway&placement=&target=&adposition=&gclid=Cj0KCQjw1dGJBhD4ARIsANb6OdmESABFHY6IoLMPbpK8nmhx2egNPqXjOdz1aGUw3X_8KeHwY9J_MfkaAnIwEALw_wcB). Fabrication costs for small quantities vary considerably among suppliers.

## 2.8" 240x320 TFT SPI Display

The board is designed for this particular [2.8" TFT SPI Display](http://www.lcdwiki.com/2.8inch_SPI_Module_ILI9341_SKU:MSP2807). This display can be found on line from various sources, by searching for `SKU:MSP2807`.

## I2C breakout boards

The adapter board uses I2C for various pressure sensors. However, it can still be used for other I2C based breakout boards, either directly if the pin order is identical or using DuPont wires to match individual signals as shown in the [schematic](./kicad/esp32-adapter-schematic-v1x.pdf).

## Female headers

You have the choice to use [female headers](https://www.amazon.com/Glarks-Straight-Connector-Assortment-Prototype/dp/B076GZXW3Z/ref=pd_sbs_3/147-7037756-9410528?pd_rd_w=f0DzS&pf_rd_p=3676f086-9496-4fd7-8490-77cf7f43f846&pf_rd_r=XJ7KEPZZ1EA8WDMJP8NP&pd_rd_r=ec0b5867-c0b8-4d0b-9c31-e0d79fe9c3ec&pd_rd_wg=7Ns6N&pd_rd_i=B076GZXW3Z&psc=1) or permanently `solder` the parts to the board.

## Other sources of the adapter board
You can also purchase the latest designed boards on `Tindie`. 

[![Tindie](./images/tindie-small.png)](https://www.tindie.com/stores/debinix/)

I appreciate your support.
