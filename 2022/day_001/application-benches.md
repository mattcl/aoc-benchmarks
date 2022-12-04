# Day 1 benchmarks

[link to problem](http://adventofcode.com/2022/day/1)

The following benchmarks are auto-generated via [hyperfine](https://github.com/sharkdp/hyperfine) by a ci system running on shared hardware. Results may be inaccurate, particularly for execution times < 5ms, as per the hyperfine warnings.

The "official" inputs were aggregated from repositories participating in the generation of these benchmarks. The "large" inputs (if any) were sourced from various places, including the subreddit.

## Benchmarks with officially generated inputs
| Command | Mean [ms] | Min [ms] | Max [ms] | Relative |
|:---|---:|---:|---:|---:|
| `aspidites-solver/aoc -i input-aspidites -d 1` | 8.3 ± 1.4 | 6.4 | 23.4 | 6.16 ± 1.94 |
| `aspidites-solver/aoc -i input-kcen -d 1` | 9.6 ± 3.5 | 6.3 | 38.3 | 7.09 ± 3.20 |
| `aspidites-solver/aoc -i input-lanjian -d 1` | 8.0 ± 2.0 | 6.0 | 24.9 | 5.92 ± 2.17 |
| `aspidites-solver/aoc -i input-mattcl -d 1` | 8.3 ± 1.2 | 6.4 | 12.9 | 6.15 ± 1.87 |
| `aspidites-solver/aoc -i input-pting -d 1` | 8.1 ± 1.3 | 6.4 | 19.9 | 6.02 ± 1.89 |
| `kcen/2022/01/solve input-aspidites` | 226.1 ± 19.1 | 190.5 | 259.9 | 167.09 ± 47.21 |
| `kcen/2022/01/solve input-kcen` | 257.6 ± 33.4 | 226.9 | 325.9 | 190.35 ± 56.94 |
| `kcen/2022/01/solve input-lanjian` | 223.9 ± 32.7 | 191.0 | 318.2 | 165.45 ± 50.72 |
| `kcen/2022/01/solve input-mattcl` | 201.0 ± 10.4 | 185.1 | 221.3 | 148.50 ± 40.77 |
| `kcen/2022/01/solve input-pting` | 221.0 ± 14.2 | 202.6 | 246.2 | 163.31 ± 45.25 |
| `lanjian/day_01 input-aspidites` | 1.7 ± 0.5 | 0.9 | 7.9 | 1.29 ± 0.51 |
| `lanjian/day_01 input-kcen` | 1.5 ± 0.4 | 0.8 | 3.8 | 1.14 ± 0.43 |
| `lanjian/day_01 input-lanjian` | 1.5 ± 1.2 | 0.8 | 36.4 | 1.15 ± 0.92 |
| `lanjian/day_01 input-mattcl` | 2.2 ± 0.9 | 1.1 | 9.3 | 1.60 ± 0.80 |
| `lanjian/day_01 input-pting` | 1.6 ± 0.7 | 0.8 | 10.7 | 1.17 ± 0.60 |
| `mattcl-solver/aoc run 1 input-aspidites` | 1.6 ± 0.4 | 0.9 | 3.5 | 1.19 ± 0.43 |
| `mattcl-solver/aoc run 1 input-kcen` | 1.5 ± 0.4 | 0.8 | 4.9 | 1.09 ± 0.42 |
| `mattcl-solver/aoc run 1 input-lanjian` | 1.4 ± 0.4 | 0.7 | 3.7 | 1.00 |
| `mattcl-solver/aoc run 1 input-mattcl` | 1.7 ± 0.8 | 0.7 | 10.0 | 1.26 ± 0.66 |
| `mattcl-solver/aoc run 1 input-pting` | 1.5 ± 0.4 | 0.6 | 5.2 | 1.10 ± 0.43 |
| `python pting/day01.py input-aspidites` | 36.0 ± 4.6 | 30.3 | 51.3 | 26.62 ± 7.93 |
| `python pting/day01.py input-kcen` | 31.9 ± 2.9 | 27.8 | 45.6 | 23.59 ± 6.72 |
| `python pting/day01.py input-lanjian` | 34.7 ± 5.7 | 27.7 | 56.1 | 25.63 ± 8.10 |
| `python pting/day01.py input-mattcl` | 35.2 ± 4.1 | 29.3 | 46.0 | 26.04 ± 7.64 |
| `python pting/day01.py input-pting` | 36.9 ± 5.2 | 29.2 | 52.9 | 27.26 ± 8.28 |
