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
| `aspidites-solver/aoc -i input-aspidites -d 1` | 13.4 ± 1.4 | 11.7 | 25.0 | 7.74 ± 5.06 |
| `aspidites-solver/aoc -i input-kcen -d 1` | 12.9 ± 1.7 | 11.3 | 24.8 | 7.44 ± 4.90 |
| `aspidites-solver/aoc -i input-lanjian -d 1` | 12.9 ± 0.8 | 11.5 | 15.3 | 7.48 ± 4.85 |
| `aspidites-solver/aoc -i input-mattcl -d 1` | 13.4 ± 1.1 | 12.1 | 23.2 | 7.75 ± 5.04 |
| `aspidites-solver/aoc -i input-pting -d 1` | 13.3 ± 1.5 | 11.5 | 23.6 | 7.71 ± 5.04 |
| `kcen/2022/01/solve input-aspidites` | 123.1 ± 12.2 | 100.0 | 152.8 | 71.16 ± 46.45 |
| `kcen/2022/01/solve input-kcen` | 117.3 ± 12.0 | 104.7 | 152.4 | 67.81 ± 44.29 |
| `kcen/2022/01/solve input-lanjian` | 117.9 ± 14.6 | 91.1 | 150.6 | 68.18 ± 44.79 |
| `kcen/2022/01/solve input-mattcl` | 126.2 ± 19.6 | 86.0 | 170.7 | 72.95 ± 48.41 |
| `kcen/2022/01/solve input-pting` | 112.3 ± 9.0 | 93.8 | 125.9 | 64.96 ± 42.24 |
| `lanjian/day_01 input-aspidites` | 2.0 ± 0.7 | 0.9 | 5.9 | 1.18 ± 0.87 |
| `lanjian/day_01 input-kcen` | 2.4 ± 0.8 | 1.0 | 5.7 | 1.41 ± 1.01 |
| `lanjian/day_01 input-lanjian` | 1.8 ± 0.6 | 1.0 | 4.9 | 1.04 ± 0.77 |
| `lanjian/day_01 input-mattcl` | 1.9 ± 0.7 | 0.8 | 5.8 | 1.11 ± 0.84 |
| `lanjian/day_01 input-pting` | 2.0 ± 0.7 | 1.0 | 5.1 | 1.15 ± 0.84 |
| `mattcl-solver/aoc run 1 input-aspidites` | 2.1 ± 0.9 | 0.7 | 6.0 | 1.23 ± 0.93 |
| `mattcl-solver/aoc run 1 input-kcen` | 2.3 ± 0.8 | 0.8 | 8.1 | 1.35 ± 0.99 |
| `mattcl-solver/aoc run 1 input-lanjian` | 2.0 ± 0.6 | 0.8 | 5.1 | 1.14 ± 0.82 |
| `mattcl-solver/aoc run 1 input-mattcl` | 1.7 ± 1.1 | 0.7 | 24.7 | 1.00 |
| `mattcl-solver/aoc run 1 input-pting` | 2.5 ± 1.4 | 0.9 | 21.7 | 1.45 ± 1.22 |
| `python pting/day01.py input-aspidites` | 39.7 ± 8.8 | 29.5 | 72.0 | 22.95 ± 15.65 |
| `python pting/day01.py input-kcen` | 38.5 ± 6.6 | 29.0 | 62.8 | 22.24 ± 14.86 |
| `python pting/day01.py input-lanjian` | 38.5 ± 8.3 | 26.2 | 65.8 | 22.25 ± 15.13 |
| `python pting/day01.py input-mattcl` | 38.6 ± 8.3 | 27.7 | 67.5 | 22.32 ± 15.19 |
| `python pting/day01.py input-pting` | 35.9 ± 5.0 | 27.6 | 53.2 | 20.76 ± 13.71 |
