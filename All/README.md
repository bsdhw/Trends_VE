BSD Virtual Hardware Trends
---------------------------

A project to identify most popular virtual hardware characteristics and track their change
over time based on data collected by BSD users at https://BSD-Hardware.info.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe/blob/master/INSTALL.BSD.md) tool:

    hw-probe -all -upload

OS-specific reports: [helloSystem](/Dist/helloSystem), [OPNsense](/Dist/OPNsense).

This report is for one last month. Overall report since the beginning of time: [TestCoverage_VE](https://github.com/bsdhw/TestCoverage_VE)

Period: Mar, 2022.

Contents
--------

* [ System ](#system)
  - [ OS                       ](#os)
  - [ OS Family                ](#os-family)
  - [ Arch                     ](#arch)
  - [ DE                       ](#de)
  - [ Display Server           ](#display-server)
  - [ Display Manager          ](#display-manager)
  - [ OS Lang                  ](#os-lang)
  - [ Boot Mode                ](#boot-mode)
  - [ Filesystem               ](#filesystem)
  - [ Part. scheme             ](#part-scheme)

* [ Board ](#board)
  - [ Vendor                   ](#vendor)
  - [ Model                    ](#model)
  - [ Model Family             ](#model-family)
  - [ MFG Year                 ](#mfg-year)
  - [ Form Factor              ](#form-factor)
  - [ Coreboot                 ](#coreboot)
  - [ RAM Size                 ](#ram-size)
  - [ RAM Used                 ](#ram-used)
  - [ Total Drives             ](#total-drives)
  - [ Has CD-ROM               ](#has-cd-rom)
  - [ Has Ethernet             ](#has-ethernet)
  - [ Has WiFi                 ](#has-wifi)
  - [ Has Bluetooth            ](#has-bluetooth)

* [ Location ](#location)
  - [ Country                  ](#country)
  - [ City                     ](#city)

* [ Drives ](#drives)
  - [ Drive Vendor             ](#drive-vendor)
  - [ Drive Model              ](#drive-model)
  - [ HDD Vendor               ](#hdd-vendor)
  - [ SSD Vendor               ](#ssd-vendor)
  - [ Drive Kind               ](#drive-kind)
  - [ Drive Connector          ](#drive-connector)
  - [ Drive Size               ](#drive-size)
  - [ Space Total              ](#space-total)
  - [ Space Used               ](#space-used)
  - [ Malfunc. Drives          ](#malfunc-drives)
  - [ Malfunc. Drive Vendor    ](#malfunc-drive-vendor)
  - [ Malfunc. HDD Vendor      ](#malfunc-hdd-vendor)
  - [ Malfunc. Drive Kind      ](#malfunc-drive-kind)
  - [ Failed Drives            ](#failed-drives)
  - [ Failed Drive Vendor      ](#failed-drive-vendor)
  - [ Drive Status             ](#drive-status)

* [ Storage controller ](#storage-controller)
  - [ Storage Vendor           ](#storage-vendor)
  - [ Storage Model            ](#storage-model)
  - [ Storage Kind             ](#storage-kind)

* [ Processor ](#processor)
  - [ CPU Vendor               ](#cpu-vendor)
  - [ CPU Model                ](#cpu-model)
  - [ CPU Model Family         ](#cpu-model-family)
  - [ CPU Cores                ](#cpu-cores)
  - [ CPU Sockets              ](#cpu-sockets)
  - [ CPU Threads              ](#cpu-threads)
  - [ CPU Microarch            ](#cpu-microarch)

* [ Graphics ](#graphics)
  - [ GPU Vendor               ](#gpu-vendor)
  - [ GPU Model                ](#gpu-model)
  - [ GPU Combo                ](#gpu-combo)
  - [ GPU Driver               ](#gpu-driver)
  - [ GPU Memory               ](#gpu-memory)

* [ Monitor ](#monitor)
  - [ Monitor Vendor           ](#monitor-vendor)
  - [ Monitor Model            ](#monitor-model)
  - [ Monitor Resolution       ](#monitor-resolution)
  - [ Monitor Diagonal         ](#monitor-diagonal)
  - [ Monitor Width            ](#monitor-width)
  - [ Aspect Ratio             ](#aspect-ratio)
  - [ Monitor Area             ](#monitor-area)
  - [ Pixel Density            ](#pixel-density)
  - [ Multiple Monitors        ](#multiple-monitors)

* [ Network ](#network)
  - [ Net Controller Vendor    ](#net-controller-vendor)
  - [ Net Controller Model     ](#net-controller-model)
  - [ Wireless Vendor          ](#wireless-vendor)
  - [ Wireless Model           ](#wireless-model)
  - [ Ethernet Vendor          ](#ethernet-vendor)
  - [ Ethernet Model           ](#ethernet-model)
  - [ Net Controller Kind      ](#net-controller-kind)
  - [ Used Controller          ](#used-controller)
  - [ NICs                     ](#nics)
  - [ IPv6                     ](#ipv6)

* [ Bluetooth ](#bluetooth)
  - [ Bluetooth Vendor         ](#bluetooth-vendor)
  - [ Bluetooth Model          ](#bluetooth-model)

* [ Sound ](#sound)
  - [ Sound Vendor             ](#sound-vendor)
  - [ Sound Model              ](#sound-model)

* [ Memory ](#memory)
  - [ Memory Vendor            ](#memory-vendor)
  - [ Memory Model             ](#memory-model)
  - [ Memory Kind              ](#memory-kind)
  - [ Memory Form Factor       ](#memory-form-factor)
  - [ Memory Size              ](#memory-size)
  - [ Memory Speed             ](#memory-speed)

* [ Printers & scanners ](#printers--scanners)
  - [ Printer Vendor           ](#printer-vendor)
  - [ Printer Model            ](#printer-model)
  - [ Scanner Vendor           ](#scanner-vendor)
  - [ Scanner Model            ](#scanner-model)

* [ Camera ](#camera)
  - [ Camera Vendor            ](#camera-vendor)
  - [ Camera Model             ](#camera-model)

* [ Security ](#security)
  - [ Fingerprint Vendor       ](#fingerprint-vendor)
  - [ Fingerprint Model        ](#fingerprint-model)
  - [ Chipcard Vendor          ](#chipcard-vendor)
  - [ Chipcard Model           ](#chipcard-model)

* [ Unsupported ](#unsupported)
  - [ Unsupported Devices      ](#unsupported-devices)
  - [ Unsupported Device Types ](#unsupported-device-types)


System
------

OS
--

Installed operating systems

![OS](./images/pie_chart_bsd/os_name.svg)

![OS](./images/line_chart_bsd/os_name.svg)

| Name                | Computers | Percent |
|---------------------|-----------|---------|
| helloSystem 0.7.0   | 30        | 38.46%  |
| OPNsense 22.1.2     | 15        | 19.23%  |
| OPNsense 22.1.4     | 10        | 12.82%  |
| OPNsense 22.1.3     | 10        | 12.82%  |
| helloSystem 0.8.0   | 8         | 10.26%  |
| OPNsense 22.7       | 1         | 1.28%   |
| OPNsense 21.1       | 1         | 1.28%   |
| FreeBSD 13.0-STABLE | 1         | 1.28%   |
| FreeBSD 13.0-p8     | 1         | 1.28%   |
| FreeBSD 13.0-p7     | 1         | 1.28%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart_bsd/os_family.svg)

![OS Family](./images/line_chart_bsd/os_family.svg)

| Name        | Computers | Percent |
|-------------|-----------|---------|
| helloSystem | 38        | 48.72%  |
| OPNsense    | 37        | 47.44%  |
| FreeBSD     | 3         | 3.85%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart_bsd/os_arch.svg)

![Arch](./images/line_chart_bsd/os_arch.svg)

| Name  | Computers | Percent |
|-------|-----------|---------|
| amd64 | 78        | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart_bsd/os_de.svg)

![DE](./images/line_chart_bsd/os_de.svg)

| Name         | Computers | Percent |
|--------------|-----------|---------|
| helloDesktop | 38        | 48.72%  |
| Console      | 38        | 48.72%  |
| XFCE         | 1         | 1.28%   |
| LXQt         | 1         | 1.28%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart_bsd/os_display_server.svg)

![Display Server](./images/line_chart_bsd/os_display_server.svg)

| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 40        | 51.28%  |
| Console | 38        | 48.72%  |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart_bsd/os_display_manager.svg)

![Display Manager](./images/line_chart_bsd/os_display_manager.svg)

| Name    | Computers | Percent |
|---------|-----------|---------|
| SLiM    | 38        | 48.72%  |
| Console | 38        | 48.72%  |
| XDM     | 1         | 1.28%   |
| SDDM    | 1         | 1.28%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart_bsd/os_lang.svg)

![OS Lang](./images/line_chart_bsd/os_lang.svg)

| Lang    | Computers | Percent |
|---------|-----------|---------|
| en_US   | 37        | 47.44%  |
| Unknown | 35        | 44.87%  |
| C       | 6         | 7.69%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart_bsd/os_boot_mode.svg)

![Boot Mode](./images/line_chart_bsd/os_boot_mode.svg)

| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 62        | 79.49%  |
| BIOS | 16        | 20.51%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart_bsd/os_filesystem.svg)

![Filesystem](./images/line_chart_bsd/os_filesystem.svg)

| Type   | Computers | Percent |
|--------|-----------|---------|
| Zfs    | 35        | 44.87%  |
| Ufs    | 28        | 35.9%   |
| Cd9660 | 15        | 19.23%  |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart_bsd/os_part_scheme.svg)

![Part. scheme](./images/line_chart_bsd/os_part_scheme.svg)

| Type | Computers | Percent |
|------|-----------|---------|
| GPT  | 63        | 80.77%  |
| MBR  | 15        | 19.23%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart_bsd/node_vendor.svg)

![Vendor](./images/line_chart_bsd/node_vendor.svg)

| Name                             | Computers | Percent |
|----------------------------------|-----------|---------|
| QEMU                             | 30        | 38.46%  |
| Oracle                           | 22        | 28.21%  |
| VMware                           | 20        | 25.64%  |
| Microsoft                        | 5         | 6.41%   |
| Parallels Software International | 1         | 1.28%   |

Model
-----

Motherboard model

![Model](./images/pie_chart_bsd/node_model.svg)

![Model](./images/line_chart_bsd/node_model.svg)

| Name                                                        | Computers | Percent |
|-------------------------------------------------------------|-----------|---------|
| Oracle VirtualBox                                           | 22        | 28.21%  |
| QEMU Standard PC (i440FX + PIIX, 1996)                      | 20        | 25.64%  |
| VMware Virtual Platform                                     | 17        | 21.79%  |
| QEMU Standard PC (Q35 + ICH9, 2009)                         | 10        | 12.82%  |
| Microsoft Virtual Machine                                   | 5         | 6.41%   |
| VMware VMware7,1                                            | 3         | 3.85%   |
| Parallels Software International Parallels Virtual Platform | 1         | 1.28%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart_bsd/node_model_family.svg)

![Model Family](./images/line_chart_bsd/node_model_family.svg)

| Name                                       | Computers | Percent |
|--------------------------------------------|-----------|---------|
| QEMU Standard                              | 30        | 38.46%  |
| Oracle VirtualBox                          | 22        | 28.21%  |
| VMware Virtual                             | 17        | 21.79%  |
| Microsoft Virtual                          | 5         | 6.41%   |
| VMware VMware7                             | 3         | 3.85%   |
| Parallels Software International Parallels | 1         | 1.28%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart_bsd/node_year.svg)

![MFG Year](./images/line_chart_bsd/node_year.svg)

| Year    | Computers | Percent |
|---------|-----------|---------|
| 2006    | 22        | 28.21%  |
| 2014    | 21        | 26.92%  |
| 2020    | 13        | 16.67%  |
| 2018    | 8         | 10.26%  |
| 2015    | 8         | 10.26%  |
| 2021    | 3         | 3.85%   |
| 2017    | 1         | 1.28%   |
| 2016    | 1         | 1.28%   |
| Unknown | 1         | 1.28%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart_bsd/node_formfactor.svg)

![Form Factor](./images/line_chart_bsd/node_formfactor.svg)

| Name            | Computers | Percent |
|-----------------|-----------|---------|
| Virtual machine | 78        | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart_bsd/node_coreboot.svg)

![Coreboot](./images/line_chart_bsd/node_coreboot.svg)

| Used | Computers | Percent |
|------|-----------|---------|
| No   | 78        | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart_bsd/node_ram_total.svg)

![RAM Size](./images/line_chart_bsd/node_ram_total.svg)

| Size in GB | Computers | Percent |
|------------|-----------|---------|
| 2.01-3.0   | 25        | 32.05%  |
| 4.01-8.0   | 23        | 29.49%  |
| 8.01-16.0  | 16        | 20.51%  |
| 3.01-4.0   | 4         | 5.13%   |
| 1.01-2.0   | 4         | 5.13%   |
| 16.01-24.0 | 3         | 3.85%   |
| 0.51-1.0   | 3         | 3.85%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart_bsd/node_ram_used.svg)

![RAM Used](./images/line_chart_bsd/node_ram_used.svg)

| Used GB  | Computers | Percent |
|----------|-----------|---------|
| 0.01-0.5 | 73        | 93.59%  |
| 0.51-1.0 | 5         | 6.41%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart_bsd/node_total_drives.svg)

![Total Drives](./images/line_chart_bsd/node_total_drives.svg)

| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 55        | 70.51%  |
| 0      | 21        | 26.92%  |
| 2      | 2         | 2.56%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart_bsd/node_has_cdrom.svg)

![Has CD-ROM](./images/line_chart_bsd/node_has_cdrom.svg)

| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 69        | 88.46%  |
| No        | 9         | 11.54%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart_bsd/node_has_ethernet.svg)

![Has Ethernet](./images/line_chart_bsd/node_has_ethernet.svg)

| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 50        | 64.1%   |
| No        | 28        | 35.9%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart_bsd/node_has_wifi.svg)

![Has WiFi](./images/line_chart_bsd/node_has_wifi.svg)

| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 76        | 97.44%  |
| Yes       | 2         | 2.56%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart_bsd/node_has_bluetooth.svg)

![Has Bluetooth](./images/line_chart_bsd/node_has_bluetooth.svg)

| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 77        | 98.72%  |
| Yes       | 1         | 1.28%   |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart_bsd/node_location.svg)

![Country](./images/line_chart_bsd/node_location.svg)

| Country     | Computers | Percent |
|-------------|-----------|---------|
| USA         | 13        | 16.67%  |
| Germany     | 9         | 11.54%  |
| UK          | 5         | 6.41%   |
| France      | 5         | 6.41%   |
| Romania     | 4         | 5.13%   |
| Czechia     | 4         | 5.13%   |
| China       | 4         | 5.13%   |
| Canada      | 4         | 5.13%   |
| Russia      | 3         | 3.85%   |
| Austria     | 3         | 3.85%   |
| Taiwan      | 2         | 2.56%   |
| Japan       | 2         | 2.56%   |
| Indonesia   | 2         | 2.56%   |
| Hungary     | 2         | 2.56%   |
| Brazil      | 2         | 2.56%   |
| UAE         | 1         | 1.28%   |
| Switzerland | 1         | 1.28%   |
| Sweden      | 1         | 1.28%   |
| Spain       | 1         | 1.28%   |
| Serbia      | 1         | 1.28%   |
| Poland      | 1         | 1.28%   |
| Lebanon     | 1         | 1.28%   |
| Italy       | 1         | 1.28%   |
| Guatemala   | 1         | 1.28%   |
| Greece      | 1         | 1.28%   |
| Ghana       | 1         | 1.28%   |
| Bulgaria    | 1         | 1.28%   |
| Belgium     | 1         | 1.28%   |
| Australia   | 1         | 1.28%   |

City
----

Geographic location (city)

![City](./images/pie_chart_bsd/node_city.svg)

![City](./images/line_chart_bsd/node_city.svg)

| City                    | Computers | Percent |
|-------------------------|-----------|---------|
| Prague                  | 3         | 3.85%   |
| Berlin                  | 3         | 3.85%   |
| Yunlin                  | 2         | 2.56%   |
| Saitama                 | 2         | 2.56%   |
| Paris                   | 2         | 2.56%   |
| Navodari                | 2         | 2.56%   |
| Zhuhai                  | 1         | 1.28%   |
| Yorba Linda             | 1         | 1.28%   |
| Waukesha                | 1         | 1.28%   |
| Washington              | 1         | 1.28%   |
| Warsaw                  | 1         | 1.28%   |
| Warendorf               | 1         | 1.28%   |
| Vienna                  | 1         | 1.28%   |
| Ufa                     | 1         | 1.28%   |
| Trois-RiviÃ¨res       | 1         | 1.28%   |
| Thessaloniki            | 1         | 1.28%   |
| Talavera de la Reina    | 1         | 1.28%   |
| SzÃ©kesfehÃ©rvÃ¡r | 1         | 1.28%   |
| Stockholm               | 1         | 1.28%   |
| Spittal an der Drau     | 1         | 1.28%   |
| Sofia                   | 1         | 1.28%   |
| Semarang                | 1         | 1.28%   |
| Seattle                 | 1         | 1.28%   |
| Sao Paulo               | 1         | 1.28%   |
| San Antonio             | 1         | 1.28%   |
| Sainte-Julie            | 1         | 1.28%   |
| Qiqihar                 | 1         | 1.28%   |
| Pilsen                  | 1         | 1.28%   |
| Passau                  | 1         | 1.28%   |
| Munich                  | 1         | 1.28%   |
| Montreal                | 1         | 1.28%   |
| Milton Keynes           | 1         | 1.28%   |
| Milan                   | 1         | 1.28%   |
| Melbourne               | 1         | 1.28%   |
| Los Angeles             | 1         | 1.28%   |
| Kurgan                  | 1         | 1.28%   |
| Krasnodar               | 1         | 1.28%   |
| Kingston upon Thames    | 1         | 1.28%   |
| Jakarta                 | 1         | 1.28%   |
| Hampton                 | 1         | 1.28%   |
| Guatemala City          | 1         | 1.28%   |
| Guangzhou               | 1         | 1.28%   |
| Groedig                 | 1         | 1.28%   |
| Gresham                 | 1         | 1.28%   |
| Gennevilliers           | 1         | 1.28%   |
| Frankfurt am Main       | 1         | 1.28%   |
| Findlay                 | 1         | 1.28%   |
| Ferndown                | 1         | 1.28%   |
| Everett                 | 1         | 1.28%   |
| Dubai                   | 1         | 1.28%   |
| Dongguan                | 1         | 1.28%   |
| Coventry                | 1         | 1.28%   |
| Courtenay               | 1         | 1.28%   |
| ConstanÈ›a           | 1         | 1.28%   |
| Charleroi               | 1         | 1.28%   |
| Cacoal                  | 1         | 1.28%   |
| Budapest                | 1         | 1.28%   |
| Bucharest               | 1         | 1.28%   |
| Bubenreuth              | 1         | 1.28%   |
| Brookline               | 1         | 1.28%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart_bsd/drive_vendor.svg)

![Drive Vendor](./images/line_chart_bsd/drive_vendor.svg)

| Vendor | Computers | Drives | Percent |
|--------|-----------|--------|---------|
| VBOX   | 21        | 21     | 36.84%  |
| VMware | 17        | 18     | 29.82%  |
| QEMU   | 14        | 15     | 24.56%  |
| Msft   | 5         | 5      | 8.77%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart_bsd/drive_model.svg)

![Drive Model](./images/line_chart_bsd/drive_model.svg)

| Model               | Computers | Percent |
|---------------------|-----------|---------|
| VBOX HARDDISK       | 21        | 36.84%  |
| QEMU HARDDISK       | 14        | 24.56%  |
| VMware Virtual S    | 9         | 15.79%  |
| VMware Virtual disk | 8         | 14.04%  |
| Msft Virtual Disk   | 5         | 8.77%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart_bsd/drive_hdd_vendor.svg)

![HDD Vendor](./images/line_chart_bsd/drive_hdd_vendor.svg)

| Vendor | Computers | Drives | Percent |
|--------|-----------|--------|---------|
| VBOX   | 21        | 21     | 36.84%  |
| VMware | 17        | 18     | 29.82%  |
| QEMU   | 14        | 15     | 24.56%  |
| Msft   | 5         | 5      | 8.77%   |

SSD Vendor
----------

Solid state drive vendors

Zero info for selected period =(

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart_bsd/drive_kind.svg)

![Drive Kind](./images/line_chart_bsd/drive_kind.svg)

| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 57        | 59     | 100%    |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart_bsd/drive_bus.svg)

![Drive Connector](./images/line_chart_bsd/drive_bus.svg)

| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 57        | 59     | 100%    |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart_bsd/drive_size.svg)

![Drive Size](./images/line_chart_bsd/drive_size.svg)

| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 57        | 59     | 100%    |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart_bsd/drive_space_total.svg)

![Space Total](./images/line_chart_bsd/drive_space_total.svg)

| Size in GB | Computers | Percent |
|------------|-----------|---------|
| 1-20       | 43        | 55.13%  |
| 21-50      | 21        | 26.92%  |
| 51-100     | 9         | 11.54%  |
| 101-250    | 5         | 6.41%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart_bsd/drive_space_used.svg)

![Space Used](./images/line_chart_bsd/drive_space_used.svg)

| Used GB | Computers | Percent |
|---------|-----------|---------|
| 1-20    | 77        | 98.72%  |
| 21-50   | 1         | 1.28%   |

Malfunc. Drives
---------------

Drive models with a malfunction

Zero info for selected period =(

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

Zero info for selected period =(

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

Zero info for selected period =(

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

Zero info for selected period =(

Failed Drives
-------------

Failed drive models

Zero info for selected period =(

Failed Drive Vendor
-------------------

Failed drive vendors

Zero info for selected period =(

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart_bsd/drive_status.svg)

![Drive Status](./images/line_chart_bsd/drive_status.svg)

| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 57        | 59     | 100%    |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart_bsd/storage_vendor.svg)

![Storage Vendor](./images/line_chart_bsd/storage_vendor.svg)

| Vendor                    | Computers | Percent |
|---------------------------|-----------|---------|
| Intel                     | 78        | 62.9%   |
| Red Hat                   | 22        | 17.74%  |
| LSI Logic / Symbios Logic | 12        | 9.68%   |
| VMware                    | 7         | 5.65%   |
| Broadcom / LSI            | 5         | 4.03%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart_bsd/storage_model.svg)

![Storage Model](./images/line_chart_bsd/storage_model.svg)

| Model                                                                 | Computers | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| Intel 82371AB/EB/MB PIIX4 IDE                                         | 45        | 34.35%  |
| Intel 82371SB PIIX3 IDE [Natoma/Triton II]                            | 20        | 15.27%  |
| Red Hat Virtio SCSI                                                   | 14        | 10.69%  |
| Intel 82801IR/IO/IH (ICH9R/DO/DH) 6 port SATA Controller [AHCI mode]  | 13        | 9.92%   |
| LSI Logic / Symbios Logic 53c1030 PCI-X Fusion-MPT Dual Ultra320 SCSI | 12        | 9.16%   |
| Red Hat Virtio block device                                           | 8         | 6.11%   |
| Broadcom / LSI SAS1068 PCI-X Fusion-MPT SAS                           | 5         | 3.82%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]         | 4         | 3.05%   |
| VMware SATA AHCI controller                                           | 3         | 2.29%   |
| VMware NVMe SSD Controller                                            | 3         | 2.29%   |
| VMware PVSCSI SCSI Controller                                         | 2         | 1.53%   |
| Intel 82801HR/HO/HH (ICH8R/DO/DH) 6 port SATA Controller [AHCI mode]  | 1         | 0.76%   |
| Intel 82801BA IDE U100 Controller                                     | 1         | 0.76%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart_bsd/storage_kind.svg)

![Storage Kind](./images/line_chart_bsd/storage_kind.svg)

| Kind | Computers | Percent |
|------|-----------|---------|
| IDE  | 66        | 50.77%  |
| SCSI | 34        | 26.15%  |
| SATA | 21        | 16.15%  |
| SAS  | 6         | 4.62%   |
| NVMe | 3         | 2.31%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart_bsd/cpu_vendor.svg)

![CPU Vendor](./images/line_chart_bsd/cpu_vendor.svg)

| Vendor  | Computers | Percent |
|---------|-----------|---------|
| Intel   | 35        | 44.87%  |
| QEMU    | 30        | 38.46%  |
| AMD     | 9         | 11.54%  |
| Unknown | 4         | 5.13%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart_bsd/cpu_model.svg)

![CPU Model](./images/line_chart_bsd/cpu_model.svg)

| Model                                          | Computers | Percent |
|------------------------------------------------|-----------|---------|
| QEMU pc-i440fx-6.1                             | 9         | 11.54%  |
| QEMU pc-q35-6.1                                | 7         | 8.97%   |
|                                                | 4         | 5.13%   |
| QEMU pc-i440fx-6.2                             | 3         | 3.85%   |
| QEMU pc-i440fx-5.2                             | 3         | 3.85%   |
| QEMU pc-i440fx-impish                          | 2         | 2.56%   |
| Intel Core i9-9900K CPU @ 3.60GHz              | 2         | 2.56%   |
| Intel Core i7-4610M CPU @ 3.00GHz              | 2         | 2.56%   |
| QEMU pc-q35-6.2                                | 1         | 1.28%   |
| QEMU pc-q35-6.0                                | 1         | 1.28%   |
| QEMU pc-q35-4.2                                | 1         | 1.28%   |
| QEMU pc-i440fx-jammy                           | 1         | 1.28%   |
| QEMU pc-i440fx-focal                           | 1         | 1.28%   |
| QEMU pc-i440fx-4.1                             | 1         | 1.28%   |
| Intel Xeon Silver 4110 CPU @ 2.10GHz           | 1         | 1.28%   |
| Intel Xeon CPU X5660 @ 2.80GHz                 | 1         | 1.28%   |
| Intel Xeon CPU X5650 @ 2.67GHz                 | 1         | 1.28%   |
| Intel Xeon CPU X5560 @ 2.80GHz                 | 1         | 1.28%   |
| Intel Xeon CPU E5620 @ 2.40GHz                 | 1         | 1.28%   |
| Intel Xeon CPU E5-2660 0 @ 2.20GHz             | 1         | 1.28%   |
| Intel Xeon CPU E3-1285 v6 @ 4.10GHz            | 1         | 1.28%   |
| Intel Xeon CPU E3-1231 v3 @ 3.40GHz            | 1         | 1.28%   |
| Intel Xeon CPU D-1541 @ 2.10GHz                | 1         | 1.28%   |
| Intel Core i7-6920HQ CPU @ 2.90GHz             | 1         | 1.28%   |
| Intel Core i7-4930K CPU @ 3.40GHz              | 1         | 1.28%   |
| Intel Core i7-4810MQ CPU @ 2.80GHz             | 1         | 1.28%   |
| Intel Core i7-3615QM CPU @ 2.30GHz             | 1         | 1.28%   |
| Intel Core i7-10750H CPU @ 2.60GHz             | 1         | 1.28%   |
| Intel Core i7                                  | 1         | 1.28%   |
| Intel Core i5-9400 CPU @ 2.90GHz               | 1         | 1.28%   |
| Intel Core i5-7200U CPU @ 2.50GHz              | 1         | 1.28%   |
| Intel Core i5-6500 CPU @ 3.20GHz               | 1         | 1.28%   |
| Intel Core i5-4300U CPU @ 1.90GHz              | 1         | 1.28%   |
| Intel Core i5-4278U CPU @ 2.60GHz              | 1         | 1.28%   |
| Intel Core i5-3470 CPU @ 3.20GHz               | 1         | 1.28%   |
| Intel Core i5-10400 CPU @ 2.90GHz              | 1         | 1.28%   |
| Intel Core i5-10210U CPU @ 1.60GHz             | 1         | 1.28%   |
| Intel Core i3-6100U CPU @ 2.30GHz              | 1         | 1.28%   |
| Intel Core i3-3220 CPU @ 3.30GHz               | 1         | 1.28%   |
| Intel Core i3-2328M CPU @ 2.20GHz              | 1         | 1.28%   |
| Intel Celeron J4105 CPU @ 1.50GHz              | 1         | 1.28%   |
| Intel 11th Gen Core i7-11800H @ 2.30GHz        | 1         | 1.28%   |
| Intel 11th Gen Core i5-11400H @ 2.70GHz        | 1         | 1.28%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz        | 1         | 1.28%   |
| Intel 11th Gen Core i3-1125G4 @ 2.00GHz        | 1         | 1.28%   |
| AMD Ryzen 9 5950X 16-Core Processor            | 1         | 1.28%   |
| AMD Ryzen 9 3900X 12-Core Processor            | 1         | 1.28%   |
| AMD Ryzen 7 2700X Eight-Core Processor         | 1         | 1.28%   |
| AMD Ryzen 5 3600 6-Core Processor              | 1         | 1.28%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx  | 1         | 1.28%   |
| AMD Ryzen 5 2600 Six-Core Processor            | 1         | 1.28%   |
| AMD E2-9000 RADEON R2, 4 COMPUTE CORES 2C+2G   | 1         | 1.28%   |
| AMD A9-9400 RADEON R5, 5 COMPUTE CORES 2C+3G   | 1         | 1.28%   |
| AMD A10-9700 RADEON R7, 10 COMPUTE CORES 4C+6G | 1         | 1.28%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart_bsd/cpu_family.svg)

![CPU Model Family](./images/line_chart_bsd/cpu_family.svg)

| Model             | Computers | Percent |
|-------------------|-----------|---------|
| Other             | 39        | 50%     |
| Intel Xeon        | 8         | 10.26%  |
| Intel Core i7     | 8         | 10.26%  |
| Intel Core i5     | 8         | 10.26%  |
| Intel Core i3     | 3         | 3.85%   |
| AMD Ryzen 5       | 3         | 3.85%   |
| Intel Core i9     | 2         | 2.56%   |
| AMD Ryzen 9       | 2         | 2.56%   |
| Intel Xeon Silver | 1         | 1.28%   |
| Intel Celeron     | 1         | 1.28%   |
| AMD Ryzen 7       | 1         | 1.28%   |
| AMD E2            | 1         | 1.28%   |
| AMD A10           | 1         | 1.28%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart_bsd/cpu_cores.svg)

![CPU Cores](./images/line_chart_bsd/cpu_cores.svg)

| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 25        | 32.05%  |
| 4      | 19        | 24.36%  |
| 1      | 19        | 24.36%  |
| 8      | 7         | 8.97%   |
| 6      | 5         | 6.41%   |
| 3      | 2         | 2.56%   |
| 12     | 1         | 1.28%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart_bsd/cpu_sockets.svg)

![CPU Sockets](./images/line_chart_bsd/cpu_sockets.svg)

| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 54        | 69.23%  |
| 2      | 10        | 12.82%  |
| 4      | 8         | 10.26%  |
| 6      | 3         | 3.85%   |
| 8      | 2         | 2.56%   |
| 3      | 1         | 1.28%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart_bsd/cpu_threads.svg)

![CPU Threads](./images/line_chart_bsd/cpu_threads.svg)

| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 75        | 96.15%  |
| 2      | 3         | 3.85%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart_bsd/cpu_microarch.svg)

![CPU Microarch](./images/line_chart_bsd/cpu_microarch.svg)

| Name          | Computers | Percent |
|---------------|-----------|---------|
| KabyLake      | 9         | 11.54%  |
| Haswell       | 9         | 11.54%  |
| NetBurst      | 8         | 10.26%  |
| Zen 2         | 6         | 7.69%   |
| Westmere      | 6         | 7.69%   |
| Skylake       | 6         | 7.69%   |
| SandyBridge   | 4         | 5.13%   |
| IvyBridge     | 4         | 5.13%   |
| Unknown       | 4         | 5.13%   |
| Zen+          | 3         | 3.85%   |
| Excavator     | 3         | 3.85%   |
| CometLake     | 3         | 3.85%   |
| TigerLake     | 2         | 2.56%   |
| Penryn        | 2         | 2.56%   |
| K8 Hammer     | 2         | 2.56%   |
| Goldmont plus | 2         | 2.56%   |
| Broadwell     | 2         | 2.56%   |
| Zen 3         | 1         | 1.28%   |
| Zen           | 1         | 1.28%   |
| Nehalem       | 1         | 1.28%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart_bsd/gpu_vendor.svg)

![GPU Vendor](./images/line_chart_bsd/gpu_vendor.svg)

| Vendor                 | Computers | Percent |
|------------------------|-----------|---------|
| VMware                 | 38        | 48.72%  |
| Bochs                  | 16        | 20.51%  |
| Red Hat                | 13        | 16.67%  |
| Microsoft              | 5         | 6.41%   |
| InnoTek Systemberatung | 4         | 5.13%   |
| Parallels              | 1         | 1.28%   |
| Cirrus Logic           | 1         | 1.28%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart_bsd/gpu_model.svg)

![GPU Model](./images/line_chart_bsd/gpu_model.svg)

| Model                                              | Computers | Percent |
|----------------------------------------------------|-----------|---------|
| VMware SVGA II Adapter                             | 38        | 48.72%  |
| Bochs VGA                                          | 16        | 20.51%  |
| Red Hat QXL paravirtual graphic card               | 12        | 15.38%  |
| Microsoft Hyper-V virtual VGA                      | 5         | 6.41%   |
| InnoTek Systemberatung VirtualBox Graphics Adapter | 4         | 5.13%   |
| Red Hat Virtio GPU                                 | 1         | 1.28%   |
| Parallels Accelerated Virtual Video Adapter        | 1         | 1.28%   |
| Cirrus Logic GD 5446                               | 1         | 1.28%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart_bsd/gpu_combo.svg)

![GPU Combo](./images/line_chart_bsd/gpu_combo.svg)

| Name                       | Computers | Percent |
|----------------------------|-----------|---------|
| 1 x VMware                 | 38        | 48.72%  |
| Other                      | 16        | 20.51%  |
| 1 x Red Hat                | 13        | 16.67%  |
| 1 x Microsoft              | 5         | 6.41%   |
| 1 x InnoTek Systemberatung | 4         | 5.13%   |
| 1 x Parallels              | 1         | 1.28%   |
| 1 x Cirrus Logic           | 1         | 1.28%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart_bsd/gpu_driver.svg)

![GPU Driver](./images/line_chart_bsd/gpu_driver.svg)

| Driver  | Computers | Percent |
|---------|-----------|---------|
| Free    | 60        | 76.92%  |
| Unknown | 18        | 23.08%  |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart_bsd/gpu_memory.svg)

![GPU Memory](./images/line_chart_bsd/gpu_memory.svg)

| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 78        | 100%    |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart_bsd/mon_vendor.svg)

![Monitor Vendor](./images/line_chart_bsd/mon_vendor.svg)

| Vendor | Computers | Percent |
|--------|-----------|---------|
| RYI    | 4         | 100%    |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart_bsd/mon_model.svg)

![Monitor Model](./images/line_chart_bsd/mon_model.svg)

| Model                                            | Computers | Percent |
|--------------------------------------------------|-----------|---------|
| RYI 109-B5 RYI0001 1920x1440 360x270mm 17.7-inch | 4         | 100%    |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart_bsd/mon_resolution.svg)

![Monitor Resolution](./images/line_chart_bsd/mon_resolution.svg)

| Resolution | Computers | Percent |
|------------|-----------|---------|
| 1920x1440  | 4         | 100%    |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart_bsd/mon_diagonal.svg)

![Monitor Diagonal](./images/line_chart_bsd/mon_diagonal.svg)

| Inches | Computers | Percent |
|--------|-----------|---------|
| 17     | 4         | 100%    |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart_bsd/mon_width.svg)

![Monitor Width](./images/line_chart_bsd/mon_width.svg)

| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 351-400     | 4         | 100%    |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart_bsd/mon_ratio.svg)

![Aspect Ratio](./images/line_chart_bsd/mon_ratio.svg)

| Ratio | Computers | Percent |
|-------|-----------|---------|
| 4/3   | 4         | 100%    |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart_bsd/mon_area.svg)

![Monitor Area](./images/line_chart_bsd/mon_area.svg)

| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 151-200        | 4         | 100%    |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart_bsd/mon_density.svg)

![Pixel Density](./images/line_chart_bsd/mon_density.svg)

| Density | Computers | Percent |
|---------|-----------|---------|
| 121-160 | 4         | 100%    |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart_bsd/mon_total.svg)

![Multiple Monitors](./images/line_chart_bsd/mon_total.svg)

| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 71        | 91.03%  |
| 1     | 7         | 8.97%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart_bsd/net_vendor.svg)

![Net Controller Vendor](./images/line_chart_bsd/net_vendor.svg)

| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Intel                 | 41        | 52.56%  |
| Red Hat               | 21        | 26.92%  |
| VMware                | 8         | 10.26%  |
| Realtek Semiconductor | 5         | 6.41%   |
| Qumranet              | 3         | 3.85%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart_bsd/net_model.svg)

![Net Controller Model](./images/line_chart_bsd/net_model.svg)

| Model                                                    | Computers | Percent |
|----------------------------------------------------------|-----------|---------|
| Intel 82540EM Gigabit Ethernet Controller                | 22        | 27.85%  |
| Red Hat Virtio network device                            | 21        | 26.58%  |
| Intel 82545EM Gigabit Ethernet Controller (Copper)       | 14        | 17.72%  |
| VMware VMXNET3 Ethernet Controller                       | 8         | 10.13%  |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter    | 3         | 3.8%    |
| Qumranet Virtio network device                           | 3         | 3.8%    |
| Intel 82599ES 10-Gigabit SFI/SFP+ Network Connection     | 2         | 2.53%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter | 1         | 1.27%   |
| Realtek RTL8125 2.5GbE Controller                        | 1         | 1.27%   |
| Intel I350 Gigabit Network Connection                    | 1         | 1.27%   |
| Intel Ethernet Controller X710 for 10GbE SFP+            | 1         | 1.27%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]             | 1         | 1.27%   |
| Intel 82574L Gigabit Network Connection                  | 1         | 1.27%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart_bsd/net_wireless_vendor.svg)

![Wireless Vendor](./images/line_chart_bsd/net_wireless_vendor.svg)

| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Realtek Semiconductor | 1         | 50%     |
| Intel                 | 1         | 50%     |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart_bsd/net_wireless_model.svg)

![Wireless Model](./images/line_chart_bsd/net_wireless_model.svg)

| Model                                                    | Computers | Percent |
|----------------------------------------------------------|-----------|---------|
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter | 1         | 50%     |
| Intel Centrino Wireless-N 1000 [Condor Peak]             | 1         | 50%     |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart_bsd/net_ethernet_vendor.svg)

![Ethernet Vendor](./images/line_chart_bsd/net_ethernet_vendor.svg)

| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Intel                 | 40        | 76.92%  |
| VMware                | 8         | 15.38%  |
| Realtek Semiconductor | 4         | 7.69%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart_bsd/net_ethernet_model.svg)

![Ethernet Model](./images/line_chart_bsd/net_ethernet_model.svg)

| Model                                                 | Computers | Percent |
|-------------------------------------------------------|-----------|---------|
| Intel 82540EM Gigabit Ethernet Controller             | 22        | 41.51%  |
| Intel 82545EM Gigabit Ethernet Controller (Copper)    | 14        | 26.42%  |
| VMware VMXNET3 Ethernet Controller                    | 8         | 15.09%  |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter | 3         | 5.66%   |
| Intel 82599ES 10-Gigabit SFI/SFP+ Network Connection  | 2         | 3.77%   |
| Realtek RTL8125 2.5GbE Controller                     | 1         | 1.89%   |
| Intel I350 Gigabit Network Connection                 | 1         | 1.89%   |
| Intel Ethernet Controller X710 for 10GbE SFP+         | 1         | 1.89%   |
| Intel 82574L Gigabit Network Connection               | 1         | 1.89%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart_bsd/net_kind.svg)

![Net Controller Kind](./images/line_chart_bsd/net_kind.svg)

| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 50        | 65.79%  |
| Unknown  | 24        | 31.58%  |
| WiFi     | 2         | 2.63%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart_bsd/net_used.svg)

![Used Controller](./images/line_chart_bsd/net_used.svg)

| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 50        | 86.21%  |
| Unknown  | 8         | 13.79%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart_bsd/net_nics.svg)

![NICs](./images/line_chart_bsd/net_nics.svg)

| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 43        | 55.13%  |
| 2     | 17        | 21.79%  |
| 3     | 6         | 7.69%   |
| 0     | 5         | 6.41%   |
| 4     | 4         | 5.13%   |
| 6     | 3         | 3.85%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart_bsd/node_ipv6.svg)

![IPv6](./images/line_chart_bsd/node_ipv6.svg)

| Used | Computers | Percent |
|------|-----------|---------|
| No   | 73        | 93.59%  |
| Yes  | 5         | 6.41%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart_bsd/bt_vendor.svg)

![Bluetooth Vendor](./images/line_chart_bsd/bt_vendor.svg)

| Vendor | Computers | Percent |
|--------|-----------|---------|
| VMware | 1         | 100%    |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart_bsd/bt_model.svg)

![Bluetooth Model](./images/line_chart_bsd/bt_model.svg)

| Model                            | Computers | Percent |
|----------------------------------|-----------|---------|
| VMware Virtual Bluetooth Adapter | 1         | 100%    |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart_bsd/snd_vendor.svg)

![Sound Vendor](./images/line_chart_bsd/snd_vendor.svg)

| Vendor  | Computers | Percent |
|---------|-----------|---------|
| Intel   | 42        | 80.77%  |
| Ensoniq | 10        | 19.23%  |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart_bsd/snd_model.svg)

![Sound Model](./images/line_chart_bsd/snd_model.svg)

| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Intel 82801AA AC'97 Audio Controller                                       | 20        | 38.46%  |
| Intel 82801FB/FBM/FR/FW/FRW (ICH6 Family) High Definition Audio Controller | 11        | 21.15%  |
| Ensoniq ES1371/ES1373 / Creative Labs CT2518                               | 10        | 19.23%  |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 9         | 17.31%  |
| Intel Sunrise Point-LP HD Audio                                            | 1         | 1.92%   |
| Intel 82801BA/BAM AC'97 Audio Controller                                   | 1         | 1.92%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart_bsd/memory_vendor.svg)

![Memory Vendor](./images/line_chart_bsd/memory_vendor.svg)

| Vendor             | Computers | Percent |
|--------------------|-----------|---------|
| QEMU               | 30        | 52.63%  |
| Unknown            | 18        | 31.58%  |
| Microsoft          | 5         | 8.77%   |
| VMware Virtual RAM | 3         | 5.26%   |
| Unknown            | 1         | 1.75%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart_bsd/memory_model.svg)

![Memory Model](./images/line_chart_bsd/memory_model.svg)

| Model                                            | Computers | Percent |
|--------------------------------------------------|-----------|---------|
| Unknown                                          | 18        | 26.87%  |
| QEMU RAM Module 2GB DIMM RAM                     | 8         | 11.94%  |
| QEMU RAM Module 4GB DIMM RAM                     | 6         | 8.96%   |
| QEMU RAM Module 8GB DIMM RAM                     | 4         | 5.97%   |
| Microsoft RAM Module 3968MB                      | 3         | 4.48%   |
| VMware Virtual RAM RAM VMW-8192MB 8GB DIMM DRAM  | 2         | 2.99%   |
| QEMU RAM Module 3GB DIMM RAM                     | 2         | 2.99%   |
| QEMU RAM Module 16GB DIMM RAM                    | 2         | 2.99%   |
| Microsoft RAM Module 2GB                         | 2         | 2.99%   |
| Microsoft RAM Module 128MB                       | 2         | 2.99%   |
| VMware Virtual RAM RAM VMW-512MB 512MB DIMM DRAM | 1         | 1.49%   |
| VMware Virtual RAM RAM VMW-4096MB 4GB DIMM DRAM  | 1         | 1.49%   |
| VMware Virtual RAM RAM VMW-32MB 32MB DIMM DRAM   | 1         | 1.49%   |
| VMware Virtual RAM RAM VMW-256MB 256MB DIMM DRAM | 1         | 1.49%   |
| VMware Virtual RAM RAM VMW-2048MB 2GB DIMM DRAM  | 1         | 1.49%   |
| VMware Virtual RAM RAM VMW-128MB 128MB DIMM DRAM | 1         | 1.49%   |
| VMware Virtual RAM RAM VMW-1024MB 1GB DIMM DRAM  | 1         | 1.49%   |
| Unknown RAM Module 64MB DIMM DRAM                | 1         | 1.49%   |
| Unknown RAM Module 128MB DIMM DRAM               | 1         | 1.49%   |
| QEMU RAM Module 8096MB DIMM RAM                  | 1         | 1.49%   |
| QEMU RAM Module 6GB DIMM RAM                     | 1         | 1.49%   |
| QEMU RAM Module 6148MB DIMM RAM                  | 1         | 1.49%   |
| QEMU RAM Module 4064MB DIMM RAM                  | 1         | 1.49%   |
| QEMU RAM Module 4000MB DIMM RAM                  | 1         | 1.49%   |
| QEMU RAM Module 16000MB DIMM RAM                 | 1         | 1.49%   |
| QEMU RAM Module 1536MB DIMM RAM                  | 1         | 1.49%   |
| QEMU RAM Module 10GB DIMM RAM                    | 1         | 1.49%   |
| Microsoft RAM Module 4228MB                      | 1         | 1.49%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart_bsd/memory_kind.svg)

![Memory Kind](./images/line_chart_bsd/memory_kind.svg)

| Kind    | Computers | Percent |
|---------|-----------|---------|
| RAM     | 30        | 53.57%  |
| DRAM    | 21        | 37.5%   |
| Unknown | 5         | 8.93%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart_bsd/memory_formfactor.svg)

![Memory Form Factor](./images/line_chart_bsd/memory_formfactor.svg)

| Name    | Computers | Percent |
|---------|-----------|---------|
| DIMM    | 50        | 89.29%  |
| Unknown | 5         | 8.93%   |
| SODIMM  | 1         | 1.79%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart_bsd/memory_size.svg)

![Memory Size](./images/line_chart_bsd/memory_size.svg)

| Size  | Computers | Percent |
|-------|-----------|---------|
| 2048  | 16        | 22.22%  |
| 4096  | 15        | 20.83%  |
| 8192  | 11        | 15.28%  |
| 128   | 4         | 5.56%   |
| 3968  | 3         | 4.17%   |
| 1024  | 3         | 4.17%   |
| 16384 | 2         | 2.78%   |
| 3072  | 2         | 2.78%   |
| 512   | 2         | 2.78%   |
| 256   | 2         | 2.78%   |
| 16000 | 1         | 1.39%   |
| 10240 | 1         | 1.39%   |
| 8096  | 1         | 1.39%   |
| 6148  | 1         | 1.39%   |
| 6144  | 1         | 1.39%   |
| 4228  | 1         | 1.39%   |
| 4064  | 1         | 1.39%   |
| 4000  | 1         | 1.39%   |
| 1536  | 1         | 1.39%   |
| 64    | 1         | 1.39%   |
| 32    | 1         | 1.39%   |
| 16    | 1         | 1.39%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart_bsd/memory_speed.svg)

![Memory Speed](./images/line_chart_bsd/memory_speed.svg)

| Speed   | Computers | Percent |
|---------|-----------|---------|
| Unknown | 55        | 98.21%  |
| 667     | 1         | 1.79%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart_bsd/printer_vendor.svg)

![Printer Vendor](./images/line_chart_bsd/printer_vendor.svg)

| Vendor    | Computers | Percent |
|-----------|-----------|---------|
| PARALLELS | 1         | 100%    |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart_bsd/printer_model.svg)

![Printer Model](./images/line_chart_bsd/printer_model.svg)

| Model                                                                           | Computers | Percent |
|---------------------------------------------------------------------------------|-----------|---------|
| PARALLELS Virtual Printer (/Users/m/Parallels/HelloSystem 0.8.pvm/parallel.txt) | 1         | 100%    |

Scanner Vendor
--------------

Scanner device vendors

Zero info for selected period =(

Scanner Model
-------------

Scanner device models

Zero info for selected period =(

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart_bsd/camera_vendor.svg)

![Camera Vendor](./images/line_chart_bsd/camera_vendor.svg)

| Vendor    | Computers | Percent |
|-----------|-----------|---------|
| PARALLELS | 1         | 100%    |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart_bsd/camera_model.svg)

![Camera Model](./images/line_chart_bsd/camera_model.svg)

| Model                        | Computers | Percent |
|------------------------------|-----------|---------|
| PARALLELS FaceTime HD Camera | 1         | 100%    |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

Zero info for selected period =(

Fingerprint Model
-----------------

Fingerprint sensor models

Zero info for selected period =(

Chipcard Vendor
---------------

Chipcard module vendors

Zero info for selected period =(

Chipcard Model
--------------

Chipcard module models

Zero info for selected period =(

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart_bsd/device_unsupported.svg)

![Unsupported Devices](./images/line_chart_bsd/device_unsupported.svg)

| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 76        | 97.44%  |
| 1     | 2         | 2.56%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart_bsd/device_unsupported_type.svg)

![Unsupported Device Types](./images/line_chart_bsd/device_unsupported_type.svg)

| Type         | Computers | Percent |
|--------------|-----------|---------|
| Net/wireless | 2         | 100%    |

