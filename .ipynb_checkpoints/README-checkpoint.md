# Overwatch Heroes & Player Analysis (Psychological Similarity)

GitHub repository for the Medium publication:  
**"We Are Who We Lock: A Similarity Study of Overwatch Heroes & Player Psychology"**

https://medium.com/@kwanjosh25

This project models Overwatch heroes using psychological features — such as mobility, self-sustain, mechanical skill, and durability — and uses cosine similarity to identify clusters of player mindset (Mastery, Healing, Protection, Instinct).

---

## 🧠 Project Contents

| Folder/File | Purpose |
|-------------|---------|
| `data/overwatch_hero_psychology.csv` | Custom dataset (psychological hero matrix) |
| `analysis.ipynb` or `analysis.py` | Full similarity analysis (cosine similarity, radar, heatmap) |
| `outputs/` | Generated similarity tables (.csv/.md) |
| `visuals/` | Radar charts & similarity heatmap images |
| `requirements.txt` | Python dependencies |

---

## 🛠 How to Run

```bash
pip install -r requirements.txt
# or manually:
# pip install pandas numpy scikit-learn matplotlib seaborn

jupyter lab      # open analysis.ipynb and run all cells
# OR
python analysis.py   # run full pipeline (if using script version)
