# Day 2 benchmarks

[link to problem](http://adventofcode.com/2022/day/2)

The following benchmarks are auto-generated via [hyperfine](https://github.com/sharkdp/hyperfine) by a ci system running on shared hardware. Results may be inaccurate, particularly for execution times < 5ms, as per the hyperfine warnings.

The "official" inputs were aggregated from repositories participating in the generation of these benchmarks. The "large" inputs (if any) were sourced from various places, including the subreddit.

## Benchmarks with officially generated inputs
| Command | Mean [ms] | Min [ms] | Max [ms] | Relative |
|:---|---:|---:|---:|---:|
| `aspidites-solver/aoc -i input-aspidites -d 2` | 12.6 ± 0.8 | 11.5 | 15.5 | 9.51 ± 3.29 |
| `aspidites-solver/aoc -i input-kcen -d 2` | 12.6 ± 1.0 | 11.7 | 23.8 | 9.50 ± 3.33 |
| `aspidites-solver/aoc -i input-lanjian -d 2` | 12.9 ± 1.1 | 11.5 | 17.9 | 9.77 ± 3.43 |
| `aspidites-solver/aoc -i input-mattcl -d 2` | 12.0 ± 0.4 | 11.5 | 14.7 | 9.08 ± 3.11 |
| `aspidites-solver/aoc -i input-pting -d 2` | 12.4 ± 1.1 | 11.4 | 24.5 | 9.37 ± 3.29 |
| `kcen/2022/02/solve input-aspidites` | 1.7 ± 0.4 | 0.9 | 4.0 | 1.27 ± 0.54 |
| `kcen/2022/02/solve input-kcen` | 2.0 ± 1.2 | 0.8 | 14.7 | 1.48 ± 1.06 |
| `kcen/2022/02/solve input-lanjian` | 1.5 ± 0.6 | 0.6 | 5.5 | 1.13 ± 0.58 |
| `kcen/2022/02/solve input-mattcl` | 1.6 ± 0.7 | 0.7 | 9.3 | 1.24 ± 0.67 |
| `kcen/2022/02/solve input-pting` | 1.5 ± 0.6 | 0.8 | 12.1 | 1.15 ± 0.58 |
| `lanjian/day_02 input-aspidites` | 2.4 ± 0.7 | 1.0 | 8.1 | 1.83 ± 0.82 |
| `lanjian/day_02 input-kcen` | 2.2 ± 0.6 | 1.0 | 6.8 | 1.66 ± 0.74 |
| `lanjian/day_02 input-lanjian` | 1.7 ± 0.7 | 1.0 | 12.6 | 1.30 ± 0.67 |
| `lanjian/day_02 input-mattcl` | 1.7 ± 0.5 | 1.0 | 4.1 | 1.29 ± 0.57 |
| `lanjian/day_02 input-pting` | 1.9 ± 0.4 | 1.0 | 4.6 | 1.42 ± 0.59 |
| `mattcl-solver/aoc run 2 input-aspidites` | 1.7 ± 0.5 | 0.9 | 7.0 | 1.28 ± 0.60 |
| `mattcl-solver/aoc run 2 input-kcen` | 1.3 ± 0.5 | 0.9 | 7.2 | 1.00 |
| `mattcl-solver/aoc run 2 input-lanjian` | 1.6 ± 0.6 | 0.7 | 7.0 | 1.24 ± 0.60 |
| `mattcl-solver/aoc run 2 input-mattcl` | 1.8 ± 0.8 | 0.9 | 9.1 | 1.38 ± 0.79 |
| `mattcl-solver/aoc run 2 input-pting` | 1.6 ± 0.5 | 0.9 | 5.7 | 1.23 ± 0.56 |
| `python pting/day02.py input-aspidites` | 37.9 ± 5.9 | 31.4 | 55.8 | 28.69 ± 10.76 |
| `python pting/day02.py input-kcen` | 38.8 ± 6.4 | 30.7 | 66.6 | 29.39 ± 11.11 |
| `python pting/day02.py input-lanjian` | 33.4 ± 4.7 | 28.0 | 53.4 | 25.30 ± 9.32 |
| `python pting/day02.py input-mattcl` | 38.8 ± 4.9 | 30.6 | 55.5 | 29.37 ± 10.67 |
| `python pting/day02.py input-pting` | 35.7 ± 4.1 | 30.4 | 47.7 | 26.98 ± 9.70 |
