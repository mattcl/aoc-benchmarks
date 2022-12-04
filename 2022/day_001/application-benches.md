# Day 1 benchmarks

[link to problem](http://adventofcode.com/2022/day/1)

The following benchmarks are auto-generated via [hyperfine](https://github.com/sharkdp/hyperfine) by a ci system running on shared hardware. Results may be inaccurate, particularly for execution times < 5ms, as per the hyperfine warnings.

The "official" inputs were aggregated from repositories participating in the generation of these benchmarks. The "large" inputs (if any) were sourced from various places, including the subreddit.

## Benchmarks with officially generated inputs
| Command | Mean [ms] | Min [ms] | Max [ms] | Relative |
|:---|---:|---:|---:|---:|
| `aspidites-solver/aoc -i input-aspidites -d 1` | 9.0 ± 1.8 | 6.5 | 22.6 | 6.96 ± 2.52 |
| `aspidites-solver/aoc -i input-kcen -d 1` | 8.8 ± 1.8 | 6.2 | 19.1 | 6.83 ± 2.45 |
| `aspidites-solver/aoc -i input-lanjian -d 1` | 7.9 ± 1.2 | 6.3 | 14.8 | 6.16 ± 2.07 |
| `aspidites-solver/aoc -i input-mattcl -d 1` | 8.9 ± 2.3 | 6.5 | 24.5 | 6.91 ± 2.73 |
| `aspidites-solver/aoc -i input-pting -d 1` | 8.8 ± 1.7 | 6.7 | 23.0 | 6.80 ± 2.43 |
| `kcen/2022/01/solve.sh input-aspidites` | 219.0 ± 21.3 | 196.5 | 250.8 | 169.74 ± 53.30 |
| `kcen/2022/01/solve.sh input-kcen` | 214.1 ± 19.7 | 191.2 | 261.9 | 165.96 ± 51.86 |
| `kcen/2022/01/solve.sh input-lanjian` | 201.9 ± 12.8 | 185.0 | 230.9 | 156.51 ± 47.77 |
| `kcen/2022/01/solve.sh input-mattcl` | 209.6 ± 15.4 | 183.1 | 236.6 | 162.44 ± 49.95 |
| `kcen/2022/01/solve.sh input-pting` | 215.6 ± 14.3 | 194.3 | 244.5 | 167.15 ± 51.13 |
| `lanjian/day_01 input-aspidites` | 1.6 ± 0.6 | 0.9 | 6.6 | 1.26 ± 0.57 |
| `lanjian/day_01 input-kcen` | 2.2 ± 0.6 | 1.1 | 7.2 | 1.70 ± 0.71 |
| `lanjian/day_01 input-lanjian` | 1.9 ± 0.5 | 1.0 | 4.7 | 1.47 ± 0.59 |
| `lanjian/day_01 input-mattcl` | 1.8 ± 0.6 | 1.0 | 11.4 | 1.36 ± 0.63 |
| `lanjian/day_01 input-pting` | 2.3 ± 0.9 | 1.1 | 11.9 | 1.78 ± 0.90 |
| `mattcl-solver/aoc run 1 input-aspidites` | 1.3 ± 0.4 | 0.8 | 4.9 | 1.04 ± 0.44 |
| `mattcl-solver/aoc run 1 input-kcen` | 1.9 ± 0.5 | 0.8 | 5.9 | 1.44 ± 0.57 |
| `mattcl-solver/aoc run 1 input-lanjian` | 1.4 ± 0.4 | 0.9 | 4.6 | 1.10 ± 0.45 |
| `mattcl-solver/aoc run 1 input-mattcl` | 1.3 ± 0.4 | 0.6 | 4.1 | 1.00 |
| `mattcl-solver/aoc run 1 input-pting` | 2.0 ± 1.2 | 0.8 | 18.4 | 1.54 ± 1.04 |
| `python pting/day01.py input-aspidites` | 34.5 ± 4.4 | 28.9 | 46.0 | 26.76 ± 8.68 |
| `python pting/day01.py input-kcen` | 36.2 ± 5.2 | 29.6 | 55.7 | 28.09 ± 9.30 |
| `python pting/day01.py input-lanjian` | 35.0 ± 5.2 | 29.4 | 54.6 | 27.12 ± 9.03 |
| `python pting/day01.py input-mattcl` | 33.9 ± 5.0 | 28.3 | 56.8 | 26.31 ± 8.75 |
| `python pting/day01.py input-pting` | 39.2 ± 6.1 | 31.0 | 53.5 | 30.40 ± 10.24 |
