# Day 2 benchmarks

[link to problem](http://adventofcode.com/2022/day/2)

The following benchmarks are auto-generated via [hyperfine](https://github.com/sharkdp/hyperfine) by a ci system running on shared hardware. Results may be inaccurate, particularly for execution times < 5ms, as per the hyperfine warnings.

The "official" inputs were aggregated from repositories participating in the generation of these benchmarks. The "large" inputs (if any) were sourced from various places, including the subreddit.

## Benchmarks with officially generated inputs
| Command | Mean [ms] | Min [ms] | Max [ms] | Relative |
|:---|---:|---:|---:|---:|
| `aspidites-solver/aoc -i input-aspidites -d 2` | 58.1 ± 4.7 | 52.6 | 72.9 | 43.64 ± 14.89 |
| `aspidites-solver/aoc -i input-kcen -d 2` | 58.1 ± 4.4 | 53.2 | 69.4 | 43.58 ± 14.82 |
| `aspidites-solver/aoc -i input-lanjian -d 2` | 63.0 ± 8.2 | 53.3 | 91.2 | 47.28 ± 16.84 |
| `aspidites-solver/aoc -i input-mattcl -d 2` | 57.4 ± 5.2 | 52.7 | 84.5 | 43.09 ± 14.82 |
| `aspidites-solver/aoc -i input-pting -d 2` | 63.4 ± 9.7 | 51.5 | 93.7 | 47.61 ± 17.37 |
| `kcen/2022/02/solve.sh input-aspidites` | 219.7 ± 18.3 | 195.9 | 262.9 | 164.93 ± 56.40 |
| `kcen/2022/02/solve.sh input-kcen` | 220.6 ± 13.3 | 201.0 | 253.6 | 165.62 ± 55.82 |
| `kcen/2022/02/solve.sh input-lanjian` | 224.3 ± 14.7 | 201.7 | 259.1 | 168.40 ± 56.92 |
| `kcen/2022/02/solve.sh input-mattcl` | 215.7 ± 11.5 | 195.4 | 236.5 | 161.93 ± 54.38 |
| `kcen/2022/02/solve.sh input-pting` | 305.8 ± 37.7 | 250.4 | 374.7 | 229.54 ± 81.19 |
| `lanjian/day_02 input-aspidites` | 1.7 ± 0.4 | 1.0 | 4.3 | 1.29 ± 0.53 |
| `lanjian/day_02 input-kcen` | 1.9 ± 0.4 | 1.2 | 4.9 | 1.40 ± 0.56 |
| `lanjian/day_02 input-lanjian` | 2.2 ± 0.7 | 1.0 | 7.5 | 1.65 ± 0.76 |
| `lanjian/day_02 input-mattcl` | 2.0 ± 0.8 | 1.0 | 7.2 | 1.52 ± 0.76 |
| `lanjian/day_02 input-pting` | 1.5 ± 0.5 | 0.9 | 5.9 | 1.11 ± 0.53 |
| `mattcl-solver/aoc run 2 input-aspidites` | 1.3 ± 0.4 | 0.8 | 6.4 | 1.00 |
| `mattcl-solver/aoc run 2 input-kcen` | 1.6 ± 0.6 | 0.8 | 9.7 | 1.19 ± 0.58 |
| `mattcl-solver/aoc run 2 input-lanjian` | 3.1 ± 2.0 | 1.0 | 20.9 | 2.35 ± 1.69 |
| `mattcl-solver/aoc run 2 input-mattcl` | 1.6 ± 0.4 | 0.9 | 5.3 | 1.22 ± 0.51 |
| `mattcl-solver/aoc run 2 input-pting` | 1.7 ± 0.6 | 0.8 | 6.0 | 1.24 ± 0.62 |
| `python pting/day02.py input-aspidites` | 35.2 ± 5.1 | 29.3 | 59.5 | 26.38 ± 9.55 |
| `python pting/day02.py input-kcen` | 37.9 ± 6.6 | 30.1 | 61.7 | 28.44 ± 10.67 |
| `python pting/day02.py input-lanjian` | 36.7 ± 5.9 | 30.5 | 64.9 | 27.55 ± 10.16 |
| `python pting/day02.py input-mattcl` | 34.9 ± 4.7 | 29.7 | 55.4 | 26.22 ± 9.38 |
| `python pting/day02.py input-pting` | 34.4 ± 3.2 | 28.8 | 46.8 | 25.80 ± 8.89 |
