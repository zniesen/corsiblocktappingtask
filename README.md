# Corsi Block-Tapping Task (Forward, Modified 4x4 Version)

This repository contains an **Inquisit script for a modified Forward Corsi Block-Tapping Task**, based on Millisecond Software’s implementation and adapted by Zoe Niesen (2024).  

Unlike the adaptive version, this task uses a **fixed 4x4 grid** and a **predetermined set of sequences (lengths 3–5)**. All sequences are always presented, regardless of participant performance.

---

## 🧠 Task Overview
- Participants view a **grid of 16 boxes (4x4 layout)**.  
- Boxes light up in a **predefined sequence**, which participants must reproduce by clicking the boxes in the same order.  
- Sequence lengths: **3, 4, and 5 boxes**.  
- **All sequences are presented**, even if participants make errors.  
- Duration: **~1 minute**.  

---

## 📊 Data Output
The script produces **two data files per participant**:

1. **Raw data file** (`corsiblocktappingtask_raw*.iqdat`)  
   - Device and system info  
   - Trial-level responses, latencies, accuracy  
   - Sequence and response strings  
   - Block span (longest correctly recalled sequence)  
   - Total correct sequences recalled  

2. **Summary data file** (`corsiblocktappingtask_summary*.iqdat`)  
   - Participant/session identifiers  
   - Task completion status  
   - Block span and total score  

---

## ⚙️ Features
- Fixed **4x4 grid of blocks**.  
- **Non-adaptive** — all sequences are always shown.  
- Optimized for **touchscreens** (adapts for mouse use as well).  
- Editable parameters for:  
  - Colors (blocks, taps, board, screen)  
  - Canvas sizing (absolute vs. relative)  
  - Timing (intervals, feedback)  
  - Feedback & scoring options  
  - Optional age question (with normative grouping from Kessels et al., 2000)  

---

## ✏️ Customization
The script can be customized by editing:  
- Sequence patterns  
- Color scheme  
- Feedback settings  
- Stimulus sizing  

This version may also serve as a **template for other fixed-sequence memory tasks**.

---

## 🔗 Original Script
This script is a modified version of the Forward Corsi Block-Tapping Task by **Millisecond Software, LLC (2022)**.  
Original version available here:  [Millisecond Software – Corsi Block-Tapping Task](https://www.millisecond.com/download/library/corsiblocktappingtask)

---

## 📚 References
- Kessels, R.P.C., van Zandvoort, M.J.E., Postma, A., Kappelle, L.J., & de Haan, E.H.F. (2000).
	The Corsi block-tapping task: Standardization and normative data. Applied Neuropsychology,
	7(4), 252-258.
- Corsi, P. M. (1972). Human memory and the medial temporal region of the brain. 
	Dissertation Abstracts International, 34, 819B.

---

## 📜 Copyright & License

Copyright © 2022 Millisecond Software, LLC  
Modified work Copyright © 2024 Zoe Niesen  
Used with permission from Millisecond Software
