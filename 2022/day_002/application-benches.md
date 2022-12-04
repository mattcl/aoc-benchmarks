# Day 2 benchmarks

[link to problem](http://adventofcode.com/2022/day/2)

The following benchmarks are auto-generated via [hyperfine](https://github.com/sharkdp/hyperfine) by a ci system running on shared hardware. Results may be inaccurate, particularly for execution times < 5ms, as per the hyperfine warnings.

The "official" inputs were aggregated from repositories participating in the generation of these benchmarks. The "large" inputs (if any) were sourced from various places, including the subreddit.

## Benchmarks with officially generated inputs
| Command | Mean [ms] | Min [ms] | Max [ms] | Relative |
|:---|---:|---:|---:|---:|
| `aspidites-solver/aoc -i input-aspidites -d 2` | 12.6 ± 0.9 | 11.4 | 18.0 | 8.46 ± 3.25 |
| `aspidites-solver/aoc -i input-kcen -d 2` | 12.9 ± 1.4 | 11.3 | 24.8 | 8.64 ± 3.40 |
| `aspidites-solver/aoc -i input-lanjian -d 2` | 12.2 ± 2.3 | 11.2 | 36.5 | 8.23 ± 3.46 |
| `aspidites-solver/aoc -i input-mattcl -d 2` | 12.0 ± 0.6 | 11.1 | 16.9 | 8.07 ± 3.08 |
| `aspidites-solver/aoc -i input-pting -d 2` | 13.3 ± 1.1 | 11.6 | 18.1 | 8.95 ± 3.46 |
| `kcen/2022/02/solve input-aspidites` | 4.6 ± 1.3 | 3.0 | 21.0 | 3.12 ± 1.45 |
| `kcen/2022/02/solve input-kcen` | 5.1 ± 1.7 | 2.6 | 15.8 | 3.40 ± 1.72 |
| `kcen/2022/02/solve input-lanjian` | 4.9 ± 1.7 | 2.8 | 15.0 | 3.28 ± 1.70 |
| `kcen/2022/02/solve input-mattcl` | 4.3 ± 1.0 | 2.7 | 10.2 | 2.88 ± 1.27 |
| `kcen/2022/02/solve input-pting` | 4.1 ± 0.8 | 2.9 | 11.8 | 2.75 ± 1.19 |
| `lanjian/day_02 input-aspidites` | 2.4 ± 0.8 | 1.1 | 8.1 | 1.63 ± 0.80 |
| `lanjian/day_02 input-kcen` | 2.2 ± 0.8 | 1.2 | 11.7 | 1.49 ± 0.76 |
| `lanjian/day_02 input-lanjian` | 1.6 ± 0.5 | 1.0 | 4.4 | 1.11 ± 0.54 |
| `lanjian/day_02 input-mattcl` | 1.8 ± 0.6 | 1.1 | 9.4 | 1.24 ± 0.63 |
| `lanjian/day_02 input-pting` | 1.9 ± 0.6 | 1.0 | 5.0 | 1.28 ± 0.62 |
| `mattcl-solver/aoc run 2 input-aspidites` | 1.5 ± 0.5 | 0.8 | 6.0 | 1.03 ± 0.53 |
| `mattcl-solver/aoc run 2 input-kcen` | 1.5 ± 0.5 | 0.9 | 4.5 | 1.01 ± 0.51 |
| `mattcl-solver/aoc run 2 input-lanjian` | 1.5 ± 0.6 | 1.0 | 8.7 | 1.00 |
| `mattcl-solver/aoc run 2 input-mattcl` | 1.7 ± 0.6 | 0.9 | 5.8 | 1.12 ± 0.59 |
| `mattcl-solver/aoc run 2 input-pting` | 1.9 ± 0.5 | 0.9 | 4.1 | 1.25 ± 0.59 |
| `python pting/day02.py input-aspidites` | 35.8 ± 5.8 | 28.4 | 67.7 | 24.08 ± 9.89 |
| `python pting/day02.py input-kcen` | 40.1 ± 12.2 | 28.0 | 103.8 | 26.94 ± 13.06 |
| `python pting/day02.py input-lanjian` | 35.6 ± 6.1 | 28.0 | 67.9 | 23.94 ± 9.94 |
| `python pting/day02.py input-mattcl` | 36.3 ± 7.3 | 28.4 | 65.6 | 24.42 ± 10.44 |
| `python pting/day02.py input-pting` | 33.3 ± 3.2 | 28.0 | 47.1 | 22.36 ± 8.72 |
