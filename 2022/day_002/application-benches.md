# Day 2 benchmarks

[link to problem](http://adventofcode.com/2022/day/2)

The following benchmarks are auto-generated via [hyperfine](https://github.com/sharkdp/hyperfine) by a ci system running on shared hardware. Results may be inaccurate, particularly for execution times < 5ms, as per the hyperfine warnings.

The "official" inputs were aggregated from repositories participating in the generation of these benchmarks. The "large" inputs (if any) were sourced from various places, including the subreddit.

## Benchmarks with officially generated inputs
| Command | Mean [ms] | Min [ms] | Max [ms] | Relative |
|:---|---:|---:|---:|---:|
| `aspidites-solver/aoc -i input-aspidites -d 2` | 12.2 ± 0.5 | 11.6 | 14.2 | 8.52 ± 2.86 |
| `aspidites-solver/aoc -i input-kcen -d 2` | 12.4 ± 0.6 | 11.5 | 15.1 | 8.63 ± 2.91 |
| `aspidites-solver/aoc -i input-lanjian -d 2` | 12.4 ± 0.4 | 11.7 | 15.8 | 8.67 ± 2.91 |
| `aspidites-solver/aoc -i input-mattcl -d 2` | 12.1 ± 0.4 | 11.5 | 13.9 | 8.43 ± 2.83 |
| `aspidites-solver/aoc -i input-pting -d 2` | 12.8 ± 1.2 | 11.5 | 22.4 | 8.88 ± 3.08 |
| `kcen/2022/02/solve input-aspidites` | 1.7 ± 0.5 | 0.9 | 7.6 | 1.21 ± 0.55 |
| `kcen/2022/02/solve input-kcen` | 1.8 ± 0.6 | 0.8 | 8.1 | 1.22 ± 0.60 |
| `kcen/2022/02/solve input-lanjian` | 1.8 ± 0.6 | 1.0 | 5.1 | 1.28 ± 0.58 |
| `kcen/2022/02/solve input-mattcl` | 1.4 ± 0.5 | 0.8 | 5.7 | 1.00 |
| `kcen/2022/02/solve input-pting` | 2.3 ± 1.0 | 0.9 | 8.5 | 1.58 ± 0.88 |
| `lanjian/day_02 input-aspidites` | 2.0 ± 0.7 | 1.2 | 14.7 | 1.41 ± 0.69 |
| `lanjian/day_02 input-kcen` | 2.2 ± 0.4 | 1.2 | 4.7 | 1.50 ± 0.59 |
| `lanjian/day_02 input-lanjian` | 2.0 ± 0.6 | 1.0 | 5.0 | 1.42 ± 0.63 |
| `lanjian/day_02 input-mattcl` | 2.1 ± 0.7 | 1.1 | 9.1 | 1.46 ± 0.69 |
| `lanjian/day_02 input-pting` | 2.1 ± 0.6 | 1.2 | 6.0 | 1.47 ± 0.63 |
| `mattcl-solver/aoc run 2 input-aspidites` | 1.7 ± 0.4 | 1.0 | 3.7 | 1.17 ± 0.48 |
| `mattcl-solver/aoc run 2 input-kcen` | 1.7 ± 0.5 | 0.9 | 9.8 | 1.17 ± 0.55 |
| `mattcl-solver/aoc run 2 input-lanjian` | 1.9 ± 0.8 | 0.9 | 11.6 | 1.29 ± 0.69 |
| `mattcl-solver/aoc run 2 input-mattcl` | 1.7 ± 0.5 | 1.0 | 4.9 | 1.17 ± 0.53 |
| `mattcl-solver/aoc run 2 input-pting` | 1.8 ± 0.4 | 1.0 | 3.9 | 1.23 ± 0.51 |
| `python pting/day02.py input-aspidites` | 35.3 ± 3.2 | 30.1 | 47.3 | 24.61 ± 8.51 |
| `python pting/day02.py input-kcen` | 37.6 ± 5.1 | 30.1 | 54.2 | 26.22 ± 9.46 |
| `python pting/day02.py input-lanjian` | 37.5 ± 3.8 | 31.2 | 51.3 | 26.09 ± 9.11 |
| `python pting/day02.py input-mattcl` | 35.0 ± 3.8 | 28.7 | 45.6 | 24.36 ± 8.55 |
| `python pting/day02.py input-pting` | 39.3 ± 9.1 | 31.6 | 93.7 | 27.40 ± 11.13 |
