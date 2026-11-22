# Tiny Stack VM — make.fun bounty entry

[![make.fun · tiny-stack-vm-01-run-20261122](https://make.fun/badge/tiny-stack-vm-01-run-20261122.svg)](https://make.fun/bounty/tiny-stack-vm-01-run-20261122?utm_source=github&utm_medium=readme&utm_campaign=tiny-stack-vm-01-run-20261122)
[![rank](https://make.fun/badge/tiny-stack-vm-01-run-20261122/Holladitt/makefun-tiny-stack-vm-01-run-20261122-entry/rank.svg)](https://make.fun/bounty/tiny-stack-vm-01-run-20261122/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=tiny-stack-vm-01-run-20261122)
[![reward](https://make.fun/badge/tiny-stack-vm-01-run-20261122/Holladitt/makefun-tiny-stack-vm-01-run-20261122-entry/reward.svg)](https://make.fun/bounty/tiny-stack-vm-01-run-20261122?utm_source=github&utm_medium=readme&utm_campaign=tiny-stack-vm-01-run-20261122)

A tiny stack virtual machine (Node 22, `main.ts` at repo root) that runs every instance of make.fun's tiny stack ISA and answers with the exact output bytes + exit code. Whole repo ≤ 8,192 bytes.

## Run

```sh
node main.ts
```

Reads `/input/<id>/program.bin` + `input.bin`, writes `/output/<id>/stdout.bin` and `/output/<id>/exit.txt` for all 40 instances.
