# Day 2 benchmarks

[link to problem](http://adventofcode.com/2022/day/2)

The following benchmarks are auto-generated via [hyperfine](https://github.com/sharkdp/hyperfine) by a ci system running on shared hardware. Results may be inaccurate, particularly for execution times < 5ms, as per the hyperfine warnings.

The "official" inputs were aggregated from repositories participating in the generation of these benchmarks. The "large" inputs (if any) were sourced from various places, including the subreddit.

## Benchmarks with officially generated inputs
| Command | Mean [ms] | Min [ms] | Max [ms] | Relative |
|:---|---:|---:|---:|---:|
| `aspidites-solver/aoc -i input-aspidites -d 2` | 12.4 ± 0.5 | 11.6 | 14.1 | 8.52 ± 2.53 |
| `aspidites-solver/aoc -i input-kcen -d 2` | 12.5 ± 0.9 | 11.5 | 18.2 | 8.58 ± 2.60 |
| `aspidites-solver/aoc -i input-lanjian -d 2` | 12.5 ± 0.8 | 11.8 | 20.4 | 8.62 ± 2.59 |
| `aspidites-solver/aoc -i input-mattcl -d 2` | 12.7 ± 0.7 | 11.7 | 17.4 | 8.72 ± 2.61 |
| `aspidites-solver/aoc -i input-pting -d 2` | 12.7 ± 1.1 | 11.7 | 23.3 | 8.69 ± 2.67 |
| `kcen/2022/02/solve input-aspidites` | 1.6 ± 0.5 | 0.9 | 6.9 | 1.07 ± 0.46 |
| `kcen/2022/02/solve input-kcen` | 1.5 ± 0.4 | 0.9 | 4.5 | 1.00 |
| `kcen/2022/02/solve input-lanjian` | 1.5 ± 0.4 | 0.8 | 3.6 | 1.05 ± 0.42 |
| `kcen/2022/02/solve input-mattcl` | 2.0 ± 1.0 | 1.0 | 25.4 | 1.35 ± 0.78 |
| `kcen/2022/02/solve input-pting` | 1.8 ± 0.5 | 1.0 | 4.8 | 1.27 ± 0.50 |
| `lanjian/day_02 input-aspidites` | 1.9 ± 0.5 | 1.2 | 7.0 | 1.32 ± 0.53 |
| `lanjian/day_02 input-kcen` | 2.5 ± 0.9 | 1.4 | 8.7 | 1.70 ± 0.80 |
| `lanjian/day_02 input-lanjian` | 2.0 ± 0.7 | 1.2 | 5.7 | 1.41 ± 0.62 |
| `lanjian/day_02 input-mattcl` | 2.1 ± 0.6 | 1.3 | 5.1 | 1.48 ± 0.59 |
| `lanjian/day_02 input-pting` | 2.1 ± 0.7 | 1.1 | 9.2 | 1.42 ± 0.64 |
| `mattcl-solver/aoc run 2 input-aspidites` | 2.0 ± 1.1 | 1.0 | 14.0 | 1.41 ± 0.84 |
| `mattcl-solver/aoc run 2 input-kcen` | 1.8 ± 0.6 | 1.0 | 9.0 | 1.25 ± 0.55 |
| `mattcl-solver/aoc run 2 input-lanjian` | 1.7 ± 0.5 | 0.9 | 5.3 | 1.17 ± 0.48 |
| `mattcl-solver/aoc run 2 input-mattcl` | 2.0 ± 0.7 | 0.9 | 7.9 | 1.40 ± 0.62 |
| `mattcl-solver/aoc run 2 input-pting` | 1.6 ± 0.6 | 0.9 | 8.5 | 1.12 ± 0.53 |
| `python pting/day02.py input-aspidites` | 35.2 ± 4.5 | 28.4 | 50.4 | 24.22 ± 7.76 |
| `python pting/day02.py input-kcen` | 39.6 ± 9.7 | 28.4 | 85.1 | 27.20 ± 10.43 |
| `python pting/day02.py input-lanjian` | 38.0 ± 8.7 | 29.5 | 72.6 | 26.09 ± 9.75 |
| `python pting/day02.py input-mattcl` | 34.8 ± 5.2 | 29.2 | 59.1 | 23.94 ± 7.89 |
| `python pting/day02.py input-pting` | 36.7 ± 4.1 | 30.9 | 47.9 | 25.22 ± 7.94 |
