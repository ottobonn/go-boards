# Goban construction notes

## Full-size Dimensions

From https://senseis.xmp.net/?EquipmentDimensions

Dimension                  SI       Imperial      Japanese
                          (mm)       (inch)
Board width               424.2     16 23/32     1.4  shaku 尺
Board length              454.5     17 29/32     1.5  shaku 尺
Board thickness           151.5      5 31/32     0.5  shaku 尺
Line spacing width-wise    22           7/8      7.26 bu 分
Line spacing length-wise   23.7        15/16     7.82 bu 分
Line thickness              1           1/32     0.3  bu 分
Star point marker diameter  4           5/32     1.2  bu 分
Stone diameter             22.5        29/32     7.5  bu 分

(424.2mm wide - (18 stripes * 22mm)) / 2 sides = 14.099mm border width-wise
(454.5mm long - (18 stripes * 23.7mm)) / 2 sides = 13.95mm border length-wise

So we'll assume a 14mm border all around.

## 13x13 Dimensions

13 lines / 12 stripes * 22mm width-wise spacing = 264mm wide without border
264mm + (2 * 14mm)  = 292mm wide
                    = 11.496 in

13 lines / 12 stripes * 23.7mm length-wise spacing = 284.4mm long without border
284.4mm + (2 * 14mm)  = 312.4mm long
                      = 12.299 in

## 9x9 Dimensions

9 lines / 8 stripes * 22mm width-wise spacing = 176 mm wide without border
176 mm wide + (2 * 14mm)  = 204mm wide overall
                          = 8.031 inches wide

9 lines / 8 stripes * 23.7mm length-wise spacing = 189.6mm long without border
189.6mm long + (2 * 14mm) = 217.6mm long overall
                          = 8.567 inches long

# Metal inlay

* 18ga dead soft red brass wire (50ft will cover almost one 19x19 board)
* 4mm brass rod stock for star points
