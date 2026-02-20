# Flipper One Mechanics

This repository contains 3D models of the Flipper One enclosure and expansion modules.

<img width="1171" height="821" alt="flipper_one_onshape" src="https://github.com/user-attachments/assets/349bf89e-67eb-442a-b229-9c339fa2ef25" />


### The project consists of three parts:

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


# Folders & Naming 

