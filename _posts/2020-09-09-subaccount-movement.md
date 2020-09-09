---
layout: posts
permalink: /subaccount-movement/
repository: https://github.com/saud-learning-services/subaccount-movement-script
syzygy: https://ubc.syzygy.ca

title: Subaccount Movement

summary: Subaccount Movement is a Jupyter Notebook and Python script that moves any Sauder course into a specific Canvas sub-account. Upon providing the necessary input, the script will locate the appropriate sub-account, migrate the course to it, and produce a CSV file detailing the courses and the sub-accounts.
---

## Input
* Account ID *(last digits of URL when visiting accounts page)
* Canvas Token *(generate through Account => Settings)

## Output

### `.csv` detailing

- **Course ID** (as it appears on Canvas)
- **Course Code** (as it appears on Canvas)
- **Course Name** (as it appears on Canvas)
- **Term ID** (semester term)
- **Original Account** (account course was originally in)
- **New Account** (account course has been moved to)
- **New Account ID** (as it appears in the output PDFs)
- **Match at** (course property used to match course to new account)

> NOTE: this table contains sensitive information and should **NOT** be distributed or uploaded anywhere
