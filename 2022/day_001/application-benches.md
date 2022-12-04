# Day 1 benchmarks

[link to problem](http://adventofcode.com/2022/day/1)

The following benchmarks are auto-generated via [hyperfine](https://github.com/sharkdp/hyperfine) by a ci system running on shared hardware. Results may be inaccurate, particularly for execution times < 5ms, as per the hyperfine warnings.

The "official" inputs were aggregated from repositories participating in the generation of these benchmarks. The "large" inputs (if any) were sourced from various places, including the subreddit.

## Benchmarks with officially generated inputs
| Command | Mean [ms] | Min [ms] | Max [ms] | Relative |
|:---|---:|---:|---:|---:|
| `aspidites-solver/aoc -i input-aspidites -d 1` | 12.7 ± 0.6 | 11.7 | 15.6 | 10.21 ± 4.09 |
| `aspidites-solver/aoc -i input-kcen -d 1` | 12.8 ± 1.1 | 11.7 | 20.2 | 10.31 ± 4.18 |
| `aspidites-solver/aoc -i input-lanjian -d 1` | 12.3 ± 0.7 | 11.5 | 16.2 | 9.93 ± 3.98 |
| `aspidites-solver/aoc -i input-mattcl -d 1` | 12.6 ± 1.1 | 11.6 | 23.0 | 10.17 ± 4.13 |
| `aspidites-solver/aoc -i input-pting -d 1` | 12.8 ± 1.0 | 11.7 | 19.0 | 10.28 ± 4.16 |
| `kcen/2022/01/solve input-aspidites` | 208.2 ± 27.6 | 184.8 | 285.0 | 167.44 ± 70.06 |
| `kcen/2022/01/solve input-kcen` | 239.0 ± 14.6 | 217.1 | 266.4 | 192.16 ± 77.16 |
| `kcen/2022/01/solve input-lanjian` | 214.9 ± 11.8 | 198.4 | 237.4 | 172.79 ± 69.23 |
| `kcen/2022/01/solve input-mattcl` | 230.9 ± 32.3 | 182.1 | 273.0 | 185.73 ± 78.14 |
| `kcen/2022/01/solve input-pting` | 212.3 ± 33.2 | 180.7 | 283.9 | 170.70 ± 72.81 |
| `lanjian/day_01 input-aspidites` | 1.9 ± 0.7 | 0.9 | 5.8 | 1.54 ± 0.83 |
| `lanjian/day_01 input-kcen` | 2.5 ± 1.2 | 1.0 | 14.5 | 1.98 ± 1.27 |
| `lanjian/day_01 input-lanjian` | 1.6 ± 0.8 | 0.9 | 12.7 | 1.25 ± 0.80 |
| `lanjian/day_01 input-mattcl` | 2.1 ± 0.7 | 1.0 | 7.7 | 1.66 ± 0.87 |
| `lanjian/day_01 input-pting` | 1.8 ± 0.7 | 0.9 | 8.3 | 1.45 ± 0.82 |
| `mattcl-solver/aoc run 1 input-aspidites` | 1.6 ± 0.5 | 0.8 | 5.3 | 1.30 ± 0.68 |
| `mattcl-solver/aoc run 1 input-kcen` | 1.8 ± 0.6 | 0.8 | 5.2 | 1.49 ± 0.74 |
| `mattcl-solver/aoc run 1 input-lanjian` | 1.2 ± 0.5 | 0.7 | 4.9 | 1.00 |
| `mattcl-solver/aoc run 1 input-mattcl` | 1.7 ± 1.0 | 0.8 | 16.6 | 1.40 ± 1.00 |
| `mattcl-solver/aoc run 1 input-pting` | 1.7 ± 0.5 | 0.9 | 6.5 | 1.38 ± 0.69 |
| `python pting/day01.py input-aspidites` | 32.4 ± 2.8 | 27.6 | 42.3 | 26.04 ± 10.58 |
| `python pting/day01.py input-kcen` | 43.7 ± 9.6 | 34.1 | 77.8 | 35.11 ± 15.94 |
| `python pting/day01.py input-lanjian` | 38.2 ± 8.8 | 28.3 | 95.8 | 30.73 ± 14.09 |
| `python pting/day01.py input-mattcl` | 34.0 ± 4.2 | 27.9 | 47.6 | 27.38 ± 11.38 |
| `python pting/day01.py input-pting` | 34.7 ± 4.4 | 27.4 | 48.1 | 27.93 ± 11.63 |
