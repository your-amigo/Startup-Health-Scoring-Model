# What is this project?

This project is part of my internship task for ScaleDux.  
The goal is to look at data from 100 different startups and give each one a score (out of 100) to see which startups look the strongest.

This score is based on things like:
- How experienced the team is
- How big the market is
- How many users the startup has
- How much money it spends
- How much funding it got
- What the company is worth

---

# What I Did (Step by Step)

1. Opened the startup data file using Python.
2. Cleaned the numbers and brought them to the same scale so they can be compared.
3. Gave less points to startups that spend too much money (burn rate).
4. Gave importance (weights) to each factor.
5. Added all points to get a total score out of 100.
6. Sorted the startups from best to worst based on their scores.
7. Made simple charts to show what I found.

---

# How I Gave Points

Each startup got points based on these factors:

| Factor                    | Importance |
|---------------------------|------------|
| Team Experience           | 15%        |
| Market Size               | 15%        |
| Monthly Active Users      | 20%        |
| Money Spent (Burn Rate)   | 10%        |
| Money Raised (Funding)    | 20%        |
| Company Value (Valuation) | 20%        |

The final score is a mix of all of these.

---

# Charts I Included

- A bar chart showing scores of all startups
- A graph showing how scores are spread out
- A heatmap showing which features are related
- A chart comparing score vs rank
- Top 10 startups as per scores
- A chart comparing funding vs valuation

---

# Insights

- Startups with more users usually scored higher.
- Spending less money helped some startups rank better.
- Just raising money is not enough — how they use it matters too.
- Funding and company value are closely connected.
- A good team can make a big difference.
- The best startups had a balance of everything: team, users, funding, and smart spending.


---
