# Automatic-Forward-Reverse-Motor-Cycle-Washing-Machine-Logic---Classic-Control

##  Project Overview

This project implements a **Classic Control (Relay Logic)** system that simulates a **washing machine motor cycle**.

The motor operates in a continuous loop:

* Forward → Stop → Reverse → Stop → repeat

---

##  Project Type

 Classic Control (Hardwired Relay Logic)
 No PLC used

---

##  Objective

To design a cyclic motor operation that:

* Alternates direction automatically
* Includes time delays between operations
* Repeats continuously without user intervention

---

## 🔧 Components Used

* Forward Contactor (KF)
* Reverse Contactor (KR)
* Timer Relays (Multiple ON delay timers)
* Stop Button (NC)
* 3-Phase Motor

---

##  Working Principle

The system operates in a continuous loop:

###  Step 1: Forward Operation

* Motor runs in Forward direction for **5 seconds**

---

###  Step 2: توقف (Delay)

* Motor stops for **2 seconds**

---

###  Step 3: Reverse Operation

* Motor runs in Reverse direction for **5 seconds**

---

###  Step 4: توقف (Delay)

* Motor stops for **2 seconds**

---

###  Cycle Repeats Automatically

The sequence continues indefinitely:
Forward → Stop → Reverse → Stop → repeat

---

##  Interlocking Protection

* Forward (KF) and Reverse (KR) are interlocked
* Prevents both directions from running simultaneously

---

##  Key Concepts

* Cyclic operation
* Sequential control
* Multi-timer coordination
* Forward / Reverse motor control
* Classic control systems



##  Demo Video

[video](./video.mp4)

---

##  How to Operate

1. Power ON system
2. Motor starts automatic cycle:

   * Forward → Stop → Reverse → Stop
3. Press Stop → system stops immediately

---

##  Notes

* All timers are configured as ON delay
* Proper sequencing is critical for correct operation
* Timing values can be adjusted as needed

---

## ⚠️ Note About Demo Video

During the demo video, the Stop button did not respond at the end.

This was due to a loose connection in the **normally closed (NC) Stop circuit wiring**.

This highlights the importance of:

* Proper wiring checks
* Troubleshooting in control circuits
* Verifying NC safety circuits before operation

The issue was identified and corrected afterward.
