# C0PP3R
⚠ **IMPORTANT - READ BEFORE ANYTHING ELSE** ⚠

C0PP3R is a **Windows GDI + audio experiment project** created for **learning and demonstration purposes**.
This repository contains **two completely separate builds**:

- a **SAFE / HARMLESS build** (recommended)
- a **DESTRUCTIVE build** (DO NOT RUN on real system)

---
## Safety Version (RECOMMENDED)
**Path:** `Safety/`

- Uses **GDI visual effects**
- Uses **bytebeat audio**
- Runs in **user mode**
- ❌ Does NOT modify disk
- ❌ Does NOT touch boot records
- ❌ Does NOT disable system tools
- ❌ Does NOT persist

This version is intended for:
- GDI experimentation
- Bytebeat audio tests
- Windows graphics curiosity
- Learning WinAPI behavior

👉 **This is the only version you should run on a real machine.**

## ☠ Destructive Version (DO NOT RUN)
**Path:** `Destructive/`

This build contains **intentional system-destructive behavior**, including but not limited to:
- Low-level disk writes
- System destabilization
- Forced system failure scenarios

🚫 **DO NOT RUN ON:**
- Real hardware
- Your main PC
- Any system you care about
- Someone else's computer

🧪 If examined at all, it should be:
- Source-code only
- Inside an isolated virtual machine
- For educational reading, not execution

---
## 🧠 Educational Intent
This project exists to explore:
- Windows GDI internals
- Thread behavior
- Bytebeat sound generation
- WinAPI graphics and audio limits

it is **not** meant for:
- Real-world malware deployment
- Pranking users
- Damaging systems
- Bypassing OS protections

---
## 🛠 Build Notes

- Built using **MinGW-w64**
- Executables may require:
  - `libstdc++-6.dll`
  - `libgcc_s_seh-1.dll`

These are **normal C++ runtime dependencies**, not malicious component.

---
## ⚖ Disclaimer
You are responsible for what you run.

I am **not** take responsibilities for:
- Data loss
- System damage
- Misuse of the destructive build

If you don't understand exactly what something does, **do not run it**.

---
## 🧩 Final Note
If you're here to learn:
✔ Read the source
✔ Run the harmless build
✔ Experiment safely

If you're here to break stuff:
❌ This repo is not for you

Stay curious — not reckless.
