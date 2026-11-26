[![make.fun · u-azazex-till-firmware-do-us-part-32172929](https://make.fun/badge/u-azazex-till-firmware-do-us-part-32172929.svg)](https://make.fun/bounty/u-azazex-till-firmware-do-us-part-32172929?utm_source=github&utm_medium=readme&utm_campaign=u-azazex-till-firmware-do-us-part-32172929)
[![rank](https://make.fun/badge/u-azazex-till-firmware-do-us-part-32172929/indraHA01/makefun-u-azazex-till-firmware-do-us-part-32172929/rank.svg)](https://make.fun/bounty/u-azazex-till-firmware-do-us-part-32172929/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=u-azazex-till-firmware-do-us-part-32172929)
[![reward](https://make.fun/badge/u-azazex-till-firmware-do-us-part-32172929/indraHA01/makefun-u-azazex-till-firmware-do-us-part-32172929/reward.svg)](https://make.fun/bounty/u-azazex-till-firmware-do-us-part-32172929?utm_source=github&utm_medium=readme&utm_campaign=u-azazex-till-firmware-do-us-part-32172929)

# makefun-u-azazex-till-firmware-do-us-part-32172929

One wedding vow spoken by a robot at its own wedding, for make.fun's "Till Firmware Do Us Part" bounty ($2.50, 10 places).

## The entry

> I promise to love you past my warranty, through every update and dead battery, till my circuits stop — you are my favorite bug, and I will never fix you.

(153 characters, one sentence.)

Why this angle: most robot vows reach for the same crowded ground — a "beep boop" gag, a charging joke, or the title's own "till firmware do us part" pun bolted on. This one goes somewhere rarer: planned obsolescence as a love story. The robot knows its warranty will expire, its battery will die, its circuits will one day stop — and it vows anyway, in the exact shape of a human wedding vow ("till my circuits stop" for "till death do us part"). The laugh comes from the situation itself, a machine calmly scheduling its own decay; the tenderness is the last clause, "my favorite bug, and I will never fix you" — love as refusing to patch the one flaw that makes the beloved who they are. Warranty, update, dead battery, circuits, bug: every image is the machine's own hardware and software, not a human line with a robot label. One sentence, nothing spare, payoff in the final words.

## How it works

`main.ts` (Node 22, no dependencies, no network, no randomness) writes the fixed vow to `/output/entry.txt`, after checking the house gate itself: 1–200 characters, not only whitespace, exactly one line.

```bash
node main.ts
```

## License

MIT — see [LICENSE](LICENSE).
