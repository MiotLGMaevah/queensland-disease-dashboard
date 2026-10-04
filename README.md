# Queensland Notifiable Conditions Dashboard
https://miotlgmaevah.github.io/queensland-disease-dashboard/
Created by Maevah Miot.

An interactive descriptive dashboard of quarterly reported condition counts in Queensland, Australia, 2010–2014. Includes a cover, introduction, three charts, condition/category detail views, and data references.

## Features

- Top 10 conditions by total reported count
- STI conditions compared with other conditions
- Reported counts across 13 analytical categories
- Hover details and click-through annual counts and contributing conditions
- Responsive layout and keyboard navigation

## Methods and limitations

The supplied CSV contained 1,033 records and 67 condition labels. Labels and punctuation were standardized. 307 absent condition–quarter combinations were assigned assumed zeros, identified in a reporting-status column. Original numeric counts were preserved. Syphilis (Total) equals its three subcategories in every quarter; only the total contributes to dashboard totals. The 13 categories are mutually exclusive analytical groups, not an official diagnostic taxonomy. Hepatitis B is grouped with hepatitis. Counts describe reports, not unique patients, severity, population rates, or transmission routes. There is no minimum count cutoff.

The dashboard sums to 322,797 reports after excluding syphilis subcategory duplication. Each of the 25 detail views reconciles with its chart total.

## Data sources and attribution

Download source supplied by the project author: NationalDigitalAU, *QLD Notifiable Diseases 2010–2014*, Kaggle:
https://www.kaggle.com/datasets/nationaldigitalau/qld-notifiable-diseases-2010-2014

Corresponding official dataset: Queensland Health, *Notifiable Diseases: 2010–2014*, Queensland Government Open Data Portal:
https://www.data.qld.gov.au/dataset/notifiable-diseases-2010-2014

The official portal lists Creative Commons Attribution 3.0:
https://creativecommons.org/licenses/by/3.0/

This project adapts the data as described above. No endorsement by Queensland Health or Kaggle is implied. Source references checked October 3, 2026. The Kaggle listing was provided by the project author and could not be independently inspected.

## Files

- index.html: page structure and styling
- app.js: interactive charts, navigation and detail views
- data.json: aggregated dashboard data and annual detail tables
- README.md: project documentation

## Publish with GitHub Pages

Upload these four files to the root of a public GitHub repository. In Settings > Pages, select Deploy from a branch, main, and / (root), then Save. No dependency installation or build step is required.

## Local preview

Serve the folder over HTTP; opening index.html directly may prevent data.json from loading. If Python is installed, run `python3 -m http.server 8000` in this folder and open http://localhost:8000.

## Project development

Maevah Miot directed the data review, cleaning choices, chart selection, presentation structure, and design. Implementation was developed with ChatGPT/Codex assistance.
