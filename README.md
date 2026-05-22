# ⚽ Chelsea vs Tottenham — xG Tactical Analysis (Football Data Project)

A data-driven football analytics project analyzing the Premier League match between **Chelsea F.C.** and **Tottenham Hotspur F.C.** using expected goals (xG), shot location data, and player-level performance insights.

This project goes beyond the scoreline to understand:

> Who created better chances, who executed better, and how the match was actually decided.

---

## 🎯 1. Objective

- Analyze chance quality (xG) vs shot volume  
- Evaluate attacking efficiency under pressure  
- Understand shot location patterns and spatial dominance  
- Identify key player contributions in decisive moments  
- Compare **process vs execution** in match outcome  

---

## 📊 2. Data Used

**Event-level match dataset including:**

- Shot-level data with xG values  
- Shot coordinates (X, Y) mapped to pitch  
- Shot outcomes:
  - Goal
  - Saved Shot
  - Blocked Shot
  - Missed Shot
  - Hit Post  

- Player-level contribution metrics  
- Situation types:
  - Open Play  
  - Set Pieces  
  - Direct Free Kicks  
  - Corners  

### 🛠 Tools

- Python (Pandas, Matplotlib, Seaborn)  
- mplsoccer (pitch visualisation)  
- Spatial coordinate transformation  

---

## 🧠 3. Key Findings

### ⚔️ xG Battle

- Chelsea: ~1.09  
- Tottenham: ~2.24  

👉 Tottenham created significantly higher-quality chances.

---

### 🎯 Chance Quality vs Execution

- Tottenham: Higher xG + better box entries  
- Chelsea: Fewer chances but more clinical finishing moments  

👉 **Match theme: process dominance vs execution efficiency**

---

### 👟 Key Player Impact

- Richarlison → 0.71 xG goal (elite conversion)  
- James Maddison → 0.49 xG blocked shot (big missed chance)  
- Andrey Santos → 0.61 xG goal (clinical finish)  
- Enzo Fernández → low xG goal (~0.016 overperformance)  

👉 Tottenham dominated creation, Chelsea dominated decisive moments.

---

## 📈 4. Visuals Included

- ⚽ Shot map with xG intensity overlay  
- 📍 Pitch heatmaps of attacking zones  
- 👟 Player shot distribution maps  
- 📊 Shot outcome breakdown  
- 🧠 Situation-based xG analysis  
<img width="1591" height="765" alt="image" src="https://github.com/user-attachments/assets/777f8479-b72d-4927-8670-e25045bb6213" />


### Key Insight

- Tottenham → dense central box activity  
- Chelsea → scattered, lower-density shot profile  

---

## ⚔️ 5. Tactical Implications

### Tottenham Hotspur F.C.

- Strong central penetration  
- High xG chance creation  
- Frequent access to dangerous zones  
- ❌ Inefficient finishing under pressure  

### Chelsea F.C.

- Lower attacking volume  
- Reliance on individual moments  
- Overperformance in finishing  
- Limited sustained pressure  

---

## 📌 6. Actionable Recommendations

### Tottenham

- Improve finishing efficiency in high-xG zones  
- Increase composure in box situations  
- Convert ≥0.3 xG chances at a higher rate  

### Chelsea

- Improve structured chance creation  
- Increase central progression  
- Reduce reliance on low-xG shots  

---

## 🏁 7. Conclusion

**Tottenham controlled the process.  
Chelsea controlled the moments.**

This match highlights the classic trade-off between:

> ⚔️ Process (Tottenham) vs Execution (Chelsea)

- Tottenham created better chances  
- Chelsea finished more decisive moments  
- Result decided by fine margins in attacking efficiency  

---

## 📁 8. Project Structure
chelsea-vs-tottenham-analysis/
│
├── data/
│ └── Chelsea vs Tottenham.csv
│
├── notebooks/
│ └── analysis.ipynb
│
├── visuals/
│ ├── shot_map.png
│ ├── heatmap.png
│ └── xg_analysis.png
│
├── README.md
└── requirements.txt


---

## 🚀 9. Future Improvements

- Interactive Streamlit dashboard  
- Player comparison tool (xG radar charts)  
- Pass network analysis  
- Expected Threat (xT) modeling  
- Multi-match tactical comparison  

---

## 👤 Author

Built by a football data analyst focused on turning match data into tactical insight and storytelling.

---

## ⭐ If you like this project

- Star the repository ⭐  
- Fork it 🍴  
- Use it in your own football analytics work ⚽  
