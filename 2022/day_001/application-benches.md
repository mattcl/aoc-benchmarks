# Day 1 benchmarks

[link to problem](http://adventofcode.com/2022/day/1)

The following benchmarks are auto-generated via [hyperfine](https://github.com/sharkdp/hyperfine) by a ci system running on shared hardware. Results may be inaccurate, particularly for execution times < 5ms, as per the hyperfine warnings.

The "official" inputs were aggregated from repositories participating in the generation of these benchmarks. The "large" inputs (if any) were sourced from various places, including the subreddit.

## Benchmarks with officially generated inputs
| Command | Mean [ms] | Min [ms] | Max [ms] | Relative |
|:---|---:|---:|---:|---:|
| `aspidites-solver/aoc -i input-aspidites -d 1` | 9.0 ± 3.0 | 6.8 | 36.0 | 8.74 ± 5.06 |
| `aspidites-solver/aoc -i input-kcen -d 1` | 8.1 ± 1.4 | 6.2 | 17.9 | 7.85 ± 3.97 |
| `aspidites-solver/aoc -i input-lanjian -d 1` | 7.9 ± 1.5 | 5.9 | 19.9 | 7.65 ± 3.90 |
| `aspidites-solver/aoc -i input-mattcl -d 1` | 7.5 ± 1.1 | 6.1 | 12.3 | 7.33 ± 3.62 |
| `aspidites-solver/aoc -i input-pting -d 1` | 7.6 ± 1.0 | 5.9 | 11.9 | 7.43 ± 3.65 |
| `kcen/2022/01/solve input-aspidites` | 206.3 ± 13.9 | 189.4 | 243.3 | 200.92 ± 96.00 |
| `kcen/2022/01/solve input-kcen` | 205.9 ± 21.3 | 177.9 | 248.4 | 200.55 ± 97.12 |
| `kcen/2022/01/solve input-lanjian` | 202.1 ± 17.0 | 179.0 | 228.0 | 196.84 ± 94.58 |
| `kcen/2022/01/solve input-mattcl` | 212.9 ± 14.7 | 182.3 | 236.5 | 207.38 ± 99.14 |
| `kcen/2022/01/solve input-pting` | 193.5 ± 8.2 | 181.5 | 214.8 | 188.46 ± 89.51 |
| `lanjian/day_01 input-aspidites` | 1.4 ± 0.5 | 0.7 | 6.0 | 1.32 ± 0.77 |
| `lanjian/day_01 input-kcen` | 1.3 ± 0.4 | 0.7 | 4.6 | 1.29 ± 0.74 |
| `lanjian/day_01 input-lanjian` | 1.2 ± 0.4 | 0.7 | 5.9 | 1.21 ± 0.70 |
| `lanjian/day_01 input-mattcl` | 1.7 ± 0.6 | 0.8 | 7.3 | 1.63 ± 0.95 |
| `lanjian/day_01 input-pting` | 1.4 ± 0.5 | 0.7 | 5.6 | 1.40 ± 0.81 |
| `mattcl-solver/aoc run 1 input-aspidites` | 1.0 ± 0.5 | 0.5 | 7.9 | 1.00 |
| `mattcl-solver/aoc run 1 input-kcen` | 1.2 ± 0.5 | 0.6 | 5.7 | 1.17 ± 0.74 |
| `mattcl-solver/aoc run 1 input-lanjian` | 1.3 ± 0.7 | 0.5 | 7.1 | 1.24 ± 0.88 |
| `mattcl-solver/aoc run 1 input-mattcl` | 1.1 ± 0.5 | 0.4 | 9.1 | 1.06 ± 0.71 |
| `mattcl-solver/aoc run 1 input-pting` | 2.0 ± 1.6 | 0.6 | 17.5 | 1.92 ± 1.84 |
| `python pting/day01.py input-aspidites` | 34.8 ± 4.4 | 28.3 | 50.6 | 33.90 ± 16.60 |
| `python pting/day01.py input-kcen` | 35.1 ± 6.1 | 27.6 | 61.4 | 34.22 ± 17.24 |
| `python pting/day01.py input-lanjian` | 31.7 ± 2.9 | 27.7 | 41.3 | 30.90 ± 14.88 |
| `python pting/day01.py input-mattcl` | 35.5 ± 4.6 | 28.7 | 47.4 | 34.61 ± 16.97 |
| `python pting/day01.py input-pting` | 32.9 ± 3.3 | 28.2 | 42.8 | 32.06 ± 15.51 |
