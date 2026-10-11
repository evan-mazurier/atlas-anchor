# atlas-anchor

Daily fingerprints of an Atlas ledger. Each line of `anchors.jsonl` is one day: the date, the number of ledger lines, the hash of that day's last line, and when it was anchored.

The ledger itself never leaves the machine. If it is ever edited and re-chained, its hashes stop matching the lines here.

The branch is protected (no force pushes, no deletions, linear history), so lines can only be added.
