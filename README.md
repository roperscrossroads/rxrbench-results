# rxrbench-results

What [rxrbench](https://github.com/roperscrossroads/rxrbench) has been seen to do on real boards:
the newest result of each verb of its board exercise, by board type and firmware, with the date
and the tool commit it ran against. Published at
<https://roperscrossroads.github.io/rxrbench-results/> (`index.md`).

The table is written by the hardware CI (a private repository and a runner on a bench host) with
`tools/matrix.py --ledger --public`, which keeps out board names, hosts, addresses and image names
and runs the tool's privacy check before anything is written. Each run that changes the table is
a commit here, so the history of a cell is `git log -p index.md`.

Nothing here is written by hand.
