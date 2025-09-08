# ⚽ FIFA Player Data: Cleaning & Analysis

## 📌 Project Objective

The goal of this project is to analyze the FIFA players dataset (18,207
rows, 18 columns) to extract meaningful insights about player
attributes, clubs, and market values.\
It includes **data cleaning, exploratory data analysis (EDA), and
visualization**.

------------------------------------------------------------------------

## 📊 Dataset Description

-   **Rows:** 18,207\
-   **Columns:** 18

### Key Columns:

-   `ID` → Unique player ID\
-   `Name` → Player name\
-   `Age` → Player's age\
-   `Nationality` → Country of the player\
-   `Overall` → Overall rating (1--100)\
-   `Potential` → Future potential rating\
-   `Club` → Current club\
-   `Value` → Market value (in thousands)\
-   `Wage` → Weekly wage (in thousands)\
-   `Preferred Foot` → Left / Right\
-   `International Reputation` → Rating (1--5)\
-   `Skill Moves` → Rating (1--5)\
-   `Position` → Playing position\
-   `Joined` → Year joined current club\
-   `Contract Valid Until` → Contract expiry date\
-   `Height` & `Weight` → Physical attributes\
-   `Release Clause` → Buy-out clause

------------------------------------------------------------------------

## 🛠️ Tools & Libraries

-   **pandas** → Data manipulation\
-   **NumPy** → Numerical operations\
-   **matplotlib** → Data visualization\
-   **seaborn** → Statistical visualization

------------------------------------------------------------------------

## 🔍 Exploratory Data Analysis (EDA)

### Player Ratings

-   Ratings follow a **normal distribution**.\
-   Most players: **60--70 overall rating**.\
-   Few players above **85 overall**.

### Age Distribution

-   Most players are **20--28 years old**.\
-   Peak: **21--24 years**.\
-   Very few above 35 or below 18.

### Nationalities

-   **England** has the most players (due to multiple league levels).\
-   European & South American countries dominate the top 10.

### Age vs. Overall Rating

-   Peak performance in **late 20s -- early 30s**.\
-   Decline after early 30s.

### Preferred Foot

-   Right-footed players dominate (**≈14,000 players**).\
-   Left-footed players are far fewer (**≈4,000 players**).

### Top Clubs by Average Rating

-   **Juventus, Napoli, Inter, Real Madrid, Barcelona, PSG, Bayern
    Munich** lead.\
-   Average player rating: **78--82**.

### Correlations

-   `Overall` ↔ `Potential` → **Strong positive correlation (0.66)**\
-   `Value` ↔ `Overall` (0.63) / `Potential` (0.58)\
-   `Wage` ↔ `Overall` (0.67)\
-   `Release Clause` ↔ `Value` (0.97, almost perfect)\
-   `Height` ↔ `Weight` (0.75)\
-   `Age` ↔ `Overall` (-0.25, slight negative)

### Wage vs Age

-   **16--20** → Low wages, rising gradually.\
-   **20--30** → Steady rise, **peak at 28--30 years**.\
-   **30--35** → Decline begins.\
-   **35+** → Sharp drop, only a few superstar veterans remain high.

------------------------------------------------------------------------

## ✅ Conclusion

-   Football is dominated by **young, right-footed players**.\
-   **Player peak**: Late 20s to early 30s (both performance & wages).\
-   **England** contributes the most players, but elite clubs (Juventus,
    Real Madrid, PSG, etc.) have the **highest-rated squads**.\
-   **Market value & wages** are tightly linked with ratings, potential,
    and international reputation.

------------------------------------------------------------------------

## 🚀 How to Run

1.  Clone this repository or open the folder in **VS Code**.\

2.  Install dependencies:

    ``` bash
    pip install pandas numpy matplotlib seaborn
    ```

3.  Run the Jupyter Notebook or Python script to explore the dataset and
    visualizations.

------------------------------------------------------------------------

👨‍💻 *Author: \[Your Name\]*\
📅 *Project Date: 2025*
