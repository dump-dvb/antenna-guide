# Dipole antenna guide

TODO: add picture of the antenna

## Parts
The antenna is constructed using following parts:

| Part name                    | Count | Note                                                                                                               | Link |
|---|---|---|---|
| SO239 socket                 | 1x    |                                                                                                                    | [https://www.ebay.de/itm/294407664610](https://www.ebay.de/itm/294407664610) |
| M20 pvc pipe                 | 1x    | widend part at one end fits perfectly over the PL259 to BNC adapter                                                | [https://www.hornbach.de/shop/Installationsrohr-starr-M20-grau-2-0-m/10367394/artikel.html](https://www.hornbach.de/shop/Installationsrohr-starr-M20-grau-2-0-m/10367394/artikel.html) |
| PL259 to BNC adapter         | 1x    |                                                                                                                    | [https://www.ebay.de/itm/384868148089](https://www.ebay.de/itm/384868148089) |
| 50Ω BNC cable                | 1x    |                                                                                                                    |      |
| hollow brass rods            | 1x    | any solderable hollow rod would work, this one is 5mm OD. 3D files may need adjustment                             | [https://www.hornbach.de/shop/Messing-Rundrohr-aussen-5-0-mm-innen-4-1-mm-Laenge-1000-mm/6178978/artikel.html](https://www.hornbach.de/shop/Messing-Rundrohr-aussen-5-0-mm-innen-4-1-mm-Laenge-1000-mm/6178978/artikel.html) |
| `center_part.slvs`           | 1x    | 3d printed part, adjust hole size for your metal rods                                                              | [center_part.stl](https://github.com/dump-dvb/antenna-guide/blob/master/dipole-antenna/center_part.stl) |
| `end_cap.slvs`               | 2x    | 3d printed part                                                                                                    | [end_cap.stl](https://github.com/dump-dvb/antenna-guide/blob/master/dipole-antenna/end_cap.stl) |
| `connector_center_back.slvs` | 1x    | 3d print part, makes shure the antenna does not rotate on the plastic tubing                                       | [connector_center_back.slvs](https://github.com/dump-dvb/antenna-guide/blob/master/dipole-antenna/connector_center_back.stl) |
| `mast_mount.slvs`            | 1x    | 3d print part, solid plastic block with a hole for the tubing and some screw holes for securing it on a mast mount | [mast_mount.slvs](https://github.com/dump-dvb/antenna-guide/blob/master/dipole-antenna/mast_mount.stl) |

`center_part.slvs` is the Solvespace file for center part connecting of the antenna holding everything together.

`end_cap.slvs` is the Solvespace file for end caps of the 20mm pipeing. Alternatively the antenna can be capped of with an anemometer and disgused as a weather station.

STL files for the anemometer can be found [here](TODO).
They have to be scaled down by TODO% and a custom cap `anemometer_end_cap.slvs` and `anemometer_shaft.slvs` need to be used.
