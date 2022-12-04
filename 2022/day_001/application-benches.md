# Day 1 benchmarks

[link to problem](http://adventofcode.com/2022/day/1)

The following benchmarks are auto-generated via [hyperfine](https://github.com/sharkdp/hyperfine) by a ci system running on shared hardware. Results may be inaccurate, particularly for execution times < 5ms, as per the hyperfine warnings.

The "official" inputs were aggregated from repositories participating in the generation of these benchmarks. The "large" inputs (if any) were sourced from various places, including the subreddit.

## Benchmarks with officially generated inputs
| Command | Mean [ms] | Min [ms] | Max [ms] | Relative |
|:---|---:|---:|---:|---:|
| `aspidites-solver/aoc -i input-aspidites -d 1` | 12.4 ± 0.9 | 11.6 | 22.2 | 10.72 ± 2.76 |
| `aspidites-solver/aoc -i input-kcen -d 1` | 12.5 ± 0.6 | 11.6 | 15.3 | 10.81 ± 2.73 |
| `aspidites-solver/aoc -i input-lanjian -d 1` | 12.8 ± 1.6 | 11.5 | 30.5 | 11.10 ± 3.08 |
| `aspidites-solver/aoc -i input-mattcl -d 1` | 14.5 ± 13.6 | 11.8 | 131.8 | 12.55 ± 12.19 |
| `aspidites-solver/aoc -i input-pting -d 1` | 13.0 ± 1.9 | 11.6 | 26.6 | 11.24 ± 3.24 |
| `kcen/2022/01/solve input-aspidites` | 106.8 ± 8.2 | 96.1 | 125.7 | 92.63 ± 24.03 |
| `kcen/2022/01/solve input-kcen` | 103.3 ± 8.5 | 89.8 | 129.2 | 89.61 ± 23.39 |
| `kcen/2022/01/solve input-lanjian` | 114.0 ± 17.5 | 96.2 | 165.9 | 98.86 ± 28.82 |
| `kcen/2022/01/solve input-mattcl` | 110.4 ± 6.8 | 98.0 | 126.5 | 95.75 ± 24.45 |
| `kcen/2022/01/solve input-pting` | 109.3 ± 15.8 | 97.7 | 157.6 | 94.82 ± 27.20 |
| `lanjian/day_01 input-aspidites` | 1.7 ± 0.9 | 0.9 | 10.8 | 1.45 ± 0.86 |
| `lanjian/day_01 input-kcen` | 1.7 ± 0.6 | 0.9 | 6.3 | 1.48 ± 0.61 |
| `lanjian/day_01 input-lanjian` | 1.4 ± 0.4 | 0.9 | 3.3 | 1.25 ± 0.44 |
| `lanjian/day_01 input-mattcl` | 1.4 ± 0.5 | 0.9 | 6.6 | 1.18 ± 0.50 |
| `lanjian/day_01 input-pting` | 1.6 ± 0.6 | 0.8 | 6.1 | 1.42 ± 0.61 |
| `mattcl-solver/aoc run 1 input-aspidites` | 1.3 ± 0.7 | 0.6 | 10.9 | 1.14 ± 0.63 |
| `mattcl-solver/aoc run 1 input-kcen` | 1.3 ± 0.4 | 0.6 | 5.5 | 1.11 ± 0.48 |
| `mattcl-solver/aoc run 1 input-lanjian` | 1.2 ± 0.3 | 0.7 | 2.8 | 1.00 |
| `mattcl-solver/aoc run 1 input-mattcl` | 1.3 ± 0.5 | 0.7 | 5.3 | 1.11 ± 0.49 |
| `mattcl-solver/aoc run 1 input-pting` | 1.3 ± 0.4 | 0.8 | 5.0 | 1.16 ± 0.43 |
| `python pting/day01.py input-aspidites` | 35.9 ± 4.7 | 28.8 | 54.0 | 31.14 ± 8.71 |
| `python pting/day01.py input-kcen` | 32.4 ± 4.3 | 27.3 | 51.1 | 28.06 ± 7.89 |
| `python pting/day01.py input-lanjian` | 33.1 ± 4.5 | 27.6 | 46.8 | 28.68 ± 8.12 |
| `python pting/day01.py input-mattcl` | 34.9 ± 5.2 | 27.4 | 53.5 | 30.30 ± 8.73 |
| `python pting/day01.py input-pting` | 34.5 ± 5.3 | 28.4 | 68.5 | 29.96 ± 8.73 |
