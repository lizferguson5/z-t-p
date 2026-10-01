# Usual or Unusual? Z, t, and the p-Value

An interactive companion to the BIOL 200 lecture **Hypothesis Testing Basics**. Students use it to explore the normal curve, the difference between the Z- and t-distributions, what a test statistic and p-value mean, and Type I and Type II errors. They then work through biology scenarios using real Z and t lookup tables.

**Live site:** https://lizferguson5.github.io/z-t-p/

## What's inside

The page has six tabs, meant to be worked through in order. Tabs 1–4 each end with a short **Try this** list that matches the Canvas questions.

| Tab | Topic | What students do |
|---|---|---|
| 1 | Normal curve & 68/95/99.7 | Light up the 1, 2 and 3 SD zones on a tree-height curve, see where 1.96 comes from, and turn any tree height into a z-score and a probability (Φ). |
| 2 | Z vs t | Slide the sample size and watch the t-curve's 95% line shrink toward Z's 1.96. Sort six study descriptions into "Z or t." |
| 3 | Test statistic & p-value | Move a tomato-fertilizer result along an interactive version of the lecture's p-value figure and see the test statistic, the shaded p-value and the decision update. |
| 4 | Type I, Type II & power | See false positives, false negatives and power on two curves, and run 100 simulated studies at a time. |
| 5 | Scenarios | Five biology scenarios (ER wait times, cholesterol, trout feed, sparrows, blue crabs). Each one walks through choosing a table, df, the critical value, the test statistic, the decision, the p-value and the possible error. Answers are checked as students type, and a worked example is available for each scenario. |
| 6 | Tables | Full Z-table (Φ) and t-table. Clicking a cell reads it back in words. The tables are also available from the orange **Tables** button on every tab. |

## Using it in class

- Share the live site link, or put it at the top of the Canvas assignment.
- No login, install or account is needed. It runs entirely in the browser on laptops, tablets and phones. Tab 3's figure is easiest to read on a laptop.
- You can link straight to a tab by adding its name to the end of the address: `#normal`, `#zt`, `#pvalue`, `#errors`, `#scen`, `#tables`.
  Example: `https://lizferguson5.github.io/z-t-p/#pvalue`
- Student answers aren't saved. Refreshing the page clears them.

## Files

| File | Purpose |
|---|---|
| `index.html` | The entire app: HTML, styles and code in one file, with no other dependencies. |
| `README.md` | This file. |

The associated questions document (`Usual_or_Unusual_Canvas_Questions.docx`) is a resource for instructors wanting to have further engagment at the end of each section.


## Notes on the statistics

- Z-table values (Φ) are calculated in the page and match standard printed tables to four decimals.
- t critical values use the standard two-tailed table (α = 0.20, 0.10, 0.05, 0.02, 0.01). If a df isn't listed, the next smaller row is used, which is the conservative choice.
- Curves and simulations are drawn live in the browser, so results like "Run 100 studies" change a little each time.

---
Created for BIOL 200 by Liz Ferguson.
