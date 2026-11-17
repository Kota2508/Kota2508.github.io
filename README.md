# Karthik Kumar Kota — Portfolio

A responsive static portfolio site for GitHub Pages.

## Local preview

No build tools or package installation are required. From this directory, run:

```bash
python3 -m http.server 8000
```

Open <http://localhost:8000>.

## Deploy to GitHub Pages

This repository is intended to be named `Kota2508.github.io`, which publishes to <https://kota2508.github.io>.

1. Push the contents of this directory to the `main` branch.
2. In GitHub, open **Settings → Pages** and select **GitHub Actions** as the build and deployment source if it is not already selected.
3. Confirm **Settings → Actions → General → Workflow permissions** allows the workflow to run.
4. Open the **Actions** tab and wait for **Deploy portfolio to GitHub Pages** to complete.
5. Verify the site at <https://kota2508.github.io>.

The workflow in `.github/workflows/pages.yml` uploads this static directory as the Pages artifact and deploys it. The site has no server-side runtime.

## Updating project destinations

Project links currently point to the planned public repositories:

- `Kota2508/applytrack`
- `Kota2508/ordercore`
- `Kota2508/vulnboard`

Update the links in `index.html` if repository names change.
