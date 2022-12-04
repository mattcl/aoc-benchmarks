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
| `aspidites-solver/aoc -i input-aspidites -d 3` | 12.7 ± 2.8 | 11.3 | 27.4 | 11.53 ± 6.65 |
| `aspidites-solver/aoc -i input-kcen -d 3` | 14.8 ± 4.5 | 11.6 | 28.1 | 13.42 ± 8.21 |
| `aspidites-solver/aoc -i input-lanjian -d 3` | 12.5 ± 2.1 | 11.3 | 24.3 | 11.33 ± 6.32 |
| `aspidites-solver/aoc -i input-mattcl -d 3` | 15.0 ± 4.7 | 11.5 | 30.3 | 13.62 ± 8.38 |
| `aspidites-solver/aoc -i input-pting -d 3` | 12.8 ± 2.5 | 11.5 | 24.8 | 11.62 ± 6.57 |
| `kcen/2022/03/solve input-aspidites` | 299.6 ± 46.6 | 251.4 | 378.2 | 271.67 ± 150.45 |
| `kcen/2022/03/solve input-kcen` | 284.7 ± 21.3 | 239.8 | 316.2 | 258.16 ± 138.58 |
| `kcen/2022/03/solve input-lanjian` | 237.3 ± 12.9 | 219.1 | 261.9 | 215.18 ± 114.98 |
| `kcen/2022/03/solve input-mattcl` | 245.0 ± 33.6 | 209.5 | 302.0 | 222.19 ± 121.97 |
| `kcen/2022/03/solve input-pting` | 239.3 ± 21.9 | 202.6 | 283.7 | 216.98 ± 117.03 |
| `lanjian/day_03 input-aspidites` | 2.0 ± 1.7 | 0.5 | 27.5 | 1.77 ± 1.78 |
| `lanjian/day_03 input-kcen` | 1.6 ± 0.7 | 0.5 | 4.8 | 1.41 ± 0.97 |
| `lanjian/day_03 input-lanjian` | 1.1 ± 0.6 | 0.6 | 6.4 | 1.00 |
| `lanjian/day_03 input-mattcl` | 1.5 ± 0.7 | 0.4 | 7.9 | 1.38 ± 0.99 |
| `lanjian/day_03 input-pting` | 1.3 ± 0.6 | 0.4 | 5.8 | 1.17 ± 0.85 |
| `mattcl-solver/aoc run 3 input-aspidites` | 1.7 ± 0.7 | 0.6 | 5.8 | 1.51 ± 1.03 |
| `mattcl-solver/aoc run 3 input-kcen` | 1.4 ± 0.6 | 0.7 | 3.9 | 1.28 ± 0.85 |
| `mattcl-solver/aoc run 3 input-lanjian` | 1.4 ± 0.6 | 0.6 | 6.9 | 1.25 ± 0.88 |
| `mattcl-solver/aoc run 3 input-mattcl` | 1.3 ± 0.7 | 0.6 | 11.0 | 1.20 ± 0.88 |
| `mattcl-solver/aoc run 3 input-pting` | 1.3 ± 0.6 | 0.6 | 5.5 | 1.16 ± 0.83 |
| `python pting/day03.py input-aspidites` | 37.2 ± 9.6 | 28.7 | 90.6 | 33.77 ± 19.96 |
| `python pting/day03.py input-kcen` | 35.6 ± 4.6 | 29.7 | 54.7 | 32.31 ± 17.67 |
| `python pting/day03.py input-lanjian` | 35.6 ± 5.3 | 29.3 | 70.4 | 32.32 ± 17.85 |
| `python pting/day03.py input-mattcl` | 37.3 ± 6.9 | 26.4 | 60.4 | 33.86 ± 19.05 |
| `python pting/day03.py input-pting` | 42.7 ± 10.3 | 27.4 | 79.5 | 38.69 ± 22.58 |
