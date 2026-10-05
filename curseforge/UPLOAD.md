# CurseForge upload checklist

Files in this folder: `summary.txt` (project summary), `description.md` (project description, paste in the
Markdown editor).

## 1. Before uploading
- [ ] Icon in the mod: `src/main/resources/manholes_logo.png` (or `logoFile` in `neoforge.mods.toml`).
- [ ] Rebuild: `./gradlew build` -> `build/libs/manholes-1.7.3.jar`.
- [ ] Screenshots / GIF: test in game and capture screenshots (closed manhole in village, prying HUD, map, travel).

## 2. Create the project (Minecraft > Mods)
| Field | Value |
|---|---|
| Name | Manhole Travel |
| Slug | `manhole-travel` |
| Summary | contents of `summary.txt` |
| Description | contents of `description.md` (Markdown) |
| Avatar | `curseforge/icon/mod_icon_1024.png` (1024x1024) |
| Main category | Transportation |
| Other categories | Adventure and RPG, Map and Information, Utility & QoL |
| License | MIT |
| Source URL | https://github.com/Feffolino/manhole-travel |
| Issues URL | https://github.com/Feffolino/manhole-travel/issues |

## 3. Upload the file
| Field | Value |
|---|---|
| File | `build/libs/manholes-1.7.3.jar` |
| Display name | Manhole Travel 1.7.3 (1.21.1 NeoForge) |
| Release type | Release |
| Game version | 1.21.1 |
| Mod loader | NeoForge |
| Environment | Client and Server (required on both) |
| Java | Java 21 |
| Changelog | contents of `CHANGELOG.md` |

## 4. Relations (file upload page, "Related projects")
| Project | Type |
|---|---|
| KubeJS | Optional dependency |
| FTB Teams | Optional dependency |
| FTB Chunks | Optional dependency |

Do not mark any as Required: only NeoForge is needed.

## 5. After approval
- [ ] Tag the release on GitHub: `git tag v1.7.3 && git push origin v1.7.3`.