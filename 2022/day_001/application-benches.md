# Day 1 benchmarks

[link to problem](http://adventofcode.com/2022/day/1)

The following benchmarks are auto-generated via [hyperfine](https://github.com/sharkdp/hyperfine) by a ci system running on shared hardware. Results may be inaccurate, particularly for execution times < 5ms, as per the hyperfine warnings.

The "official" inputs were aggregated from repositories participating in the generation of these benchmarks. The "large" inputs (if any) were sourced from various places, including the subreddit.

## Benchmarks with officially generated inputs
| Command | Mean [ms] | Min [ms] | Max [ms] | Relative |
|:---|---:|---:|---:|---:|
| `aspidites-solver/aoc -i input-aspidites -d 1` | 6.4 ± 1.0 | 5.2 | 19.0 | 9.12 ± 4.14 |
| `aspidites-solver/aoc -i input-kcen -d 1` | 7.6 ± 1.0 | 5.9 | 11.7 | 10.83 ± 4.83 |
| `aspidites-solver/aoc -i input-lanjian -d 1` | 6.8 ± 1.2 | 5.4 | 16.7 | 9.63 ± 4.45 |
| `aspidites-solver/aoc -i input-mattcl -d 1` | 7.0 ± 0.8 | 5.9 | 13.6 | 9.92 ± 4.37 |
| `aspidites-solver/aoc -i input-pting -d 1` | 7.2 ± 1.0 | 5.8 | 14.2 | 10.19 ± 4.55 |
| `kcen/2022/01/solve.sh input-aspidites` | 194.3 ± 8.4 | 178.1 | 209.1 | 275.38 ± 118.06 |
| `kcen/2022/01/solve.sh input-kcen` | 220.8 ± 28.0 | 190.8 | 271.8 | 312.99 ± 139.26 |
| `kcen/2022/01/solve.sh input-lanjian` | 189.6 ± 13.4 | 169.6 | 216.4 | 268.77 ± 116.21 |
| `kcen/2022/01/solve.sh input-mattcl` | 190.3 ± 10.6 | 175.0 | 206.2 | 269.75 ± 116.04 |
| `kcen/2022/01/solve.sh input-pting` | 198.8 ± 11.5 | 184.8 | 228.4 | 281.70 ± 121.26 |
| `lanjian/day_01 input-aspidites` | 1.0 ± 0.3 | 0.6 | 3.8 | 1.39 ± 0.71 |
| `lanjian/day_01 input-kcen` | 1.2 ± 0.4 | 0.6 | 3.3 | 1.77 ± 0.91 |
| `lanjian/day_01 input-lanjian` | 1.1 ± 0.4 | 0.6 | 4.1 | 1.62 ± 0.89 |
| `lanjian/day_01 input-mattcl` | 1.3 ± 0.6 | 0.5 | 7.8 | 1.83 ± 1.21 |
| `lanjian/day_01 input-pting` | 1.0 ± 0.3 | 0.6 | 3.7 | 1.45 ± 0.73 |
| `mattcl-solver/aoc run 1 input-aspidites` | 0.8 ± 0.3 | 0.4 | 3.4 | 1.19 ± 0.64 |
| `mattcl-solver/aoc run 1 input-kcen` | 1.0 ± 0.5 | 0.3 | 6.5 | 1.36 ± 0.90 |
| `mattcl-solver/aoc run 1 input-lanjian` | 0.7 ± 0.3 | 0.4 | 2.8 | 1.00 |
| `mattcl-solver/aoc run 1 input-mattcl` | 1.0 ± 0.5 | 0.4 | 6.3 | 1.36 ± 0.92 |
| `mattcl-solver/aoc run 1 input-pting` | 1.2 ± 0.9 | 0.4 | 12.5 | 1.66 ± 1.48 |
| `python pting/day01.py input-aspidites` | 31.3 ± 4.3 | 26.0 | 46.9 | 44.30 ± 19.83 |
| `python pting/day01.py input-kcen` | 32.1 ± 3.8 | 27.1 | 47.0 | 45.45 ± 20.13 |
| `python pting/day01.py input-lanjian` | 31.1 ± 3.6 | 26.0 | 49.7 | 44.12 ± 19.49 |
| `python pting/day01.py input-mattcl` | 31.6 ± 2.3 | 27.2 | 37.9 | 44.78 ± 19.38 |
| `python pting/day01.py input-pting` | 34.1 ± 5.7 | 28.2 | 54.8 | 48.32 ± 22.15 |
