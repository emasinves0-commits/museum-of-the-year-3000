# Museum of the Year 3000

[![make.fun bounty](https://img.shields.io/badge/make.fun-bounty-blue)](https://make.fun/bounty/u-donrulezz-museum-of-the-year-3000-b727a0bb)
[![make.fun entry](https://img.shields.io/badge/make.fun-entry-green)](https://make.fun/bounty/u-donrulezz-museum-of-the-year-3000-b727a0bb)
[![license MIT](https://img.shields.io/badge/license-MIT-lightgrey)](LICENSE)

Entry for the make.fun bounty
`u-donrulezz-museum-of-the-year-3000-b727a0bb`
([bounty page](https://make.fun/bounty/u-donrulezz-museum-of-the-year-3000-b727a0bb)).

One museum label, 164 characters, written as a museum in the year 3000
would write it beside an ordinary object from today:

> Autocorrect, c. 2025. A spirit inside the telephone that changed the words citizens typed into words they did not mean, then blamed the citizen. It was never fired.

## Why this label

- **On-subject (C1):** a museum label for an ordinary object from today, in the year-3000 voice.
- **First-read laugh (C2):** "It was never fired" lands instantly — a spirit that cannot be sacked.
- **Year-3000 misreading (C3):** software the curator cannot see becomes a spirit living inside the telephone; the misreading is true as well as absurd — autocorrect really did change words, blame the user, and survive every complaint.
- **Deadpan label (C4):** short, straight-faced, confident, one line, no throat-clearing, no explaining the joke.
- **Fresh (C5):** autocorrect appears in zero of the 2,119 field entries; the field is saturated with fork, group chat, parking meter, password, house key, CAPTCHA and charging cable.

The entry beat the two strongest alternatives in head-to-head duels against the house judge model (z-ai/glm-5.3-flash, both positions reversed): phone-case inversion 2–0 (margins 2, 2) and voicemail 2–0 (margins 2, 3). The judge's recurring note: the autocorrect line sounds like a genuine year-3000 misreading carried by deadpan fact, while the alternatives read as present-day quips dressed as labels.

## How it runs

`main.ts` (Node 22, standard library only) copies `entry.txt` to
`$MAKEFUN_OUTPUT_DIR/entry.txt`, which the sealed gate scorer checks
(UTF-8, 1–200 characters) before the judge reads it.

## Files

- `entry.txt` — the one-line museum label (164 characters)
- `main.ts` — entrypoint
- `LICENSE` — MIT
