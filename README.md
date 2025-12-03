Totally fair. Let’s stop fighting the code fences and do this the simple way.

Below is the **entire README.md as plain text**.
**Copy from the first line (`# Aillio Bean Stirrer`) through the last line** and paste it straight into your README on GitHub.

No extra backticks, no nested code blocks, nothing fancy.

---

# Aillio Bean Stirrer

### Open Hardware Release • Designed by Dustin Betterly

<img src="images/hero_render.png" width="900"/>

The **Aillio Bean Stirrer** is an open-hardware accessory designed for the **Aillio R1 and R2 cooling bowls**.
Its purpose is simple: **speed up the cooling cycle and help remove any chaff that didn’t escape during roasting.**

By actively agitating the beans during cooling, the stirrer:

* Accelerates heat dissipation
* Improves airflow through the bean mass
* Breaks up clumps for more uniform cooling
* Helps eject additional trapped chaff
* Reduces total cooling time compared to passive airflow alone

**This tool is for post-roast cooling only.
It is NOT designed for use inside the roasting drum.**

---

## ✨ Features

* Rapid bean agitation for faster, more uniform cooling
* Helps remove residual chaff that didn’t exit the drum
* High-temperature stir paddle (PA6-CF recommended)
* Wear-friendly PTFE washer system
* Completely printable housing, paddle, and thumb screws
* Tested for safe use with hot roasted beans
* Open hardware — remix, improve, share

---

## 📦 Repository Contents

/STL

* 3D Print - Bean Stirrer.stl
* 3D Print - Bottom Wear Plate.stl
* 3D Print - Top Wear Plate.stl
* 3D Print Axel Hub.stl
* 3D Print M5 Thumb Screw.stl
* 3D Print Motor Body Base.stl
* 3D Print Motor Body Wire Cover.stl
* Motor Body Cover.stl

/docs

* Aillio_Stirrer_Manual_FINAL_NEW_EXPLODED.pdf
* Exploded_View.pdf

/images

* hero_render.png

Other:

* README.md
* LICENSE

---

## 🧰 Bill of Materials (BOM)

See:

* docs/Exploded_View.pdf

Key hardware:

* 80 mm stainless square rod (cut to length)
* PTFE shoulder washers
* Heat-set inserts
* Assorted M3/M5 fasteners
* 12 V DC motor (reverse-rotation supported)

---

## 🛠 Material Recommendations

| Part           | Material | Brand             | Notes                                                     |
| -------------- | -------- | ----------------- | --------------------------------------------------------- |
| Stir Paddle    | PA6-CF   | Polymaker Fiberon | High heat deflection so hot beans won’t deform the paddle |
| Wear Plates    | PA6-CF   | Polymaker Fiberon | Low friction and heat resistant                           |
| Housing/Covers | PLA-CF   | Bambu Labs        | Rigid, stable, clean finish                               |
| Thumb Screws   | PLA-CF   | Bambu Labs        | Strong and easy to bond to steel screws                   |

---

## 🪚 Cutting the Square Rod (80 mm)

The stainless square bar must be cut to **80 mm** final length.

Steps:

1. Mark 80 mm with calipers or a precise ruler.
2. Cut using a hacksaw, bandsaw, or cutoff wheel.
3. Deburr both ends with a file or sandpaper.
4. Verify a smooth sliding fit into the printed hubs.
5. Target tolerance: 80 ± 0.25 mm.

---

## 🖨 Printing Guidance

### Stir Paddle (PA6-CF)

* Print upside-down.
* Supports: build plate only.
* Add a pause to insert the embedded nut.
* Optional: coat in resin and sand for a smoother finish.

### Thumb Screws

* Pause print to insert the M5 screw.
* Secure with resin or superglue.

---

## 🔧 Assembly Overview

See:

* docs/Aillio_Stirrer_Manual_FINAL_NEW_EXPLODED.pdf
* docs/Exploded_View.pdf

General notes:

* Center the stir paddle on the cooling bowl’s middle pin.
* Do not overtighten the paddle screw; it should rotate freely.
* Leave motor screws slightly loose during alignment.
* Apply blue Loctite after final positioning.

---

## ⚡ Motor & Power

* 12 V DC motor.
* If the paddle spins backward, swap polarity on the motor leads.
* Recommended power supply: 12 V / 2 A.

---

## 🛡 License — CC BY-NC 4.0

You may:

* Print and remix for personal use.
* Share non-commercially.
* Must credit: **Dustin Betterly**.

You may not:

* Sell the files.
* Sell printed parts or kits.
* Use this design commercially without permission.

Full license: [https://creativecommons.org/licenses/by-nc/4.0/](https://creativecommons.org/licenses/by-nc/4.0/)

---

## 🙌 Credits

**Design & documentation:**
Dustin Betterly

**Render:**
images/hero_render.png

---

## 🗂 Version History

### v1.0 — Initial Public Release

* Finalized STL files.
* Updated exploded view.
* Complete build manual.
* Purpose clarified (cooling + chaff removal).
* CC BY-NC license applied.

> If you build it, share your results!
> Pull requests, improvements, and remixes are welcome (non-commercial only).
