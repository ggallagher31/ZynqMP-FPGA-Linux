### Build Device Drivers and Services Package

#### udmabuf-4.14.0-xlnx-v2018.2-zynqmp-fpga_1.3.2-1_arm64.deb

##### Download repository

```console
shell$ git clone --recursive --depth=1 -b v1.3.2 git://github.com/ikwzm/udmabuf-kmod-dpkg
shell$ cd udmabuf-kmod-dpkg
```

##### Cross Compile for linux-xlnx-v2018.2-zynqmp-fpga

```console
shell$ sudo debian/rules arch=arm64 deb_arch=arm64 kernel_release=4.14.0-xlnx-v2018.2-zynqmp-fpga kernel_src_dir=../../linux-xlnx-v2018.2-zynqmp-fpga binary
    :
    :
    :
shell$ file ../udmabuf-4.14.0-xlnx-v2018.2-zynqmp-fpga_1.3.2-1_arm64.deb
../udmabuf-4.14.0-xlnx-v2018.2-zynqmp-fpga_1.3.2-1_arm64.deb: Debian binary package (format 2.0)
```

#### fclkcfg-4.14.0-xlnx-v2018.2-zynqmp-fpga_1.1.0-1_arm64.deb

##### Download repository

```console
shell$ git clone --recursive --depth=1 -b v1.1.0 git://github.com/ikwzm/fclkcfg-kmod-dpkg
shell$ cd fclkcfg-kmod-dpkg
```

##### Cross Compile for linux-xlnx-v2018.2-zynqmp-fpga

```console
shell$ sudo debian/rules arch=arm64 deb_arch=arm64 kernel_release=4.14.0-xlnx-v2018.2-zynqmp-fpga kernel_src_dir=../../linux-xlnx-v2018.2-zynqmp-fpga binary
    :
    :
    :
shell$ file ../fclkcfg-4.14.0-xlnx-v2018.2-zynqmp-fpga_1.1.0-1_arm64.deb
../fclkcfg-4.14.0-xlnx-v2018.2-zynqmp-fpga_1.1.0-1_arm64.deb: Debian binary package (format 2.0)
```


