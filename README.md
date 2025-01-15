# Commonized/Unified Galaxy A03s, A04e, M04 and A06 Kernel source

### Known issue
- ~A03s/A037F: Firmware download failed, causing wifi, bluetooth or maybe gps and fmradio doesn't work. (This is related to mtk connectivity driver, a patch may fix it)~ Fixed in [mtk_connectivity_module@f57390c](https://github.com/rsuntkOrgs/mtk_connectivity_module/commit/f57390ca7332a2a6cead7ab5731f90aeef4a3db5)
- ~On older binary, the screen turns black immedietly, GPU driver confirmed.~ Fixed in hq-cmn-u6

### ToDo
- A06/A065F: Import more blobs, rename HQ_PROJECT_A06 to HQ_PROJECT_O8
- A03s/A04e under U7: Merge GPU blobs into hq-cmn

### How to clone this repository
```sh
git clone https://github.com/rsuntk/android_kernel_samsung_huaqin-cmn.git
```

### Credits
- [@rsuntk](https://github.com/rsuntk) - The Kernel source
- [@hiratazx](https://github.com/hiratazx) - For helping
- And all yukiprjkt members
