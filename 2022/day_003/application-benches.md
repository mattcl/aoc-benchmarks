# Day 3 benchmarks

[link to problem](http://adventofcode.com/2022/day/3)

The following benchmarks are auto-generated via [hyperfine](https://github.com/sharkdp/hyperfine) by a ci system running on shared hardware. Results may be inaccurate, particularly for execution times < 5ms, as per the hyperfine warnings.

[ci pipeline](http://ci.papercode.net:8080/teams/aoc2022/pipelines/aoc-compare-2022)

The "official" inputs were aggregated from repositories participating in the generation of these benchmarks. The "large" inputs (if any) were sourced from various places, including the subreddit.

## Repos (with solutions for day 3)


- [aspidites](https://github.com/aspidites/aoc2022)
- [kcen](https://github.com/kcen/AdventOfCode)
- [lanjian](https://github.com/LanJian/aoc-2022)
- [mattcl](https://github.com/mattcl/aoc2022)
- [pting](https://github.com/pting/aoc2022)

## Benchmarks with officially generated inputs
| Command | Mean [ms] | Min [ms] | Max [ms] | Relative |
|:---|---:|---:|---:|---:|
| `aspidites-solver/aoc -i input-aspidites -d 3` | 12.8 ± 2.3 | 11.4 | 23.9 | 12.42 ± 4.74 |
| `aspidites-solver/aoc -i input-kcen -d 3` | 16.6 ± 5.2 | 12.1 | 25.5 | 16.14 ± 7.48 |
| `aspidites-solver/aoc -i input-lanjian -d 3` | 14.2 ± 4.1 | 11.5 | 27.0 | 13.81 ± 6.11 |
| `aspidites-solver/aoc -i input-mattcl -d 3` | 14.3 ± 4.4 | 11.4 | 26.2 | 13.95 ± 6.38 |
| `aspidites-solver/aoc -i input-pting -d 3` | 12.1 ± 0.8 | 11.5 | 21.8 | 11.79 ± 4.06 |
| `kcen/2022/03/solve input-aspidites` | 254.6 ± 14.9 | 237.8 | 281.4 | 247.99 ± 85.08 |
| `kcen/2022/03/solve input-kcen` | 232.6 ± 27.1 | 207.0 | 298.1 | 226.56 ± 81.01 |
| `kcen/2022/03/solve input-lanjian` | 217.0 ± 24.6 | 192.2 | 265.8 | 211.29 ± 75.35 |
| `kcen/2022/03/solve input-mattcl` | 290.6 ± 39.0 | 248.5 | 381.9 | 282.98 ± 102.91 |
| `kcen/2022/03/solve input-pting` | 234.2 ± 16.9 | 213.9 | 275.2 | 228.11 ± 78.84 |
| `lanjian/day_03 input-aspidites` | 1.3 ± 0.6 | 0.6 | 11.4 | 1.29 ± 0.74 |
| `lanjian/day_03 input-kcen` | 1.4 ± 0.5 | 0.6 | 6.2 | 1.35 ± 0.68 |
| `lanjian/day_03 input-lanjian` | 1.7 ± 0.7 | 0.7 | 6.7 | 1.64 ± 0.86 |
| `lanjian/day_03 input-mattcl` | 1.2 ± 0.6 | 0.6 | 6.5 | 1.13 ± 0.66 |
| `lanjian/day_03 input-pting` | 1.1 ± 0.4 | 0.7 | 9.6 | 1.04 ± 0.56 |
| `mattcl-solver/aoc run 3 input-aspidites` | 1.4 ± 0.6 | 0.7 | 5.9 | 1.38 ± 0.77 |
| `mattcl-solver/aoc run 3 input-kcen` | 1.8 ± 0.6 | 0.7 | 6.0 | 1.79 ± 0.83 |
| `mattcl-solver/aoc run 3 input-lanjian` | 1.6 ± 0.6 | 0.7 | 5.3 | 1.60 ± 0.83 |
| `mattcl-solver/aoc run 3 input-mattcl` | 1.4 ± 0.6 | 0.6 | 5.5 | 1.35 ± 0.74 |
| `mattcl-solver/aoc run 3 input-pting` | 1.0 ± 0.3 | 0.7 | 3.4 | 1.00 |
| `python pting/day03.py input-aspidites` | 37.7 ± 5.0 | 30.0 | 53.1 | 36.68 ± 13.32 |
| `python pting/day03.py input-kcen` | 37.7 ± 6.0 | 29.8 | 62.7 | 36.70 ± 13.72 |
| `python pting/day03.py input-lanjian` | 36.6 ± 7.2 | 27.0 | 67.9 | 35.62 ± 13.92 |
| `python pting/day03.py input-mattcl` | 35.8 ± 9.8 | 27.4 | 68.8 | 34.84 ± 15.15 |
| `python pting/day03.py input-pting` | 34.8 ± 5.5 | 29.4 | 67.6 | 33.88 ± 12.65 |
