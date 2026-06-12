# Fare Brothers Maintenance Page

Upload these files to the same GitHub Pages folder/branch:

- index.html
- admin.html
- status-config.json

Current recommended status:

- 99 = No active outage
- 90 = Planned outage
- 0 = Upgrades in progress
- 1-6 = Progress stages

The admin page cannot directly update GitHub for everyone because this is static HTML. Use admin.html to download the new status-config.json, then commit/replace it in GitHub.
