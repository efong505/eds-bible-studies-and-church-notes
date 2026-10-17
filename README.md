# Ed's Bible Studies and Church Notes

A public library of **individually approved** Bible studies and church notes.

## Published studies

- [Bishops, Deacons, the Fivefold Ministry, and God's Appointments in the Church](./studies/bishops-deacons-fivefold-ministry.md) — October 17, 2026; includes three Mermaid diagrams.

## Website

The website is implemented in [index.html](./index.html) and loads the published Markdown study from the `studies/` folder. To activate GitHub Pages, open **Settings → Pages → Build and deployment**, select **Deploy from a branch**, choose **main** and **/(root)**, then save. Once deployed, the expected URL is:

https://efong505.github.io/eds-bible-studies-and-church-notes/

## Publication policy

The private `Lord-of-Hosts` repository remains private. Only studies explicitly approved for public sharing should be copied into this repository. Review personal data, comments, metadata, and references before each publication. The public site must not access the private repository, and public source history may remain accessible after deletions.

## Technical notes

Static GitHub Pages site; no backend or private credentials. Markdown rendering uses Marked, sanitization uses DOMPurify, and diagrams use Mermaid from public CDNs. Internet access is required for these libraries to load.
