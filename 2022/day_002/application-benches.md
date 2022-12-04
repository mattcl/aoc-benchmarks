# Day 2 benchmarks

[link to problem](http://adventofcode.com/2022/day/2)

The following benchmarks are auto-generated via [hyperfine](https://github.com/sharkdp/hyperfine) by a ci system running on shared hardware. Results may be inaccurate, particularly for execution times < 5ms, as per the hyperfine warnings.

The "official" inputs were aggregated from repositories participating in the generation of these benchmarks. The "large" inputs (if any) were sourced from various places, including the subreddit.

## Benchmarks with officially generated inputs
| Command | Mean [ms] | Min [ms] | Max [ms] | Relative |
|:---|---:|---:|---:|---:|
| `aspidites-solver/aoc -i input-aspidites -d 2` | 57.0 ± 5.6 | 49.7 | 76.0 | 43.15 ± 30.40 |
| `aspidites-solver/aoc -i input-kcen -d 2` | 56.8 ± 5.3 | 50.9 | 79.6 | 42.95 ± 30.24 |
| `aspidites-solver/aoc -i input-lanjian -d 2` | 58.1 ± 4.1 | 51.2 | 70.6 | 43.96 ± 30.83 |
| `aspidites-solver/aoc -i input-mattcl -d 2` | 62.3 ± 6.0 | 50.7 | 76.1 | 47.11 ± 33.19 |
| `aspidites-solver/aoc -i input-pting -d 2` | 59.6 ± 6.1 | 53.0 | 80.0 | 45.10 ± 31.80 |
| `kcen/2022/02/solve.sh input-aspidites` | 218.3 ± 17.0 | 197.6 | 252.3 | 165.19 ± 115.98 |
| `kcen/2022/02/solve.sh input-kcen` | 205.7 ± 11.1 | 179.7 | 224.2 | 155.62 ± 108.91 |
| `kcen/2022/02/solve.sh input-lanjian` | 232.9 ± 31.1 | 198.2 | 293.9 | 176.24 ± 125.21 |
| `kcen/2022/02/solve.sh input-mattcl` | 211.5 ± 20.7 | 183.9 | 250.2 | 160.05 ± 112.77 |
| `kcen/2022/02/solve.sh input-pting` | 201.6 ± 17.0 | 181.3 | 238.9 | 152.53 ± 107.20 |
| `lanjian/day_02 input-aspidites` | 1.9 ± 0.5 | 1.1 | 6.2 | 1.45 ± 1.08 |
| `lanjian/day_02 input-kcen` | 1.7 ± 0.4 | 1.2 | 4.6 | 1.26 ± 0.92 |
| `lanjian/day_02 input-lanjian` | 2.2 ± 0.5 | 1.1 | 4.9 | 1.63 ± 1.21 |
| `lanjian/day_02 input-mattcl` | 1.7 ± 0.6 | 1.1 | 9.2 | 1.31 ± 1.01 |
| `lanjian/day_02 input-pting` | 2.2 ± 1.3 | 1.1 | 12.6 | 1.68 ± 1.55 |
| `mattcl-solver/aoc run 2 input-aspidites` | 1.7 ± 0.6 | 0.9 | 5.7 | 1.30 ± 1.00 |
| `mattcl-solver/aoc run 2 input-kcen` | 1.3 ± 0.9 | 0.8 | 22.4 | 1.00 |
| `mattcl-solver/aoc run 2 input-lanjian` | 1.6 ± 0.5 | 0.9 | 7.6 | 1.18 ± 0.91 |
| `mattcl-solver/aoc run 2 input-mattcl` | 2.1 ± 0.7 | 1.0 | 8.2 | 1.59 ± 1.22 |
| `mattcl-solver/aoc run 2 input-pting` | 1.7 ± 0.8 | 0.9 | 10.0 | 1.27 ± 1.06 |
| `python pting/day02.py input-aspidites` | 38.2 ± 6.2 | 28.6 | 61.6 | 28.93 ± 20.72 |
| `python pting/day02.py input-kcen` | 33.7 ± 3.6 | 27.6 | 44.1 | 25.47 ± 17.97 |
| `python pting/day02.py input-lanjian` | 34.1 ± 4.1 | 27.4 | 46.3 | 25.80 ± 18.27 |
| `python pting/day02.py input-mattcl` | 35.1 ± 5.4 | 27.8 | 48.1 | 26.52 ± 18.96 |
| `python pting/day02.py input-pting` | 39.7 ± 10.1 | 27.1 | 98.0 | 30.01 ± 22.30 |
