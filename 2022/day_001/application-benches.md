# Day 1 benchmarks

[link to problem](http://adventofcode.com/2022/day/1)

The following benchmarks are auto-generated via [hyperfine](https://github.com/sharkdp/hyperfine) by a ci system running on shared hardware. Results may be inaccurate, particularly for execution times < 5ms, as per the hyperfine warnings.

The "official" inputs were aggregated from repositories participating in the generation of these benchmarks. The "large" inputs (if any) were sourced from various places, including the subreddit.

## Benchmarks with officially generated inputs
| Command | Mean [ms] | Min [ms] | Max [ms] | Relative |
|:---|---:|---:|---:|---:|
| `aspidites-solver/aoc -i input-aspidites -d 1` | 12.1 ± 0.6 | 11.3 | 15.1 | 12.51 ± 5.18 |
| `aspidites-solver/aoc -i input-kcen -d 1` | 12.7 ± 1.8 | 11.4 | 25.3 | 13.05 ± 5.67 |
| `aspidites-solver/aoc -i input-lanjian -d 1` | 12.6 ± 0.8 | 11.6 | 16.1 | 13.01 ± 5.40 |
| `aspidites-solver/aoc -i input-mattcl -d 1` | 12.2 ± 0.5 | 11.4 | 14.3 | 12.55 ± 5.17 |
| `aspidites-solver/aoc -i input-pting -d 1` | 11.9 ± 0.5 | 11.2 | 14.0 | 12.29 ± 5.07 |
| `kcen/2022/01/solve input-aspidites` | 102.2 ± 7.5 | 92.5 | 121.7 | 105.26 ± 43.87 |
| `kcen/2022/01/solve input-kcen` | 111.7 ± 13.5 | 92.9 | 146.9 | 115.10 ± 49.23 |
| `kcen/2022/01/solve input-lanjian` | 112.6 ± 18.6 | 91.7 | 177.5 | 115.97 ± 51.29 |
| `kcen/2022/01/solve input-mattcl` | 108.6 ± 13.5 | 89.0 | 148.5 | 111.82 ± 47.93 |
| `kcen/2022/01/solve input-pting` | 98.9 ± 9.1 | 89.2 | 132.2 | 101.85 ± 42.82 |
| `lanjian/day_01 input-aspidites` | 1.4 ± 0.5 | 0.7 | 10.3 | 1.45 ± 0.80 |
| `lanjian/day_01 input-kcen` | 1.5 ± 0.4 | 0.9 | 5.2 | 1.55 ± 0.76 |
| `lanjian/day_01 input-lanjian` | 1.7 ± 0.7 | 1.0 | 10.3 | 1.75 ± 1.01 |
| `lanjian/day_01 input-mattcl` | 1.7 ± 0.7 | 0.7 | 12.0 | 1.71 ± 0.98 |
| `lanjian/day_01 input-pting` | 1.3 ± 0.5 | 0.7 | 4.4 | 1.32 ± 0.76 |
| `mattcl-solver/aoc run 1 input-aspidites` | 1.0 ± 0.4 | 0.5 | 7.0 | 1.00 |
| `mattcl-solver/aoc run 1 input-kcen` | 1.4 ± 0.5 | 0.6 | 4.9 | 1.46 ± 0.79 |
| `mattcl-solver/aoc run 1 input-lanjian` | 1.4 ± 0.7 | 0.6 | 9.8 | 1.47 ± 0.91 |
| `mattcl-solver/aoc run 1 input-mattcl` | 1.3 ± 0.7 | 0.6 | 14.2 | 1.35 ± 0.93 |
| `mattcl-solver/aoc run 1 input-pting` | 1.0 ± 0.4 | 0.6 | 6.1 | 1.04 ± 0.63 |
| `python pting/day01.py input-aspidites` | 32.9 ± 3.2 | 27.8 | 42.6 | 33.91 ± 14.29 |
| `python pting/day01.py input-kcen` | 31.6 ± 2.7 | 27.5 | 42.2 | 32.58 ± 13.65 |
| `python pting/day01.py input-lanjian` | 32.6 ± 3.6 | 28.0 | 49.1 | 33.59 ± 14.26 |
| `python pting/day01.py input-mattcl` | 35.1 ± 4.1 | 27.5 | 49.8 | 36.15 ± 15.42 |
| `python pting/day01.py input-pting` | 33.1 ± 5.3 | 26.8 | 59.0 | 34.12 ± 15.04 |
