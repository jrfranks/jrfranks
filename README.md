# John R. Franks

Kernel, filesystems, device drivers, and board bring-up. Contract and rescue work. US remote.

I have shipped storage and firmware that had to stay up: filesystem and on-disk layout, distributed object storage, RAID and disk-controller firmware, SCSI, USB, disk and network drivers, and board bring-up. Patent [US 8,793,527](https://patents.google.com/patent/US8793527B1) covers distributed storage clusters. Public work is userspace and firmware. The kernel and driver record is the employment history, not a GitHub repo.

## What I take

- Filesystems, block layout, and storage control planes
- Device drivers and kernel debugging in C
- Board bring-up, boot firmware, and hardware debug
- Embedded firmware: AVR, Arduino, ESP32, Nerves
- Conformance and failure-mode tests for the above

## Public work

- [ArkFS](https://github.com/jrfranks/ArkFS) — never-delete temporal FUSE filesystem in Rust, with an Elixir simulation harness and POSIX/FUSE conformance tests. Userspace, not an in-kernel filesystem.
- [MoistureController](https://github.com/jrfranks/MoistureController) — fail-closed AVR irrigation controller. Sleep-current budget, alarm wake, power-gated sensing, CRC EEPROM. Active tree is `firmware/avr-ultra/`.
- [BatteryManager](https://github.com/jrfranks/BatteryManager) — Arduino charge controller for lead-acid, LiFePO4, and Li-ion.

Independent. I own architecture, review, and what ships.
