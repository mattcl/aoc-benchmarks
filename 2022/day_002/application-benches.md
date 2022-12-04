# Day 2 benchmarks

[link to problem](http://adventofcode.com/2022/day/2)

The following benchmarks are auto-generated via [hyperfine](https://github.com/sharkdp/hyperfine) by a ci system running on shared hardware. Results may be inaccurate, particularly for execution times < 5ms, as per the hyperfine warnings.

The "official" inputs were aggregated from repositories participating in the generation of these benchmarks. The "large" inputs (if any) were sourced from various places, including the subreddit.

## Benchmarks with officially generated inputs
| Command | Mean [ms] | Min [ms] | Max [ms] | Relative |
|:---|---:|---:|---:|---:|
| `aspidites-solver/aoc -i input-aspidites -d 2` | 55.5 ± 3.3 | 51.0 | 67.7 | 46.35 ± 13.31 |
| `aspidites-solver/aoc -i input-kcen -d 2` | 53.9 ± 3.0 | 50.1 | 66.0 | 44.96 ± 12.87 |
| `aspidites-solver/aoc -i input-lanjian -d 2` | 57.3 ± 4.5 | 52.8 | 75.4 | 47.83 ± 13.96 |
| `aspidites-solver/aoc -i input-mattcl -d 2` | 69.4 ± 29.1 | 54.3 | 214.6 | 57.96 ± 29.23 |
| `aspidites-solver/aoc -i input-pting -d 2` | 61.1 ± 5.8 | 53.2 | 79.2 | 51.02 ± 15.14 |
| `kcen/2022/02/solve.sh input-aspidites` | 220.1 ± 25.0 | 182.4 | 262.1 | 183.70 ± 55.67 |
| `kcen/2022/02/solve.sh input-kcen` | 232.6 ± 21.0 | 203.7 | 270.6 | 194.17 ± 57.30 |
| `kcen/2022/02/solve.sh input-lanjian` | 213.3 ± 24.8 | 192.3 | 280.1 | 178.02 ± 54.12 |
| `kcen/2022/02/solve.sh input-mattcl` | 249.5 ± 27.6 | 216.0 | 311.9 | 208.29 ± 62.90 |
| `kcen/2022/02/solve.sh input-pting` | 213.9 ± 25.5 | 185.1 | 265.9 | 178.55 ± 54.48 |
| `lanjian/day_02 input-aspidites` | 1.4 ± 0.8 | 0.7 | 11.4 | 1.17 ± 0.73 |
| `lanjian/day_02 input-kcen` | 1.6 ± 0.6 | 0.9 | 7.1 | 1.35 ± 0.60 |
| `lanjian/day_02 input-lanjian` | 1.8 ± 0.6 | 0.9 | 10.4 | 1.47 ± 0.66 |
| `lanjian/day_02 input-mattcl` | 1.8 ± 0.5 | 1.0 | 6.6 | 1.48 ± 0.61 |
| `lanjian/day_02 input-pting` | 1.7 ± 0.7 | 0.7 | 7.9 | 1.39 ± 0.73 |
| `mattcl-solver/aoc run 2 input-aspidites` | 1.2 ± 0.3 | 0.6 | 3.0 | 1.00 |
| `mattcl-solver/aoc run 2 input-kcen` | 1.3 ± 0.5 | 0.6 | 3.8 | 1.05 ± 0.54 |
| `mattcl-solver/aoc run 2 input-lanjian` | 1.7 ± 0.6 | 0.8 | 7.4 | 1.38 ± 0.61 |
| `mattcl-solver/aoc run 2 input-mattcl` | 1.5 ± 0.6 | 0.6 | 6.8 | 1.22 ± 0.59 |
| `mattcl-solver/aoc run 2 input-pting` | 2.1 ± 0.8 | 0.6 | 6.8 | 1.73 ± 0.86 |
| `python pting/day02.py input-aspidites` | 34.4 ± 3.6 | 28.1 | 50.2 | 28.67 ± 8.60 |
| `python pting/day02.py input-kcen` | 32.3 ± 3.9 | 27.0 | 45.0 | 26.97 ± 8.24 |
| `python pting/day02.py input-lanjian` | 35.0 ± 3.8 | 28.7 | 47.3 | 29.18 ± 8.79 |
| `python pting/day02.py input-mattcl` | 33.8 ± 4.1 | 28.0 | 47.7 | 28.21 ± 8.64 |
| `python pting/day02.py input-pting` | 34.6 ± 4.6 | 27.3 | 50.5 | 28.91 ± 8.98 |
