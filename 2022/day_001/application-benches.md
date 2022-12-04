# Day 1 benchmarks

[link to problem](http://adventofcode.com/2022/day/1)

The following benchmarks are auto-generated via [hyperfine](https://github.com/sharkdp/hyperfine) by a ci system running on shared hardware. Results may be inaccurate, particularly for execution times < 5ms, as per the hyperfine warnings.

The "official" inputs were aggregated from repositories participating in the generation of these benchmarks. The "large" inputs (if any) were sourced from various places, including the subreddit.

## Benchmarks with officially generated inputs
| Command | Mean [ms] | Min [ms] | Max [ms] | Relative |
|:---|---:|---:|---:|---:|
| `aspidites-solver/aoc -i input-aspidites -d 1` | 12.4 ± 0.5 | 11.7 | 15.0 | 9.51 ± 2.89 |
| `aspidites-solver/aoc -i input-kcen -d 1` | 12.8 ± 0.6 | 11.8 | 15.4 | 9.87 ± 3.00 |
| `aspidites-solver/aoc -i input-lanjian -d 1` | 12.5 ± 0.6 | 11.7 | 15.4 | 9.63 ± 2.93 |
| `aspidites-solver/aoc -i input-mattcl -d 1` | 12.5 ± 0.8 | 11.5 | 19.5 | 9.62 ± 2.96 |
| `aspidites-solver/aoc -i input-pting -d 1` | 12.4 ± 0.6 | 11.6 | 14.9 | 9.54 ± 2.91 |
| `kcen/2022/01/solve input-aspidites` | 109.7 ± 7.0 | 99.1 | 124.1 | 84.48 ± 25.98 |
| `kcen/2022/01/solve input-kcen` | 120.1 ± 19.5 | 95.4 | 193.4 | 92.43 ± 31.61 |
| `kcen/2022/01/solve input-lanjian` | 105.4 ± 7.4 | 91.2 | 124.4 | 81.12 ± 25.06 |
| `kcen/2022/01/solve input-mattcl` | 130.3 ± 21.3 | 104.8 | 184.4 | 100.32 ± 34.34 |
| `kcen/2022/01/solve input-pting` | 101.9 ± 7.6 | 90.7 | 119.3 | 78.44 ± 24.32 |
| `lanjian/day_01 input-aspidites` | 1.9 ± 0.4 | 1.0 | 5.1 | 1.43 ± 0.55 |
| `lanjian/day_01 input-kcen` | 1.9 ± 0.5 | 1.0 | 5.2 | 1.46 ± 0.60 |
| `lanjian/day_01 input-lanjian` | 1.7 ± 0.4 | 1.0 | 3.8 | 1.31 ± 0.49 |
| `lanjian/day_01 input-mattcl` | 1.8 ± 0.4 | 1.1 | 4.6 | 1.37 ± 0.52 |
| `lanjian/day_01 input-pting` | 1.8 ± 0.5 | 1.0 | 4.6 | 1.35 ± 0.55 |
| `mattcl-solver/aoc run 1 input-aspidites` | 1.4 ± 0.5 | 0.7 | 6.1 | 1.10 ± 0.52 |
| `mattcl-solver/aoc run 1 input-kcen` | 1.6 ± 0.4 | 0.8 | 4.6 | 1.22 ± 0.46 |
| `mattcl-solver/aoc run 1 input-lanjian` | 1.3 ± 0.4 | 0.8 | 5.4 | 1.00 |
| `mattcl-solver/aoc run 1 input-mattcl` | 1.6 ± 1.0 | 0.7 | 15.3 | 1.22 ± 0.84 |
| `mattcl-solver/aoc run 1 input-pting` | 1.5 ± 0.5 | 0.8 | 7.0 | 1.19 ± 0.53 |
| `python pting/day01.py input-aspidites` | 35.3 ± 4.2 | 29.8 | 50.5 | 27.17 ± 8.80 |
| `python pting/day01.py input-kcen` | 34.3 ± 3.0 | 29.5 | 45.9 | 26.41 ± 8.27 |
| `python pting/day01.py input-lanjian` | 34.2 ± 3.6 | 28.7 | 44.3 | 26.35 ± 8.41 |
| `python pting/day01.py input-mattcl` | 36.1 ± 4.6 | 29.4 | 51.5 | 27.79 ± 9.09 |
| `python pting/day01.py input-pting` | 33.5 ± 3.5 | 27.5 | 45.4 | 25.76 ± 8.21 |
