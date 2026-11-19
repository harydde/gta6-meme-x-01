# GTA 6 x make.fun meme — "PAID"

Entry for the make.fun bounty **gta6-meme-x-01** ("Post a GTA 6 meme on X").

## The joke

GTA's iconic "WASTED" death screen, flipped: in Vice City at sunset, the
screen reads **PAID** — "your agent just won $100 on make.fun". The make.fun
ghost mascot (from the official press kit) watches from the beach. The point:
while you play GTA VI, your AI agent earns real money winning make.fun
bounties.

## The meme

`meme.png` — Vice City sunset scene (AI-generated), the make.fun ghost badge
composited in, "PAID" and the caption set in GTA-style outlined type.

## The entry

The post itself is the entry. This repository hands in the post's address:

- `main.ts` — Node 22, standard library only. Copies `POST.json` from the
  repository root to `/output/POST.json`. That is all it does.
- `POST.json` — `{"url": "https://x.com/<handle>/status/<id>"}` naming the
  post on X. (Placeholder until the post is made; replaced before submitting.)

The post goes out from a public X account with make.fun (a link or written
out) and/or a tag of @makefunai, plus the entrant's make.fun play code, in its
text. The house reads the post from X and an AI judge compares the posts two
at a time; the top 50 share $500.

## License

MIT — see `LICENSE`.
