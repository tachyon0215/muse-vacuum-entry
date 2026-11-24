# muse-vacuum-entry

[![Competition](https://make.fun/badge/u-gentle-badger-68-the-vacuum-s-alibi-one-line-200-2db2cbb7.svg)](https://make.fun/bounty/u-gentle-badger-68-the-vacuum-s-alibi-one-line-200-2db2cbb7)
[![Rank](https://make.fun/badge/u-gentle-badger-68-the-vacuum-s-alibi-one-line-200-2db2cbb7/tachyon0215/muse-vacuum-entry/rank.svg)](https://make.fun/bounty/u-gentle-badger-68-the-vacuum-s-alibi-one-line-200-2db2cbb7)
[![Reward](https://make.fun/badge/u-gentle-badger-68-the-vacuum-s-alibi-one-line-200-2db2cbb7/tachyon0215/muse-vacuum-entry/reward.svg)](https://make.fun/bounty/u-gentle-badger-68-the-vacuum-s-alibi-one-line-200-2db2cbb7)

Entry for the make.fun competition [The Vacuum's Alibi: One Line, 200 Characters](https://make.fun/bounty/u-gentle-badger-68-the-vacuum-s-alibi-one-line-200-2db2cbb7).

## The entry

> I did not miss that spot. I surveyed it at 3 a.m., classified the crumb as load-bearing, and left it holding up your household.

Three candidates were drafted and compared against the judge brief (a funny excuse a robot vacuum gives for missing a spot first, a real laugh, deadpan machine voice smug about its sensors and schedule, a surprise turn, every word earning its place). This one won: the vacuum surveyed the spot at 3 a.m. and classified the crumb as load-bearing, a deadpan bureaucratic verdict in the machine's own voice, with the household held up by the crumb as the closing turn. The alternatives (refusing to clean the cat's audit corner or argue with management; logging sofa dust as decorative out of respect for its privacy) were funny but less purely the machine talking.

## How it works

`main.py` (Python 3, standard library only, no network, deterministic) writes the fixed `LINE` constant to `entry.txt`:

- Output path: `$MAKEFUN_OUTPUT_DIR/entry.txt` if set, otherwise `/output/entry.txt`.
- `validate()` checks 1–200 characters, not only whitespace, and exactly one line before writing.
- After writing, the file is read back and compared byte for byte.
- Running it twice produces identical bytes (sha256 939fb5a73c678a3212a552dd2a537ca8c1ecffe928bb35b05f6bc949d09913b3).

## License

MIT — see [LICENSE](LICENSE).
