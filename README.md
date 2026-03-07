# Data Journalism Projects

This repository is for tracking my data science and journalism projects. Some projects have a strong focus on data analysis with less emphasis on journalism, while others are journalism-heavy with minimal data analysis. The common thread is their contribution to evidence-based journalism.

## Directory Structure

Each project has its own directory, named using the following pattern:

`YYYYMMDD-project-slug`

For example:

`20260115-danish-housing-prices`

## Project File

Inside each project directory, there should be a primary markdown file containing useful information about the project. This file follows the naming convention:

`YYYYMMDD-PLATFORMCODE-project-slug.md`

`PLATFORMCODE` is a short code representing the publication or platform, for example:

*   `LWID`: Last Week in Denmark
*   `gazeteDK`: gazeteDK

### Project File Header

The first few lines of the project file should contain the following metadata:

*   **Title:** The title of the article or project.
*   **Copyright:** The copyright holder.
*   **License:** The license under which the work is released.
*   **Project Duration:** The start and end dates of the project. If the start date is unknown, use `Jan 1 2026`.

## Media Files

For now, media files (images, videos, etc.) will be stored within their respective project directories. A `media-info.md` file may be used to describe where various resources live and how to retrieve them.

## Template

Here is a template to follow when adding new projects to this repository.

### Example Directory and File Structure:

```
20260101-example-project/
└── 20260101-LWID-example-project.md
```

### Example `20260101-LWID-example-project.md` content:

```markdown
**Title:** Example Project Title
**Copyright:** © 2026 Your Name
**License:** All Rights Reserved
**Project Duration:** 2026-01-01 to 2026-02-01

---

This is where the main content of your project file will go.
```
