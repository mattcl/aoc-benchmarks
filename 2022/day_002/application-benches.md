# Day 2 benchmarks

[link to problem](http://adventofcode.com/2022/day/2)

The following benchmarks are auto-generated via [hyperfine](https://github.com/sharkdp/hyperfine) by a ci system running on shared hardware. Results may be inaccurate, particularly for execution times < 5ms, as per the hyperfine warnings.

The "official" inputs were aggregated from repositories participating in the generation of these benchmarks. The "large" inputs (if any) were sourced from various places, including the subreddit.

## Benchmarks with officially generated inputs
| Command | Mean [ms] | Min [ms] | Max [ms] | Relative |
|:---|---:|---:|---:|---:|
| `aspidites-solver/aoc -i input-aspidites -d 2` | 59.0 ± 6.4 | 51.0 | 80.0 | 37.11 ± 11.07 |
| `aspidites-solver/aoc -i input-kcen -d 2` | 64.0 ± 6.0 | 53.8 | 78.5 | 40.25 ± 11.80 |
| `aspidites-solver/aoc -i input-lanjian -d 2` | 64.0 ± 7.4 | 54.2 | 91.1 | 40.21 ± 12.10 |
| `aspidites-solver/aoc -i input-mattcl -d 2` | 59.2 ± 4.3 | 53.2 | 73.5 | 37.22 ± 10.69 |
| `aspidites-solver/aoc -i input-pting -d 2` | 65.1 ± 7.8 | 55.1 | 88.2 | 40.89 ± 12.37 |
| `kcen/2022/02/solve input-aspidites` | 213.8 ± 8.1 | 205.0 | 229.0 | 134.38 ± 37.68 |
| `kcen/2022/02/solve input-kcen` | 224.1 ± 31.3 | 193.8 | 293.0 | 140.83 ± 43.78 |
| `kcen/2022/02/solve input-lanjian` | 215.2 ± 6.7 | 205.6 | 234.7 | 135.28 ± 37.82 |
| `kcen/2022/02/solve input-mattcl` | 236.7 ± 40.2 | 183.5 | 302.1 | 148.78 ± 48.46 |
| `kcen/2022/02/solve input-pting` | 256.1 ± 34.1 | 215.2 | 338.9 | 160.98 ± 49.61 |
| `lanjian/day_02 input-aspidites` | 1.7 ± 0.7 | 1.0 | 11.2 | 1.08 ± 0.53 |
| `lanjian/day_02 input-kcen` | 2.0 ± 0.6 | 1.0 | 7.6 | 1.27 ± 0.51 |
| `lanjian/day_02 input-lanjian` | 2.1 ± 0.8 | 1.0 | 11.9 | 1.34 ± 0.60 |
| `lanjian/day_02 input-mattcl` | 2.3 ± 0.6 | 1.1 | 6.3 | 1.45 ± 0.57 |
| `lanjian/day_02 input-pting` | 1.7 ± 0.6 | 1.0 | 7.1 | 1.09 ± 0.47 |
| `mattcl-solver/aoc run 2 input-aspidites` | 1.6 ± 0.4 | 0.9 | 6.3 | 1.00 |
| `mattcl-solver/aoc run 2 input-kcen` | 1.7 ± 0.4 | 0.9 | 5.2 | 1.10 ± 0.41 |
| `mattcl-solver/aoc run 2 input-lanjian` | 1.8 ± 0.6 | 0.8 | 7.0 | 1.15 ± 0.49 |
| `mattcl-solver/aoc run 2 input-mattcl` | 2.1 ± 0.9 | 0.9 | 10.8 | 1.29 ± 0.66 |
| `mattcl-solver/aoc run 2 input-pting` | 1.6 ± 0.5 | 0.8 | 4.7 | 1.02 ± 0.42 |
| `python pting/day02.py input-aspidites` | 35.3 ± 4.8 | 29.4 | 63.6 | 22.21 ± 6.87 |
| `python pting/day02.py input-kcen` | 36.7 ± 4.6 | 29.8 | 46.1 | 23.07 ± 7.03 |
| `python pting/day02.py input-lanjian` | 39.4 ± 7.9 | 30.1 | 67.4 | 24.78 ± 8.49 |
| `python pting/day02.py input-mattcl` | 37.2 ± 6.4 | 29.3 | 77.3 | 23.41 ± 7.63 |
| `python pting/day02.py input-pting` | 34.6 ± 3.9 | 30.2 | 49.8 | 21.76 ± 6.51 |
