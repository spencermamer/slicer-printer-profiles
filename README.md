# Sovol SV04 Slicer Profiles

## Consolidated PrusaSlicer Profiles

This repository contains consolidated PrusaSlicer profiles for various printers, filaments, and print settings. The profiles have been organized and cleaned up to provide a more streamlined experience.

### Removed CNC Profiles

The following CNC profiles have been removed from the repository:
- `CNC/PrusaSlicer/filament/CNC.ini`
- `CNC/PrusaSlicer/print/CNC Dremel Scribe 3mm Outline.ini`
- `CNC/PrusaSlicer/print/CNC Dremel Scribe 3mm Surface.ini`
- `CNC/PrusaSlicer/print/CNC Mill 3.2mm.ini`
- `CNC/PrusaSlicer/printer/E3V2 CNC Dremel Scribe 3 mm Outline.ini`
- `CNC/PrusaSlicer/printer/E3V2 CNC Dremel Scribe 3 mm Surface.ini`
- `CNC/PrusaSlicer/printer/E3V2 CNC Mill 3-5mm.ini`

### New Consolidated Profiles

The new consolidated profiles include settings for different printers, filaments, and print settings. These profiles are designed to be more efficient and easier to manage.

### How to Use

1. **Profile Types**: PrusaSlicer uses three main types of profiles: Printer, Filament, and Print settings. Each profile type can be customized to suit specific needs.
2. **Profile Files**: Profiles are stored in `.ini` files. For example, `PrusaSlicer-SV04/PrusaSlicer/filament/ABS - SV04.ini` is a filament profile, and `PrusaSlicer-SV04/PrusaSlicer/print/Detail 0.08mm with Scripts (0.4mm nozzle) SV04.ini` is a print settings profile.
3. **Profile Location**: Profiles are typically stored in the `%APPDATA%\PrusaSlicer` directory on Windows. You can copy profiles to this directory to make them available in PrusaSlicer.
4. **Custom G-code**: Profiles can include custom G-code for specific actions, such as start and end G-code. For example, `PrusaSlicer-SV04/PrusaSlicer/printer/SV04 Dual and Single Mode (0.4mm nozzle).ini` includes custom start and end G-code.
5. **Inheritance**: Profiles can inherit settings from other profiles using the `inherits` attribute. This allows for creating base profiles and extending them with specific settings.
6. **Post-Processing Scripts**: Profiles can include post-processing scripts to modify the generated G-code. For example, the `post_process` attribute in `PrusaSlicer-SV04/PrusaSlicer/print/Detail 0.08mm with Scripts (0.4mm nozzle) SV04.ini` specifies scripts to run after slicing.
7. **Profile Management in PrusaSlicer**: You can manage profiles directly within PrusaSlicer by importing, exporting, and editing them through the user interface.

For more detailed information, you can refer to the profiles in the repository, such as those in the `PrusaSlicer-SV04/PrusaSlicer` directory.
