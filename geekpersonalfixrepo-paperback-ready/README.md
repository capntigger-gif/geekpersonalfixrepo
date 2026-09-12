# Geek Personal Fix Repo

Personal Paperback v0.9 extensions, including a fixed League of Comic Geeks tracker.

## Installation

After GitHub Pages has been enabled and the workflow has run, add this repository to Paperback:

`https://capntigger-gif.github.io/geekpersonalfixrepo/0.9/stable/`

In Paperback:

**Settings → Extensions → Add Repository**

Then install **LeagueOfComicGeeks**.

## What was fixed

The League of Comic Geeks progress tracker now sends completed Paperback chapter-read events to the site's **Read List** instead of the **Collection** list.

## Build

```bash
npm install
npm run tsc
npm run bundle
```

The bundle command generates the `bundles/` directory and the `versioning.json` manifest used by Paperback.
