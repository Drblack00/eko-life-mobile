# Èkó Life Mobile

Unity rebuild of the **Èkó Life** Lagos life-sim, built native for iOS and Android.
Original code — same brand and life-sim feel as the web game, rebuilt for mobile.

- Web game (live): https://github.com/Drblack00/eko-life
- Mobile repo: this one

## Open it in Unity

1. Install **Unity Hub** on your Mac.
2. In Unity Hub, install a **Unity 6 LTS** editor.
3. Unity Hub → **Add** → **Add project from disk** → pick this folder.
4. Open the project. Unity generates `Library/`, `Temp/` etc. on first open —
   all of it is git-ignored, so a fresh clone stays small.

> `ProjectSettings/ProjectVersion.txt` pins Unity `6000.0.23f1`. If your
> installed editor is newer, Hub will offer to upgrade the project — say yes.

## Where things go

- `Assets/` — everything you make: scenes, scripts, prefabs, art, audio
- `Packages/manifest.json` — Unity package dependencies
- `ProjectSettings/` — editor + player settings (Android and iOS targets)

## Roadmap

- [ ] Core life-sim loop: class assignment, jobs, energy, rent, property
- [ ] Mobile-first UI — touch controls, portrait + landscape
- [ ] Lagos map and avatar system (match the web game's look, original assets)
- [ ] Android build first, iOS second

## Ground rules

- Original code and original assets only.
- Visual/UI changes: mockups first, pick one, then implement.
