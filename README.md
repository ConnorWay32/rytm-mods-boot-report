# rytm-mods-boot-report

Evidence for the Elektron Analog Rytm MKII on OS 1.73, for Modwerk's [Add a machine](https://github.com/repeat98/modwerk/blob/main/docs/ADD_A_MACHINE.md) steps 2, 3 and 4:

- **Stock file rebuilt exactly:** Elektron's OS 1.73 `.syx` unpacked and repacked byte for byte (matching SHA-256).
- **Modified OS boots:** a build of [rytm-mods-src](https://github.com/ConnorWay32/rytm-mods-src) flashed to a real unit, booted with a working mod, and recovered with the stock OS.
- **Core with hooks:** elekloader's core for the Rytm (`mods/core-ar2`) with two test mods, every shared event observed on a unit.

See [BOOT_REPORT.md](BOOT_REPORT.md) (steps 2 and 3) and [CORE_REPORT.md](CORE_REPORT.md) (step 4). No firmware is included; only hashes, sizes, addresses, observations and photos.
