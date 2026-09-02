# onesymbios.com

The Symbios marketing site. Static HTML, no build step, no dependencies.

**This repo is the site.** Editing a file here and saving it to `main` publishes it, usually
within a minute. Netlify watches this repo and does the rest. There is nothing else to run.

## What is here

```
index.html            homepage
launch/index.html     launch animation, at /launch/
representation/       Symbios Representation demo app, live but not linked from anywhere
og-image.png          preview image used when a link is shared
netlify.toml          tells Netlify to publish this folder as-is
```

Every page is one self-contained file, styling and behaviour included. Open one straight from
disk in a browser and it looks exactly like the live thing.

## Editing

For a small change, edit the file on github.com: open it, click the pencil, save with
"Commit changes". That publishes it.

For anything larger or uncertain, work on a branch. Branch deploys give a private preview URL
and are free, where publishing to `main` costs Netlify credits. Preview first, then merge once.

## Undoing

Every published version is in this repo's history. Open Commits, find the change, revert it.

Backups of every version published before September 2026, and the history of how the site used
to be built, are kept on Kyle's Mac under `Symbios/Marketing & Communications/Website/`.

Symbios is a culture consultancy. Culture is a profit strategy.
Say hello at connect@onesymbios.com
