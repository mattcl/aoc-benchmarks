# Day 1 benchmarks

[link to problem](http://adventofcode.com/2022/day/1)

The following benchmarks are auto-generated via [hyperfine](https://github.com/sharkdp/hyperfine) by a ci system running on shared hardware. Results may be inaccurate, particularly for execution times < 5ms, as per the hyperfine warnings.

[ci pipeline](http://ci.papercode.net:8080/teams/aoc2022/pipelines/aoc-compare-2022)

The "official" inputs were aggregated from repositories participating in the generation of these benchmarks. The "large" inputs (if any) were sourced from various places, including the subreddit.

## Repos (with solutions for day 1)


- [aspidites](https://github.com/aspidites/aoc2022)
- [kcen](https://github.com/kcen/AdventOfCode)
- [lanjian](https://github.com/LanJian/aoc-2022)
- [mattcl](https://github.com/mattcl/aoc2022)
- [pting](https://github.com/pting/aoc2022)

## Benchmarks with officially generated inputs
| Command | Mean [ms] | Min [ms] | Max [ms] | Relative |
|:---|---:|---:|---:|---:|
| `aspidites-solver/aoc -i input-aspidites -d 1` | 12.6 ± 1.1 | 11.3 | 24.5 | 10.27 ± 5.04 |
| `aspidites-solver/aoc -i input-kcen -d 1` | 13.0 ± 0.8 | 11.8 | 16.8 | 10.64 ± 5.18 |
| `aspidites-solver/aoc -i input-lanjian -d 1` | 13.2 ± 1.3 | 11.5 | 23.1 | 10.76 ± 5.30 |
| `aspidites-solver/aoc -i input-mattcl -d 1` | 13.0 ± 1.0 | 11.4 | 20.5 | 10.66 ± 5.21 |
| `aspidites-solver/aoc -i input-pting -d 1` | 12.2 ± 0.7 | 11.3 | 14.4 | 10.01 ± 4.87 |
| `kcen/2022/01/solve input-aspidites` | 106.8 ± 8.6 | 89.6 | 121.8 | 87.34 ± 42.79 |
| `kcen/2022/01/solve input-kcen` | 107.0 ± 14.0 | 90.4 | 137.7 | 87.48 ± 43.78 |
| `kcen/2022/01/solve input-lanjian` | 115.4 ± 12.7 | 95.5 | 139.0 | 94.37 ± 46.77 |
| `kcen/2022/01/solve input-mattcl` | 109.7 ± 10.3 | 94.0 | 138.4 | 89.68 ± 44.15 |
| `kcen/2022/01/solve input-pting` | 115.5 ± 13.7 | 88.9 | 146.0 | 94.39 ± 46.97 |
| `lanjian/day_01 input-aspidites` | 1.8 ± 0.9 | 0.9 | 12.3 | 1.47 ± 1.03 |
| `lanjian/day_01 input-kcen` | 2.5 ± 0.9 | 1.1 | 5.9 | 2.02 ± 1.22 |
| `lanjian/day_01 input-lanjian` | 2.1 ± 0.7 | 0.9 | 6.5 | 1.73 ± 1.01 |
| `lanjian/day_01 input-mattcl` | 2.2 ± 0.8 | 0.9 | 7.7 | 1.77 ± 1.09 |
| `lanjian/day_01 input-pting` | 1.7 ± 0.7 | 0.9 | 5.3 | 1.35 ± 0.88 |
| `mattcl-solver/aoc run 1 input-aspidites` | 2.1 ± 1.1 | 0.8 | 11.8 | 1.70 ± 1.23 |
| `mattcl-solver/aoc run 1 input-kcen` | 2.5 ± 0.9 | 1.0 | 11.8 | 2.06 ± 1.24 |
| `mattcl-solver/aoc run 1 input-lanjian` | 1.2 ± 0.6 | 0.8 | 9.7 | 1.00 |
| `mattcl-solver/aoc run 1 input-mattcl` | 2.2 ± 0.8 | 0.9 | 8.9 | 1.79 ± 1.06 |
| `mattcl-solver/aoc run 1 input-pting` | 1.4 ± 0.6 | 0.8 | 5.0 | 1.13 ± 0.71 |
| `python pting/day01.py input-aspidites` | 36.5 ± 6.1 | 29.2 | 60.5 | 29.80 ± 15.24 |
| `python pting/day01.py input-kcen` | 41.6 ± 12.0 | 26.6 | 79.9 | 34.03 ± 19.16 |
| `python pting/day01.py input-lanjian` | 43.2 ± 11.9 | 26.1 | 70.7 | 35.35 ± 19.68 |
| `python pting/day01.py input-mattcl` | 35.5 ± 6.4 | 26.0 | 65.1 | 29.03 ± 14.97 |
| `python pting/day01.py input-pting` | 39.1 ± 10.3 | 26.3 | 77.0 | 31.95 ± 17.58 |
