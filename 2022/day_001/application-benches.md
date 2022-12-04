# Day 1 benchmarks

[link to problem](http://adventofcode.com/2022/day/1)

The following benchmarks are auto-generated via [hyperfine](https://github.com/sharkdp/hyperfine) by a ci system running on shared hardware. Results may be inaccurate, particularly for execution times < 5ms, as per the hyperfine warnings.

The "official" inputs were aggregated from repositories participating in the generation of these benchmarks. The "large" inputs (if any) were sourced from various places, including the subreddit.

## Benchmarks with officially generated inputs
| Command | Mean [ms] | Min [ms] | Max [ms] | Relative |
|:---|---:|---:|---:|---:|
| `aspidites-solver/aoc -i input-aspidites -d 1` | 13.2 ± 1.1 | 11.6 | 20.4 | 9.34 ± 5.82 |
| `aspidites-solver/aoc -i input-kcen -d 1` | 13.2 ± 1.2 | 11.8 | 24.0 | 9.29 ± 5.80 |
| `aspidites-solver/aoc -i input-lanjian -d 1` | 12.4 ± 0.8 | 11.3 | 16.2 | 8.76 ± 5.44 |
| `aspidites-solver/aoc -i input-mattcl -d 1` | 12.0 ± 0.7 | 11.0 | 15.8 | 8.45 ± 5.24 |
| `aspidites-solver/aoc -i input-pting -d 1` | 13.1 ± 2.1 | 11.4 | 27.7 | 9.24 ± 5.90 |
| `kcen/2022/01/solve input-aspidites` | 118.4 ± 20.0 | 100.5 | 193.0 | 83.54 ± 53.49 |
| `kcen/2022/01/solve input-kcen` | 128.7 ± 33.4 | 91.0 | 225.2 | 90.80 ± 60.83 |
| `kcen/2022/01/solve input-lanjian` | 112.3 ± 21.4 | 86.4 | 165.8 | 79.24 ± 51.23 |
| `kcen/2022/01/solve input-mattcl` | 99.4 ± 11.7 | 85.8 | 128.3 | 70.15 ± 44.11 |
| `kcen/2022/01/solve input-pting` | 112.2 ± 11.4 | 90.1 | 139.5 | 79.16 ± 49.55 |
| `lanjian/day_01 input-aspidites` | 1.6 ± 0.9 | 0.6 | 8.9 | 1.15 ± 0.94 |
| `lanjian/day_01 input-kcen` | 2.1 ± 0.9 | 0.9 | 6.7 | 1.51 ± 1.12 |
| `lanjian/day_01 input-lanjian` | 1.5 ± 0.7 | 0.7 | 5.7 | 1.09 ± 0.83 |
| `lanjian/day_01 input-mattcl` | 2.1 ± 1.0 | 0.9 | 9.9 | 1.49 ± 1.17 |
| `lanjian/day_01 input-pting` | 1.4 ± 0.9 | 0.7 | 10.7 | 1.00 |
| `mattcl-solver/aoc run 1 input-aspidites` | 1.5 ± 0.7 | 0.6 | 8.2 | 1.05 ± 0.82 |
| `mattcl-solver/aoc run 1 input-kcen` | 3.1 ± 3.9 | 0.9 | 51.1 | 2.17 ± 3.07 |
| `mattcl-solver/aoc run 1 input-lanjian` | 1.9 ± 0.8 | 0.7 | 6.6 | 1.32 ± 1.00 |
| `mattcl-solver/aoc run 1 input-mattcl` | 1.6 ± 0.6 | 0.7 | 5.6 | 1.10 ± 0.81 |
| `mattcl-solver/aoc run 1 input-pting` | 1.6 ± 0.6 | 0.6 | 5.8 | 1.11 ± 0.81 |
| `python pting/day01.py input-aspidites` | 33.4 ± 5.0 | 27.0 | 49.4 | 23.60 ± 15.00 |
| `python pting/day01.py input-kcen` | 35.2 ± 6.1 | 25.5 | 61.4 | 24.87 ± 15.96 |
| `python pting/day01.py input-lanjian` | 67.5 ± 37.9 | 30.3 | 245.8 | 47.60 ± 39.75 |
| `python pting/day01.py input-mattcl` | 32.1 ± 6.2 | 25.2 | 55.9 | 22.66 ± 14.66 |
| `python pting/day01.py input-pting` | 37.9 ± 8.7 | 27.3 | 72.7 | 26.74 ± 17.61 |
