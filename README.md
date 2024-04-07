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

This repository automatically fetches and stores the latest Team Fortress 2 (TF2) item schema ( `GetSchemaItems` ), schema overview ( `GetSchemaOverview` ) and items_game, in JSON, XML, and VDF formats, directly from the Steam API.

## Usage
To make retrieval faster, you can pair this repository with jsdelivr. This will proxy the repository and store it on the edge.

Use one of the following URLs depending on your need:

| File ( FORMAT)             | Link                                                                                |
| ---------------------------|-------------------------------------------------------------------------------------|
| Item Schema ( JSON )       | `https://cdn.jsdelivr.net/gh/tsuza/tf2-item-schema/files/item_schema_json.txt`      |
| Item Schema ( VDF )        | `https://cdn.jsdelivr.net/gh/tsuza/tf2-item-schema/files/item_schema_vdf.txt`       |
| Item Schema ( XML )        | `https://cdn.jsdelivr.net/gh/tsuza/tf2-item-schema/files/item_schema_xml.txt`       |
| Schema Overview ( JSON )   | `https://cdn.jsdelivr.net/gh/tsuza/tf2-item-schema/files/schema_overview_json.txt`  |
| Schema Overview ( VDF )    | `https://cdn.jsdelivr.net/gh/tsuza/tf2-item-schema/files/schema_overview_vdf.txt`   |
| Schema Overview ( XML )    | `https://cdn.jsdelivr.net/gh/tsuza/tf2-item-schema/files/schema_overview_xml.txt`   |
| Items Game ( VDF )         | `https://cdn.jsdelivr.net/gh/tsuza/tf2-item-schema/files/items_game_vdf.txt`        |
| Items Game ( JSON )        | `https://cdn.jsdelivr.net/gh/tsuza/tf2-item-schema/files/items_game_json.txt`       |

> [!WARNING]\
> `jsdelivr` caches the file which may refresh after ~12 hours. If you can't afford having a slightly older version of the files and you can't wait, use `https://raw.githubusercontent.com/tsuza/tf2-item-schema/master/files/$file$` instead, and replace `$file$` with whatever you need.