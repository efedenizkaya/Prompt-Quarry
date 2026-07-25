# Data Analysis Templates

Structured prompts for interpreting data, running experiments, and communicating findings — built to keep every claim grounded in what the data actually shows, with uncertainty and limitations stated explicitly rather than smoothed over.

[← Back to main README](../README.md)

## Prompts

| Prompt | What it does |
|---|---|
| [A/B Test Results Interpreter](./A-B%20Test%20Results%20Interpreter.md) | Assesses statistical and practical significance separately, checks test power, and gives a ship/iterate/kill call grounded in both |
| [Chart Description Generator](./Chart%20Description%20Generator.md) | Writes an accessible, screen-reader-friendly chart description without overstating what the data shows |
| [Customer Feedback Analyser](./Customer%20Feedback%20Analyser.md) | Extracts real themes from feedback by frequency and severity, with representative (not just dramatic) examples |
| [Data Cleaning Instructions](./Data%20Cleaning%20Instructions.md) | Builds a step-by-step cleaning pipeline tailored to the actual sample data, with code and flagged trade-offs |
| [Data Dictionary Generator](./Data%20Dictionary%20Generator.md) | Documents a schema table-by-table, separating confirmed structure from inferred business meaning |
| [Data Interpreter](./Data%20Interpreter.md) | Analyzes a dataset for trends and insights, distinguishing what the data shows from what might explain it |
| [Report Summary Generator](./Report%20Summary%20Generator.md) | Condenses a long report into a one-page executive brief without inflating its certainty |
| [SQL Generator](./SQL%20Generator.md) | Writes an optimized, dialect-correct SQL query from a technical requirement, with index and explain-plan notes |
| [Survey Question Designer](./Survey%20Question%20Designer.md) | Designs a survey that fits a time budget, with each question mapped to the research objective and checked for bias |
| [Trend Analysis Prompt](./Trend%20Analysis%20Prompt.md) | Analyzes time-series data for trends and seasonality, and forecasts next quarter with an honest confidence range |

## How to use

1. Open the prompt file you need.
2. Copy the full contents into your AI tool (Claude, ChatGPT, etc.).
3. Fill in the `{placeholders}` with your actual data, schema, or requirements.
4. Leave optional placeholders blank if you don't have that info — most prompts handle missing context gracefully and will state their assumptions or flag insufficient data rather than guess silently.
