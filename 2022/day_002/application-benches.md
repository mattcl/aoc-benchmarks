# Day 2 benchmarks

[link to problem](http://adventofcode.com/2022/day/2)

The following benchmarks are auto-generated via [hyperfine](https://github.com/sharkdp/hyperfine) by a ci system running on shared hardware. Results may be inaccurate, particularly for execution times < 5ms, as per the hyperfine warnings.

The "official" inputs were aggregated from repositories participating in the generation of these benchmarks. The "large" inputs (if any) were sourced from various places, including the subreddit.

## Benchmarks with officially generated inputs
| Command | Mean [ms] | Min [ms] | Max [ms] | Relative |
|:---|---:|---:|---:|---:|
| `aspidites-solver/aoc -i input-aspidites -d 2` | 62.4 ± 10.8 | 51.5 | 94.7 | 47.01 ± 25.03 |
| `aspidites-solver/aoc -i input-kcen -d 2` | 56.8 ± 4.0 | 52.0 | 70.6 | 42.77 ± 21.76 |
| `aspidites-solver/aoc -i input-lanjian -d 2` | 62.3 ± 8.7 | 53.2 | 88.8 | 46.90 ± 24.52 |
| `aspidites-solver/aoc -i input-mattcl -d 2` | 63.6 ± 12.3 | 52.9 | 108.3 | 47.89 ± 25.85 |
| `aspidites-solver/aoc -i input-pting -d 2` | 63.0 ± 10.4 | 54.9 | 109.5 | 47.45 ± 25.16 |
| `kcen/2022/02/solve.sh input-aspidites` | 226.2 ± 20.1 | 193.5 | 257.7 | 170.32 ± 87.13 |
| `kcen/2022/02/solve.sh input-kcen` | 256.0 ± 31.3 | 216.7 | 317.4 | 192.78 ± 99.95 |
| `kcen/2022/02/solve.sh input-lanjian` | 241.5 ± 43.6 | 201.1 | 364.8 | 181.88 ± 97.33 |
| `kcen/2022/02/solve.sh input-mattcl` | 235.6 ± 19.7 | 199.9 | 276.3 | 177.39 ± 90.59 |
| `kcen/2022/02/solve.sh input-pting` | 220.7 ± 37.9 | 184.3 | 316.0 | 166.19 ± 88.47 |
| `lanjian/day_02 input-aspidites` | 1.8 ± 0.6 | 0.8 | 4.5 | 1.34 ± 0.83 |
| `lanjian/day_02 input-kcen` | 2.1 ± 0.9 | 0.8 | 10.5 | 1.58 ± 1.05 |
| `lanjian/day_02 input-lanjian` | 1.9 ± 0.8 | 0.8 | 5.3 | 1.41 ± 0.93 |
| `lanjian/day_02 input-mattcl` | 2.2 ± 0.9 | 1.0 | 6.9 | 1.65 ± 1.09 |
| `lanjian/day_02 input-pting` | 2.4 ± 1.2 | 0.7 | 10.4 | 1.83 ± 1.30 |
| `mattcl-solver/aoc run 2 input-aspidites` | 1.3 ± 0.7 | 0.5 | 6.0 | 1.00 |
| `mattcl-solver/aoc run 2 input-kcen` | 2.1 ± 0.9 | 0.6 | 6.4 | 1.59 ± 1.05 |
| `mattcl-solver/aoc run 2 input-lanjian` | 2.0 ± 1.0 | 0.6 | 10.5 | 1.49 ± 1.05 |
| `mattcl-solver/aoc run 2 input-mattcl` | 1.9 ± 0.8 | 0.6 | 6.3 | 1.40 ± 0.91 |
| `mattcl-solver/aoc run 2 input-pting` | 2.2 ± 1.5 | 0.6 | 20.5 | 1.64 ± 1.41 |
| `python pting/day02.py input-aspidites` | 36.1 ± 6.4 | 26.8 | 66.1 | 27.17 ± 14.50 |
| `python pting/day02.py input-kcen` | 36.2 ± 11.2 | 27.0 | 83.4 | 27.28 ± 16.14 |
| `python pting/day02.py input-lanjian` | 38.9 ± 9.4 | 28.3 | 74.8 | 29.29 ± 16.38 |
| `python pting/day02.py input-mattcl` | 41.3 ± 8.6 | 30.5 | 82.2 | 31.08 ± 16.95 |
| `python pting/day02.py input-pting` | 42.3 ± 11.0 | 28.3 | 80.0 | 31.82 ± 18.06 |
