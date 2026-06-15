# HP Pavilion 14 CE-1005NA — Hackintosh OpenCore EFI

Working **OpenCore** EFI folder for an HP Pavilion 14 CE-1005NA running
macOS Catalina (2020).

Replaces the older Clover EFI in [m3rtngs/EFI](https://github.com/m3rtngs/EFI).

## Specs

- HP Pavilion 14-ce1005na
- Intel Core i5-8265U (Whiskey Lake)
- Intel UHD 620
- 8 GB RAM
- macOS Catalina (10.15)

## What's in here

```
EFI/
├── BOOT/    # BOOTx64.efi
└── OC/      # OpenCore + config.plist, ACPI patches, kexts, drivers
```

## Use

1. Mount your EFI partition.
2. Replace the `EFI/` folder with the one in this repo.
3. Reboot — choose macOS at the OpenCore picker.

Tested with OpenCore from late 2020. Newer macOS releases will need
config.plist updates (Sample.plist comparisons, OpenCore upgrade guide).

> Archived — kept for reference. Battery and brightness work; sleep / Wi-Fi
> behaviour depends on the specific BCM chip your model shipped with.
