# Day 1 benchmarks

[link to problem](http://adventofcode.com/2022/day/1)

The following benchmarks are auto-generated via [hyperfine](https://github.com/sharkdp/hyperfine) by a ci system running on shared hardware. Results may be inaccurate, particularly for execution times < 5ms, as per the hyperfine warnings.

The "official" inputs were aggregated from repositories participating in the generation of these benchmarks. The "large" inputs (if any) were sourced from various places, including the subreddit.

## Benchmarks with officially generated inputs
| Command | Mean [ms] | Min [ms] | Max [ms] | Relative |
|:---|---:|---:|---:|---:|
| `aspidites-solver/aoc -i input-aspidites -d 1` | 13.5 ± 1.0 | 12.0 | 17.9 | 13.52 ± 4.99 |
| `aspidites-solver/aoc -i input-kcen -d 1` | 11.8 ± 0.6 | 11.0 | 17.2 | 11.82 ± 4.32 |
| `aspidites-solver/aoc -i input-lanjian -d 1` | 11.9 ± 0.7 | 11.1 | 15.3 | 11.98 ± 4.39 |
| `aspidites-solver/aoc -i input-mattcl -d 1` | 12.3 ± 0.5 | 11.0 | 14.3 | 12.39 ± 4.51 |
| `aspidites-solver/aoc -i input-pting -d 1` | 12.4 ± 0.9 | 11.0 | 22.8 | 12.48 ± 4.61 |
| `kcen/2022/01/solve input-aspidites` | 114.9 ± 12.7 | 98.8 | 145.0 | 115.34 ± 43.61 |
| `kcen/2022/01/solve input-kcen` | 104.5 ± 8.5 | 90.9 | 130.6 | 104.92 ± 38.89 |
| `kcen/2022/01/solve input-lanjian` | 103.8 ± 10.6 | 88.1 | 132.6 | 104.18 ± 39.13 |
| `kcen/2022/01/solve input-mattcl` | 103.8 ± 14.6 | 85.8 | 150.2 | 104.24 ± 40.44 |
| `kcen/2022/01/solve input-pting` | 120.3 ± 20.5 | 102.9 | 201.0 | 120.78 ± 48.26 |
| `lanjian/day_01 input-aspidites` | 1.4 ± 0.4 | 0.8 | 3.0 | 1.40 ± 0.64 |
| `lanjian/day_01 input-kcen` | 1.7 ± 0.5 | 0.7 | 3.9 | 1.69 ± 0.76 |
| `lanjian/day_01 input-lanjian` | 1.4 ± 0.5 | 0.7 | 5.2 | 1.36 ± 0.71 |
| `lanjian/day_01 input-mattcl` | 1.3 ± 0.8 | 0.6 | 16.6 | 1.34 ± 0.91 |
| `lanjian/day_01 input-pting` | 1.8 ± 0.5 | 0.7 | 3.6 | 1.78 ± 0.79 |
| `mattcl-solver/aoc run 1 input-aspidites` | 1.1 ± 0.4 | 0.6 | 3.6 | 1.14 ± 0.58 |
| `mattcl-solver/aoc run 1 input-kcen` | 1.3 ± 0.5 | 0.6 | 3.7 | 1.29 ± 0.67 |
| `mattcl-solver/aoc run 1 input-lanjian` | 1.1 ± 0.4 | 0.5 | 3.6 | 1.07 ± 0.58 |
| `mattcl-solver/aoc run 1 input-mattcl` | 1.0 ± 0.4 | 0.5 | 3.9 | 1.00 |
| `mattcl-solver/aoc run 1 input-pting` | 1.9 ± 0.8 | 0.6 | 6.3 | 1.87 ± 1.08 |
| `python pting/day01.py input-aspidites` | 39.0 ± 6.2 | 29.1 | 67.9 | 39.20 ± 15.47 |
| `python pting/day01.py input-kcen` | 34.4 ± 4.2 | 26.7 | 48.6 | 34.59 ± 13.21 |
| `python pting/day01.py input-lanjian` | 31.0 ± 2.8 | 26.2 | 46.0 | 31.18 ± 11.62 |
| `python pting/day01.py input-mattcl` | 32.1 ± 4.2 | 26.4 | 45.4 | 32.24 ± 12.40 |
| `python pting/day01.py input-pting` | 37.9 ± 6.2 | 28.9 | 55.6 | 38.10 ± 15.13 |
