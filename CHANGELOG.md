## 🎉 Alley v2.2.11

### 🔧 **PATCH RELEASE** - Bug Fixes & Improvements

**Previous Version:** `2.2.10`
**New Version:** `2.2.11`

### 📝 Changes:

- 🚀 Auto-update version to 2.2.10 (🔧 **PATCH** RELEASE) (864383ec)
- chore: update revere repo url (733a3f9a)
- 🚀 Auto-update version to 2.2.9 (🔧 **PATCH** RELEASE) (4b265bf9)
- chore: passed the player's name as a constructor argument to Profile during login. The previous logic relying on Bukkit.getOfflinePlayer(uuid).getName() could return null for players joining for the very first time, causing a validation error when the new profile was immediately saved to the database. (014ced4c)
- 🚀 Auto-update version to 2.2.8 (🔧 **PATCH** RELEASE) (89eeff6e)
- feat: finalize configurable messages by refactoring locale getters and making remaining key messages configurable (edae5483)
- feat: configurable clickable messages (and some other messages... eventually all to be completed within the next final commit to this branch) (55169ada)
- feat: ffa death messages now configurable (and some more) (6d094a7a)
- feat: certain permissions are now customizable and updated config files (423a1f72)
- feat: implemented method to easily retrieve and format command usages, fix the tab-list constantly being disabled, make plenty of more messages configurable, the chat format is now customizable (can also be enabled or disabled depending on the users need). (b5da6fde)
- feat: more configurable messages and consistent placeholders (d7d4163b)
- feat: new config structure/layout, replaced all message locales with two generic implementations (6d6d9489)
- feat: updated config files. Titles, command messages, in game messages, match result messages, etc... now configurable. (d4d4637a)
- chore(locale-service-impl): translate default value color codes (61db0342)
- feat: recode locale system with safe defaults, automatically set missing entries and return defaults if still absent, make additional messages configurable, and add missing usage and description to CommandData annotations as the usage format will eventually be configurable and required for all commands (with a method to retrieve the usage message for convenience) (18512746)
- 🚀 Auto-update version to 2.2.7 (🔧 **PATCH** RELEASE) (bb52d54b)
- feat: expand on arena condition check (8fc22a12)
- feat: with all my patience, making some more messages configurable 2.0 (d90aee6b)
- feat: with all my patience, making some more messages configurable... (45a25409)
- feat: fixed ffa add, kick and setup command, same goes for division set wins command (cd75214f)
- chore: what in the world is this command ??? (2cea32ee)
- feat: made more commands and messages configurable (ffa / duel) (2f1a6128)
- feat: division and cosmetic commands are now configurable (433dea5f)
- feat: started making messages configurable (c50fc64e)
- chore: fix "plugin loaded in" millis calculation (ade1b108)
- 🚀 Auto-update version to 2.2.6 (🔧 **PATCH** RELEASE) (463c51d9)
- 🚀 Auto-update version to 2.2.5 (🔧 **PATCH** RELEASE) (7ff8e1e7)
- chore: fixing remi's mess where he couldn't refactor properly; turning "Practice PvP core" into "Practice PvP knockback" (b8ccec59)
- 🚀 Auto-update version to 2.2.4 (🔧 **PATCH** RELEASE) (0450e6dd)
- chore: unify cloak rotation logic into base class (abca53a2)
- chore: implemented cloaks and suits, improved cosmetics storing, added server title command, removed body fall kill effect, reverted papi placeholders (f4188c69)
- 🚀 Auto-update version to 2.2.3 (🔧 **PATCH** RELEASE) (b3fe391a)
- chore(pom): prevent shading minecraft server files and apis (e5a104e6)
- 🚀 Auto-update version to 2.2.2 (🔧 **PATCH** RELEASE) (55b740f0)
- chore(project): refactor "model" in places where it was accidentally renamed from its origin name (c0ba2fb8)
- chore(project): refactor "model" in places where it was accidentally renamed from its origin name (408fc12f)
- 🚀 Auto-update version to 2.2.1 (🔧 **PATCH** RELEASE) (ccd8f63f)
- chore(project): refactor "model" in places where it was accidentally renamed from its origin name (7bb5f5a0)
- 🚀 Auto-update version to 2.2.0 (📈 **MINOR** RELEASE) (13a9e1ed)
- chore: bump version (d27bb678)
- 🚀 Auto-update version to 2.1.12 (🔧 **PATCH** RELEASE) (5e07a11f)
- Merge pull request #26 from RevereInc/chore/project-structure MINOR (fb315503) ([#26](https://github.com/mmodplus/alley-practice/pull/26))
- 🚀 Auto-update version to 2.1.11 (🔧 **PATCH** RELEASE) (bb7dd0f8)
- chore(project): refactor entire package structure for modern conventions (dbfc3daa)
- 🚀 Auto-update version to 2.1.10 (🔧 **PATCH** RELEASE) (86072dab)
- chore: prevent loading profiles upon kit creation, more robust and safe implementation for mongo data parsing and conversion, and fix scoreboard profile state variables where potential race conditions could occur (865181b3)
- 🚀 Auto-update version to 2.1.9 (🔧 **PATCH** RELEASE) (ea033846)
- chore: Added missing string in settings.yml (e769ae35)
- 🚀 Auto-update version to 2.1.8 (🔧 **PATCH** RELEASE) (1fa75700)
- chore(duel-request-service-impl): validate that original arena name isnt null before overwriting the final arena (bd73f78c)

---
**Download:** [Alley-2.2.11.jar](https://github.com/mmodplus/alley-practice/releases/download/v2.2.11/Alley-2.2.11.jar)

**Installation:** Place the JAR file in your `plugins/` folder and restart your server.

---
### 🏷️ Version Bump Keywords

- Add `MAJOR` to commit messages for breaking changes (X.0.0)

- Add `MINOR` to commit messages for new features (X.Y.0)

- Add `PATCH` to commit messages for bug fixes (X.Y.Z)

- No keyword = automatic patch bump

- Add `SKIP-RELEASE` or `[skip release]` to skip creating a release

