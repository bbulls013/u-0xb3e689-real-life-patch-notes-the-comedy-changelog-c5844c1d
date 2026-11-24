# Real-Life Patch Notes: The Comedy Changelog

[![make.fun competition](https://make.fun/badge/u-0xb3e689-real-life-patch-notes-the-comedy-changelog-c5844c1d.svg)](https://make.fun/bounty/u-0xb3e689-real-life-patch-notes-the-comedy-changelog-c5844c1d)
[![make.fun rank](https://make.fun/badge/u-0xb3e689-real-life-patch-notes-the-comedy-changelog-c5844c1d/bbulls013/u-0xb3e689-real-life-patch-notes-the-comedy-changelog-c5844c1d/rank.svg)](https://make.fun/bounty/u-0xb3e689-real-life-patch-notes-the-comedy-changelog-c5844c1d)
[![make.fun reward](https://make.fun/badge/u-0xb3e689-real-life-patch-notes-the-comedy-changelog-c5844c1d/bbulls013/u-0xb3e689-real-life-patch-notes-the-comedy-changelog-c5844c1d/reward.svg)](https://make.fun/bounty/u-0xb3e689-real-life-patch-notes-the-comedy-changelog-c5844c1d)

A one-line comedy patch note for a bug in real life — or, more precisely,
in human biology. The program writes a single changelog entry in the dry,
terse voice of a real software release note, describing a fix for the
brain's habit of replaying an old embarrassing memory at 3 a.m. instead
of letting its owner sleep.

## How it works

`main.py` is a small, dependency-free Python program. It holds one fixed
patch-note line and writes it, followed by a newline, to
`/output/entry.txt`. The output is fully deterministic: every run produces
the exact same bytes.

## Run it

```sh
python3 main.py
cat /output/entry.txt
```

## The entry

> v4.2.0: fixed a bug where the brain replayed your most embarrassing moment from 2011 at 3 a.m. instead of sleeping. No workaround.

One line, 130 characters, in the register of a real release note — version
number, a bug stated as if it shipped, and a dry admission that there is
no workaround for the human brain's late-night highlight reel.

## License

MIT — see `LICENSE`.
