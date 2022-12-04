# Day 1 benchmarks

[link to problem](http://adventofcode.com/2022/day/1)

The following benchmarks are auto-generated via [hyperfine](https://github.com/sharkdp/hyperfine) by a ci system running on shared hardware. Results may be inaccurate, particularly for execution times < 5ms, as per the hyperfine warnings.

The "official" inputs were aggregated from repositories participating in the generation of these benchmarks. The "large" inputs (if any) were sourced from various places, including the subreddit.

## Benchmarks with officially generated inputs
| Command | Mean [ms] | Min [ms] | Max [ms] | Relative |
|:---|---:|---:|---:|---:|
| `aspidites-solver/aoc -i input-aspidites -d 1` | 9.0 ± 1.3 | 7.0 | 18.0 | 5.39 ± 2.14 |
| `aspidites-solver/aoc -i input-kcen -d 1` | 9.5 ± 2.0 | 7.1 | 24.8 | 5.68 ± 2.41 |
| `aspidites-solver/aoc -i input-lanjian -d 1` | 8.9 ± 1.5 | 6.7 | 19.8 | 5.33 ± 2.17 |
| `aspidites-solver/aoc -i input-mattcl -d 1` | 8.6 ± 1.4 | 6.8 | 20.0 | 5.17 ± 2.08 |
| `aspidites-solver/aoc -i input-pting -d 1` | 8.6 ± 1.1 | 6.9 | 14.0 | 5.16 ± 2.00 |
| `kcen/2022/01/solve.sh input-aspidites` | 222.3 ± 34.2 | 189.3 | 316.2 | 132.99 ± 53.01 |
| `kcen/2022/01/solve.sh input-kcen` | 216.0 ± 25.9 | 186.1 | 283.1 | 129.22 ± 49.98 |
| `kcen/2022/01/solve.sh input-lanjian` | 214.5 ± 30.1 | 190.2 | 291.4 | 128.35 ± 50.51 |
| `kcen/2022/01/solve.sh input-mattcl` | 215.4 ± 9.6 | 198.3 | 233.4 | 128.92 ± 47.76 |
| `kcen/2022/01/solve.sh input-pting` | 212.7 ± 23.8 | 187.0 | 265.6 | 127.29 ± 48.93 |
| `lanjian/day_01 input-aspidites` | 1.9 ± 0.6 | 1.0 | 12.4 | 1.13 ± 0.55 |
| `lanjian/day_01 input-kcen` | 1.7 ± 0.6 | 0.9 | 4.8 | 1.03 ± 0.52 |
| `lanjian/day_01 input-lanjian` | 1.9 ± 0.7 | 0.9 | 7.3 | 1.16 ± 0.58 |
| `lanjian/day_01 input-mattcl` | 1.7 ± 0.6 | 0.8 | 6.8 | 1.00 |
| `lanjian/day_01 input-pting` | 2.1 ± 0.5 | 1.0 | 4.9 | 1.23 ± 0.55 |
| `mattcl-solver/aoc run 1 input-aspidites` | 1.7 ± 0.5 | 0.9 | 4.9 | 1.05 ± 0.47 |
| `mattcl-solver/aoc run 1 input-kcen` | 1.7 ± 0.8 | 0.7 | 9.6 | 1.01 ± 0.58 |
| `mattcl-solver/aoc run 1 input-lanjian` | 1.8 ± 1.1 | 0.7 | 21.8 | 1.07 ± 0.76 |
| `mattcl-solver/aoc run 1 input-mattcl` | 1.7 ± 0.7 | 0.8 | 11.8 | 1.02 ± 0.55 |
| `mattcl-solver/aoc run 1 input-pting` | 1.7 ± 0.7 | 0.8 | 12.2 | 1.04 ± 0.55 |
| `python pting/day01.py input-aspidites` | 37.0 ± 4.9 | 29.9 | 51.5 | 22.16 ± 8.66 |
| `python pting/day01.py input-kcen` | 32.9 ± 3.6 | 27.5 | 43.9 | 19.71 ± 7.55 |
| `python pting/day01.py input-lanjian` | 34.9 ± 3.7 | 29.2 | 45.8 | 20.87 ± 7.99 |
| `python pting/day01.py input-mattcl` | 37.0 ± 4.8 | 28.9 | 54.2 | 22.15 ± 8.63 |
| `python pting/day01.py input-pting` | 36.7 ± 5.0 | 30.0 | 52.9 | 21.98 ± 8.62 |
