# nardole

```
System:    Host: nardole Kernel: 6.3.5 x86_64 bits: 64 compiler: gcc v: 11.3.0 
           parameters: initrd=\efi\nixos\1i38sn8spkzhmny6slmpr47jcr0ic9hc-initrd-linux-6.3.5-initrd.efi 
           init=/nix/store/ivwrzkkrvjmxsq6j7b82x9mnfiw09hrk-nixos-system-nardole-22.11.20230613.14ff5cd/init 
           console=tty0 console=ttyS0,115200 console=ttyS1,115200n8 console=tty1 nohibernate 
           loglevel=4 
           Console: N/A Distro: NixOS 22.11 (Raccoon) 
Machine:   Type: Desktop System: sysGen www.sysgen.de product: Super Server v: 0123456789 
           serial: 0123456789 Chassis: type: 3 v: 0123456789 serial: 0123456789 
           Mobo: Supermicro model: X12SCZ-TLN4F v: 1.01A serial: UM20BS000427 
           UEFI: American Megatrends v: 1.0a date: 01/11/2021 
Memory:    RAM: total: 125.69 GiB used: 85.06 GiB (67.7%) 
           Array-1: capacity: 128 GiB note: est. slots: 4 EC: None max-module-size: 32 GiB 
           note: est. 
           Device-1: DIMMA1 size: 32 GiB speed: 2400 MT/s type: DDR4 
           detail: synchronous unbuffered (unregistered) bus-width: 64 bits total: 64 bits 
           manufacturer: Kingston part-no: KHX3200C16D4/32GX serial: 825151A9 
           Device-2: DIMMA2 size: 32 GiB speed: 2400 MT/s type: DDR4 
           detail: synchronous unbuffered (unregistered) bus-width: 64 bits total: 64 bits 
           manufacturer: Kingston part-no: KHX3200C16D4/32GX serial: 735150BB 
           Device-3: DIMMB1 size: 32 GiB speed: 2400 MT/s type: DDR4 
           detail: synchronous unbuffered (unregistered) bus-width: 64 bits total: 64 bits 
           manufacturer: Kingston part-no: KHX3200C16D4/32GX serial: 735171CE 
           Device-4: DIMMB2 size: 32 GiB speed: 2400 MT/s type: DDR4 
           detail: synchronous unbuffered (unregistered) bus-width: 64 bits total: 64 bits 
           manufacturer: Kingston part-no: KHX3200C16D4/32GX serial: 041171D8 
PCI Slots: Slot: 4 type: x4 PCI Express 3 x8 PCH SLOT4 PCI-E 3.0 X4 (IN X8) status: In Use 
           length: Short 
           Slot: 6 type: x16 PCI Express 3 x16 CPU SLOT6 PCI-E 3.0 X16 status: In Use length: Long 
           Slot: 7 type: x4 PCI Express 3 x4 PCH SLOT7 PCI-E 3.0 X4 status: Available 
           length: Short 
           Slot: N/A type: x4 M.2 Socket 3 PCI-E M.2-M1 status: Available length: Short 
           Slot: N/A type: x1 M.2 Socket 1-SD PCI-E M.2-E1 status: Available length: Short 
CPU:       Info: 10-Core model: Intel Core i9-10900K bits: 64 type: MT MCP arch: Comet Lake 
           family: 6 model-id: A5 (165) stepping: 5 microcode: E0 cache: L1: 640 KiB L2: 20 MiB 
           L3: 20 MiB 
           flags: avx avx2 lm nx pae sse sse2 sse3 sse4_1 sse4_2 ssse3 vmx bogomips: 147994 
           Speed: 800 MHz min/max: 800/5300 MHz base/boost: 3600/3700 volts: 1.0 V 
           ext-clock: 100 MHz Core speeds (MHz): 1: 800 2: 4468 3: 4696 4: 3700 5: 3700 6: 3700 
           7: 1301 8: 3700 9: 4765 10: 3700 11: 3700 12: 3700 13: 1226 14: 3700 15: 3700 16: 3700 
           17: 3700 18: 4296 19: 800 20: 3700 
           Vulnerabilities: Type: itlb_multihit status: KVM: VMX disabled 
           Type: l1tf status: Not affected 
           Type: mds status: Not affected 
           Type: meltdown status: Not affected 
           Type: mmio_stale_data 
           status: Vulnerable: Clear CPU buffers attempted, no microcode; SMT vulnerable 
           Type: retbleed mitigation: Enhanced IBRS 
           Type: spec_store_bypass mitigation: Speculative Store Bypass disabled via prctl 
           Type: spectre_v1 mitigation: usercopy/swapgs barriers and __user pointer sanitization 
           Type: spectre_v2 mitigation: Enhanced / Automatic IBRS, IBPB: conditional, RSB filling, 
           PBRSB-eIBRS: SW sequence 
           Type: srbds status: Vulnerable: No microcode 
           Type: tsx_async_abort status: Not affected 
Graphics:  Device-1: ASPEED Graphics Family vendor: Super Micro driver: ast v: kernel 
           bus-ID: 05:00.0 chip-ID: 1a03:2000 class-ID: 0300 
           Display: server: No display server data found. Headless machine? tty: N/A 
           Message: Advanced graphics data unavailable in console for root. 
Audio:     Device-1: Intel Comet Lake PCH cAVS vendor: Super Micro driver: snd_hda_intel v: kernel 
           alternate: snd_soc_skl,snd_sof_pci_intel_cnl bus-ID: 00:1f.3 chip-ID: 8086:06c8 
           class-ID: 0403 
           Sound Server-1: ALSA v: k6.3.5 running: yes 
Network:   Device-1: Intel Ethernet I219-LM vendor: Super Micro driver: e1000e v: kernel 
           port: efa0 bus-ID: 00:1f.6 chip-ID: 8086:0d4c class-ID: 0200 
           IF: eno1 state: down mac: 3c:ec:ef:2c:f5:14 
           Device-2: Mellanox MT27710 Family [ConnectX-4 Lx] driver: mlx5_core v: kernel 
           port: efa0 bus-ID: 02:00.0 chip-ID: 15b3:1015 class-ID: 0200 
           IF: slave0 state: up speed: 10000 Mbps duplex: full mac: b8:ce:f6:0b:ee:74 
           Device-3: Mellanox MT27710 Family [ConnectX-4 Lx] driver: mlx5_core v: kernel 
           port: efa0 bus-ID: 02:00.1 chip-ID: 15b3:1015 class-ID: 0200 
           IF: slave1 state: up speed: 10000 Mbps duplex: full mac: b8:ce:f6:0b:ee:74 
           Device-4: Intel I210 Gigabit Network vendor: Super Micro driver: igb v: kernel 
           port: 4000 bus-ID: 03:00.0 chip-ID: 8086:1533 class-ID: 0200 
           IF: eno2 state: down mac: 3c:ec:ef:2c:f5:15 
           Device-5: Intel Ethernet X550 vendor: Super Micro driver: ixgbe v: kernel port: 3000 
           bus-ID: 06:00.0 chip-ID: 8086:1563 class-ID: 0200 
           IF: eno3 state: down mac: 3c:ec:ef:30:36:1a 
           Device-6: Intel Ethernet X550 vendor: Super Micro driver: ixgbe v: kernel port: 3000 
           bus-ID: 06:00.1 chip-ID: 8086:1563 class-ID: 0200 
           IF: eno4 state: down mac: 3c:ec:ef:30:36:1b 
           IF-ID-1: bond1 state: up speed: 20000 Mbps duplex: full mac: b8:ce:f6:0b:ee:74 
           IP v4: 131.159.102.2/24 type: dynamic scope: global 
           IP v6: 2a09:80c0:102::2/128 type: dynamic noprefixroute scope: global 
           IP v6: 2a09:80c0:102::f000:0/64 scope: global 
           IP v6: fe80::bace:f6ff:fe0b:ee74/64 scope: link 
           IF-ID-2: bonding_masters state: N/A speed: N/A duplex: N/A mac: N/A 
           IF-ID-3: docker0 state: down mac: 02:42:5b:af:6e:0b 
           IP v4: 172.17.0.1/16 scope: global broadcast: 172.17.255.255 
           IF-ID-4: eth0 state: down mac: b0:3a:f2:b6:05:9f 
           IF-ID-5: tinc.retiolum state: unknown speed: 10000 Mbps duplex: full mac: N/A 
           IP v6: 42:0:3c46:362d:a9aa:4996:c78e:839a/16 scope: global 
           WAN IP: 131.159.102.2 
Bluetooth: Device-1: Insyde RNDIS/Ethernet Gadget type: USB driver: rndis_host v: kernel 
           bus-ID: 1-13.2:4 chip-ID: 0b1f:03ee class-ID: 0a00 
           Report: This feature requires one of these tools: hciconfig/bt-adapter 
RAID:      Device-1: zpool1 type: zfs status: ONLINE level: linear size: 928 GiB free: 180 GiB 
           allocated: 748 GiB 
           Components: Online: N/A 
           Device-2: zpool2 type: zfs status: ONLINE level: linear size: 14.5 TiB free: 13.6 TiB 
           allocated: 936 GiB 
           Components: Online: N/A 
           Device-3: zroot type: zfs status: ONLINE level: linear size: 888 GiB free: 814 GiB 
           allocated: 73.8 GiB 
           Components: Online: N/A 
Drives:    Local Storage: total: raw: 23.62 TiB usable: 39.89 TiB used: 1.38 TiB (3.5%) 
           ID-1: /dev/nvme0n1 maj-min: 259:0 vendor: Samsung model: SSD 970 EVO Plus 1TB 
           size: 931.51 GiB block-size: physical: 512 B logical: 512 B speed: 31.6 Gb/s lanes: 4 
           rotation: SSD serial: S4EWNX0R410276D rev: 2B2QEXM7 temp: -273° (0 Kelvin) C 
           scheme: GPT 
           SMART: yes health: PASSED on: 59d 16h cycles: 5 read-units: 81,844,376 [41.9 TB] 
           written-units: 25,492,960 [13.0 TB] 
           ID-2: /dev/sda maj-min: 8:0 vendor: Samsung model: MZ7LH960HAJR-00005 
           family: based SSDs size: 894.25 GiB block-size: physical: 4096 B logical: 512 B 
           sata: 3.2 speed: 6.0 Gb/s rotation: SSD serial: S45NNA0N900985 rev: 404Q temp: 25 C 
           scheme: GPT 
           SMART: yes state: enabled health: PASSED on: 2y 107d 15h cycles: 44 read: 17.83 TiB 
           written: 30.97 TiB 
           ID-3: /dev/sdb maj-min: 8:16 vendor: Western Digital model: WD80EFBX-68AZZN0 
           size: 7.28 TiB block-size: physical: 4096 B logical: 512 B sata: 3.2 speed: 6.0 Gb/s 
           rotation: 7200 rpm serial: VRHZGW5K rev: 0A85 temp: 32 C scheme: GPT 
           SMART: yes state: enabled health: PASSED on: 1y 228d 23h cycles: 3 
           ID-4: /dev/sdc maj-min: 8:32 vendor: Western Digital model: WD80EFBX-68AZZN0 
           size: 7.28 TiB block-size: physical: 4096 B logical: 512 B sata: 3.2 speed: 6.0 Gb/s 
           rotation: 7200 rpm serial: VRJ0RM2K rev: 0A85 temp: 30 C scheme: GPT 
           SMART: yes state: enabled health: PASSED on: 1y 228d 23h cycles: 3 
           ID-5: /dev/sdd maj-min: 8:48 vendor: Western Digital model: WD80EFBX-68AZZN0 
           size: 7.28 TiB block-size: physical: 4096 B logical: 512 B sata: 3.2 speed: 6.0 Gb/s 
           rotation: 7200 rpm serial: VRJ0HPEK rev: 0A85 temp: 29 C scheme: GPT 
           SMART: yes state: enabled health: PASSED on: 1y 228d 23h cycles: 3 
Partition: ID-1: / raw-size: N/A size: 835.11 GiB used: 49.39 GiB (5.9%) fs: zfs 
           logical: zroot/root/nixos 
           ID-2: /boot raw-size: 500 MiB size: 499.7 MiB (99.95%) used: 82.6 MiB (16.5%) fs: vfat 
           block-size: 512 B dev: /dev/sda1 maj-min: 8:1 
           ID-3: /tmp raw-size: N/A size: 785.8 GiB used: 74.6 MiB (0.0%) fs: zfs 
           logical: zroot/root/tmp 
Swap:      Alert: No swap data was found. 
Sensors:   Message: No ipmi sensor data found. 
           System Temperatures: lm-sensors cpu: 38.0 C mobo: N/A 
           Fan Speeds (RPM): lm-sensors N/A 
Info:      Processes: 549 
           Uptime: 13:11:53  up 2 days 13:08,  0 users,  load average: 0.24, 0.05, 0.02 wakeups: 0 
           Init: systemd v: 251 target: multi-user.target tool: systemctl Compilers: gcc: 11.3.0 
           Packages: nix-default: 0 nix-sys: 418 lib: 69 nix-usr: 0 Client: Sudo v: 1.9.13p3 
           inxi: 3.3.04 
```
![hardware topology](nardole.lstopo.svg)
