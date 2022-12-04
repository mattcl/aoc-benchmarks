# Day 1 benchmarks

[link to problem](http://adventofcode.com/2022/day/1)

The following benchmarks are auto-generated via [hyperfine](https://github.com/sharkdp/hyperfine) by a ci system running on shared hardware. Results may be inaccurate, particularly for execution times < 5ms, as per the hyperfine warnings.

The "official" inputs were aggregated from repositories participating in the generation of these benchmarks. The "large" inputs (if any) were sourced from various places, including the subreddit.

## Benchmarks with officially generated inputs
| Command | Mean [ms] | Min [ms] | Max [ms] | Relative |
|:---|---:|---:|---:|---:|
| `aspidites-solver/aoc -i input-aspidites -d 1` | 12.5 ± 0.5 | 11.7 | 14.4 | 9.27 ± 3.34 |
| `aspidites-solver/aoc -i input-kcen -d 1` | 11.9 ± 0.4 | 11.3 | 13.7 | 8.79 ± 3.17 |
| `aspidites-solver/aoc -i input-lanjian -d 1` | 12.5 ± 0.9 | 11.6 | 23.4 | 9.28 ± 3.40 |
| `aspidites-solver/aoc -i input-mattcl -d 1` | 12.5 ± 0.6 | 11.7 | 15.6 | 9.24 ± 3.34 |
| `aspidites-solver/aoc -i input-pting -d 1` | 12.6 ± 1.0 | 11.7 | 23.5 | 9.33 ± 3.43 |
| `kcen/2022/01/solve input-aspidites` | 104.7 ± 4.8 | 95.1 | 114.7 | 77.60 ± 28.03 |
| `kcen/2022/01/solve input-kcen` | 106.6 ± 10.5 | 86.6 | 132.8 | 79.04 ± 29.38 |
| `kcen/2022/01/solve input-lanjian` | 106.2 ± 6.1 | 94.6 | 118.3 | 78.75 ± 28.59 |
| `kcen/2022/01/solve input-mattcl` | 109.4 ± 10.7 | 89.8 | 133.7 | 81.11 ± 30.13 |
| `kcen/2022/01/solve input-pting` | 106.9 ± 4.6 | 97.8 | 116.5 | 79.24 ± 28.61 |
| `lanjian/day_01 input-aspidites` | 1.6 ± 0.5 | 0.8 | 8.0 | 1.19 ± 0.56 |
| `lanjian/day_01 input-kcen` | 1.9 ± 0.4 | 1.0 | 6.8 | 1.38 ± 0.59 |
| `lanjian/day_01 input-lanjian` | 1.6 ± 0.4 | 0.9 | 3.7 | 1.18 ± 0.53 |
| `lanjian/day_01 input-mattcl` | 2.1 ± 0.9 | 1.0 | 9.7 | 1.53 ± 0.84 |
| `lanjian/day_01 input-pting` | 2.0 ± 0.8 | 1.0 | 10.1 | 1.47 ± 0.78 |
| `mattcl-solver/aoc run 1 input-aspidites` | 1.5 ± 0.5 | 0.7 | 6.0 | 1.08 ± 0.52 |
| `mattcl-solver/aoc run 1 input-kcen` | 1.3 ± 0.5 | 0.6 | 4.4 | 1.00 |
| `mattcl-solver/aoc run 1 input-lanjian` | 1.5 ± 0.4 | 0.8 | 6.1 | 1.12 ± 0.52 |
| `mattcl-solver/aoc run 1 input-mattcl` | 1.8 ± 0.7 | 0.8 | 7.1 | 1.31 ± 0.70 |
| `mattcl-solver/aoc run 1 input-pting` | 1.6 ± 0.5 | 0.8 | 4.7 | 1.18 ± 0.56 |
| `python pting/day01.py input-aspidites` | 37.0 ± 7.9 | 28.3 | 64.0 | 27.42 ± 11.42 |
| `python pting/day01.py input-kcen` | 38.9 ± 7.4 | 29.3 | 62.8 | 28.84 ± 11.71 |
| `python pting/day01.py input-lanjian` | 35.0 ± 5.8 | 25.5 | 63.3 | 25.98 ± 10.27 |
| `python pting/day01.py input-mattcl` | 33.4 ± 3.3 | 28.2 | 44.3 | 24.79 ± 9.22 |
| `python pting/day01.py input-pting` | 35.0 ± 3.5 | 28.6 | 44.7 | 25.92 ± 9.65 |
