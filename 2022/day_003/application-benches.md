# Day 3 benchmarks

[link to problem](http://adventofcode.com/2022/day/3)

The following benchmarks are auto-generated via [hyperfine](https://github.com/sharkdp/hyperfine) by a ci system running on shared hardware. Results may be inaccurate, particularly for execution times < 5ms, as per the hyperfine warnings.

The "official" inputs were aggregated from repositories participating in the generation of these benchmarks. The "large" inputs (if any) were sourced from various places, including the subreddit.

## Benchmarks with officially generated inputs
| Command | Mean [ms] | Min [ms] | Max [ms] | Relative |
|:---|---:|---:|---:|---:|
| `aspidites-solver/aoc -i input-aspidites -d 3` | 14.5 ± 4.4 | 11.8 | 32.1 | 12.15 ± 6.33 |
| `aspidites-solver/aoc -i input-kcen -d 3` | 14.0 ± 3.6 | 11.7 | 25.4 | 11.68 ± 5.80 |
| `aspidites-solver/aoc -i input-lanjian -d 3` | 13.4 ± 3.1 | 11.4 | 25.3 | 11.19 ± 5.44 |
| `aspidites-solver/aoc -i input-mattcl -d 3` | 14.8 ± 4.4 | 11.9 | 27.4 | 12.34 ± 6.39 |
| `aspidites-solver/aoc -i input-pting -d 3` | 14.9 ± 4.7 | 11.8 | 27.4 | 12.49 ± 6.62 |
| `kcen/2022/03/solve input-aspidites` | 236.8 ± 24.8 | 208.5 | 301.0 | 197.92 ± 86.72 |
| `kcen/2022/03/solve input-kcen` | 269.7 ± 27.5 | 220.0 | 318.8 | 225.37 ± 98.60 |
| `kcen/2022/03/solve input-lanjian` | 550.8 ± 347.9 | 204.8 | 1302.7 | 460.32 ± 350.53 |
| `kcen/2022/03/solve input-mattcl` | 274.5 ± 32.8 | 233.2 | 336.1 | 229.39 ± 101.37 |
| `kcen/2022/03/solve input-pting` | 248.6 ± 34.8 | 224.6 | 334.3 | 207.71 ± 93.04 |
| `lanjian/day_03 input-aspidites` | 1.2 ± 0.5 | 0.6 | 4.5 | 1.00 |
| `lanjian/day_03 input-kcen` | 1.8 ± 0.7 | 0.6 | 5.6 | 1.51 ± 0.84 |
| `lanjian/day_03 input-lanjian` | 1.7 ± 0.8 | 0.6 | 10.1 | 1.45 ± 0.88 |
| `lanjian/day_03 input-mattcl` | 1.6 ± 0.7 | 0.7 | 5.9 | 1.30 ± 0.78 |
| `lanjian/day_03 input-pting` | 2.0 ± 1.1 | 0.6 | 9.1 | 1.64 ± 1.12 |
| `mattcl-solver/aoc run 3 input-aspidites` | 1.8 ± 0.8 | 0.7 | 8.2 | 1.52 ± 0.91 |
| `mattcl-solver/aoc run 3 input-kcen` | 1.9 ± 0.7 | 0.7 | 5.7 | 1.55 ± 0.89 |
| `mattcl-solver/aoc run 3 input-lanjian` | 1.4 ± 0.7 | 0.6 | 5.4 | 1.19 ± 0.74 |
| `mattcl-solver/aoc run 3 input-mattcl` | 1.9 ± 0.7 | 0.8 | 8.6 | 1.58 ± 0.92 |
| `mattcl-solver/aoc run 3 input-pting` | 1.4 ± 0.7 | 0.6 | 9.0 | 1.13 ± 0.77 |
| `python pting/day03.py input-aspidites` | 36.0 ± 7.8 | 27.6 | 67.2 | 30.12 ± 14.38 |
| `python pting/day03.py input-kcen` | 62.6 ± 37.0 | 26.6 | 326.3 | 52.35 ± 38.10 |
| `python pting/day03.py input-lanjian` | 41.5 ± 9.7 | 30.8 | 77.3 | 34.67 ± 16.83 |
| `python pting/day03.py input-mattcl` | 40.5 ± 8.6 | 31.6 | 70.0 | 33.81 ± 16.08 |
| `python pting/day03.py input-pting` | 35.6 ± 5.1 | 27.3 | 54.5 | 29.72 ± 13.33 |
