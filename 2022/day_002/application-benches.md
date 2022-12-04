# Day 2 benchmarks

[link to problem](http://adventofcode.com/2022/day/2)

The following benchmarks are auto-generated via [hyperfine](https://github.com/sharkdp/hyperfine) by a ci system running on shared hardware. Results may be inaccurate, particularly for execution times < 5ms, as per the hyperfine warnings.

The "official" inputs were aggregated from repositories participating in the generation of these benchmarks. The "large" inputs (if any) were sourced from various places, including the subreddit.

## Benchmarks with officially generated inputs
| Command | Mean [ms] | Min [ms] | Max [ms] | Relative |
|:---|---:|---:|---:|---:|
| `aspidites-solver/aoc -i input-aspidites -d 2` | 59.2 ± 5.6 | 52.2 | 81.0 | 44.49 ± 16.54 |
| `aspidites-solver/aoc -i input-kcen -d 2` | 57.3 ± 4.1 | 52.6 | 73.6 | 43.07 ± 15.79 |
| `aspidites-solver/aoc -i input-lanjian -d 2` | 56.9 ± 4.4 | 52.1 | 70.4 | 42.77 ± 15.72 |
| `aspidites-solver/aoc -i input-mattcl -d 2` | 57.6 ± 5.1 | 49.4 | 69.9 | 43.25 ± 16.01 |
| `aspidites-solver/aoc -i input-pting -d 2` | 56.9 ± 5.3 | 52.2 | 71.3 | 42.75 ± 15.88 |
| `kcen/2022/02/solve input-aspidites` | 229.0 ± 21.0 | 200.6 | 267.3 | 171.97 ± 63.80 |
| `kcen/2022/02/solve input-kcen` | 225.8 ± 15.3 | 194.1 | 250.7 | 169.55 ± 62.02 |
| `kcen/2022/02/solve input-lanjian` | 214.9 ± 12.9 | 192.3 | 234.5 | 161.42 ± 58.84 |
| `kcen/2022/02/solve input-mattcl` | 290.0 ± 55.4 | 206.3 | 395.1 | 217.77 ± 88.65 |
| `kcen/2022/02/solve input-pting` | 241.1 ± 32.3 | 209.3 | 319.8 | 181.03 ± 69.44 |
| `lanjian/day_02 input-aspidites` | 1.6 ± 0.8 | 0.8 | 14.9 | 1.23 ± 0.72 |
| `lanjian/day_02 input-kcen` | 1.9 ± 0.4 | 1.1 | 4.6 | 1.39 ± 0.60 |
| `lanjian/day_02 input-lanjian` | 1.6 ± 0.5 | 1.0 | 10.5 | 1.23 ± 0.60 |
| `lanjian/day_02 input-mattcl` | 1.6 ± 0.4 | 1.0 | 4.7 | 1.19 ± 0.54 |
| `lanjian/day_02 input-pting` | 2.2 ± 0.6 | 1.0 | 5.1 | 1.64 ± 0.76 |
| `mattcl-solver/aoc run 2 input-aspidites` | 1.7 ± 0.7 | 0.6 | 9.5 | 1.31 ± 0.72 |
| `mattcl-solver/aoc run 2 input-kcen` | 1.4 ± 0.6 | 0.8 | 10.4 | 1.07 ± 0.61 |
| `mattcl-solver/aoc run 2 input-lanjian` | 1.5 ± 1.1 | 0.7 | 26.7 | 1.12 ± 0.91 |
| `mattcl-solver/aoc run 2 input-mattcl` | 1.3 ± 0.5 | 0.7 | 4.4 | 1.00 |
| `mattcl-solver/aoc run 2 input-pting` | 1.6 ± 0.4 | 0.8 | 5.3 | 1.19 ± 0.54 |
| `python pting/day02.py input-aspidites` | 35.3 ± 7.0 | 27.9 | 61.1 | 26.51 ± 10.87 |
| `python pting/day02.py input-kcen` | 35.4 ± 4.1 | 29.7 | 49.7 | 26.61 ± 10.04 |
| `python pting/day02.py input-lanjian` | 35.4 ± 4.8 | 30.0 | 55.3 | 26.60 ± 10.22 |
| `python pting/day02.py input-mattcl` | 34.7 ± 5.3 | 27.7 | 55.3 | 26.10 ± 10.18 |
| `python pting/day02.py input-pting` | 35.1 ± 4.0 | 29.8 | 47.7 | 26.37 ± 9.94 |
