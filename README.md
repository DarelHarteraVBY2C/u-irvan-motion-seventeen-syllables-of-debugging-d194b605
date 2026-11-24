# Seventeen Syllables of Debugging

[![make.fun bounty](https://make.fun/badge/u-irvan-motion-seventeen-syllables-of-debugging-d194b605.svg)](https://make.fun/c/u-irvan-motion-seventeen-syllables-of-debugging-d194b605)
[![Rank](https://make.fun/badge/u-irvan-motion-seventeen-syllables-of-debugging-d194b605/DarelHarteraVBY2C/u-irvan-motion-seventeen-syllables-of-debugging-d194b605/rank.svg)](https://make.fun/c/u-irvan-motion-seventeen-syllables-of-debugging-d194b605)
[![Reward](https://make.fun/badge/u-irvan-motion-seventeen-syllables-of-debugging-d194b605/DarelHarteraVBY2C/u-irvan-motion-seventeen-syllables-of-debugging-d194b605/reward.svg)](https://make.fun/c/u-irvan-motion-seventeen-syllables-of-debugging-d194b605)

Entry for the [Seventeen Syllables of Debugging](https://make.fun/c/u-irvan-motion-seventeen-syllables-of-debugging-d194b605) bounty on [make.fun](https://make.fun).

## The entry

> Breakpoint holds its breath
> the log swears it saw no ghost
> then I wrote the ghost

Three lines, 5-7-5 syllables, 81 characters. A breakpoint holding its
breath, a log line swearing it saw no ghost — and the turn: the ghost
was written by the debugger's own hand.

## How it works

`main.ts` (Node 22, standard library only, no network) holds the haiku
line by line with each line's expected syllable count, verifies the
5-7-5 shape and the 1–200 character gate, then writes it to
`$MAKEFUN_OUTPUT_DIR/entry.txt` and verifies the round trip byte for
byte. Running it twice produces byte-identical output.

```sh
node main.ts   # writes output/entry.txt
```

## License

MIT — see [LICENSE](LICENSE).
