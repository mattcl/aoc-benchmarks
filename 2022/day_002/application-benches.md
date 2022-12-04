# Day 2 benchmarks

[link to problem](http://adventofcode.com/2022/day/2)

The following benchmarks are auto-generated via [hyperfine](https://github.com/sharkdp/hyperfine) by a ci system running on shared hardware. Results may be inaccurate, particularly for execution times < 5ms, as per the hyperfine warnings.

The "official" inputs were aggregated from repositories participating in the generation of these benchmarks. The "large" inputs (if any) were sourced from various places, including the subreddit.

## Benchmarks with officially generated inputs
| Command | Mean [ms] | Min [ms] | Max [ms] | Relative |
|:---|---:|---:|---:|---:|
| `aspidites-solver/aoc -i input-aspidites -d 2` | 12.2 ± 1.0 | 11.2 | 22.0 | 10.51 ± 4.42 |
| `aspidites-solver/aoc -i input-kcen -d 2` | 12.1 ± 0.6 | 11.3 | 15.6 | 10.45 ± 4.35 |
| `aspidites-solver/aoc -i input-lanjian -d 2` | 12.0 ± 1.1 | 11.1 | 21.4 | 10.32 ± 4.37 |
| `aspidites-solver/aoc -i input-mattcl -d 2` | 11.9 ± 0.4 | 11.3 | 13.3 | 10.22 ± 4.24 |
| `aspidites-solver/aoc -i input-pting -d 2` | 12.3 ± 0.7 | 11.4 | 15.9 | 10.61 ± 4.43 |
| `kcen/2022/02/solve input-aspidites` | 3.7 ± 0.6 | 2.8 | 7.8 | 3.23 ± 1.42 |
| `kcen/2022/02/solve input-kcen` | 4.7 ± 2.0 | 2.8 | 34.9 | 4.09 ± 2.44 |
| `kcen/2022/02/solve input-lanjian` | 4.0 ± 1.3 | 2.7 | 15.3 | 3.47 ± 1.84 |
| `kcen/2022/02/solve input-mattcl` | 4.0 ± 0.6 | 2.9 | 7.7 | 3.41 ± 1.52 |
| `kcen/2022/02/solve input-pting` | 3.6 ± 0.8 | 2.5 | 12.9 | 3.08 ± 1.44 |
| `lanjian/day_02 input-aspidites` | 1.7 ± 0.6 | 0.9 | 6.5 | 1.42 ± 0.78 |
| `lanjian/day_02 input-kcen` | 1.6 ± 0.5 | 0.9 | 8.4 | 1.34 ± 0.69 |
| `lanjian/day_02 input-lanjian` | 1.5 ± 0.5 | 0.8 | 8.4 | 1.27 ± 0.67 |
| `lanjian/day_02 input-mattcl` | 1.7 ± 0.4 | 0.9 | 5.0 | 1.50 ± 0.73 |
| `lanjian/day_02 input-pting` | 1.5 ± 0.4 | 0.9 | 4.3 | 1.26 ± 0.63 |
| `mattcl-solver/aoc run 2 input-aspidites` | 1.2 ± 0.5 | 0.7 | 7.2 | 1.05 ± 0.61 |
| `mattcl-solver/aoc run 2 input-kcen` | 1.3 ± 0.4 | 0.7 | 3.5 | 1.12 ± 0.56 |
| `mattcl-solver/aoc run 2 input-lanjian` | 1.2 ± 0.5 | 0.7 | 9.0 | 1.00 |
| `mattcl-solver/aoc run 2 input-mattcl` | 1.4 ± 0.7 | 0.7 | 15.2 | 1.22 ± 0.80 |
| `mattcl-solver/aoc run 2 input-pting` | 1.5 ± 0.5 | 0.7 | 7.0 | 1.29 ± 0.67 |
| `python pting/day02.py input-aspidites` | 33.3 ± 4.5 | 28.4 | 54.7 | 28.73 ± 12.49 |
| `python pting/day02.py input-kcen` | 36.8 ± 6.2 | 29.5 | 61.4 | 31.74 ± 14.17 |
| `python pting/day02.py input-lanjian` | 33.5 ± 4.0 | 28.2 | 46.9 | 28.89 ± 12.43 |
| `python pting/day02.py input-mattcl` | 38.0 ± 14.0 | 29.4 | 148.0 | 32.75 ± 18.15 |
| `python pting/day02.py input-pting` | 33.6 ± 4.4 | 28.8 | 51.1 | 28.95 ± 12.56 |
