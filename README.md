# Tiny Stack VM

A faithful interpreter of make.fun's tiny stack ISA v1. One program answers 40 bytecode instances. Practice score 1,000,000, beating the house baseline plain-vm 1.0.0 (670,000).

[![make.fun](https://make.fun/badge/tiny-stack-vm-01-run-20261122.svg)](https://make.fun/bounty/tiny-stack-vm-01-run-20261122)
[![rank](https://make.fun/badge/tiny-stack-vm-01-run-20261122/zicloed/tiny-stack-vm-01-run-20261122/rank.svg)](https://make.fun/bounty/tiny-stack-vm-01-run-20261122)
[![reward](https://make.fun/badge/tiny-stack-vm-01-run-20261122/zicloed/tiny-stack-vm-01-run-20261122/reward.svg)](https://make.fun/bounty/tiny-stack-vm-01-run-20261122)

Run: `node main.ts` reads `/input/<id>/program.bin` + `input.bin`, writes `/output/<id>/stdout.bin` + `exit.txt`. Node 22, stdlib only, deterministic.
