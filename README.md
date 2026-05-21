# Chelsea vs Tottenham — xG Tactical Analysis (Football Data Project)

A data-driven football analytics project analyzing the Premier League match between Chelsea F.C. and Tottenham Hotspur F.C. using expected goals (xG), shot location data, and player-level performance insights.

This project focuses on moving beyond the scoreline to understand:

Who created better chances, who executed better, and how the match was actually decided.

# 1. Objective
Analyze chance quality (xG) vs shot volume
Evaluate attacking efficiency under pressure
Understand shot location patterns and spatial dominance
Identify key player contributions in decisive moments
Compare process vs execution in match outcome
# 2. Data Used
Event-level shot dataset
xG values per shot
Shot coordinates (X, Y) mapped to pitch
Shot outcomes (Goal, Saved, Blocked, Missed, Post)
Player-level contribution metrics
Situation types:
Open Play
Set Pieces
Direct Free Kicks
Corners

Tools:

Python (Pandas, Matplotlib, Seaborn)
mplsoccer (pitch visualisation)
Spatial coordinate transformation
# 3. Key Findings
⚔️ xG Battle
Chelsea: ~1.09
Tottenham: ~2.24

👉 Tottenham created significantly higher-quality chances.

🎯 Chance Quality vs Execution
Tottenham: Better box entries + higher xG shots
Chelsea: Fewer chances but more clinical finishing moments

👉 Match = process dominance vs execution efficiency

👟 Key Player Impact
Richarlison → 0.71 xG goal (elite chance conversion)
James Maddison → 0.49 xG blocked shot (big missed chance)
Andrey Santos → 0.61 xG goal (clinical finish)
Enzo Fernández → low xG goal (~0.016 overperformance)

👉 Tottenham dominated creation, Chelsea dominated key moments.

# 4. Visuals

This project includes:

⚽ Shot map (xG intensity overlay)
📍 Pitch heatmaps (attacking zones)
👟 Player shot distributions
📊 Shot outcome breakdown
🧠 Situation-based xG analysis

Key visual insight:

Tottenham = dense central box activity
Chelsea = scattered, lower-density shot profile
# 5. Tactical Implications
Tottenham Hotspur F.C.
Strong central penetration
High xG chance creation
Repeated access to dangerous zones
BUT inefficient finishing under pressure
Chelsea F.C.
Lower attacking volume
Reliance on individual moments
Overperformance in finishing
Limited sustained pressure
$ 6. Actionable Recommendations
Tottenham:
Improve finishing efficiency in high-xG zones
Focus on composure in box situations
Convert ≥0.3 xG chances at higher rate
Chelsea:
Improve chance creation structure
Increase central progression
Reduce reliance on low-xG shots
# 7. Conclusion

Tottenham controlled the process.
Chelsea controlled the moments.

This match is a clear example of:

⚔️ Process (Tottenham) vs Execution (Chelsea)

Tottenham created better chances
Chelsea finished more decisive moments
Outcome decided by fine margins in attacking efficiency
📁 Project Structure
📁 chelsea-vs-tottenham-analysis
│
├── data/
│   └── match_shot_data.csv
│
├── notebooks/
│   └── analysis.ipynb
│
├── visuals/
│   ├── shot_map.png
│   ├── heatmap.png
│   └── xg_analysis.png
│
├── README.md
└── requirements.txt
# Future Improvements
Interactive Streamlit dashboard
Player comparison tool (xG radar charts)
Pass network analysis
Expected Threat (xT) modeling
Multi-match tactical comparison
# Author

Built by a football data analyst focused on turning match data into tactical insight and storytelling.

⭐ If you like this project
Star the repository ⭐
Fork it 🍴
Use it for your own football analytics work ⚽
