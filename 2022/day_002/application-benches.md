# Day 2 benchmarks

[link to problem](http://adventofcode.com/2022/day/2)

The following benchmarks are auto-generated via [hyperfine](https://github.com/sharkdp/hyperfine) by a ci system running on shared hardware. Results may be inaccurate, particularly for execution times < 5ms, as per the hyperfine warnings.

The "official" inputs were aggregated from repositories participating in the generation of these benchmarks. The "large" inputs (if any) were sourced from various places, including the subreddit.

## Benchmarks with officially generated inputs
| Command | Mean [ms] | Min [ms] | Max [ms] | Relative |
|:---|---:|---:|---:|---:|
| `aspidites-solver/aoc -i input-aspidites -d 2` | 57.3 ± 6.2 | 51.3 | 73.1 | 32.03 ± 13.22 |
| `aspidites-solver/aoc -i input-kcen -d 2` | 60.2 ± 5.6 | 53.7 | 80.5 | 33.66 ± 13.77 |
| `aspidites-solver/aoc -i input-lanjian -d 2` | 70.3 ± 17.3 | 57.2 | 148.0 | 39.31 ± 18.43 |
| `aspidites-solver/aoc -i input-mattcl -d 2` | 62.3 ± 13.6 | 51.6 | 125.5 | 34.88 ± 15.85 |
| `aspidites-solver/aoc -i input-pting -d 2` | 63.5 ± 8.2 | 53.8 | 88.3 | 35.53 ± 14.88 |
| `kcen/2022/02/solve.sh input-aspidites` | 226.5 ± 26.1 | 188.7 | 269.9 | 126.67 ± 52.55 |
| `kcen/2022/02/solve.sh input-kcen` | 247.7 ± 25.0 | 206.8 | 283.9 | 138.52 ± 56.95 |
| `kcen/2022/02/solve.sh input-lanjian` | 270.0 ± 66.2 | 190.6 | 408.2 | 151.05 ± 70.68 |
| `kcen/2022/02/solve.sh input-mattcl` | 237.1 ± 14.7 | 204.0 | 262.5 | 132.62 ± 53.49 |
| `kcen/2022/02/solve.sh input-pting` | 230.5 ± 17.8 | 195.0 | 253.3 | 128.92 ± 52.34 |
| `lanjian/day_02 input-aspidites` | 2.3 ± 1.0 | 1.2 | 11.5 | 1.30 ± 0.75 |
| `lanjian/day_02 input-kcen` | 2.2 ± 0.8 | 1.2 | 11.1 | 1.25 ± 0.65 |
| `lanjian/day_02 input-lanjian` | 3.2 ± 1.1 | 1.4 | 7.8 | 1.77 ± 0.94 |
| `lanjian/day_02 input-mattcl` | 1.8 ± 0.7 | 1.0 | 5.4 | 1.03 ± 0.56 |
| `lanjian/day_02 input-pting` | 2.6 ± 0.9 | 1.1 | 5.9 | 1.43 ± 0.75 |
| `mattcl-solver/aoc run 2 input-aspidites` | 1.9 ± 0.9 | 0.9 | 8.1 | 1.07 ± 0.68 |
| `mattcl-solver/aoc run 2 input-kcen` | 2.3 ± 0.9 | 1.0 | 7.8 | 1.29 ± 0.71 |
| `mattcl-solver/aoc run 2 input-lanjian` | 1.8 ± 0.7 | 1.0 | 7.1 | 1.00 |
| `mattcl-solver/aoc run 2 input-mattcl` | 2.3 ± 0.9 | 0.9 | 6.2 | 1.28 ± 0.71 |
| `mattcl-solver/aoc run 2 input-pting` | 2.1 ± 0.9 | 0.9 | 13.4 | 1.18 ± 0.69 |
| `python pting/day02.py input-aspidites` | 38.9 ± 9.0 | 27.7 | 81.0 | 21.73 ± 10.01 |
| `python pting/day02.py input-kcen` | 48.7 ± 15.4 | 33.0 | 108.7 | 27.23 ± 13.84 |
| `python pting/day02.py input-lanjian` | 39.7 ± 10.6 | 27.5 | 75.6 | 22.19 ± 10.64 |
| `python pting/day02.py input-mattcl` | 37.9 ± 12.6 | 29.6 | 81.0 | 21.21 ± 11.02 |
| `python pting/day02.py input-pting` | 39.0 ± 8.5 | 30.4 | 80.3 | 21.81 ± 9.90 |
