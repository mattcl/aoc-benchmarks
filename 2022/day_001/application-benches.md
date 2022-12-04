# Day 1 benchmarks

[link to problem](http://adventofcode.com/2022/day/1)

The following benchmarks are auto-generated via [hyperfine](https://github.com/sharkdp/hyperfine) by a ci system running on shared hardware. Results may be inaccurate, particularly for execution times < 5ms, as per the hyperfine warnings.

The "official" inputs were aggregated from repositories participating in the generation of these benchmarks. The "large" inputs (if any) were sourced from various places, including the subreddit.

## Benchmarks with officially generated inputs
| Command | Mean [ms] | Min [ms] | Max [ms] | Relative |
|:---|---:|---:|---:|---:|
| `aspidites-solver/aoc -i input-aspidites -d 1` | 9.7 ± 3.3 | 6.9 | 53.7 | 6.77 ± 3.77 |
| `aspidites-solver/aoc -i input-kcen -d 1` | 7.8 ± 1.3 | 5.7 | 16.6 | 5.44 ± 2.56 |
| `aspidites-solver/aoc -i input-lanjian -d 1` | 9.1 ± 3.1 | 5.8 | 51.0 | 6.34 ± 3.53 |
| `aspidites-solver/aoc -i input-mattcl -d 1` | 8.8 ± 2.4 | 5.6 | 17.0 | 6.12 ± 3.19 |
| `aspidites-solver/aoc -i input-pting -d 1` | 8.5 ± 2.2 | 5.9 | 16.2 | 5.96 ± 3.03 |
| `kcen/2022/01/solve.sh input-aspidites` | 232.4 ± 33.3 | 182.0 | 285.4 | 162.26 ± 75.17 |
| `kcen/2022/01/solve.sh input-kcen` | 236.8 ± 39.5 | 181.2 | 321.7 | 165.30 ± 77.89 |
| `kcen/2022/01/solve.sh input-lanjian` | 229.2 ± 18.0 | 207.7 | 270.7 | 160.03 ± 71.63 |
| `kcen/2022/01/solve.sh input-mattcl` | 283.0 ± 67.4 | 220.0 | 430.8 | 197.61 ± 98.99 |
| `kcen/2022/01/solve.sh input-pting` | 226.4 ± 20.7 | 201.6 | 275.3 | 158.03 ± 71.12 |
| `lanjian/day_01 input-aspidites` | 1.7 ± 0.8 | 0.8 | 8.0 | 1.22 ± 0.75 |
| `lanjian/day_01 input-kcen` | 2.4 ± 1.1 | 0.9 | 11.2 | 1.64 ± 1.06 |
| `lanjian/day_01 input-lanjian` | 2.4 ± 1.0 | 0.8 | 7.7 | 1.71 ± 1.02 |
| `lanjian/day_01 input-mattcl` | 2.1 ± 1.0 | 0.8 | 9.0 | 1.47 ± 0.97 |
| `lanjian/day_01 input-pting` | 1.9 ± 0.8 | 1.0 | 5.4 | 1.34 ± 0.80 |
| `mattcl-solver/aoc run 1 input-aspidites` | 1.9 ± 0.8 | 0.7 | 6.8 | 1.33 ± 0.80 |
| `mattcl-solver/aoc run 1 input-kcen` | 2.2 ± 1.4 | 0.6 | 38.5 | 1.52 ± 1.21 |
| `mattcl-solver/aoc run 1 input-lanjian` | 1.4 ± 0.6 | 0.6 | 5.4 | 1.00 |
| `mattcl-solver/aoc run 1 input-mattcl` | 1.6 ± 0.7 | 0.6 | 4.9 | 1.13 ± 0.70 |
| `mattcl-solver/aoc run 1 input-pting` | 1.8 ± 1.1 | 0.7 | 21.7 | 1.25 ± 0.92 |
| `python pting/day01.py input-aspidites` | 41.5 ± 11.6 | 28.1 | 83.3 | 28.99 ± 15.12 |
| `python pting/day01.py input-kcen` | 34.7 ± 6.6 | 26.8 | 67.9 | 24.25 ± 11.65 |
| `python pting/day01.py input-lanjian` | 38.3 ± 8.4 | 28.1 | 77.8 | 26.72 ± 13.16 |
| `python pting/day01.py input-mattcl` | 36.7 ± 8.3 | 27.4 | 67.2 | 25.64 ± 12.68 |
| `python pting/day01.py input-pting` | 34.3 ± 7.6 | 26.5 | 74.2 | 23.98 ± 11.82 |
