# Hardware

This document records the practical hardware configuration needed for maintenance,
compatibility checks, upgrades, and environment recovery.

Only publish information that is useful for those purposes. This is a public
repository, not a complete hardware inventory.

## Main laptop

- **Device:** Acer Nitro V 15
- **Platform:** AMD
- **CPU:** AMD Ryzen 5 7535HS — 6 cores / 12 threads
- **Graphics:** NVIDIA GeForce RTX 4050 Laptop GPU, 6 GB; integrated AMD Radeon Graphics
- **Memory:** 32 GB DDR5 SO-DIMM (2 × 16 GB), currently operating at 4800 MT/s
- **System storage:** Kingston NVMe SSD, approximately 512 GB
- **Additional storage:** Kingston NVMe SSD, approximately 1 TB
- **Display:** 15.6-inch-class Full HD panel, 144 Hz
- **Wireless:** Wi-Fi 6 and Bluetooth
- **Wired network:** Gigabit Ethernet
- **Operating system:** Windows 11 Pro, x64
- **Firmware interface:** UEFI

### Maintenance notes

- Keep exact firmware, BIOS, embedded-controller, VBIOS, SSD firmware, and driver
  versions in a private local inventory if they are needed for troubleshooting.
- Do not publish board identifiers, hardware IDs, serial numbers, UUIDs, MAC
  addresses, Windows installation identifiers, or diagnostic exports.
- Verify SSD temperatures with a trusted monitoring utility before drawing
  conclusions from individual sensor readings. Keep detailed sensor output private.
- Check cooling performance under load and during idle operation.
- Record upgrade compatibility and maintenance outcomes without including
  device-unique identifiers.

## Desktop PC

Known configuration (verify before treating as current):

- **CPU:** Intel Core i5-3470
- **GPU:** NVIDIA GeForce GT 1030
- **Monitor:** 27-inch, 60 Hz

## Peripherals

Add monitors, keyboard, mouse, audio devices, and other peripherals when useful.

## Publication rule

The public hardware profile should describe capabilities, not expose a precise
fingerprint of the machine. Detailed diagnostic reports belong in private storage.
