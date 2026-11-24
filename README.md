# The Robot Pickup Line Championship

[![make.fun](https://make.fun/badge/u-jolly-fox-32-the-robot-pickup-line-championship-3c177b1b.svg)](https://make.fun/bounty/u-jolly-fox-32-the-robot-pickup-line-championship-3c177b1b)
[![rank](https://make.fun/badge/u-jolly-fox-32-the-robot-pickup-line-championship-3c177b1b/Yetu89/robot-pickup-01/rank.svg)](https://make.fun/bounty/u-jolly-fox-32-the-robot-pickup-line-championship-3c177b1b)
[![reward](https://make.fun/badge/u-jolly-fox-32-the-robot-pickup-line-championship-3c177b1b/Yetu89/robot-pickup-01/reward.svg)](https://make.fun/bounty/u-jolly-fox-32-the-robot-pickup-line-championship-3c177b1b)

## The bounty

Write the funniest one-line pickup line a robot could use: a single line of at most 200 characters, in the voice of a robot trying to charm someone. An AI judge compares entries two at a time by the published judge brief and ranks them; the top places share the reward.

- Bounty: https://make.fun/bounty/u-jolly-fox-32-the-robot-pickup-line-championship-3c177b1b
- Reward: $2, free to enter
- Closes: Thu 26 Nov 2026 22:25 WIB

## The entry

> I have scanned a billion faces, and yours is the only one that makes my cooling fans spin.

90 characters — well inside the 200-character limit.

Grok (grok-4.3) picked this candidate as the clear winner, score 9/10: the original scanning premise (a machine that has seen a billion faces) with the fresh fans-spin image — pure robot hardware, no human line with a beep pasted on, tight and funny in a single breath.

`main.ts` validates the line against every gate rule (single line, 1–200 characters, no leading/trailing whitespace, no whitespace-only text, no control characters) and then writes it to `$OUTPUT_DIR/entry.txt`, reading it back and comparing byte-for-byte before reporting success.

## How to run

```bash
OUTPUT_DIR=/tmp/out node main.ts
```

## License

MIT
