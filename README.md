[![CI status](https://github.com/eic/epic/actions/workflows/linux-eic-shell.yml/badge.svg)](https://github.com/eic/epic/actions/workflows/linux-eic-shell.yml)

Overview
--------

<a href="https://eic.github.io/epic/artifacts/epic_craterlake_views/view1_top.pdf"><img align="right" alt="craterlake" src="https://eic.github.io/epic/artifacts/epic_craterlake_views/view1_top.png" width="70%"/></a>

**Detector geometry:**
- [Empty viewer](https://eic.github.io/epic/geoviewer)
- Craterlake: [viewer](https://eic.github.io/epic/geoviewer?nobrowser&file=artifacts/tgeo/epic_craterlake.root&item=default;1&opt=clipx;clipy;transp30;zoom120;ROTY320;ROTZ340;trz0;trr0;ctrl;all) [tgeo](https://eic.github.io/epic//artifacts/tgeo/epic_craterlake.root) [step](https://eic.github.io/epic//artifacts/epic_craterlake_no_bhcal.stp/epic_craterlake_no_bhcal.stp)
- Subsystems:
  - Inner detector: [viewer](https://eic.github.io/epic/geoviewer?nobrowser&file=artifacts/tgeo/epic_inner_detector.root&item=default;1&opt=clipx;clipy;transp30;zoom120;ROTY320;ROTZ340;trz0;trr0;ctrl;all) [tgeo](https://eic.github.io/epic//artifacts/tgeo/epic_inner_detector.root)
  - Calorimetry: [viewer](https://eic.github.io/epic/geoviewer?nobrowser&file=artifacts/tgeo/epic_calorimeters.root&item=default;1&opt=clipx;clipy;transp30;zoom120;ROTY320;ROTZ340;trz0;trr0;ctrl;all) [tgeo](https://eic.github.io/epic//artifacts/tgeo/epic_calorimeters.root)
    - Imaging: [viewer](https://eic.github.io/epic/geoviewer?nobrowser&file=artifacts/tgeo/epic_imaging_only.root&item=default;1&opt=clipx;clipy;transp30;zoom55;ROTY49;ROTZ350;trz0;trr0;ctrl;all) [tgeo](https://eic.github.io/epic//artifacts/tgeo/epic_imaging.root) [step](https://eic.github.io/epic//artifacts/epic_imaging_only.stp/epic_imaging_only.stp)
  - PID: [viewer](https://eic.github.io/epic/geoviewer?nobrowser&file=artifacts/tgeo/epic_pid_only.root&item=default;1&opt=clipx;clipy;transp30;zoom75;ROTY320;ROTZ340;trz0;trr0;ctrl;all) [tgeo](https://eic.github.io/epic//artifacts/tgeo/epic_pid_only.root)
    - dRICH: [viewer](https://eic.github.io/epic/geoviewer?nobrowser&file=artifacts/tgeo/epic_drich_only.root&item=default;1&opt=clipx;clipy;transp30;zoom75;ROTY290;ROTZ350;trz0;trr0;ctrl;all) [tgeo](https://eic.github.io/epic//artifacts/tgeo/epic_drich_only.root) [step](https://eic.github.io/epic//artifacts/epic_drich_only.stp/epic_drich_only.stp)
    - pfRICH: [viewer](https://eic.github.io/epic/geoviewer?nobrowser&file=artifacts/tgeo/epic_pfrich_only.root&item=default;1&opt=clipx;clipy;transp30;zoom55;ROTY49;ROTZ350;trz0;trr0;ctrl;all) [tgeo](https://eic.github.io/epic//artifacts/tgeo/epic_pfrich_only.root)
    - DIRC: [viewer](https://eic.github.io/epic/geoviewer?nobrowser&file=artifacts/tgeo/epic_dirc_only.root&item=default;1&opt=clipx;clipy;transp30;zoom120;ROTY320;ROTZ340;trz0;trr0;ctrl;all) [tgeo](https://eic.github.io/epic//artifacts/tgeo/epic_dirc_only.root) [step](https://eic.github.io/epic//artifacts/epic_dirc_only.stp/epic_dirc_only.stp)
  - Tracking: [viewer](https://eic.github.io/epic/geoviewer?nobrowser&file=artifacts/tgeo/epic_craterlake_tracking_only.root&item=default;1&opt=clipx;clipy;transp30;zoom75;ROTY320;ROTZ340;trz0;trr0;ctrl;all) [tgeo](https://eic.github.io/epic//artifacts/tgeo/epic_craterlake_tracking_only.root) [step](https://eic.github.io/epic//artifacts/epic_craterlake_tracking_only.stp/epic_craterlake_tracking_only.stp)
    - Vertex: [viewer](https://eic.github.io/epic/geoviewer?nobrowser&file=artifacts/tgeo/epic_vertex_only.root&item=default;1&opt=clipx;clipy;transp30;zoom120;ROTY320;ROTZ340;trz0;trr0;ctrl;all) [tgeo](https://eic.github.io/epic//artifacts/tgeo/epic_vertex_only.root)
    - TOF: [viewer](https://eic.github.io/epic/geoviewer?nobrowser&file=artifacts/tgeo/epic_tof_only.root&item=default;1&opt=clipx;clipy;transp30;zoom55;ROTY49;ROTZ350;trz0;trr0;ctrl;all) [tgeo](https://eic.github.io/epic//artifacts/tgeo/epic_tof_only.root)
  - Beamline: [viewer](https://eic.github.io/epic/geoviewer?nobrowser&file=artifacts/tgeo/epic_ip6.root&item=default;1&opt=clipx;clipy;transp30;zoom40;ROTY290;ROTZ350;trz0;trr0;ctrl;all)  [tgeo](https://eic.github.io/epic//artifacts/tgeo/epic_ip6.root) [step](https://eic.github.io/epic//artifacts/epic_ip6.stp/epic_ip6.stp)

**Detector parameters:**
- Craterlake: [text](https://eic.github.io/epic/artifacts/constants/epic_craterlake_constants.out) [toml](https://eic.github.io/epic/artifacts/constants/epic_craterlake_constants.toml) [csv](https://eic.github.io/epic/artifacts/DetectorParameterTable/epic_craterlake.csv) [html](https://eic.github.io/epic/artifacts/DetectorParameterTable/epic_craterlake.html)

Getting Started
---------------

This assumes you have DD4hep installed in your environment. Please use the eic-shell container (see the [EIC environment tutorial](https://eic.github.io/tutorial-setting-up-environment/)). If you are just looking to do simulation and reconstruction with unmodified ePIC geometry, you don't need to compile it yourself. The instructions below are for when you are looking to do development:

Get a copy of the latest version from this repository:
```bash
git clone https://github.com/eic/epic.git
```

### Compilation

To configure, build, and install the geometry (to the `install` directory), use the following commands:
```bash
cmake -B build -S . -DCMAKE_INSTALL_PREFIX=install
cmake --build build
cmake --install build
```
To load the geometry, you can use the scripts in the `install` directory:
```bash
source install/bin/thisepic.sh
```

### Contributing

See [Contributing Guidelines](https://github.com/eic/EICrecon/blob/main/CONTRIBUTING.md).

Related useful links
--------------------

- EIC tutorial: [Geometry Development with DD4hep](https://eic.github.io/tutorial-geometry-development-using-dd4hep/)
- [DD4hep repository](https://github.com/AIDAsoft/DD4hep)
- [DD4hep User's Manuals](https://dd4hep.web.cern.ch/dd4hep/page/users-manual/)
- [ACTS DD4hep plugin documentation](https://acts.readthedocs.io/en/latest/plugins/dd4hep.html)

---

## ZDC PbWO4 Crystal Geometry Update

This repository includes the updated PbWO4 crystal geometry for the ZDC crystal calorimeter based on the current preTDR design.

The new geometry uses 2 × 2 × 7 cm PbWO4 crystals in a 30 × 30 array and changes the crystal support material from CarbonFiber to Aluminum.

### Files added

#### `compact/far_forward/ZDC_Crystal_PbWO4_TDR.xml`

- Defines the PbWO4 crystal geometry.
- Crystal size: 2 × 2 × 7 cm.
- 30 × 30 crystal array.
- Support material: Aluminum.
- Existing position, readout, segmentation, socket configuration, and other unchanged geometry parameters are retained.

#### `configurations/zdc_pbwo4_sipm.yml`

- Adds a dedicated configuration for testing the PbWO4 crystal ZDC together with the existing SiPM-on-tile section.
- Generates `epic_zdc_pbwo4_sipm.xml` during the build.

### Existing connected files

#### `src/ZDC_Crystal_geo.cpp`

The existing ZDC crystal constructor is used by the new XML.

No modification was required because the existing constructor already reads the crystal material, dimensions, support material, number of cells, socket geometry, and placement information from the XML.

The constructor successfully created the PbWO4 geometry during testing.

#### `compact/far_forward/ZDC_SiPMonTile.xml`

The existing SiPM-on-tile ZDC geometry is used together with the PbWO4 crystal section in the new configuration.

No modification was required.

#### `compact/far_forward/default.xml`

This file currently continues to reference `ZDC_Crystal_LYSO.xml`.

It was intentionally left unchanged so this update does not replace the current default ZDC crystal configuration.

### Generated configuration

The new configuration successfully generates:

`install/share/epic/epic_zdc_pbwo4_sipm.xml`

with the expected includes:

- `ZDC_Crystal_PbWO4_TDR.xml`
- `ZDC_SiPMonTile.xml`

### Validation

Validation was performed from a fresh clone of the repository to verify that the geometry did not depend on files from the previous working directory.

Verification results:

- Fresh repository clone: PASS
- Checkout of `zdc-pbwo4-tdr`: PASS
- CMake configuration: PASS
- Build/install: PASS
- `zdc_pbwo4_sipm.yml` configuration generation: PASS
- Generated `epic_zdc_pbwo4_sipm.xml`: PASS
- `geoConverter`: PASS
- DD4hep geometry check: `Nothing to fix`
- ROOT geometry validation: PASS

`geoConverter` successfully converted:

- `ZDC_Crystal`
- `HcalFarForwardZDC_SiPMonTile`

and produced:

`test_private_ZDC_PbWO4_config.root`

The resulting geometry contained:

- 2318 nodes
- 522 volume UIDs
- Maximum of 901 placements

The DD4hep geometry check reported:

`Nothing to fix`

### ROOT geometry verification

#### `ZDC_Crystal_envelope`

- Material: Air
- Daughters: 901
- Size: 60.93 × 60.93 × 9.8 cm

#### `frame_vol`

- Material: Aluminum
- Daughters: 900
- Size: 60.93 × 60.93 × 7 cm

#### `tower_vol`

- Material: PbWO4
- Daughters: 0
- Size: 2 × 2 × 7 cm

#### `socket_vol`

- Material: ZDC_Polyethylene
- Daughters: 0
- Size: 2 × 2 × 0.25 cm

This confirms that the PbWO4 geometry, its dedicated configuration, the existing ZDC crystal constructor, and the SiPM-on-tile geometry work together successfully from a clean repository build.

