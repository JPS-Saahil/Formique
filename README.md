# Formique

> A personal asset repository. Stores files for multiple projects — web, CAD, 3D, and more.

<p align="left">
  <a href="https://github.com/JPS-Saahil" target="_blank" rel="noreferrer">
    <img src="https://img.shields.io/badge/JPS--Saahil-181717?style=for-the-badge&logo=github&logoColor=white&label=GitHub" alt="GitHub">
  </a>
  <a href="https://www.linkedin.com/me?trk=p_mwlite_feed-secondary_nav" target="_blank" rel="noreferrer">
    <img src="https://img.shields.io/badge/Profile-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white&label=LinkedIn" alt="LinkedIn">
  </a>
  <a href="mailto:jpssaahil2003@outlook.com">
    <img src="https://img.shields.io/badge/jpssaahil2003%40outlook.com-0078D4?style=for-the-badge&logo=microsoftoutlook&logoColor=white&label=Email" alt="Email">
  </a>
  <a href="https://creativecommons.org/licenses/by-nc/4.0/" target="_blank" rel="noreferrer">
    <img src="https://img.shields.io/badge/CC%20BY--NC%204.0-6E6E6E?style=for-the-badge&logo=creativecommons&logoColor=white&label=License" alt="License">
  </a>
</p>

## Navigation

[Overview](#overview) · [Branches](#branches) · [Structure](#structure) · [Referencing assets](#referencing-assets) · [License](#license)

---

## Overview

Formique is a centralized asset store maintained by **JPS Saahil**.

It holds files for various projects — including website assets, CAD exports, 3D models, renders, sketches, textures, and miscellaneous docs. Each project gets its own folder inside the `assets` branch. Nothing here is meant to be deployed on its own; it exists purely as storage and a source for raw file references.

---

## Branches

| Branch | Purpose |
|:--|:--|
| `main` | This README and any index or manifest files |
| `assets` | All project asset folders — the actual files |

---

## Structure

The `assets` branch is organized by project. Each project lives in its own folder.

```txt
assets (branch root)
├── project-name/
│   ├── images/
│   ├── models/
│   ├── renders/
│   ├── cad/
│   └── misc/
├── another-project/
│   └── ...
└── ...
```

Subfolders within each project folder are informal — organized however suits that project.

---

## Referencing assets

Any file in the `assets` branch can be referenced directly by its raw GitHub URL.

**Pattern**

```
https://raw.githubusercontent.com/JPS-Saahil/formique/assets/<project-name>/<path-to-file>
```

**Examples**

```
https://github.com/JPS-Saahil/Formique/tree/Assets/BLENDER%20PROJECTS
https://github.com/JPS-Saahil/Formique/tree/Assets/CAD%20Projects/Basic%20Part%20design
https://github.com/JPS-Saahil/Formique/tree/Assets/Kashmir%20shaivism%20website%20assets
```

> Keep file paths stable after referencing them externally. Renaming or moving a file will break any links pointing to it.

---

## License

Licensed under the **Creative Commons Attribution-NonCommercial 4.0 International License**.

You may share and adapt material for non-commercial use with proper attribution.

[creativecommons.org/licenses/by-nc/4.0](https://creativecommons.org/licenses/by-nc/4.0/)

---

*Maintained by [JPS Saahil](https://github.com/JPS-Saahil)*
