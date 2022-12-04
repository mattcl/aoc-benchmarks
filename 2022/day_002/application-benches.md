# Day 2 benchmarks

[link to problem](http://adventofcode.com/2022/day/2)

The following benchmarks are auto-generated via [hyperfine](https://github.com/sharkdp/hyperfine) by a ci system running on shared hardware. Results may be inaccurate, particularly for execution times < 5ms, as per the hyperfine warnings.

The "official" inputs were aggregated from repositories participating in the generation of these benchmarks. The "large" inputs (if any) were sourced from various places, including the subreddit.

## Benchmarks with officially generated inputs
| Command | Mean [ms] | Min [ms] | Max [ms] | Relative |
|:---|---:|---:|---:|---:|
| `aspidites-solver/aoc -i input-aspidites -d 2` | 75.5 ± 15.3 | 56.3 | 138.0 | 52.06 ± 21.15 |
| `aspidites-solver/aoc -i input-kcen -d 2` | 60.4 ± 5.7 | 53.0 | 79.1 | 41.61 ± 15.16 |
| `aspidites-solver/aoc -i input-lanjian -d 2` | 57.5 ± 5.4 | 52.7 | 78.4 | 39.64 ± 14.43 |
| `aspidites-solver/aoc -i input-mattcl -d 2` | 61.6 ± 8.0 | 53.5 | 77.8 | 42.48 ± 15.92 |
| `aspidites-solver/aoc -i input-pting -d 2` | 56.6 ± 4.1 | 52.9 | 71.5 | 38.98 ± 14.00 |
| `kcen/2022/02/solve.sh input-aspidites` | 234.5 ± 24.2 | 213.8 | 308.4 | 161.61 ± 59.25 |
| `kcen/2022/02/solve.sh input-kcen` | 225.0 ± 21.7 | 197.6 | 276.2 | 155.11 ± 56.59 |
| `kcen/2022/02/solve.sh input-lanjian` | 217.6 ± 17.1 | 199.9 | 261.5 | 149.98 ± 54.07 |
| `kcen/2022/02/solve.sh input-mattcl` | 233.8 ± 23.3 | 202.8 | 270.8 | 161.18 ± 58.93 |
| `kcen/2022/02/solve.sh input-pting` | 239.6 ± 27.6 | 205.4 | 285.4 | 165.13 ± 61.13 |
| `lanjian/day_02 input-aspidites` | 1.8 ± 0.5 | 1.0 | 4.6 | 1.25 ± 0.54 |
| `lanjian/day_02 input-kcen` | 2.1 ± 0.6 | 1.1 | 7.6 | 1.44 ± 0.65 |
| `lanjian/day_02 input-lanjian` | 2.0 ± 0.5 | 1.0 | 7.2 | 1.36 ± 0.59 |
| `lanjian/day_02 input-mattcl` | 1.9 ± 0.6 | 1.0 | 8.0 | 1.32 ± 0.61 |
| `lanjian/day_02 input-pting` | 1.9 ± 0.6 | 1.1 | 9.3 | 1.33 ± 0.64 |
| `mattcl-solver/aoc run 2 input-aspidites` | 1.7 ± 0.5 | 0.8 | 5.9 | 1.15 ± 0.51 |
| `mattcl-solver/aoc run 2 input-kcen` | 1.5 ± 0.5 | 0.8 | 12.0 | 1.00 |
| `mattcl-solver/aoc run 2 input-lanjian` | 1.5 ± 0.4 | 0.9 | 5.6 | 1.07 ± 0.48 |
| `mattcl-solver/aoc run 2 input-mattcl` | 1.7 ± 0.7 | 0.7 | 9.1 | 1.17 ± 0.66 |
| `mattcl-solver/aoc run 2 input-pting` | 1.7 ± 0.5 | 0.8 | 4.8 | 1.20 ± 0.56 |
| `python pting/day02.py input-aspidites` | 37.2 ± 5.5 | 30.3 | 57.8 | 25.66 ± 9.80 |
| `python pting/day02.py input-kcen` | 35.5 ± 6.3 | 29.6 | 76.4 | 24.47 ± 9.64 |
| `python pting/day02.py input-lanjian` | 37.5 ± 6.6 | 29.9 | 72.1 | 25.86 ± 10.18 |
| `python pting/day02.py input-mattcl` | 38.6 ± 6.2 | 31.5 | 67.3 | 26.61 ± 10.31 |
| `python pting/day02.py input-pting` | 37.0 ± 5.8 | 29.5 | 52.8 | 25.49 ± 9.81 |
