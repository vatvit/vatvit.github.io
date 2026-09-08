# vatvit.github.io

Published artefacts for **vatvit's** projects — anything that needs a permanent, public,
login-free address. Live at <https://vatvit.github.io/>.

It exists because store consoles ask for a *URL*, not a file. A privacy policy, a licence or a
press kit has to be reachable by a reviewer who has no account and no access to the project, and
that address has to keep working for as long as the listing does.

## Who may use it

**Only projects whose GitHub owner is `vatvit`.**

Publishing another identity's artefact here would put the string `vatvit` into that project's store
listing, which is exactly what that project's identity isolation forbids. A project under a
different owner needs its own host — do not reach for this repo by reflex because it is convenient.

## Layout

One folder per project, documents directly inside it:

```
index.md                    the landing page; add a section per project
_config.yml                 Pages config — theme, link rewriting
dark-maze/
  privacy.md                -> https://vatvit.github.io/dark-maze/privacy/
```

Flat on purpose. A project that later publishes a lot can grow subfolders
(`dark-maze/press/…`) **without moving anything already published** — which matters, because a URL
that has reached a store console cannot be changed without editing every console and passing
review again.

## Adding a document

1. Create `<project>/<document>.md`.
2. Give it front matter with a `permalink` that matches its path:

   ```yaml
   ---
   title: Dark Maze — Privacy Policy
   description: One line, used as the page description.
   permalink: /dark-maze/privacy/
   ---
   ```

   **The `permalink` is the contract.** Without it the page lands at `/dark-maze/privacy.html`
   instead, and that is not the address anyone was given.
3. Link it from `index.md`.
4. Push. Pages rebuilds in about a minute.

## Where these documents come from

**This repository publishes; it does not author.** Each document has a canonical source in the
project it belongs to, and the copy here is a publication of it:

| Published here | Canonical source |
|---|---|
| `dark-maze/privacy.md` | `PRIVACY.md` in the `game-dark-maze` repository (task MAZE-192) |

Edit the source first, then copy the body across — front matter differs, the body must not. The
game repository's copy is the one whose claims were verified against the actual build, so it is the
one that gets edited when the game changes.
