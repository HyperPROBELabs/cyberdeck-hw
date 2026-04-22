# Screen Panel Support Rod (ROD)

This directory contains the **Cyberdeck Screen Panel Support Rod** 3D STEP files and production resources.

---

# Directory Structure

The repository tree should look like this:

```
/
├── ...
├── docs
│   └── screen-panel-support-rod_manufacturing-and-assembly-manual.pdf
├── main/
│   └── screen-panel/
│       ├── mechanical/
│       │   └── rod/
│       │       ├── production/
│       │       │   ├── bom.csv
│       │       │   ├── mesh-3d-printing/
│       │       │   │   ├── rod-body.stl
│       │       │   │   ├── rod-hat.stl
│       │       │   │   ├── rod-latch.stl
│       │       │   │   └── rod-washer-gasket-multiple-sizes.stl
│       │       │   ├── rod-body.step
│       │       │   ├── rod-hat.step
│       │       │   ├── rod-latch.step
│       │       │   ├── rod-washer-gasket-multiple-sizes.step
│       │       │   └── spring-techdraw.pdf
│       │       ├── README.md
│       │       └── rod.step
│       └── ...
└── ...
```

---

# Production Files

Inside the `production` directory:

* Files located in `mesh-3d-printing/` are **STL mesh files**
* These files are intended for **3D printing manufacturing**
* STEP files are intended for **CNC machining or CAD modification**

---

# Manufacturing

Please read the manufacturing and assembly manual before production:

```
/docs/screen-panel-support-rod_manufacturing-and-assembly-manual.pdf
```

Or open directly:


[`../../../../docs/screen-panel-support-rod_manufacturing-and-assembly-manual.pdf`](../../../../docs/screen-panel-support-rod_manufacturing-and-assembly-manual.pdf)


Refer to the manual for:

* Manufacturing requirements
* Material specifications
* Assembly instructions
* Hardware details

---

# BOM List

The BOM list is located at:

```
production/bom.csv
```

For detailed BOM information, refer to **Section 3** of the [manual](../../../../docs/screen-panel-support-rod_manufacturing-and-assembly-manual.pdf).

---

# BOM Notes

The following notes are used in the BOM file:

* **Available**
  The part can be purchased or imported, but does **not** guarantee stock availability.

* **Not available**
  The part cannot be legally obtained or imported in some countries or regions.

* **Modify REQ**
  Hardware modification required. Not usable out-of-box. Warranty may be void.

* **Import WARN**
  Import may require license, certification, or documentation.

* **Custom**
  Custom-manufactured part. May require MOQ (Minimum Order Quantity).

### Example

* RF modules capable of transmission may require FCC / CE certification depending on region.

---

# License

This directory (`rod`) and the associated documentation:

```
/docs/screen-panel-support-rod_manufacturing-and-assembly-manual.pdf
```

are licensed under:

**CERN-OHL-P v2**

Notes:

* This license applies **only** to the `rod` directory
* The license **may differ** from the root repository license
* If conflicts occur, the license specified in this directory takes precedence

---

# Notes

* STEP files are provided for manufacturing and modification
* STL files are provided for rapid prototyping and 3D printing
* Always review the manual before manufacturing

---

Cyberdeck Project
Designed by KaliAssistant

