# Parv Prabhakar

Static source for parvprabhakar.com: work, writing, media and speaking, and about pages.

## Edit

Update content in `build_site.py` and styling in `site/styles.css`, then run:

```sh
python3 build_site.py
```

The generator writes the four pages into `site/` and creates a standalone HTML preview and deployable ZIP in `../deliverables/`.

## Deploy

Publish the `site/` directory to the existing Netlify project that owns parvprabhakar.com. `netlify.toml` sets the publish directory for Git-based deployments. No build command or package dependencies are needed because generated pages are committed.

Verify the custom domain belongs to the selected project before deploying. This repository being updated does not by itself confirm that the live website has changed.

## Content

Media items link to their original sources. Syndicated copies of the same interview are grouped together. Article commentary is separate from authored writing.
