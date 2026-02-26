# Keyword Mapping Dashboard

Interactive keyword research dashboard for content strategy, built around 4 content pillars.

## Files

| File | Description |
|------|-------------|
| `keyword_dashboard.html` | Standalone interactive dashboard — open directly in browser |
| `00_consolidated_keywords.csv` | Master keyword database (1,654 unique keywords) |

## Dashboard Features

- **Filters** — Search volume range, competition max, overall score min, content pillar, KW type, main topic
- **Table view** — Sortable, paginated keyword list with trend indicators
- **Charts tab** — 6 interactive charts:
  - Top 15 by Search Volume
  - Top 15 Lowest Competition
  - Keywords by Pillar (count)
  - Search Volume by Pillar
  - KW Type Breakdown (switchable metric)
  - Volume vs Competition bubble chart
- **Sweet spot detection** — 🎯 flags keywords with Vol > 50K, Competition < 50, Overall > 55

## Content Pillars

| Pillar | Description |
|--------|-------------|
| 🔴 Emotional Pain | Anxiety, suffering, existential struggles |
| 🟢 Personal Growth | Habits, productivity, self-improvement |
| 🟡 Purpose and Identity | Meaning, existentialism, nihilism, finding purpose |
| 🟣 Fundamental Knowledge | Philosophy, psychology, mental models, stoicism |

## Data

**Sources:** 14 topic files — anxiety, habits, jung, mental-models, personal-growth, philosophy, procrastination, productivity, schopenhauer, stoicism, existentialism, finding-purpose, meaning-of-life, nihilism

**Columns:** Main Topic, Keyword, Related score, Competition, Overall, Search volume, 30d ago searches, Timestamp, Number of words, KW Type, Content Pillar

## Usage

1. Open `keyword_dashboard.html` in any browser
2. Dashboard auto-loads `consolidated_keywords.csv` from the same folder
3. Use the **Reload** button in the header to refresh data after updating the CSV

## Updating the Database

Add or remove rows directly in `consolidated_keywords.csv`, save, then hit **Reload** in the dashboard. No rebuild needed.
