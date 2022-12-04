# Day 2 benchmarks

[link to problem](http://adventofcode.com/2022/day/2)

The following benchmarks are auto-generated via [hyperfine](https://github.com/sharkdp/hyperfine) by a ci system running on shared hardware. Results may be inaccurate, particularly for execution times < 5ms, as per the hyperfine warnings.

The "official" inputs were aggregated from repositories participating in the generation of these benchmarks. The "large" inputs (if any) were sourced from various places, including the subreddit.

## Benchmarks with officially generated inputs
| Command | Mean [ms] | Min [ms] | Max [ms] | Relative |
|:---|---:|---:|---:|---:|
| `aspidites-solver/aoc -i input-aspidites -d 2` | 64.2 ± 9.3 | 53.8 | 86.5 | 39.99 ± 12.70 |
| `aspidites-solver/aoc -i input-kcen -d 2` | 63.2 ± 7.6 | 52.9 | 78.4 | 39.33 ± 12.07 |
| `aspidites-solver/aoc -i input-lanjian -d 2` | 60.8 ± 7.4 | 53.5 | 92.3 | 37.88 ± 11.65 |
| `aspidites-solver/aoc -i input-mattcl -d 2` | 61.7 ± 7.2 | 52.5 | 86.9 | 38.43 ± 11.74 |
| `aspidites-solver/aoc -i input-pting -d 2` | 60.5 ± 6.7 | 53.0 | 84.9 | 37.67 ± 11.44 |
| `kcen/2022/02/solve.sh input-aspidites` | 257.9 ± 23.1 | 203.7 | 291.1 | 160.59 ± 47.59 |
| `kcen/2022/02/solve.sh input-kcen` | 220.3 ± 20.5 | 193.8 | 262.5 | 137.19 ± 40.79 |
| `kcen/2022/02/solve.sh input-lanjian` | 233.2 ± 19.5 | 210.6 | 273.5 | 145.19 ± 42.78 |
| `kcen/2022/02/solve.sh input-mattcl` | 242.5 ± 12.4 | 224.6 | 259.9 | 150.97 ± 43.34 |
| `kcen/2022/02/solve.sh input-pting` | 233.8 ± 18.2 | 211.6 | 273.5 | 145.57 ± 42.65 |
| `lanjian/day_02 input-aspidites` | 2.0 ± 0.7 | 1.1 | 8.6 | 1.22 ± 0.55 |
| `lanjian/day_02 input-kcen` | 2.2 ± 0.6 | 1.1 | 6.3 | 1.36 ± 0.52 |
| `lanjian/day_02 input-lanjian` | 2.2 ± 0.7 | 1.1 | 14.3 | 1.40 ± 0.59 |
| `lanjian/day_02 input-mattcl` | 2.2 ± 0.7 | 1.2 | 10.8 | 1.39 ± 0.60 |
| `lanjian/day_02 input-pting` | 2.4 ± 0.7 | 1.2 | 11.3 | 1.50 ± 0.63 |
| `mattcl-solver/aoc run 2 input-aspidites` | 1.6 ± 0.5 | 0.8 | 4.4 | 1.00 |
| `mattcl-solver/aoc run 2 input-kcen` | 2.0 ± 0.6 | 1.0 | 5.3 | 1.26 ± 0.50 |
| `mattcl-solver/aoc run 2 input-lanjian` | 1.8 ± 0.4 | 1.0 | 6.1 | 1.13 ± 0.41 |
| `mattcl-solver/aoc run 2 input-mattcl` | 2.1 ± 0.6 | 1.0 | 7.6 | 1.31 ± 0.52 |
| `mattcl-solver/aoc run 2 input-pting` | 2.0 ± 0.7 | 0.9 | 6.4 | 1.24 ± 0.55 |
| `python pting/day02.py input-aspidites` | 35.7 ± 4.1 | 29.7 | 48.9 | 22.26 ± 6.78 |
| `python pting/day02.py input-kcen` | 37.8 ± 5.6 | 29.9 | 54.5 | 23.55 ± 7.50 |
| `python pting/day02.py input-lanjian` | 37.1 ± 4.5 | 30.6 | 50.8 | 23.09 ± 7.10 |
| `python pting/day02.py input-mattcl` | 37.4 ± 4.9 | 30.5 | 54.5 | 23.31 ± 7.26 |
| `python pting/day02.py input-pting` | 36.0 ± 4.1 | 30.6 | 50.3 | 22.42 ± 6.84 |
