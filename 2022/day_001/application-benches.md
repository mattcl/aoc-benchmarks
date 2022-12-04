# Day 1 benchmarks

[link to problem](http://adventofcode.com/2022/day/1)

The following benchmarks are auto-generated via [hyperfine](https://github.com/sharkdp/hyperfine) by a ci system running on shared hardware. Results may be inaccurate, particularly for execution times < 5ms, as per the hyperfine warnings.

The "official" inputs were aggregated from repositories participating in the generation of these benchmarks. The "large" inputs (if any) were sourced from various places, including the subreddit.

## Benchmarks with officially generated inputs
| Command | Mean [ms] | Min [ms] | Max [ms] | Relative |
|:---|---:|---:|---:|---:|
| `aspidites-solver/aoc -i input-aspidites -d 1` | 8.2 ± 1.5 | 6.0 | 19.7 | 12.42 ± 7.09 |
| `aspidites-solver/aoc -i input-kcen -d 1` | 7.2 ± 1.6 | 5.2 | 14.1 | 10.96 ± 6.39 |
| `aspidites-solver/aoc -i input-lanjian -d 1` | 7.2 ± 1.0 | 6.0 | 14.7 | 10.92 ± 6.11 |
| `aspidites-solver/aoc -i input-mattcl -d 1` | 7.7 ± 1.0 | 6.1 | 12.4 | 11.70 ± 6.52 |
| `aspidites-solver/aoc -i input-pting -d 1` | 8.1 ± 2.1 | 5.9 | 26.8 | 12.27 ± 7.37 |
| `kcen/2022/01/solve.sh input-aspidites` | 206.5 ± 22.1 | 188.1 | 255.7 | 314.23 ± 173.54 |
| `kcen/2022/01/solve.sh input-kcen` | 215.7 ± 13.5 | 200.2 | 244.9 | 328.24 ± 179.04 |
| `kcen/2022/01/solve.sh input-lanjian` | 206.5 ± 13.6 | 187.9 | 229.3 | 314.31 ± 171.56 |
| `kcen/2022/01/solve.sh input-mattcl` | 220.4 ± 17.6 | 196.1 | 255.9 | 335.42 ± 183.71 |
| `kcen/2022/01/solve.sh input-pting` | 211.9 ± 9.0 | 200.1 | 226.5 | 322.55 ± 175.30 |
| `lanjian/day_01 input-aspidites` | 1.3 ± 0.6 | 0.4 | 10.6 | 1.91 ± 1.36 |
| `lanjian/day_01 input-kcen` | 1.5 ± 0.6 | 0.4 | 4.7 | 2.26 ± 1.49 |
| `lanjian/day_01 input-lanjian` | 1.1 ± 0.5 | 0.3 | 8.1 | 1.65 ± 1.14 |
| `lanjian/day_01 input-mattcl` | 1.2 ± 0.9 | 0.3 | 15.4 | 1.78 ± 1.67 |
| `lanjian/day_01 input-pting` | 1.5 ± 0.6 | 0.3 | 8.0 | 2.28 ± 1.54 |
| `mattcl-solver/aoc run 1 input-aspidites` | 1.2 ± 0.6 | 0.2 | 7.7 | 1.82 ± 1.39 |
| `mattcl-solver/aoc run 1 input-kcen` | 1.3 ± 1.2 | 0.2 | 19.6 | 2.01 ± 2.07 |
| `mattcl-solver/aoc run 1 input-lanjian` | 0.9 ± 0.7 | 0.1 | 12.3 | 1.39 ± 1.36 |
| `mattcl-solver/aoc run 1 input-mattcl` | 0.7 ± 0.4 | 0.2 | 3.2 | 1.00 |
| `mattcl-solver/aoc run 1 input-pting` | 1.2 ± 0.5 | 0.2 | 3.8 | 1.80 ± 1.20 |
| `python pting/day01.py input-aspidites` | 32.4 ± 3.5 | 28.5 | 44.3 | 49.25 ± 27.20 |
| `python pting/day01.py input-kcen` | 34.6 ± 4.0 | 29.3 | 47.2 | 52.66 ± 29.16 |
| `python pting/day01.py input-lanjian` | 32.6 ± 3.3 | 28.0 | 43.9 | 49.60 ± 27.35 |
| `python pting/day01.py input-mattcl` | 37.0 ± 4.3 | 28.0 | 45.5 | 56.36 ± 31.23 |
| `python pting/day01.py input-pting` | 35.8 ± 5.4 | 27.1 | 52.0 | 54.48 ± 30.66 |
