# INTEL SHEETX BI

An AI-assisted business intelligence web application for exploring spreadsheet data, creating charts, and generating evidence-based insights.

## Features

- CSV and Excel data upload
- Data profiling and field classification
- Natural-language analytics commands
- Interactive charts and dashboards
- Governed business metrics
- Insight planning and agent-assisted analysis
- Query provenance and export tools

## Repository Status

This repository currently contains a single-file frontend:
`index (4).html`.

The HTML includes the application's interface, JavaScript, and styling.

## Important: Backend Required

This is not a standalone offline application.

Authentication, spreadsheet processing, analytics queries,
saved dashboards, and scheduled digests require a separately
running Python backend.

GitHub Pages can display the frontend, but it cannot run the
Python backend. Full functionality requires backend deployment
and API configuration.

## Technology

- React and TypeScript
- Tailwind CSS
- Apache ECharts
- FastAPI backend
- DuckDB and Parquet for analytics
- SQLite for application metadata

## Publishing the Frontend

1. Rename the HTML file to `index.html`.
2. Open Settings → Pages.
3. Choose “Deploy from a branch”.
4. Select `main` and `/ (root)`.
5. Save and wait for deployment.

## Privacy

Do not commit passwords, API keys, `.env` files,
private spreadsheets, or application databases.
