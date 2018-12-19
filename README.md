# Lenovo-g505s-binaries-for-coreboot
This repository contains all need binaries/firmwares (blobs) for opensource BIOS coreboot
<br>

1) AHCI blob: change SATA mode to 5: AHCI7804: ROM Required, and AMD driver required in the OS. and select blob and change VID/PID on yours. SHA512: "fc8a30722bdf31170ce9eda75d0bc253998fe867529cd577c9b4c1097ef0751a436ef045c6d07f9b4452bfb0dc56cced265903638f8a4ba3e62133bc04322016"
<br>

2) USB 3.0:
2.1) xhci_coreboot.bin - blob from coreboot repository
2.2) extracted_from_stock_bios_2.05 (0.10.0_1022_7814).bin - blob extracted via https://github.com/felixheld/fch_xhci_rom_dumper from stock bios (v 2.05)
