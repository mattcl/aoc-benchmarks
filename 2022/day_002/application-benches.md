# Day 2 benchmarks

[link to problem](http://adventofcode.com/2022/day/2)

The following benchmarks are auto-generated via [hyperfine](https://github.com/sharkdp/hyperfine) by a ci system running on shared hardware. Results may be inaccurate, particularly for execution times < 5ms, as per the hyperfine warnings.

The "official" inputs were aggregated from repositories participating in the generation of these benchmarks. The "large" inputs (if any) were sourced from various places, including the subreddit.

## Benchmarks with officially generated inputs
| Command | Mean [ms] | Min [ms] | Max [ms] | Relative |
|:---|---:|---:|---:|---:|
| `aspidites-solver/aoc -i input-aspidites -d 2` | 57.3 ± 3.2 | 52.9 | 66.9 | 38.71 ± 13.03 |
| `aspidites-solver/aoc -i input-kcen -d 2` | 58.6 ± 6.2 | 52.2 | 83.8 | 39.57 ± 13.78 |
| `aspidites-solver/aoc -i input-lanjian -d 2` | 62.5 ± 6.0 | 53.6 | 77.8 | 42.17 ± 14.58 |
| `aspidites-solver/aoc -i input-mattcl -d 2` | 66.0 ± 9.6 | 55.9 | 94.1 | 44.57 ± 16.16 |
| `aspidites-solver/aoc -i input-pting -d 2` | 56.1 ± 4.5 | 51.4 | 73.1 | 37.87 ± 12.92 |
| `kcen/2022/02/solve.sh input-aspidites` | 227.6 ± 28.0 | 196.3 | 301.7 | 153.70 ± 54.40 |
| `kcen/2022/02/solve.sh input-kcen` | 235.9 ± 38.3 | 202.3 | 345.7 | 159.27 ± 58.87 |
| `kcen/2022/02/solve.sh input-lanjian` | 226.2 ± 10.0 | 210.2 | 246.7 | 152.76 ± 51.15 |
| `kcen/2022/02/solve.sh input-mattcl` | 229.4 ± 27.7 | 198.0 | 308.0 | 154.88 ± 54.72 |
| `kcen/2022/02/solve.sh input-pting` | 221.4 ± 46.5 | 191.8 | 368.4 | 149.47 ± 58.71 |
| `lanjian/day_02 input-aspidites` | 1.7 ± 0.4 | 1.0 | 3.9 | 1.18 ± 0.49 |
| `lanjian/day_02 input-kcen` | 1.9 ± 0.5 | 1.0 | 4.9 | 1.30 ± 0.56 |
| `lanjian/day_02 input-lanjian` | 2.0 ± 0.5 | 1.1 | 5.0 | 1.33 ± 0.54 |
| `lanjian/day_02 input-mattcl` | 1.8 ± 0.6 | 1.0 | 6.2 | 1.21 ± 0.58 |
| `lanjian/day_02 input-pting` | 1.9 ± 0.7 | 1.0 | 10.2 | 1.27 ± 0.62 |
| `mattcl-solver/aoc run 2 input-aspidites` | 1.5 ± 0.5 | 0.7 | 4.0 | 1.00 |
| `mattcl-solver/aoc run 2 input-kcen` | 1.5 ± 0.5 | 0.7 | 6.7 | 1.03 ± 0.49 |
| `mattcl-solver/aoc run 2 input-lanjian` | 1.8 ± 0.5 | 0.8 | 6.6 | 1.21 ± 0.51 |
| `mattcl-solver/aoc run 2 input-mattcl` | 1.6 ± 0.7 | 0.7 | 9.5 | 1.10 ± 0.58 |
| `mattcl-solver/aoc run 2 input-pting` | 1.6 ± 0.5 | 0.8 | 6.1 | 1.05 ± 0.48 |
| `python pting/day02.py input-aspidites` | 35.4 ± 4.9 | 27.4 | 47.8 | 23.90 ± 8.58 |
| `python pting/day02.py input-kcen` | 36.3 ± 4.4 | 30.6 | 54.0 | 24.51 ± 8.67 |
| `python pting/day02.py input-lanjian` | 37.0 ± 5.4 | 29.7 | 51.1 | 24.97 ± 9.05 |
| `python pting/day02.py input-mattcl` | 35.2 ± 5.9 | 28.8 | 55.3 | 23.76 ± 8.82 |
| `python pting/day02.py input-pting` | 36.1 ± 5.7 | 29.2 | 59.9 | 24.36 ± 8.95 |
