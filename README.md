# 🗺️ share-azgaar-map

Small app to generate links to maps generated by azgaar/fantasy-map-generator.

## 🔌 Usage

### yarn updateSubmodules

Pulls map generator.

### yarn dev

Serves map generator and launches microservice.

## 🔍 About

- `/azgaars-map-generator` **[submodule]** <- my fork of azgaar's map generator
  - Added map upload from link in query -- `?maplink=<link-to-map>`
- `/map-share-service` <- uploads maps and generates access links
  - Needs `DROPBOX_ACCESS_TOKEN` in `process.env`.
  - TODO:
    - [ ] Upload maps
    - [ ] Generate short links
- `/map-share-frontend` <- catalog of maps uploaded with the app
  - [ ] Get maps from backend
