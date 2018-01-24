## Summary {#summary}

| Algorithm | Version | Guarantee | Typical | Backup? | Correct? | Extra space |
| --- | --- | --- | --- | --- | --- | --- |
| Brute force | - | MN | 1.1 N | yes | yes | 1 |
| KMP | Full DFA | 2N | 1.1 N | no | yes | MR |
| Mismatch transitiononly | 3N | 1.1 N | no | yes | M |
| Full algorithm | 3N | N/M | yes | yes | R |
| Boyer-Moore | Mismatch char heuristic | MN | N/M | yes | yes | R |
| Rabin-Karp | Monte Carlo | 7N | 7N | no | yes* | 1 |
| Las vegas | 7N* | 7N | yes | yes | 1 |