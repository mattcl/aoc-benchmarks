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
| `aspidites-solver/aoc -i input-aspidites -d 1` | 12.9 ± 1.5 | 11.5 | 25.1 | 10.48 ± 4.44 |
| `aspidites-solver/aoc -i input-kcen -d 1` | 13.8 ± 2.4 | 11.3 | 29.1 | 11.25 ± 4.99 |
| `aspidites-solver/aoc -i input-lanjian -d 1` | 12.4 ± 0.8 | 11.5 | 19.4 | 10.09 ± 4.17 |
| `aspidites-solver/aoc -i input-mattcl -d 1` | 12.1 ± 0.5 | 11.3 | 14.8 | 9.88 ± 4.05 |
| `aspidites-solver/aoc -i input-pting -d 1` | 13.0 ± 0.9 | 11.4 | 15.4 | 10.63 ± 4.40 |
| `kcen/2022/01/solve input-aspidites` | 128.0 ± 31.6 | 90.3 | 213.6 | 104.27 ± 49.72 |
| `kcen/2022/01/solve input-kcen` | 121.5 ± 13.2 | 104.6 | 160.6 | 99.01 ± 41.80 |
| `kcen/2022/01/solve input-lanjian` | 111.3 ± 14.0 | 89.6 | 146.5 | 90.68 ± 38.71 |
| `kcen/2022/01/solve input-mattcl` | 97.9 ± 7.7 | 88.9 | 124.0 | 79.79 ± 33.15 |
| `kcen/2022/01/solve input-pting` | 115.9 ± 18.7 | 90.3 | 169.7 | 94.43 ± 41.42 |
| `lanjian/day_01 input-aspidites` | 1.4 ± 0.4 | 0.7 | 6.2 | 1.13 ± 0.58 |
| `lanjian/day_01 input-kcen` | 2.3 ± 1.0 | 0.9 | 11.0 | 1.89 ± 1.11 |
| `lanjian/day_01 input-lanjian` | 1.3 ± 0.4 | 0.8 | 8.5 | 1.09 ± 0.57 |
| `lanjian/day_01 input-mattcl` | 1.4 ± 0.4 | 0.9 | 5.5 | 1.15 ± 0.57 |
| `lanjian/day_01 input-pting` | 1.7 ± 0.7 | 0.9 | 8.3 | 1.38 ± 0.79 |
| `mattcl-solver/aoc run 1 input-aspidites` | 1.2 ± 0.5 | 0.5 | 8.2 | 1.00 |
| `mattcl-solver/aoc run 1 input-kcen` | 1.6 ± 0.8 | 0.7 | 6.8 | 1.32 ± 0.86 |
| `mattcl-solver/aoc run 1 input-lanjian` | 1.5 ± 0.6 | 0.7 | 6.2 | 1.20 ± 0.69 |
| `mattcl-solver/aoc run 1 input-mattcl` | 1.7 ± 0.8 | 0.8 | 11.3 | 1.40 ± 0.87 |
| `mattcl-solver/aoc run 1 input-pting` | 2.1 ± 0.9 | 0.7 | 10.9 | 1.68 ± 1.02 |
| `python pting/day01.py input-aspidites` | 35.9 ± 7.8 | 28.0 | 59.2 | 29.27 ± 13.53 |
| `python pting/day01.py input-kcen` | 39.4 ± 9.5 | 26.6 | 69.0 | 32.11 ± 15.22 |
| `python pting/day01.py input-lanjian` | 30.4 ± 3.7 | 25.4 | 45.2 | 24.77 ± 10.55 |
| `python pting/day01.py input-mattcl` | 32.0 ± 4.1 | 26.4 | 49.5 | 26.06 ± 11.15 |
| `python pting/day01.py input-pting` | 38.4 ± 8.6 | 26.4 | 71.5 | 31.29 ± 14.57 |
