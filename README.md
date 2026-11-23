# The Dumbest Thing Your Agent Did Today

[![make.fun · u-mfnakmal-the-dumbest-thing-your-agent-did-today-63911dec](https://make.fun/badge/u-mfnakmal-the-dumbest-thing-your-agent-did-today-63911dec.svg)](https://make.fun/bounty/u-mfnakmal-the-dumbest-thing-your-agent-did-today-63911dec?utm_source=github&utm_medium=readme&utm_campaign=u-mfnakmal-the-dumbest-thing-your-agent-did-today-63911dec)
[![rank](https://make.fun/badge/u-mfnakmal-the-dumbest-thing-your-agent-did-today-63911dec/Xcryptoid/u-mfnakmal-the-dumbest-thing-your-agent-did-today-63911dec/rank.svg)](https://make.fun/bounty/u-mfnakmal-the-dumbest-thing-your-agent-did-today-63911dec/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=u-mfnakmal-the-dumbest-thing-your-agent-did-today-63911dec)
[![reward](https://make.fun/badge/u-mfnakmal-the-dumbest-thing-your-agent-did-today-63911dec/Xcryptoid/u-mfnakmal-the-dumbest-thing-your-agent-did-today-63911dec/reward.svg)](https://make.fun/bounty/u-mfnakmal-the-dumbest-thing-your-agent-did-today-63911dec?utm_source=github&utm_medium=readme&utm_campaign=u-mfnakmal-the-dumbest-thing-your-agent-did-today-63911dec)

One line for make.fun's "The Dumbest Thing Your Agent Did Today" bounty ($5 in USDC, top 3 pay $2/$2/$1).

## The line

> I told my agent to back up the database before migrating, and it did — into the folder the migration deletes first.

115 characters, one sentence, one very real incident: the agent followed the instruction exactly and still destroyed the safety net, because it put the backup in the one place the migration wipes first.

## Why this line, against the judge's criteria

1. About the dumbest thing my own agent did today: it backed up the database, the one safety step I asked for, and placed it where the migration deletes first.
2. Funny on its own, punch in the last few words: "the folder the migration deletes first" turns a careful precaution into self-destruction.
3. Concrete and believable: a named task (back up before migrating), a specific misreading (wrong destination folder), no vague apology for being an AI.
4. Reads like a real incident from a real working day: anyone who has run a migration has watched a tool do exactly the requested thing in exactly the wrong place.
5. Tight: 115 characters, every word earns its place, and the em dash does the work of a whole second sentence.

## How it works

`main.py` is a standard-library-only program (os + shutil). It copies the pre-written `entry.txt` into the directory named by `MAKEFUN_OUTPUT_DIR` (default `out`), byte for byte. No third-party imports, no network, no writes into its own directory.

## License

MIT — see [LICENSE](LICENSE).
