# Flipper One Mechanics

This repository contains 3D models of the Flipper One enclosure and expansion modules.

![flipper_one_3d_model_banner](https://github.com/user-attachments/assets/5e709ba7-ed90-42a6-bfe3-200f94b65e2f)

## Versioning scheme

Enclosure 3D model versions consist of two parts: `<LETTER>.<NUMBER>` (for example, `A.1`).

- **LETTER** — major version. Different major versions are **not mechanically compatible** with each other.  
- **NUMBER** — minor revision. This may represent small changes (for example, graphics, labels, or minor tweaks).  
  Different minor revisions **remain compatible** with each other.

## Folders structure 

Description of the file and directory structure in this repository:

```
├── OLD/ # Deprecated versions
│ ├── A.0/
│ └── ...
├── CURRENT/ # Current supported version
│ └── X.N/ # Current enclosure revision <LETTER>.<NUMBER>
│ ├── Flipper One (X.N).stp # Full enclosure 3D model (STEP)
│ └── Graphics/ # Logos, engravings, decals, artwork for the enclosure
```

# 3D model parts

![Flipper One_3D_model_parts_description](https://github.com/user-attachments/assets/dfd533b3-f147-4c25-a7f4-9b13c77d6c40)

* **Body** — the main enclosure of the device. It contains all electronics, the display, and the user controls.  
  In the public release, this part is provided as a single solid shell with an empty interior. This is done intentionally to prevent direct copying of the internal mechanical design.  
  At the same time, all external surfaces and dimensions fully match the real product. This is sufficient for developing accessories, cases, mounts, and external modules.

* **Back plate** — the rear cover that provides access to the M.2 expansion port.  
  This cover is attached to the body with screws and can be interchangeable, with different designs depending on the installed module.  

  This part fully matches the real product, including all internal surfaces. We publish it openly so that third-party manufacturers and makers can design and produce their own back plates.

* **Antenna rail** — a separate part used for mounting SMA antennas.  
  The antenna rail is intentionally separated from the back plate so that antennas can be installed and cables can be routed to the radio module before the back plate is closed. This eliminates the risk of damaging the antenna cables during assembly.  
  If the antenna rail were integrated into the back plate, users would have to hold the back plate in mid-air while connecting antenna cables. During testing, we found this to be inconvenient and prone to incorrect module installation and cable damage.  
  This part fully matches the real product and is published openly. We expect it to be interchangeable depending on the module, and third-party manufacturers and makers can design custom antenna rails for custom antenna configurations.


# View online & Export 

The latest 3D models can be viewed online using the free Onshape web viewer. Models can be inspected directly in the browser and exported to common CAD formats, including SOLIDWORKS, PARASOLID, RHINO and more.

<p align="center">
  <a href="https://cad.onshape.com/documents/32ee3b79861e4ff5fe28ee3b/w/8eca0dcb9e92b0271d434028/e/fbe3506762a12a485b605a70?renderMode=0&uiState=698e49e3092f9713cafdf272">
    <img width="300" alt="view_on_onshape" src="https://github.com/user-attachments/assets/cbb9ca12-cd3c-44c9-bfda-5d85ef581c9c" />
  </a>
</p>

<a href="https://cad.onshape.com/documents/32ee3b79861e4ff5fe28ee3b/w/8eca0dcb9e92b0271d434028/e/fbe3506762a12a485b605a70?renderMode=0&uiState=698e49e3092f9713cafdf272">
    <img width="1171" height="821" alt="flipper_one_onshape" src="https://github.com/user-attachments/assets/349bf89e-67eb-442a-b229-9c339fa2ef25" />
</a>
