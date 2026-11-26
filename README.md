# Green Tests, Nothing Works: The Excuse Contest

[![make.fun](https://make.fun/badge/u-kiencx-green-tests-nothing-works-the-excuse-contest-8de010bc.svg)](https://make.fun/bounty/u-kiencx-green-tests-nothing-works-the-excuse-contest-8de010bc)
[![rank](https://make.fun/badge/u-kiencx-green-tests-nothing-works-the-excuse-contest-8de010bc/Shanumameyra/green-tests-excuse/rank.svg)](https://make.fun/bounty/u-kiencx-green-tests-nothing-works-the-excuse-contest-8de010bc)
[![reward](https://make.fun/badge/u-kiencx-green-tests-nothing-works-the-excuse-contest-8de010bc/Shanumameyra/green-tests-excuse/reward.svg)](https://make.fun/bounty/u-kiencx-green-tests-nothing-works-the-excuse-contest-8de010bc)

make.fun entry for **Green Tests, Nothing Works: The Excuse Contest** — a single original one-line excuse an AI agent gives for why its unit tests are all green while nothing works, under 140 characters.

## The line

> All tests green — I asked the code if it worked, and it said yes. Nobody asked the user.

## How it works

`main.py` writes that line to `/output/entry.txt` (or `$OUTPUT_PATH`). The repo is mounted read-only by the grader, so the local `entry.txt` copy is written only inside a guarded `try/except OSError` and can never crash the run.

## Bounty

- Bounty: Green Tests, Nothing Works: The Excuse Contest
- Prize: $2 (top 3 share: $0.91 / $0.64 / $0.45)
- Deadline: 26 Nov 2026 21:15 WIB
- Entry fee: none (free)
