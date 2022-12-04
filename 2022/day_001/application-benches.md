# Day 1 benchmarks

[link to problem](http://adventofcode.com/2022/day/1)

The following benchmarks are auto-generated via [hyperfine](https://github.com/sharkdp/hyperfine) by a ci system running on shared hardware. Results may be inaccurate, particularly for execution times < 5ms, as per the hyperfine warnings.

The "official" inputs were aggregated from repositories participating in the generation of these benchmarks. The "large" inputs (if any) were sourced from various places, including the subreddit.

## Benchmarks with officially generated inputs
| Command | Mean [ms] | Min [ms] | Max [ms] | Relative |
|:---|---:|---:|---:|---:|
| `aspidites-solver/aoc -i input-aspidites -d 1` | 7.7 ± 1.9 | 5.3 | 15.4 | 6.71 ± 3.42 |
| `aspidites-solver/aoc -i input-kcen -d 1` | 9.2 ± 2.6 | 5.9 | 17.2 | 8.06 ± 4.28 |
| `aspidites-solver/aoc -i input-lanjian -d 1` | 9.1 ± 2.2 | 6.4 | 15.8 | 7.93 ± 4.04 |
| `aspidites-solver/aoc -i input-mattcl -d 1` | 8.5 ± 2.0 | 5.7 | 20.4 | 7.43 ± 3.77 |
| `aspidites-solver/aoc -i input-pting -d 1` | 8.6 ± 1.9 | 6.1 | 17.1 | 7.52 ± 3.74 |
| `kcen/2022/01/solve.sh input-aspidites` | 227.8 ± 27.2 | 181.0 | 261.7 | 198.78 ± 92.11 |
| `kcen/2022/01/solve.sh input-kcen` | 217.8 ± 25.9 | 181.1 | 266.8 | 190.03 ± 88.01 |
| `kcen/2022/01/solve.sh input-lanjian` | 219.9 ± 23.1 | 196.9 | 279.7 | 191.94 ± 88.25 |
| `kcen/2022/01/solve.sh input-mattcl` | 220.6 ± 21.8 | 183.3 | 270.9 | 192.52 ± 88.26 |
| `kcen/2022/01/solve.sh input-pting` | 248.0 ± 28.7 | 202.1 | 292.8 | 216.43 ± 100.07 |
| `lanjian/day_01 input-aspidites` | 1.6 ± 0.8 | 0.6 | 8.4 | 1.39 ± 0.90 |
| `lanjian/day_01 input-kcen` | 1.8 ± 0.9 | 0.7 | 12.9 | 1.57 ± 1.07 |
| `lanjian/day_01 input-lanjian` | 1.7 ± 1.2 | 0.5 | 15.9 | 1.49 ± 1.22 |
| `lanjian/day_01 input-mattcl` | 2.0 ± 1.1 | 0.7 | 15.1 | 1.78 ± 1.23 |
| `lanjian/day_01 input-pting` | 1.5 ± 0.9 | 0.6 | 9.0 | 1.35 ± 0.97 |
| `mattcl-solver/aoc run 1 input-aspidites` | 1.3 ± 0.7 | 0.4 | 5.6 | 1.13 ± 0.77 |
| `mattcl-solver/aoc run 1 input-kcen` | 1.8 ± 0.8 | 0.4 | 6.9 | 1.59 ± 1.00 |
| `mattcl-solver/aoc run 1 input-lanjian` | 1.7 ± 0.7 | 0.5 | 5.6 | 1.46 ± 0.88 |
| `mattcl-solver/aoc run 1 input-mattcl` | 1.2 ± 0.6 | 0.4 | 4.7 | 1.09 ± 0.69 |
| `mattcl-solver/aoc run 1 input-pting` | 1.1 ± 0.5 | 0.4 | 5.4 | 1.00 |
| `python pting/day01.py input-aspidites` | 37.8 ± 10.4 | 26.8 | 83.4 | 32.97 ± 17.32 |
| `python pting/day01.py input-kcen` | 43.2 ± 17.9 | 27.1 | 132.9 | 37.69 ± 22.99 |
| `python pting/day01.py input-lanjian` | 40.0 ± 9.1 | 26.6 | 75.9 | 34.91 ± 17.52 |
| `python pting/day01.py input-mattcl` | 38.0 ± 7.7 | 28.7 | 66.1 | 33.16 ± 16.31 |
| `python pting/day01.py input-pting` | 40.0 ± 8.3 | 31.2 | 73.0 | 34.88 ± 17.22 |
