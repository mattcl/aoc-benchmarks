# Day 2 benchmarks

[link to problem](http://adventofcode.com/2022/day/2)

The following benchmarks are auto-generated via [hyperfine](https://github.com/sharkdp/hyperfine) by a ci system running on shared hardware. Results may be inaccurate, particularly for execution times < 5ms, as per the hyperfine warnings.

The "official" inputs were aggregated from repositories participating in the generation of these benchmarks. The "large" inputs (if any) were sourced from various places, including the subreddit.

## Benchmarks with officially generated inputs
| Command | Mean [ms] | Min [ms] | Max [ms] | Relative |
|:---|---:|---:|---:|---:|
| `aspidites-solver/aoc -i input-aspidites -d 2` | 58.5 ± 5.6 | 52.1 | 71.9 | 35.13 ± 8.62 |
| `aspidites-solver/aoc -i input-kcen -d 2` | 56.4 ± 4.1 | 51.7 | 69.9 | 33.83 ± 8.02 |
| `aspidites-solver/aoc -i input-lanjian -d 2` | 59.2 ± 5.7 | 52.9 | 79.8 | 35.51 ± 8.72 |
| `aspidites-solver/aoc -i input-mattcl -d 2` | 59.9 ± 6.1 | 53.5 | 80.0 | 35.96 ± 8.91 |
| `aspidites-solver/aoc -i input-pting -d 2` | 58.8 ± 5.7 | 52.0 | 76.0 | 35.27 ± 8.65 |
| `kcen/2022/02/solve.sh input-aspidites` | 206.2 ± 5.4 | 195.8 | 214.1 | 123.80 ± 28.12 |
| `kcen/2022/02/solve.sh input-kcen` | 215.0 ± 16.3 | 197.6 | 246.2 | 129.06 ± 30.72 |
| `kcen/2022/02/solve.sh input-lanjian` | 225.8 ± 34.5 | 184.0 | 315.0 | 135.51 ± 36.94 |
| `kcen/2022/02/solve.sh input-mattcl` | 203.9 ± 7.5 | 192.7 | 224.6 | 122.41 ± 27.99 |
| `kcen/2022/02/solve.sh input-pting` | 205.9 ± 8.4 | 190.3 | 219.4 | 123.58 ± 28.34 |
| `lanjian/day_02 input-aspidites` | 2.1 ± 0.5 | 1.1 | 5.9 | 1.24 ± 0.42 |
| `lanjian/day_02 input-kcen` | 3.3 ± 3.0 | 1.3 | 44.1 | 1.98 ± 1.86 |
| `lanjian/day_02 input-lanjian` | 2.2 ± 0.6 | 1.4 | 8.4 | 1.35 ± 0.49 |
| `lanjian/day_02 input-mattcl` | 1.9 ± 0.5 | 1.1 | 12.0 | 1.15 ± 0.42 |
| `lanjian/day_02 input-pting` | 2.2 ± 0.7 | 1.3 | 7.2 | 1.29 ± 0.49 |
| `mattcl-solver/aoc run 2 input-aspidites` | 1.7 ± 0.7 | 0.9 | 9.4 | 1.04 ± 0.47 |
| `mattcl-solver/aoc run 2 input-kcen` | 2.4 ± 2.1 | 0.9 | 20.4 | 1.45 ± 1.28 |
| `mattcl-solver/aoc run 2 input-lanjian` | 1.8 ± 0.8 | 0.8 | 13.9 | 1.07 ± 0.52 |
| `mattcl-solver/aoc run 2 input-mattcl` | 1.7 ± 0.4 | 1.0 | 7.3 | 1.00 |
| `mattcl-solver/aoc run 2 input-pting` | 1.8 ± 0.4 | 1.0 | 4.7 | 1.05 ± 0.34 |
| `python pting/day02.py input-aspidites` | 35.0 ± 2.7 | 30.1 | 44.5 | 21.02 ± 5.00 |
| `python pting/day02.py input-kcen` | 35.0 ± 3.9 | 29.7 | 45.8 | 21.00 ± 5.28 |
| `python pting/day02.py input-lanjian` | 35.8 ± 3.4 | 30.6 | 47.0 | 21.50 ± 5.25 |
| `python pting/day02.py input-mattcl` | 35.7 ± 6.7 | 29.3 | 86.8 | 21.41 ± 6.27 |
| `python pting/day02.py input-pting` | 35.1 ± 4.3 | 29.5 | 52.0 | 21.10 ± 5.42 |
