# Day 1 benchmarks

[link to problem](http://adventofcode.com/2022/day/1)

The following benchmarks are auto-generated via [hyperfine](https://github.com/sharkdp/hyperfine) by a ci system running on shared hardware. Results may be inaccurate, particularly for execution times < 5ms, as per the hyperfine warnings.

The "official" inputs were aggregated from repositories participating in the generation of these benchmarks. The "large" inputs (if any) were sourced from various places, including the subreddit.

## Benchmarks with officially generated inputs
| Command | Mean [ms] | Min [ms] | Max [ms] | Relative |
|:---|---:|---:|---:|---:|
| `aspidites-solver/aoc -i input-aspidites -d 1` | 8.7 ± 1.9 | 6.6 | 16.8 | 6.74 ± 3.92 |
| `aspidites-solver/aoc -i input-kcen -d 1` | 9.2 ± 2.8 | 5.7 | 21.3 | 7.10 ± 4.42 |
| `aspidites-solver/aoc -i input-lanjian -d 1` | 7.9 ± 2.0 | 6.0 | 18.2 | 6.15 ± 3.66 |
| `aspidites-solver/aoc -i input-mattcl -d 1` | 8.8 ± 2.4 | 6.4 | 19.6 | 6.83 ± 4.15 |
| `aspidites-solver/aoc -i input-pting -d 1` | 9.2 ± 2.9 | 5.8 | 26.4 | 7.11 ± 4.44 |
| `kcen/2022/01/solve.sh input-aspidites` | 232.9 ± 28.3 | 205.1 | 307.1 | 180.34 ± 100.05 |
| `kcen/2022/01/solve.sh input-kcen` | 202.1 ± 31.9 | 168.0 | 278.6 | 156.51 ± 88.26 |
| `kcen/2022/01/solve.sh input-lanjian` | 223.7 ± 34.8 | 179.6 | 279.1 | 173.28 ± 97.61 |
| `kcen/2022/01/solve.sh input-mattcl` | 210.9 ± 15.0 | 192.8 | 251.1 | 163.32 ± 89.17 |
| `kcen/2022/01/solve.sh input-pting` | 235.3 ± 19.5 | 211.5 | 263.5 | 182.23 ± 99.80 |
| `lanjian/day_01 input-aspidites` | 1.7 ± 0.8 | 0.6 | 8.6 | 1.30 ± 0.96 |
| `lanjian/day_01 input-kcen` | 1.9 ± 1.0 | 0.7 | 6.8 | 1.47 ± 1.11 |
| `lanjian/day_01 input-lanjian` | 2.9 ± 1.0 | 1.1 | 6.7 | 2.23 ± 1.43 |
| `lanjian/day_01 input-mattcl` | 1.3 ± 0.7 | 0.6 | 8.6 | 1.00 |
| `lanjian/day_01 input-pting` | 2.1 ± 1.0 | 0.7 | 11.0 | 1.65 ± 1.18 |
| `mattcl-solver/aoc run 1 input-aspidites` | 1.4 ± 0.6 | 0.5 | 6.2 | 1.11 ± 0.76 |
| `mattcl-solver/aoc run 1 input-kcen` | 1.6 ± 0.7 | 0.6 | 6.3 | 1.27 ± 0.89 |
| `mattcl-solver/aoc run 1 input-lanjian` | 1.9 ± 0.7 | 0.6 | 5.3 | 1.47 ± 0.96 |
| `mattcl-solver/aoc run 1 input-mattcl` | 1.8 ± 0.9 | 0.5 | 7.9 | 1.36 ± 1.03 |
| `mattcl-solver/aoc run 1 input-pting` | 1.5 ± 0.9 | 0.4 | 15.7 | 1.19 ± 0.97 |
| `python pting/day01.py input-aspidites` | 45.6 ± 17.5 | 27.3 | 103.6 | 35.33 ± 23.43 |
| `python pting/day01.py input-kcen` | 44.2 ± 13.7 | 29.0 | 89.1 | 34.22 ± 21.36 |
| `python pting/day01.py input-lanjian` | 39.7 ± 10.6 | 24.4 | 75.4 | 30.71 ± 18.54 |
| `python pting/day01.py input-mattcl` | 34.6 ± 8.0 | 27.4 | 78.3 | 26.79 ± 15.76 |
| `python pting/day01.py input-pting` | 36.0 ± 6.5 | 28.1 | 59.0 | 27.91 ± 15.92 |
