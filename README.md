# IBM Cognos Customer Loyalty Dashboard

A customer-loyalty analytics project built around an IBM Cognos dashboard and customer loyalty data, with supporting Google Looker Studio dashboard views added for comparison and exploration. The repository includes the source dataset and visual references for the dashboard work.

## Preview

![Customer loyalty dashboard preview](Screenshot%202026-09-24%20120214.png)

[Open the original dashboard screenshot](Screenshot%202026-09-24%20120214.png)

> The screenshot is included as a visual reference for the dashboard. The editable IBM Cognos report is not included in this repository.

## Google Looker Studio screenshots

The project now includes additional dashboard screenshots created in Google Looker Studio for review and sharing.

### Looker Studio view 1

![Google Looker Studio dashboard screenshot 1](Screenshot%202026-09-25%20122330.png)

[Open screenshot 1](Screenshot%202026-09-25%20122330.png)

### Looker Studio view 2

![Google Looker Studio dashboard screenshot 2](Screenshot%202026-09-25%20122625.png)

[Open screenshot 2](Screenshot%202026-09-25%20122625.png)

## Repository contents

| File | Description |
| --- | --- |
| [`CustomerLoyaltyProgram (1).csv`](CustomerLoyaltyProgram%20%281%29.csv) | Source customer-loyalty dataset used for analysis. |
| [`Screenshot 2026-09-24 120214.png`](Screenshot%202026-09-24%20120214.png) | Original IBM Cognos dashboard reference image. |
| [`Screenshot 2026-09-25 122330.png`](Screenshot%202026-09-25%20122330.png) | Google Looker Studio dashboard screenshot 1. |
| [`Screenshot 2026-09-25 122625.png`](Screenshot%202026-09-25%20122625.png) | Google Looker Studio dashboard screenshot 2. |

## Project goals

This project is intended to support customer-loyalty analysis in IBM Cognos and Google Looker Studio, including:

- Exploring customer and loyalty-program data
- Building interactive dashboard views and visual summaries
- Comparing dashboard design approaches across IBM Cognos and Looker Studio
- Identifying patterns that can support customer-retention and loyalty decisions
- Sharing a reproducible source dataset alongside dashboard reference images

## Getting started

### Prerequisites

- Access to IBM Cognos Analytics or another compatible analytics tool
- Access to Google Looker Studio, if you want to recreate the dashboard views
- Permission to upload or import the CSV dataset
- A local clone or download of this repository

### Use the dataset in IBM Cognos

1. Download [`CustomerLoyaltyProgram (1).csv`](CustomerLoyaltyProgram%20%281%29.csv).
2. In IBM Cognos Analytics, create a new data source or upload the CSV as a data asset.
3. Review the detected fields and data types before creating visualizations.
4. Build a dashboard using the measures and dimensions relevant to the analysis.
5. Save or export the resulting report from IBM Cognos according to your organization’s sharing policy.

### View the reference images locally

Open the screenshots in an image viewer, or view them directly from the repository on GitHub:

- `Screenshot 2026-09-24 120214.png`
- `Screenshot 2026-09-25 122330.png`
- `Screenshot 2026-09-25 122625.png`

## Data considerations

- The CSV is a large source file, so importing it may take some time depending on the Cognos or Looker Studio environment.
- Validate field types, missing values, duplicate records, and categorical values before building the final dashboard.
- Treat the dataset as analytical source data and apply your organization’s privacy, security, and retention requirements before sharing it.
- The repository does not currently include transformation scripts, a formal data dictionary, or an IBM Cognos report package.

## Reproducing or extending the analysis

To extend the project, consider adding:

- A data dictionary describing each field and its business meaning
- Data-cleaning or preparation steps
- The IBM Cognos report specification or export, where sharing is permitted
- The Looker Studio report configuration or exported assets, where sharing is permitted
- Dashboard screenshots with descriptive names and dates
- Key findings and definitions for the metrics presented

## License

No license is currently specified for this repository. Unless the repository owner adds a license, reuse and redistribution should be treated as requiring permission from the owner.
