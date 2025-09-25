# Cybersecurity Internship - Task 3
**Task:** Basic Vulnerability Scan on Your PC

## Objective
Use a free vulnerability scanner to identify common vulnerabilities on your computer and document the findings.

## Tools Suggested
- **OpenVAS / Greenbone Vulnerability Manager (GVM)** (Community edition) — free

> Note: Installing and running these scanners may require admin/root access and can take 30–60 minutes for a full scan.

## Steps I Followed (What you should do)
1. Install OpenVAS/GVM or register for Nessus Essentials and install it.
2. Start the service and open the web UI (e.g., `https://localhost:9392` for Nessus, or GVM's web UI).
3. Add a scan target: set it to your local IP (e.g., `10.188.202.130`) or `localhost`.
4. Create a full/vulnerability scan profile and start the scan. Wait until the scan finishes.
5. Export the report (HTML/PDF/CSV) and take screenshots of the results page.
6. Research remediation steps for the highest-severity findings.
7. Save the exported report and screenshots in this repo (place them in `reports/` and `screenshots/`).
8. Add a short summary of critical vulnerabilities in `vulnerability_report.md` (see template below).

## Files in this repo
- `vulnerability_report.md` — place your findings and short remediation notes here
- `scan_instructions.txt` — quick commands and tips for running scans
- `screenshots/` — store screenshots of the scan UI/results
- `reports/` — (create this folder) put exported HTML/PDF/CSV reports here

## Safety & Ethics
- Only scan machines you own or have explicit permission to scan.
- Do not use these tools against external networks without authorization.
- Scanners can cause network or system instability; run in maintenance windows if needed.
