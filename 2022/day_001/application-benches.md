# Day 1 benchmarks

[link to problem](http://adventofcode.com/2022/day/1)

The following benchmarks are auto-generated via [hyperfine](https://github.com/sharkdp/hyperfine) by a ci system running on shared hardware. Results may be inaccurate, particularly for execution times < 5ms, as per the hyperfine warnings.

The "official" inputs were aggregated from repositories participating in the generation of these benchmarks. The "large" inputs (if any) were sourced from various places, including the subreddit.

## Benchmarks with officially generated inputs
| Command | Mean [ms] | Min [ms] | Max [ms] | Relative |
|:---|---:|---:|---:|---:|
| `aspidites-solver/aoc -i input-aspidites -d 1` | 12.3 ± 1.1 | 11.4 | 23.6 | 13.45 ± 7.46 |
| `aspidites-solver/aoc -i input-kcen -d 1` | 12.9 ± 1.6 | 11.5 | 24.3 | 14.01 ± 7.86 |
| `aspidites-solver/aoc -i input-lanjian -d 1` | 12.1 ± 0.8 | 11.4 | 19.2 | 13.23 ± 7.29 |
| `aspidites-solver/aoc -i input-mattcl -d 1` | 12.1 ± 0.8 | 11.4 | 18.0 | 13.18 ± 7.26 |
| `aspidites-solver/aoc -i input-pting -d 1` | 12.4 ± 0.6 | 11.4 | 15.6 | 13.49 ± 7.41 |
| `kcen/2022/01/solve input-aspidites` | 105.5 ± 6.9 | 94.8 | 119.8 | 114.97 ± 63.32 |
| `kcen/2022/01/solve input-kcen` | 111.6 ± 9.3 | 96.2 | 139.5 | 121.52 ± 67.21 |
| `kcen/2022/01/solve input-lanjian` | 103.6 ± 8.9 | 95.0 | 132.3 | 112.86 ± 62.48 |
| `kcen/2022/01/solve input-mattcl` | 104.7 ± 10.6 | 92.8 | 136.9 | 114.10 ± 63.46 |
| `kcen/2022/01/solve input-pting` | 108.8 ± 14.6 | 86.8 | 154.8 | 118.50 ± 66.73 |
| `lanjian/day_01 input-aspidites` | 1.7 ± 1.1 | 0.6 | 15.8 | 1.91 ± 1.59 |
| `lanjian/day_01 input-kcen` | 1.9 ± 0.5 | 0.9 | 5.1 | 2.12 ± 1.29 |
| `lanjian/day_01 input-lanjian` | 1.0 ± 0.4 | 0.6 | 5.9 | 1.10 ± 0.75 |
| `lanjian/day_01 input-mattcl` | 1.6 ± 0.7 | 0.4 | 11.8 | 1.73 ± 1.19 |
| `lanjian/day_01 input-pting` | 1.6 ± 0.5 | 0.7 | 4.4 | 1.71 ± 1.07 |
| `mattcl-solver/aoc run 1 input-aspidites` | 1.0 ± 0.4 | 0.5 | 4.4 | 1.14 ± 0.76 |
| `mattcl-solver/aoc run 1 input-kcen` | 1.5 ± 0.5 | 0.5 | 5.9 | 1.61 ± 1.05 |
| `mattcl-solver/aoc run 1 input-lanjian` | 0.9 ± 0.5 | 0.4 | 5.9 | 1.00 |
| `mattcl-solver/aoc run 1 input-mattcl` | 1.2 ± 0.4 | 0.5 | 3.6 | 1.33 ± 0.86 |
| `mattcl-solver/aoc run 1 input-pting` | 1.4 ± 0.5 | 0.5 | 5.8 | 1.49 ± 0.96 |
| `python pting/day01.py input-aspidites` | 40.8 ± 13.4 | 29.1 | 97.2 | 44.47 ± 28.39 |
| `python pting/day01.py input-kcen` | 34.9 ± 4.2 | 29.8 | 46.5 | 38.00 ± 21.27 |
| `python pting/day01.py input-lanjian` | 32.0 ± 3.9 | 27.0 | 50.6 | 34.85 ± 19.52 |
| `python pting/day01.py input-mattcl` | 35.8 ± 4.8 | 28.2 | 51.2 | 38.98 ± 21.93 |
| `python pting/day01.py input-pting` | 34.8 ± 5.0 | 28.0 | 55.8 | 37.85 ± 21.40 |
