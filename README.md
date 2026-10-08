# Camera Mounts

Camera mount CAD files for B601 robots and data collection setups, plus a USDZ environment asset.

## Choose an asset

| Collection | Assets | Format |
| --- | --- | --- |
| [B601 camera mounts](#b601-camera-mounts) | 4 camera mount designs | STEP (`.step`) |
| [Data collection camera mounts](#data-collection-camera-mounts) | 4 mount designs and 4 adapter parts | STEP (`.stp`) |
| [Data collection environment](#data-collection-environment) | 1 box model | USDZ (`.usdz`) |

The catalog below covers every CAD/model file in this repository. Camera and robot names follow the upstream filenames; dimensions, fasteners, print settings, and verified compatibility are not supplied here. Check the CAD geometry against your hardware before fabrication.

## B601 camera mounts

These files originate from the B601-DM 3D printed parts collection in [reBot-DevArm](https://github.com/Seeed-Projects/reBot-DevArm/tree/main/hardware/reBot_B601_DM/3D_Printed_Parts).

### D405 / 305 mount

![Upstream CAD rendering of the D405 mount](images/b601-d405.jpg)

[Download D405_305_Mount.step](b601-camera-mounts/D405_305_Mount.step)

Camera mount identified as D405 / 305 in the source filename. The upstream D405 rendering shows a camera support plate connected to a curved mounting base. The image is a CAD rendering, not a finished-part photograph; the meaning of “305” is not documented upstream.

### D435 / Gemini 2 mount

![Upstream D435i CAD rendering associated with the D435 mount family](images/b601-d435i.jpg)

[Download D435_Gemini2_Mount.step](b601-camera-mounts/D435_Gemini2_Mount.step)

Camera mount identified as D435 / Gemini 2 in the source filename. The upstream image is labeled D435i and shows an elongated camera support plate and curved mounting base. It is a CAD reference rendering, not proof of fit for every named camera or a finished-part photograph.

### D455f mount

[Download D455f_Mount.step](b601-camera-mounts/D455f_Mount.step)

Camera mount identified as D455f in the source filename. Open the STEP model to inspect the mounting geometry. A finished-part photograph is not yet available in this repository.

### UVC32 mount

[Download UVC32_mount.step](b601-camera-mounts/UVC32_mount.step)

Camera mount identified as UVC32 in the source filename. Open the STEP model to inspect the mounting geometry. A finished-part photograph is not yet available in this repository.

## Data collection camera mounts

The upstream [Camera-Mount repository](https://github.com/xiehuangbao888/Camera-Mount) supplies four numbered mounts and four associated adapter parts. The associations below are translated from the original filenames. Upstream does not include assembly instructions or photographs; completed assemblies and camera compatibility have not been verified.

### Mount 1

[Download mount-1.stp](data-collection-camera-mounts/mount-1.stp)

Numbered camera mount design 1 for data collection. Two separate adapter variants are supplied:

- [reBot adapter](data-collection-camera-mounts/mount-1-rebot-adapter.stp): the part named “mount 1 rebot insert” upstream.
- [SO-ARM adapter](data-collection-camera-mounts/mount-1-soarm-adapter.stp): the part named “mount 1 soarm insert” upstream.

Select the adapter corresponding to your setup and inspect the interface in CAD. Finished-part photographs of the mount and both adapter variants are pending.

### Mount 2

[Download mount-2.stp](data-collection-camera-mounts/mount-2.stp)

Numbered camera mount design 2 for data collection. A separate [SO-ARM adapter](data-collection-camera-mounts/mount-2-soarm-adapter.stp) is supplied, identified upstream as the mount 2 soarm insert. Inspect the two models together to determine how they connect. Finished-part photographs of the mount and adapter are pending.

### Mount 3

[Download mount-3.stp](data-collection-camera-mounts/mount-3.stp)

Numbered camera mount design 3 for data collection. The [mount 3 / 4 adapter](data-collection-camera-mounts/mount-3-4-adapter.stp) is identified by its upstream filename as the shared insert for designs 3 and 4. Finished-part photographs of this mount and the shared adapter are pending.

### Mount 4

[Download mount-4.stp](data-collection-camera-mounts/mount-4.stp)

Numbered camera mount design 4 for data collection. Its associated part is the same [mount 3 / 4 adapter](data-collection-camera-mounts/mount-3-4-adapter.stp). Inspect the CAD geometry to compare designs 3 and 4 before choosing one. A finished-part photograph is pending.

### Original-to-English filename mapping

Only filenames have changed; the CAD file contents are preserved. Mount numbers and adapter associations remain traceable to upstream.

| Original filename | English filename |
| --- | --- |
| `数据采集摄像头支架_支架1.stp` | [`mount-1.stp`](data-collection-camera-mounts/mount-1.stp) |
| `数据采集摄像头支架_支架1插件rebot.stp` | [`mount-1-rebot-adapter.stp`](data-collection-camera-mounts/mount-1-rebot-adapter.stp) |
| `数据采集摄像头支架_支架1插件soarm.stp` | [`mount-1-soarm-adapter.stp`](data-collection-camera-mounts/mount-1-soarm-adapter.stp) |
| `数据采集摄像头支架_支架2.stp` | [`mount-2.stp`](data-collection-camera-mounts/mount-2.stp) |
| `数据采集摄像头支架_支架2插件soarm.stp` | [`mount-2-soarm-adapter.stp`](data-collection-camera-mounts/mount-2-soarm-adapter.stp) |
| `数据采集摄像头支架_支架3.stp` | [`mount-3.stp`](data-collection-camera-mounts/mount-3.stp) |
| `数据采集摄像头支架_支架3_4插件.stp` | [`mount-3-4-adapter.stp`](data-collection-camera-mounts/mount-3-4-adapter.stp) |
| `数据采集摄像头支架_支架4.stp` | [`mount-4.stp`](data-collection-camera-mounts/mount-4.stp) |

## Data collection environment

[Download box.usdz](data-collection-environment/box.usdz)

A box model from [rebot-arm-dli-isaacsim](https://github.com/yuyoujiang/rebot-arm-dli-isaacsim), supplied as a USDZ asset for a data collection environment. This is an environment model rather than a camera mount. Open it in a USDZ-compatible viewer to inspect its geometry; no physical build photograph is supplied.

## Working with the files

1. Download the mount and any associated adapter using the links above.
2. Open STEP/STP files in a CAD tool and inspect dimensions, clearances, and mounting holes.
3. Prepare fabrication files for your chosen process. STL files, print settings, and a hardware bill of materials are not included.
4. For the environment asset, use a viewer or tool that supports USDZ.

## Image sources and finished-part photographs

The two B601 reference images are copied from upstream: [D405.jpg](https://github.com/Seeed-Projects/reBot-DevArm/blob/main/hardware/reBot_B601_DM/3D_Printed_Parts/images/D405.jpg) and [D435i.jpg](https://github.com/Seeed-Projects/reBot-DevArm/blob/main/hardware/reBot_B601_DM/3D_Printed_Parts/images/D435i.jpg). Both are CAD renderings. Finished-part photographs are still needed for all mount designs and adapter variants. Add actual photographs with captions identifying the mount number, adapter, camera, and robot used.

## Sources and licensing

- B601 camera mounts and reference renderings: [Seeed-Projects/reBot-DevArm](https://github.com/Seeed-Projects/reBot-DevArm), CERN OHL-W-2.0.
- Data collection camera mounts: [xiehuangbao888/Camera-Mount](https://github.com/xiehuangbao888/Camera-Mount). No upstream license was declared when these assets were copied.
- Data collection environment: [yuyoujiang/rebot-arm-dli-isaacsim](https://github.com/yuyoujiang/rebot-arm-dli-isaacsim), MIT.

See [NOTICE.md](NOTICE.md), [LICENSE](LICENSE), and [licenses/](licenses/) for details.
