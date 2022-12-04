# Day 2 benchmarks

[link to problem](http://adventofcode.com/2022/day/2)

The following benchmarks are auto-generated via [hyperfine](https://github.com/sharkdp/hyperfine) by a ci system running on shared hardware. Results may be inaccurate, particularly for execution times < 5ms, as per the hyperfine warnings.

The "official" inputs were aggregated from repositories participating in the generation of these benchmarks. The "large" inputs (if any) were sourced from various places, including the subreddit.

## Benchmarks with officially generated inputs
| Command | Mean [ms] | Min [ms] | Max [ms] | Relative |
|:---|---:|---:|---:|---:|
| `aspidites-solver/aoc -i input-aspidites -d 2` | 12.5 ± 1.4 | 11.6 | 30.2 | 9.83 ± 3.75 |
| `aspidites-solver/aoc -i input-kcen -d 2` | 12.4 ± 0.8 | 11.6 | 16.5 | 9.80 ± 3.61 |
| `aspidites-solver/aoc -i input-lanjian -d 2` | 12.4 ± 0.5 | 11.7 | 14.8 | 9.77 ± 3.58 |
| `aspidites-solver/aoc -i input-mattcl -d 2` | 12.6 ± 1.0 | 11.5 | 24.2 | 9.91 ± 3.70 |
| `aspidites-solver/aoc -i input-pting -d 2` | 12.2 ± 0.6 | 11.4 | 17.0 | 9.61 ± 3.53 |
| `kcen/2022/02/solve input-aspidites` | 1.5 ± 0.7 | 0.9 | 9.6 | 1.19 ± 0.68 |
| `kcen/2022/02/solve input-kcen` | 1.6 ± 0.5 | 0.9 | 8.0 | 1.24 ± 0.61 |
| `kcen/2022/02/solve input-lanjian` | 1.4 ± 0.6 | 0.8 | 8.7 | 1.11 ± 0.61 |
| `kcen/2022/02/solve input-mattcl` | 1.3 ± 0.5 | 0.8 | 5.1 | 1.00 |
| `kcen/2022/02/solve input-pting` | 1.8 ± 1.1 | 0.8 | 11.6 | 1.40 ± 1.00 |
| `lanjian/day_02 input-aspidites` | 2.1 ± 0.6 | 1.1 | 5.6 | 1.68 ± 0.75 |
| `lanjian/day_02 input-kcen` | 1.8 ± 0.4 | 1.2 | 4.4 | 1.42 ± 0.62 |
| `lanjian/day_02 input-lanjian` | 2.3 ± 1.0 | 1.0 | 13.5 | 1.78 ± 1.04 |
| `lanjian/day_02 input-mattcl` | 1.6 ± 0.4 | 1.0 | 4.6 | 1.23 ± 0.54 |
| `lanjian/day_02 input-pting` | 1.9 ± 0.6 | 1.1 | 8.3 | 1.49 ± 0.74 |
| `mattcl-solver/aoc run 2 input-aspidites` | 1.8 ± 0.4 | 1.0 | 3.9 | 1.41 ± 0.60 |
| `mattcl-solver/aoc run 2 input-kcen` | 1.6 ± 0.6 | 1.0 | 6.7 | 1.29 ± 0.65 |
| `mattcl-solver/aoc run 2 input-lanjian` | 1.9 ± 0.6 | 1.0 | 7.5 | 1.46 ± 0.73 |
| `mattcl-solver/aoc run 2 input-mattcl` | 1.5 ± 0.6 | 0.9 | 6.2 | 1.20 ± 0.65 |
| `mattcl-solver/aoc run 2 input-pting` | 1.7 ± 0.4 | 0.9 | 4.1 | 1.31 ± 0.57 |
| `python pting/day02.py input-aspidites` | 38.4 ± 4.7 | 31.1 | 51.5 | 30.22 ± 11.60 |
| `python pting/day02.py input-kcen` | 33.2 ± 2.6 | 29.2 | 40.9 | 26.11 ± 9.71 |
| `python pting/day02.py input-lanjian` | 35.3 ± 3.8 | 29.3 | 47.2 | 27.79 ± 10.55 |
| `python pting/day02.py input-mattcl` | 32.9 ± 3.9 | 28.1 | 50.9 | 25.90 ± 9.91 |
| `python pting/day02.py input-pting` | 35.8 ± 4.8 | 29.9 | 51.5 | 28.22 ± 10.95 |
