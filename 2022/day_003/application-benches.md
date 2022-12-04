# Day 3 benchmarks

[link to problem](http://adventofcode.com/2022/day/3)

The following benchmarks are auto-generated via [hyperfine](https://github.com/sharkdp/hyperfine) by a ci system running on shared hardware. Results may be inaccurate, particularly for execution times < 5ms, as per the hyperfine warnings.

[ci pipeline](http://ci.papercode.net:8080/teams/aoc2022/pipelines/aoc-compare-2022)

The "official" inputs were aggregated from repositories participating in the generation of these benchmarks. The "large" inputs (if any) were sourced from various places, including the subreddit.

## Repos (with solutions for day 3)

- [aspidites](https://github.com/aspidites/aoc2022)
- [aspidites](https://github.com/aspidites/aoc2022)
- [aspidites](https://github.com/aspidites/aoc2022)
- [kcen](https://github.com/kcen/AdventOfCode)
- [kcen](https://github.com/kcen/AdventOfCode)
- [kcen](https://github.com/kcen/AdventOfCode)
- [lanjian](https://github.com/LanJian/aoc-2022)
- [lanjian](https://github.com/LanJian/aoc-2022)
- [lanjian](https://github.com/LanJian/aoc-2022)
- [mattcl](https://github.com/mattcl/aoc2022)
- [mattcl](https://github.com/mattcl/aoc2022)
- [mattcl](https://github.com/mattcl/aoc2022)
- [pting](https://github.com/pting/aoc2022)
- [pting](https://github.com/pting/aoc2022)
- [pting](https://github.com/pting/aoc2022)

## Benchmarks with officially generated inputs
| Command | Mean [ms] | Min [ms] | Max [ms] | Relative |
|:---|---:|---:|---:|---:|
| `aspidites-solver/aoc -i input-aspidites -d 3` | 15.0 ± 4.4 | 11.7 | 25.5 | 12.63 ± 6.89 |
| `aspidites-solver/aoc -i input-kcen -d 3` | 14.5 ± 4.4 | 11.6 | 25.4 | 12.24 ± 6.71 |
| `aspidites-solver/aoc -i input-lanjian -d 3` | 16.4 ± 5.8 | 11.6 | 36.6 | 13.80 ± 7.98 |
| `aspidites-solver/aoc -i input-mattcl -d 3` | 14.0 ± 3.7 | 11.6 | 24.9 | 11.77 ± 6.23 |
| `aspidites-solver/aoc -i input-pting -d 3` | 15.0 ± 4.8 | 11.5 | 28.3 | 12.65 ± 7.09 |
| `kcen/2022/03/solve input-aspidites` | 242.7 ± 20.0 | 210.4 | 265.0 | 204.38 ± 95.17 |
| `kcen/2022/03/solve input-kcen` | 251.4 ± 38.9 | 206.7 | 337.9 | 211.70 ± 102.41 |
| `kcen/2022/03/solve input-lanjian` | 260.3 ± 28.6 | 209.1 | 297.4 | 219.25 ± 103.33 |
| `kcen/2022/03/solve input-mattcl` | 241.7 ± 16.9 | 222.8 | 269.8 | 203.51 ± 94.35 |
| `kcen/2022/03/solve input-pting` | 274.2 ± 20.6 | 241.4 | 313.0 | 230.91 ± 107.25 |
| `lanjian/day_03 input-aspidites` | 1.5 ± 0.7 | 0.5 | 10.0 | 1.29 ± 0.81 |
| `lanjian/day_03 input-kcen` | 1.6 ± 0.8 | 0.4 | 6.9 | 1.39 ± 0.94 |
| `lanjian/day_03 input-lanjian` | 1.5 ± 0.6 | 0.6 | 4.2 | 1.23 ± 0.77 |
| `lanjian/day_03 input-mattcl` | 1.5 ± 0.8 | 0.5 | 4.5 | 1.26 ± 0.90 |
| `lanjian/day_03 input-pting` | 1.2 ± 0.5 | 0.4 | 4.7 | 1.00 |
| `mattcl-solver/aoc run 3 input-aspidites` | 1.7 ± 0.7 | 0.5 | 6.0 | 1.41 ± 0.85 |
| `mattcl-solver/aoc run 3 input-kcen` | 1.5 ± 0.8 | 0.5 | 6.7 | 1.26 ± 0.88 |
| `mattcl-solver/aoc run 3 input-lanjian` | 1.2 ± 0.5 | 0.5 | 3.6 | 1.04 ± 0.63 |
| `mattcl-solver/aoc run 3 input-mattcl` | 1.9 ± 1.0 | 0.5 | 10.5 | 1.56 ± 1.13 |
| `mattcl-solver/aoc run 3 input-pting` | 1.3 ± 0.6 | 0.6 | 10.1 | 1.13 ± 0.75 |
| `python pting/day03.py input-aspidites` | 34.3 ± 3.8 | 28.6 | 44.6 | 28.89 ± 13.61 |
| `python pting/day03.py input-kcen` | 40.5 ± 8.1 | 29.9 | 68.5 | 34.09 ± 17.04 |
| `python pting/day03.py input-lanjian` | 33.8 ± 4.8 | 28.0 | 53.6 | 28.50 ± 13.67 |
| `python pting/day03.py input-mattcl` | 39.5 ± 8.1 | 30.3 | 74.8 | 33.23 ± 16.69 |
| `python pting/day03.py input-pting` | 34.4 ± 6.4 | 27.4 | 65.5 | 29.01 ± 14.35 |
