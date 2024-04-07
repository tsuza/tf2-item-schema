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

This repository automatically fetches and stores the latest Team Fortress 2 (TF2) item schema in JSON, XML, and VDF formats, directly from the Steam API.

## Usage
To make retrieval faster, you can pair this repository with jsdelivr. This will proxy the repository and store it on the edge.

Use one of the following URLs depending on your preferred format:

| Item Schema Format FIle         | Link                                                                     |
| ------------------------------- |--------------------------------------------------------------------------|
| JSON format                     | `https://cdn.jsdelivr.net/gh/tsuza/tf2-item-schema/item_schema_json.txt` |
| VDF format                      | `https://cdn.jsdelivr.net/gh/tsuza/tf2-item-schema/item_schema_vdf.txt`  |
| XML format                      | `https://cdn.jsdelivr.net/gh/tsuza/tf2-item-schema/item_schema_xml.txt`  |