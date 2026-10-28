### Hi, I'm Jean-François

I live in Quebec City. I write Python and PowerShell scripts that take repetitive work off people's
hands, and I keep servers and their backups in good shape. If you spend an hour a week copying numbers
from one place to another, or checking by hand that last night's backup ran, there's a good chance a
script can do it in a few seconds.

**The kind of jobs I take on:**

- Pulling data from websites into a spreadsheet (prices, listings, product info)
- Merging and cleaning CSV or Excel files, then building the report with totals and charts
- Reading PDF invoices or statements and turning them into rows in Excel
- Connecting to an API (exchange rates, a store, a CRM) and storing the data in a database
- Small bots that send a Telegram or email alert when something changes
- Simple web dashboards in Flask so the numbers can be checked in a browser
- Command-line tools packaged properly, with tests, so they keep working after I hand them over
- Server health checks in PowerShell: IIS and Nginx logs, Windows events, disks, expiring certificates
- Automated, verified backups with Docker Compose (Postgres, SQLite), rotation and a status page
- Parametric 3D models generated from code: a batch of STL files ready for the printer from a spreadsheet

**Examples you can run:** [portfolio-automatisation](https://github.com/netposh-ux/portfolio-automatisation)
has ten working demos, each with sample data and a README that shows the output. The four newest come
with 76 automated tests:

| Demo | What it proves |
|---|---|
| [07 · Duplicate finder](https://github.com/netposh-ux/portfolio-automatisation/tree/main/07-duplicate-finder) | A packaged Python CLI, safe by default (dry run), JSON and HTML reports, 16 pytest tests |
| [08 · Server health audit](https://github.com/netposh-ux/portfolio-automatisation/tree/main/08-server-health-audit) | PowerShell 7: 5xx rate and p95 latency from IIS/Nginx logs, Windows events, certificates, disks; exit codes for monitoring; 19 Pester tests |
| [09 · Docker backup monitor](https://github.com/netposh-ux/portfolio-automatisation/tree/main/09-docker-backup-monitor) | Postgres and SQLite backups with SHA-256 checks, daily/weekly rotation, status page, restore tested; 20 pytest tests |
| [10 · Parametric STL badges](https://github.com/netposh-ux/portfolio-automatisation/tree/main/10-parametric-stl) | 3D-printable models from a few numbers or a CSV, multi-colour split, every mesh checked (closed, oriented, exact volume); 21 pytest tests |

**On my own time** I've built a trading bot for Coinbase and Kraken with its own dashboard, a home
dashboard for cameras and sensors, and a website for a non-profit.

I work in French and English. If you have a task that eats your time, open an issue on one of my
repos or reach out through the contact on this profile and describe what you do today, step by step.
