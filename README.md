# Pakistan Suicide Attacks Analysis (1995–2017)

An exploratory data analysis of suicide attacks in Pakistan over a 22-year period, uncovering patterns in frequency, geography, target types, and timing.

---

## Key Findings

- **Attack frequency and fatalities are strongly correlated** (Pearson r confirmed), peaking between 2009–2013 — likely reflecting the height of militant activity before operations like Zarb-e-Azb.
- **Quetta and Peshawar are the deadliest cities** despite having far smaller populations than Karachi or Lahore, indicating a hyper-concentration of high-yield attacks in regional capitals.
- **Soft targets kill more than hardened ones** — security forces are attacked most often, but civilian locations like mosques, markets, and parks produce the highest cumulative fatalities.
- **Closed spaces are more lethal on average** — blast containment and limited escape routes amplify casualties in enclosed environments.
- **Holiday attacks are deadlier per incident** — while over 80% of attacks occur on working days, holiday attacks yield a significantly higher average fatality rate.
- **Reporting uncertainty is significant** — the gap between minimum and maximum fatality estimates spans thousands of lives, a critical caveat for any policy conclusions.

---

## Sections

| # | Section | Question Answered |
|---|---------|-------------------|
| 1 | Attack Frequency vs Fatalities | Do more attacks mean more deaths? |
| 2 | Top 5 Deadliest Cities | Which cities bore the highest toll? |
| 3 | Deadliest Location Categories | Where do the most fatalities occur? |
| 4 | Open vs Closed Spaces | Does environment affect lethality? |
| 5 | Blast Day Type | Are some days deadlier than others? |
| 6 | Fatality Estimate Range | How uncertain is the death toll? |

---

## Tools & Libraries

- **Python 3.13**
- **Pandas** — data manipulation and aggregation
- **Seaborn / Matplotlib** — visualizations
- **SciPy** — Pearson correlation (statistical validation)

---

## Dataset

**Pakistan Suicide Attacks Dataset (1995–2017)**  
Source: [Kaggle](https://www.kaggle.com/)  
The dataset covers attack date, city, location category, target type, space type, blast day type, and fatality estimates (min/max).

---

## How to Run

```bash
git clone https://github.com/your-username/pakistan-suicide-attacks-analysis.git
cd pakistan-suicide-attacks-analysis
pip install pandas numpy seaborn matplotlib scipy
jupyter notebook project2.ipynb
```

---

## Limitations

- Fatality figures use `Killed Max` (upper-bound estimates) as the primary metric. Analysis against `Killed Min` is included in Section 6 to illustrate the uncertainty range.
- The dataset ends in 2017 and does not reflect developments after that date.

---

## Author

**Taha Arif**  
