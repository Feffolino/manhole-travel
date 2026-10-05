# CurseForge upload checklist

Files in this folder: `summary.txt` (project summary), `description.md` (project description, paste in the
Markdown editor).

## 1. Before uploading
- [ ] Icon in the mod: `src/main/resources/manholes_logo.png` (or `logoFile` in `mods.toml`).
- [ ] Rebuild: `./gradlew build` -> `build/libs/manholes-1.7.3-1.20.1.jar`.
- [ ] Verify GameTests pass on Forge 1.20.1.

## 2. Project fields
| Field | Value |
|---|---|
| Name | Manhole Travel |
| Slug | `manhole-travel` |
| Summary | contents of `summary.txt` |
| Description | contents of `description.md` (Markdown) |
| Avatar | `curseforge/icon/logo.png` |
| Main category | Transportation |
| Other categories | Adventure and RPG, Map and Information, Utility & QoL |
| License | MIT |
| Source URL | https://github.com/Feffolino/manhole-travel |
| Issues URL | https://github.com/Feffolino/manhole-travel/issues |

## 3. Upload the file
| Field | Value |
|---|---|
| File | `build/libs/manholes-1.7.3-1.20.1.jar` |
| Display name | Manhole Travel 1.7.3 (1.20.1 Forge) |
| Release type | Release |
| Game version | 1.20.1 |
| Mod loader | Forge |
| Environment | Client and Server (required on both) |
| Java | Java 17 |
| Changelog | Port to Forge 1.20.1 with identical feature parity. |

## 4. Relations (file upload page, "Related projects")
| Project | Type |
|---|---|
| KubeJS | Optional dependency |
| FTB Teams | Optional dependency |
| FTB Chunks | Optional dependency |

Do not mark any as Required: only Forge 47.4.23+ is needed.

## 5. After approval
- [ ] Tag the release on GitHub: `git tag v1.7.3-1.20.1 && git push origin v1.7.3-1.20.1`.