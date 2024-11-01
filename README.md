# ASUS GL552VW Hackintosh - Monterey version

My first time hackintosh for GL552VW, updated to Monterey
> I'll try to update to Sonoma/Sequoia but this device is old as fuck so it may not boot at all :)

## Specifications

```bash
00:00.0 Host bridge [0600]: Intel Corporation Xeon E3-1200 v5/E3-1500 v5/6th Gen Core Processor Host Bridge/DRAM Registers [8086:1910] (rev 07)
00:01.0 PCI bridge [0604]: Intel Corporation 6th-10th Gen Core Processor PCIe Controller (x16) [8086:1901] (rev 07)
00:02.0 VGA compatible controller [0300]: Intel Corporation HD Graphics 530 [8086:191b] (rev 06)
00:04.0 Signal processing controller [1180]: Intel Corporation Xeon E3-1200 v5/E3-1500 v5/6th Gen Core Processor Thermal Subsystem [8086:1903] (rev 07)
00:14.0 USB controller [0c03]: Intel Corporation 100 Series/C230 Series Chipset Family USB 3.0 xHCI Controller [8086:a12f] (rev 31)
00:14.2 Signal processing controller [1180]: Intel Corporation 100 Series/C230 Series Chipset Family Thermal Subsystem [8086:a131] (rev 31)
00:15.0 Signal processing controller [1180]: Intel Corporation 100 Series/C230 Series Chipset Family Serial IO I2C Controller #0 [8086:a160] (rev 31)
00:15.1 Signal processing controller [1180]: Intel Corporation 100 Series/C230 Series Chipset Family Serial IO I2C Controller #1 [8086:a161] (rev 31)
00:16.0 Communication controller [0780]: Intel Corporation 100 Series/C230 Series Chipset Family MEI Controller #1 [8086:a13a] (rev 31)
00:17.0 SATA controller [0106]: Intel Corporation HM170/QM170 Chipset SATA Controller [AHCI Mode] [8086:a103] (rev 31)
00:1c.0 PCI bridge [0604]: Intel Corporation 100 Series/C230 Series Chipset Family PCI Express Root Port #3 [8086:a112] (rev f1)
00:1c.3 PCI bridge [0604]: Intel Corporation 100 Series/C230 Series Chipset Family PCI Express Root Port #4 [8086:a113] (rev f1)
00:1f.0 ISA bridge [0601]: Intel Corporation HM170 Chipset LPC/eSPI Controller [8086:a14e] (rev 31)
00:1f.2 Memory controller [0580]: Intel Corporation 100 Series/C230 Series Chipset Family Power Management Controller [8086:a121] (rev 31)
00:1f.3 Audio device [0403]: Intel Corporation 100 Series/C230 Series Chipset Family HD Audio Controller [8086:a170] (rev 31)
00:1f.4 SMBus [0c05]: Intel Corporation 100 Series/C230 Series Chipset Family SMBus [8086:a123] (rev 31)
01:00.0 3D controller [0302]: NVIDIA Corporation GM107M [GeForce GTX 960M] [10de:139b] (rev a2)
02:00.0 Network controller [0280]: Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter [168c:0036] (rev 01)
03:00.0 Unassigned class [ff00]: Realtek Semiconductor Co., Ltd. RTL8411B PCI Express Card Reader [10ec:5287] (rev 01)
03:00.1 Ethernet controller [0200]: Realtek Semiconductor Co., Ltd. RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller [10ec:8168] (rev 12)

```

### Working

+ Ethernet (LAN)
+ SATA drives
+ All USB ports
+ Keyboard

### Not Working

+ Keyboard backlight 
+ Wifi (Driver is not compatible with Monterey)
+ Touchpad (Help me fix please)
+ NVIDIA GPU
> The AR9565 is so bad that only 2.4ghz so I just used my Android along with USB tethering instead.

#### License

[MIT](./LICENSE), all Kexts belong to their owners with their licenses.
> This project is forked from [baobaoit/Asus-ROG-GL552VW-Hackintosh](https://github.com/baobaoit/Asus-ROG-GL552VW-Hackintosh) with some changes for my laptop (broken BIOS and other wifi card)
