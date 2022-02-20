# Fork notes:
Fork for adjustment to be more suitable to be built with parts found from Indonesian marketplace. **This fork is still in progress and all parts are not proven to be compatible yet.** Please check the [original repo](https://github.com/keekeen/MX-Switch-Break-In-Machine/).

# MX Switch Break-In Machine
A simple machine designed to actuate/ break-in MX style switches consistently and repetitively for a smoother push feel. Watch the [assembly process and operation](https://www.youtube.com/watch?v=iYIlCdo38ZM&list=PLLd9RKaLkD3lO_kQBJ3w394Xko4Nm3RR9) of the machine here.

![alt text][snapshot]

[snapshot]: /Images/DSC05789.jpg "Machine Snapshot"

## Specifications
- Max number of switches: 36
- Compatibility: 
  -  MX style switches with total travel distance of 4mm
  -  MX style switches with total travel distance less than 4mm (tweaks required for this)

## Notes ⚠️
- The provided files are to be used at your own risk.
- The dimensional tolerances may vary between 3D printers. See acceptable tolerances under [`Production/Technical-Drawings`](/Production/Technical-Drawings).
- The complete units showed in pictures and videos shared in this repo were printed with [JLCPCB 3D printing service](https://cart.jlcpcb.com/quote), with material of 8000 Resin, and remarked to print at an 30/45 angle for better Z-axis accuracy.
- Do ensure to run the machine at a ventilated area or fan-cooled to prevent the motor from overheating.

## Bill of materials (BOM) 📜
The following is the number of quantities required for each part to assemble a complete unit. The part files required to print are under the [`Production`](/Production) folder.

Parts required to print:
| Part                                                 | Qty        | Comment |
| ---------------------------------------------------- | ---------- | ------- |
| Actuation Plate                                      | 2          | -       |
| Off Center Actuation Plate                           | 4          | -       |
| Switch Holder                                        | 4          | -       |
| Flat Profile Keycap *or 10xFlat Profile Keycap*      | 36 *or 4*  | -       |
| Machine Housing                                      | 1          | -       |
| Machine Housing 1 *or 4xMachine Housing 1*           | 2 *or 1*   | -       |
| Motor-Adjuster                                       | 1          | -       |
| Scotch Yoke                                          | 1          | -       |

Parts required to purchase:
| Part                                 | Qty | Comment | References |
| ------------------------------------ | --- | ------- | ---------- |
| TT 1:90 Gearbox DC Motor             | 1   | - | [Tokopedia (but single shaft, cannot adjust motor position manually)](https://www.tokopedia.com/cncstorebandung/motor-dc-gearbox-metal-gear-tt-motor-single-shaft-all-metal) |
| HK 0306 Needle Roller Bearing        | 2   | - | [Tokopedia](https://www.tokopedia.com/rodabearing/hk-0306-tv-a-hk0306tva-needle-roller-bearing-laher-bambu) |
| M3 x 8mm Screw                       | 6   | - | [Tokopedia](https://www.tokopedia.com/rmbtools/baut-jp-m3-x-8-stainless-steel-baut-jp-stainless-m3-x-8-mm-sus-304) |
| M3 x 12mm Screw                      | 2   | - | [Tokopedia (100pcs)](https://www.tokopedia.com/rmbtools/baut-jp-m3-x-12-mm-sekrup-skrup-baut-jp-m3-x-12-isi-100pcs-jp0312?src=topads) |
| M3 x 25mm Screw                      | 2   | - | [Tokopedia](https://www.tokopedia.com/rmbtools/baut-jp-m3-x-25-stainless-steel-baut-jp-stainless-m3-x-25mm-sus-304) |
| Female USB C to 2-pin 22 AWG Wires   | 1   | - | - |
| 8mm Diameter Bumpons                 | 4   | Optional | - |

## To-Do 📝
- A guide on breaking-in switches that have shorter travel distance will be shared soon.

## Changelog 📒
- `05/02/2022:` Initial part files commit 

## Reach me at 📩
- Discord: https://discordapp.com/users/keekeen#4907
  - Feel free to send me your enquires if you have doubt reproducing a unit for yourself.
