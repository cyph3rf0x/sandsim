# Apple II Falling Sand (Lo-Res GR Mode)

A **minimal falling sand simulation** written in **AppleSoft BASIC** for the **Apple II** using **low-resolution graphics (GR)** mode.

This project demonstrates a simple cellular automaton on a **40×40 grid**, where colored “sand” pixels fall under gravity and pile up naturally.

---

## Features

* Runs in **GR (low-res) mode**
* True **40×40 grid** matching Apple II lo-res resolution
* Uses **AppleSoft BASIC only**
* Each cell stores a **color value (0–15)**
* Simple gravity rules:

  1. Fall straight down if empty
  2. Otherwise fall down-right if empty
  3. Otherwise fall down-left if empty
  4. Otherwise stay in place
* Randomized colored starting pattern
