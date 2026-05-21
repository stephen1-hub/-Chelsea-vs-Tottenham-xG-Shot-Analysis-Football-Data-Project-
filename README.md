# ⚽ Chelsea vs Tottenham — xG & Shot Analysis (Football Data Project)

A data-driven football analytics project analyzing the Premier League match between **Chelsea F.C.** and **Tottenham Hotspur F.C.** using expected goals (xG), shot location data, and player-level performance insights.

This project focuses on moving beyond the scoreline to understand:

> Who created better chances, who executed better, and how the match was actually decided.

---

## 📊 Project Overview

This analysis breaks down the match using event-level shot data to evaluate:

- Shot quality (xG)
- Shot locations (X, Y pitch coordinates)
- Player contribution
- Finishing efficiency
- Attack patterns by situation (open play, set pieces, etc.)

The goal is to translate raw football data into tactical and performance insights.

---

## 🧠 Key Insights

### ⚔️ xG Comparison
- Chelsea xG: **~1.09**
- Tottenham xG: **~2.24**

👉 Tottenham created significantly better chances overall, despite similar shot volume.

---

### 🎯 Shot Quality vs Shot Volume
- Both teams had similar shot counts
- Tottenham generated higher **xG per shot**
- Chelsea relied on fewer but more decisive moments

👉 Match = **chance quality vs clinical execution**

---

### 👟 Player Impact

Key performers:

- 🔴 :contentReference[oaicite:0]{index=0} — highest xG chance (0.71 goal)
- ⚪ :contentReference[oaicite:1]{index=1} — missed a 0.49 xG big chance
- 🔵 :contentReference[oaicite:2]{index=2} — clinical 0.61 xG goal
- 🔵 :contentReference[oaicite:3]{index=3} — scored from extremely low xG (0.016)

👉 Tottenham dominated chance creation, Chelsea dominated finishing efficiency.

---

### 📍 Shot Location Analysis
- Tottenham shots concentrated in central penalty box zones
- Chelsea shots more scattered and lower quality
- High-value chances came from central attacking positions

👉 Spatial dominance = Tottenham

---

### ⚽ Shot Type Efficiency
- Left foot: highest xG/shot (0.25)
- Right foot: most frequent but lower quality (0.15)
- Headers: moderate efficiency (0.19)

👉 Positioning mattered more than shot type

---

### 🧩 Situation-Based xG
- Open play → dominant source of xG (~80%+)
- Set pieces → minimal impact
- Free kicks → low conversion efficiency

👉 Match was decided in open play transitions

---

## 🛠️ Tools & Technologies

- Python 🐍
- Pandas
- Matplotlib
- Seaborn
- mplsoccer ⚽
- Football xG modeling concepts
- Spatial coordinate transformation (pitch mapping)

---

## 📈 Visualizations Included

- Shot map (xG intensity)
- Heatmaps of attacking zones
- Player-level shot breakdown
- Situation-based xG distribution
- Shot outcome analysis

---

## 📌 Key Football Insight

> Tottenham created better chances.  
> Chelsea finished better moments.

This match is a clear example of:

- **Process (Tottenham) vs Execution (Chelsea)**
- **Chance quality vs conversion efficiency**

---

## 📊 Project Structure
