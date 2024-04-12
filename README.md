<div align="center">
  <h1>TF2 Item Schema</h1>
  <p>
    <strong>Automatically parses the latest TF2 item schema from the Steam API</strong>
  </p>
  <p style="margin-bottom: 0.5ex;">
    <img
        src="https://img.shields.io/github/last-commit/tsuza/tf2-item-schema"
    />
    <img
        src="https://img.shields.io/github/issues/tsuza/tf2-item-schema"
    />
    <img
        src="https://img.shields.io/github/issues-closed/tsuza/tf2-item-schema"
    />
    <img
        src="https://img.shields.io/github/repo-size/tsuza/tf2-item-schema"
    />
  </p>
</div>

## Purpose

This repository automatically fetches and stores the latest Team Fortress 2 (TF2) item schema ( `GetSchemaItems` ), schema overview ( `GetSchemaOverview` ) and items_game, in various formats ( such as VDF, JSON, and XML ) and localized in the languages supported by TF2, directly from the Steam API.

The workflow will check and eventually download the files every day at ~6:25PM CET.

## Usage
To make retrieval faster, you can pair this repository with jsdelivr. This will proxy the repository and store it on the edge.

Use the following URL format:
```
https://cdn.jsdelivr.net/gh/tsuza/tf2-item-schema/$file$
```

Just replace `$file$` with the file you need. `files/` contains the **raw** files, unlocalized. `files/localized/` contains the localized files. 
They all follow the following naming scheme: `filetype_format_language.txt` ( language should be omitted if you're not downloading from the `files/localized/` folder ). Pick the one that suits your needs.

> [!WARNING]\
> `jsdelivr` caches the file which may refresh after ~12 hours. If you can't afford having a slightly older version of the files and you can't wait, use `https://raw.githubusercontent.com/tsuza/tf2-item-schema/master/files/$file$` instead, and replace `$file$` with whatever you need.