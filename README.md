# VendBuddy Open Resources

Source for [vendbuddy.github.io](https://vendbuddy.github.io), a small static site of free resources for people who run or want to start vending machine businesses. It is published by [VendBuddy](https://vendbuddy.io), software for vending operators.

## What is on the site

- **Location Scout** (`/location-scout/`): the open-source Chrome extension that gives a quick vending fit read on the business page you are viewing.
- **Open data** (`/data/`): summaries and charts for the Vending Location Index, public vending contract commission rates, and the State of Vending Operators snapshot, with CSV downloads.
- **Checklist** (`/checklist/`): a printable 10-point vending location scorecard.
- **Calculator** (`/calculator/`): a client-side payback calculator for one machine.

## How it is built

Plain HTML and CSS plus two tiny inline scripts (checklist scoring and the calculator). No build step, no framework, no cookies, no third-party scripts or fonts. Charts are inline SVG. Every page has a canonical URL on this site, Open Graph tags, `sitemap.xml` and `robots.txt`.

To preview locally, serve the folder with any static server, for example `npx serve .` or `python -m http.server`. Root-relative links such as `/style.css` need the folder served at the site root.

## Data and reports

The summaries are original; the full reports live on vendbuddy.io:

- [Vending Location Index](https://vendbuddy.io/research/vending-location-index)
- [Vending commission rates and contract terms](https://vendbuddy.io/research/vending-commission-rates)
- [State of Vending Operators](https://vendbuddy.io/research/state-of-vending-operators)

Raw CSVs and a data dictionary are in the [vending-data](https://github.com/vendbuddy/vending-data) repository (CC BY 4.0).

## License

Code and page markup: MIT (see `LICENSE`). The datasets are CC BY 4.0, credit "VendBuddy, vendbuddy.io". The calculator and checklist are informational tools, not financial advice or income promises.

Contact: hello@vendbuddy.io
