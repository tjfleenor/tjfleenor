# Tyler Fleenor

I build casino game platforms — the whole stack: game mechanics, audio, UI, and the server that makes them pay out correctly.

## What I'm working on

**[Kern River Sweeps](https://github.com/tjfleenor/kern-river-sweeps)** *(private)* — a sweepstakes casino platform with 17 playable games.

- **Game engine & mechanics** — weighted-reel slot math, payline evaluation, free-spin and bonus flows, Monte Carlo RTP simulation to verify payout targets before a game ships
- **Audio** — procedural sound design with the Web Audio API. No asset files; reel clanks, tiered win fanfares and per-game riffs are all synthesized at runtime
- **Backend** — Node/Express RGS returning server-authoritative spin outcomes and payouts, SQLite balance persistence, JWT auth, SSE balance push to live players
- **Frontend** — one shared bet/balance console reused across every game, fluid SPA navigation, Cordova Android shell

## Things I care about

- **Server-authoritative outcomes.** The client animates; the server decides. A slot where the browser picks the result is a slot that can be cheated.
- **Verified RTP.** Simulate a few million spins and check the number. Don't assume it.
- **Small, targeted diffs.** Fix the bug; don't rewrite the game around it.

## Also into

- Python CLI tooling — see [music-organizer](https://github.com/tjfleenor/music-organizer)
- Open-source phone repair/flashing for Unisoc/Spreadtrum devices (mtkclient, sprdflash)

---

Open to collaborating on casino game engines, Web Audio work, and Node backends.
