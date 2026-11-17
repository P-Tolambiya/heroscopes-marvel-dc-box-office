# HeroScopes – Marvel vs DC Box Office Performance

Power BI report comparing Marvel and DC films (1978–2024) at three
decision levels: strategic, tactical and operational. Group project
(team of four), Nackademin Business Intelligence & Analytics, BI26.

## Idea
One dataset, three audiences. The report is built so each role in a
film company gets the view they need, with a summary page linking them:

| Page | For | Question it answers |
|------|-----|---------------------|
| Summary | All roles | The big picture, with links to each level |
| Strategic | Chief Strategy Officer | What does historical performance tell us about future strategy? |
| Tactical | Director, Franchise Performance | What explains performance differences between Marvel and DC? |
| Operational | Film Performance Monitoring Coordinator | Which films are below the 2.5x threshold and need review? |

## Report pages
![Summary](heroscopes-summary.png)
![Strategic](heroscopes-strategic.png)
![Tactical](heroscopes-tactical.png)
![Operational](heroscopes-operational.png)

## How success is measured
A film counts as a success if its worldwide gross is at least 2.5x its
budget. This is a screening rule, not a profit calculation.

## Key findings
- Marvel generated 75% of total worldwide gross from 64% of the films.
- 66.7% of Marvel's films reached the 2.5x budget target, 22.8 points
  more than DC (43.9%).
- Next step suggested in the report: commission research on these gaps
  before any investment or release decision.

## What this data cannot tell us
- Marketing spend, studio receipts, streaming revenue and audience demand
- The 2.5x rule is a screening heuristic, not profit
- Values are nominal, and the 2020s are a partial decade

## Data model and DAX
One Films table plus a dedicated measures table. DAX measures include
Success Rate, Success Rate Gap, Gross to Budget, Median Gross to Budget,
Break-Even Gap, Flop Rate, Film Share, Gross Share and a missing-data check.

## Tools
Power BI, DAX, Power Query

## Data
[Marvels and DC , data taken from kaggle]

## My role
I built the Strategic page: Chief Strategy Officer (CSO) | 
What does historical performance tell us about future strategy?]

## Team
Group project with three classmates at Nackademin.
