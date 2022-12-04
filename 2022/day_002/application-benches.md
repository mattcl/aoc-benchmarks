# Day 2 benchmarks

[link to problem](http://adventofcode.com/2022/day/2)

The following benchmarks are auto-generated via [hyperfine](https://github.com/sharkdp/hyperfine) by a ci system running on shared hardware. Results may be inaccurate, particularly for execution times < 5ms, as per the hyperfine warnings.

The "official" inputs were aggregated from repositories participating in the generation of these benchmarks. The "large" inputs (if any) were sourced from various places, including the subreddit.

## Benchmarks with officially generated inputs
| Command | Mean [ms] | Min [ms] | Max [ms] | Relative |
|:---|---:|---:|---:|---:|
| `aspidites-solver/aoc -i input-aspidites -d 2` | 12.5 ± 1.1 | 11.5 | 19.4 | 9.48 ± 3.67 |
| `aspidites-solver/aoc -i input-kcen -d 2` | 12.7 ± 1.5 | 11.6 | 27.1 | 9.70 ± 3.83 |
| `aspidites-solver/aoc -i input-lanjian -d 2` | 12.2 ± 0.6 | 11.3 | 15.8 | 9.28 ± 3.53 |
| `aspidites-solver/aoc -i input-mattcl -d 2` | 12.3 ± 0.7 | 11.3 | 16.5 | 9.37 ± 3.57 |
| `aspidites-solver/aoc -i input-pting -d 2` | 12.4 ± 0.6 | 11.6 | 15.7 | 9.45 ± 3.59 |
| `kcen/2022/02/solve input-aspidites` | 1.6 ± 0.5 | 0.8 | 4.3 | 1.21 ± 0.58 |
| `kcen/2022/02/solve input-kcen` | 1.7 ± 1.0 | 0.7 | 13.0 | 1.31 ± 0.89 |
| `kcen/2022/02/solve input-lanjian` | 2.3 ± 1.4 | 0.7 | 13.1 | 1.77 ± 1.23 |
| `kcen/2022/02/solve input-mattcl` | 1.6 ± 0.6 | 0.7 | 8.7 | 1.21 ± 0.64 |
| `kcen/2022/02/solve input-pting` | 1.6 ± 0.6 | 0.8 | 5.1 | 1.21 ± 0.62 |
| `lanjian/day_02 input-aspidites` | 1.7 ± 0.5 | 1.0 | 4.8 | 1.32 ± 0.61 |
| `lanjian/day_02 input-kcen` | 1.7 ± 0.6 | 1.0 | 6.8 | 1.33 ± 0.69 |
| `lanjian/day_02 input-lanjian` | 2.1 ± 0.8 | 1.0 | 8.6 | 1.59 ± 0.85 |
| `lanjian/day_02 input-mattcl` | 1.9 ± 0.6 | 1.0 | 7.6 | 1.47 ± 0.69 |
| `lanjian/day_02 input-pting` | 1.7 ± 0.5 | 1.0 | 5.2 | 1.32 ± 0.62 |
| `mattcl-solver/aoc run 2 input-aspidites` | 1.3 ± 0.5 | 0.7 | 5.6 | 1.00 |
| `mattcl-solver/aoc run 2 input-kcen` | 1.6 ± 0.5 | 0.9 | 4.4 | 1.23 ± 0.59 |
| `mattcl-solver/aoc run 2 input-lanjian` | 1.8 ± 0.6 | 0.9 | 7.3 | 1.36 ± 0.70 |
| `mattcl-solver/aoc run 2 input-mattcl` | 1.5 ± 0.5 | 0.7 | 4.7 | 1.15 ± 0.60 |
| `mattcl-solver/aoc run 2 input-pting` | 1.6 ± 0.5 | 0.8 | 4.3 | 1.23 ± 0.62 |
| `python pting/day02.py input-aspidites` | 34.5 ± 4.3 | 28.1 | 47.1 | 26.25 ± 10.41 |
| `python pting/day02.py input-kcen` | 35.0 ± 4.4 | 29.1 | 54.6 | 26.65 ± 10.59 |
| `python pting/day02.py input-lanjian` | 42.2 ± 11.6 | 30.1 | 94.4 | 32.09 ± 14.99 |
| `python pting/day02.py input-mattcl` | 37.8 ± 5.0 | 30.1 | 55.8 | 28.79 ± 11.49 |
| `python pting/day02.py input-pting` | 36.6 ± 3.6 | 30.6 | 47.6 | 27.86 ± 10.85 |
