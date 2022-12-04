# Day 1 benchmarks

[link to problem](http://adventofcode.com/2022/day/1)

The following benchmarks are auto-generated via [hyperfine](https://github.com/sharkdp/hyperfine) by a ci system running on shared hardware. Results may be inaccurate, particularly for execution times < 5ms, as per the hyperfine warnings.

The "official" inputs were aggregated from repositories participating in the generation of these benchmarks. The "large" inputs (if any) were sourced from various places, including the subreddit.

## Benchmarks with officially generated inputs
| Command | Mean [ms] | Min [ms] | Max [ms] | Relative |
|:---|---:|---:|---:|---:|
| `aspidites-solver/aoc -i input-aspidites -d 1` | 8.5 ± 0.9 | 6.8 | 13.1 | 5.29 ± 1.54 |
| `aspidites-solver/aoc -i input-kcen -d 1` | 8.9 ± 1.5 | 6.5 | 13.6 | 5.57 ± 1.79 |
| `aspidites-solver/aoc -i input-lanjian -d 1` | 9.1 ± 1.4 | 7.3 | 13.8 | 5.69 ± 1.77 |
| `aspidites-solver/aoc -i input-mattcl -d 1` | 8.6 ± 1.6 | 6.5 | 15.9 | 5.37 ± 1.76 |
| `aspidites-solver/aoc -i input-pting -d 1` | 9.4 ± 2.9 | 6.9 | 32.7 | 5.89 ± 2.40 |
| `kcen/2022/01/solve input-aspidites` | 212.6 ± 17.2 | 194.6 | 250.6 | 132.77 ± 37.71 |
| `kcen/2022/01/solve input-kcen` | 226.8 ± 16.8 | 206.2 | 261.8 | 141.58 ± 39.95 |
| `kcen/2022/01/solve input-lanjian` | 231.8 ± 22.6 | 200.9 | 274.8 | 144.72 ± 41.84 |
| `kcen/2022/01/solve input-mattcl` | 217.7 ± 26.0 | 189.5 | 274.7 | 135.93 ± 40.41 |
| `kcen/2022/01/solve input-pting` | 235.6 ± 31.1 | 192.4 | 312.2 | 147.13 ± 44.52 |
| `lanjian/day_01 input-aspidites` | 1.8 ± 0.5 | 1.0 | 4.6 | 1.11 ± 0.43 |
| `lanjian/day_01 input-kcen` | 1.6 ± 0.5 | 1.0 | 4.6 | 1.02 ± 0.43 |
| `lanjian/day_01 input-lanjian` | 1.6 ± 0.6 | 0.9 | 10.6 | 1.01 ± 0.45 |
| `lanjian/day_01 input-mattcl` | 1.8 ± 1.0 | 0.9 | 12.8 | 1.12 ± 0.72 |
| `lanjian/day_01 input-pting` | 2.0 ± 0.6 | 1.0 | 7.9 | 1.22 ± 0.52 |
| `mattcl-solver/aoc run 1 input-aspidites` | 1.6 ± 0.5 | 0.8 | 5.4 | 1.02 ± 0.42 |
| `mattcl-solver/aoc run 1 input-kcen` | 1.6 ± 0.6 | 0.8 | 6.3 | 1.01 ± 0.45 |
| `mattcl-solver/aoc run 1 input-lanjian` | 1.6 ± 1.0 | 0.8 | 9.0 | 1.02 ± 0.66 |
| `mattcl-solver/aoc run 1 input-mattcl` | 2.0 ± 1.1 | 0.8 | 16.7 | 1.24 ± 0.77 |
| `mattcl-solver/aoc run 1 input-pting` | 1.6 ± 0.4 | 0.8 | 4.5 | 1.00 |
| `python pting/day01.py input-aspidites` | 36.0 ± 5.3 | 28.6 | 56.5 | 22.51 ± 6.97 |
| `python pting/day01.py input-kcen` | 39.7 ± 8.9 | 29.5 | 74.9 | 24.76 ± 8.75 |
| `python pting/day01.py input-lanjian` | 34.3 ± 3.7 | 28.7 | 45.4 | 21.43 ± 6.27 |
| `python pting/day01.py input-mattcl` | 34.8 ± 3.2 | 29.4 | 43.8 | 21.71 ± 6.23 |
| `python pting/day01.py input-pting` | 35.3 ± 4.4 | 29.4 | 55.1 | 22.06 ± 6.61 |
