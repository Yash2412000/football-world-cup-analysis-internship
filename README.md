# FIFA World Cup Analysis

Exploratory data analysis and interactive Power BI dashboard built on historical FIFA World Cup data spanning all tournaments from 1930 to 2014.

The project analyses match outcomes, player participation trends, and tournament-level patterns across three structured datasets — surfacing insights into goal-scoring trends, dominant nations, attendance patterns, and match dynamics over 80+ years of competition.

---

## Datasets

| File | Description |
|---|---|
| `WorldCups.csv` | Tournament-level data: host nation, winner, runner-up, attendance, goals |
| `WorldCupMatches.csv` | Match-level data: scores, stages, venues, referee, halftime scores |
| `WorldCupPlayers.csv` | Player-level data: squad numbers, positions, events (goals, cards) |

---

## Analysis Scope

**Tournament trends**
- Goals per tournament over time and average goals per match by era
- Attendance growth across host nations and venues
- Winning nation frequency and runner-up patterns

**Match-level patterns**
- Home vs away advantage in group stage vs knockout rounds
- Score distribution and high-scoring match analysis
- Halftime lead as a predictor of match outcome

**Player & squad analysis**
- Position distribution across squads by era
- Top goal scorers and appearance leaders
- Player event frequency (goals, yellow/red cards) by stage

---

## Deliverables

- **`FIFA WORLD CUP ANALYSIS.ipynb`** — Python EDA notebook (Pandas, Matplotlib, Seaborn)
- **`WORLD CUP INTERNSHIP WORK.pbix`** — Interactive Power BI dashboard with slicers by year, nation, and stage
- **`FIFA WORLD CUP ANALYSIS.pptx`** — Presentation summarising key findings
- **`HLD.pdf` / `LOW LEVEL DOC.pdf` / `ARCHITECTURE DESIGN.pdf`** — Project documentation

---

## Stack

Python · Pandas · Matplotlib · Seaborn · Power BI

---

## Key Findings

- Average goals per match declined from ~4.7 in the 1950s to ~2.5 in the 2010s, reflecting tactical evolution
- Brazil and Germany account for over 30% of all final appearances across the tournament's history
- Halftime leaders win approximately 80% of matches — halftime score is the single strongest predictor of match outcome in the dataset
- Attendance peaked at the 1994 USA World Cup (avg. ~69,000 per match), driven by large stadium capacity

---

## Project Context

Completed as part of the Ineuron.AI Data Science Internship (Sept–Oct 2023).
