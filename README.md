# TsuiuChat Scripts Feed

Public content feed for [Tsuiu Chat](https://github.com/TsuiuChat/TsuiuChat) — role-play personas and
multi-character scenes pushed here are picked up by the app automatically (weekly check).

`feed.json` follows the app's `ScriptFeed` schema: `version` / `updatedAt` / `personas[]` / `scenes[]`
(same shape as `Persona` / `RolePlayScene` in the app source). Bump `version` and update `updatedAt` on
every change; `id`s must stay stable across releases so re-fetching never duplicates a script.
