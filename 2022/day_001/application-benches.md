# Day 1 benchmarks

[link to problem](http://adventofcode.com/2022/day/1)

The following benchmarks are auto-generated via [hyperfine](https://github.com/sharkdp/hyperfine) by a ci system running on shared hardware. Results may be inaccurate, particularly for execution times < 5ms, as per the hyperfine warnings.

The "official" inputs were aggregated from repositories participating in the generation of these benchmarks. The "large" inputs (if any) were sourced from various places, including the subreddit.

## Benchmarks with officially generated inputs
| Command | Mean [ms] | Min [ms] | Max [ms] | Relative |
|:---|---:|---:|---:|---:|
| `aspidites-solver/aoc -i input-aspidites -d 1` | 12.4 ± 1.0 | 11.6 | 19.5 | 10.07 ± 3.23 |
| `aspidites-solver/aoc -i input-kcen -d 1` | 13.2 ± 1.9 | 11.7 | 26.2 | 10.68 ± 3.67 |
| `aspidites-solver/aoc -i input-lanjian -d 1` | 12.4 ± 1.1 | 11.6 | 26.6 | 10.04 ± 3.25 |
| `aspidites-solver/aoc -i input-mattcl -d 1` | 12.4 ± 0.5 | 11.5 | 15.1 | 10.09 ± 3.17 |
| `aspidites-solver/aoc -i input-pting -d 1` | 12.2 ± 0.5 | 11.5 | 15.7 | 9.94 ± 3.12 |
| `kcen/2022/01/solve input-aspidites` | 112.4 ± 8.2 | 98.2 | 127.8 | 91.28 ± 29.20 |
| `kcen/2022/01/solve input-kcen` | 115.9 ± 15.5 | 96.7 | 165.1 | 94.12 ± 31.92 |
| `kcen/2022/01/solve input-lanjian` | 109.3 ± 13.7 | 93.6 | 145.7 | 88.74 ± 29.78 |
| `kcen/2022/01/solve input-mattcl` | 109.3 ± 11.1 | 92.7 | 137.8 | 88.71 ± 29.06 |
| `kcen/2022/01/solve input-pting` | 103.9 ± 8.5 | 92.3 | 139.9 | 84.32 ± 27.16 |
| `lanjian/day_01 input-aspidites` | 1.8 ± 2.3 | 0.8 | 87.6 | 1.46 ± 1.93 |
| `lanjian/day_01 input-kcen` | 2.1 ± 0.6 | 0.9 | 6.6 | 1.70 ± 0.74 |
| `lanjian/day_01 input-lanjian` | 2.0 ± 0.8 | 0.9 | 9.7 | 1.60 ± 0.82 |
| `lanjian/day_01 input-mattcl` | 2.1 ± 0.8 | 1.1 | 6.5 | 1.72 ± 0.85 |
| `lanjian/day_01 input-pting` | 1.8 ± 0.5 | 1.0 | 7.8 | 1.49 ± 0.64 |
| `mattcl-solver/aoc run 1 input-aspidites` | 1.3 ± 0.5 | 0.7 | 4.6 | 1.08 ± 0.55 |
| `mattcl-solver/aoc run 1 input-kcen` | 1.7 ± 0.6 | 0.8 | 6.8 | 1.41 ± 0.67 |
| `mattcl-solver/aoc run 1 input-lanjian` | 1.2 ± 0.4 | 0.7 | 4.6 | 1.00 |
| `mattcl-solver/aoc run 1 input-mattcl` | 1.7 ± 0.5 | 0.8 | 9.4 | 1.36 ± 0.59 |
| `mattcl-solver/aoc run 1 input-pting` | 1.3 ± 0.4 | 0.7 | 4.5 | 1.08 ± 0.49 |
| `python pting/day01.py input-aspidites` | 33.2 ± 3.0 | 28.3 | 42.9 | 26.93 ± 8.74 |
| `python pting/day01.py input-kcen` | 36.4 ± 5.1 | 30.2 | 50.6 | 29.57 ± 10.10 |
| `python pting/day01.py input-lanjian` | 37.8 ± 5.1 | 29.5 | 50.4 | 30.64 ± 10.39 |
| `python pting/day01.py input-mattcl` | 34.7 ± 3.9 | 28.9 | 48.9 | 28.14 ± 9.32 |
| `python pting/day01.py input-pting` | 37.5 ± 5.9 | 30.5 | 63.8 | 30.41 ± 10.60 |
