# Music Streaming Behavior — Springfield vs Shelbyville

Data cleaning and analysis in Python (pandas) to find out whether listening habits change by city and by day of the week.

## Question

Do users of a music streaming service listen differently in Springfield and Shelbyville, and on Monday compared with Friday?

## Key findings

| Metric | Springfield | Shelbyville |
|---|---|---|
| Plays | 42,741 | 18,512 |
| Users | 29,358 | 12,423 |
| Plays per user | 1.46 | 1.49 |
| Change Monday → Friday | +1.3% | +5.0% |

- **City** changes the volume of plays, not the habit. Springfield has more plays because it has more users.
- **Day** has a small effect: Friday has 2.3% more plays than Monday.

## What the project covers

- Cleaning headers, missing values and duplicated rows (3,826 removed)
- Fixing implicit duplicates in `genre` with a reusable function, verified before and after
- Separating plays from unique users, so the comparison between cities is fair
- Cross-checking a custom function against a `groupby` result

## Tech stack

Python 3, pandas, Jupyter Notebook

## Project structure

```
music-streaming-analysis/
│
├── music_streaming_analysis.ipynb   # Full analysis with outputs
├── music_project_en.csv             # Dataset
└── README.md
```

## About

Built as part of the TripleTen Data Science program.  
Author: Mario Alberto Noriega Barrios
