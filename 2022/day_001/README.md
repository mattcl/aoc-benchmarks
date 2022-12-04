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
| `aspidites-solver/aoc -i input-aspidites -d 1` | 12.7 ± 1.4 | 11.5 | 26.2 | 8.85 ± 3.79 |
| `aspidites-solver/aoc -i input-kcen -d 1` | 12.3 ± 1.2 | 11.3 | 23.7 | 8.61 ± 3.66 |
| `aspidites-solver/aoc -i input-lanjian -d 1` | 12.8 ± 0.9 | 11.6 | 17.6 | 8.93 ± 3.74 |
| `aspidites-solver/aoc -i input-mattcl -d 1` | 13.4 ± 2.3 | 11.5 | 39.8 | 9.36 ± 4.19 |
| `aspidites-solver/aoc -i input-pting -d 1` | 12.8 ± 0.9 | 11.3 | 17.7 | 8.93 ± 3.75 |
| `kcen/2022/01/solve input-aspidites` | 114.1 ± 9.9 | 100.2 | 131.6 | 79.64 ± 33.64 |
| `kcen/2022/01/solve input-kcen` | 108.9 ± 14.1 | 89.1 | 151.4 | 76.04 ± 32.95 |
| `kcen/2022/01/solve input-lanjian` | 109.3 ± 17.7 | 88.6 | 169.6 | 76.34 ± 33.88 |
| `kcen/2022/01/solve input-mattcl` | 102.5 ± 8.4 | 87.9 | 127.2 | 71.55 ± 30.15 |
| `kcen/2022/01/solve input-pting` | 115.2 ± 13.7 | 98.6 | 161.7 | 80.41 ± 34.59 |
| `lanjian/day_01 input-aspidites` | 2.1 ± 0.9 | 0.9 | 6.2 | 1.43 ± 0.87 |
| `lanjian/day_01 input-kcen` | 1.5 ± 0.7 | 0.8 | 9.7 | 1.04 ± 0.65 |
| `lanjian/day_01 input-lanjian` | 2.1 ± 0.9 | 1.0 | 9.1 | 1.50 ± 0.89 |
| `lanjian/day_01 input-mattcl` | 2.1 ± 0.9 | 1.0 | 6.9 | 1.49 ± 0.88 |
| `lanjian/day_01 input-pting` | 2.0 ± 0.8 | 0.9 | 8.8 | 1.38 ± 0.80 |
| `mattcl-solver/aoc run 1 input-aspidites` | 2.0 ± 0.7 | 0.8 | 8.2 | 1.43 ± 0.75 |
| `mattcl-solver/aoc run 1 input-kcen` | 1.7 ± 0.8 | 0.7 | 5.7 | 1.22 ± 0.74 |
| `mattcl-solver/aoc run 1 input-lanjian` | 2.1 ± 0.9 | 0.8 | 8.1 | 1.48 ± 0.86 |
| `mattcl-solver/aoc run 1 input-mattcl` | 2.1 ± 0.8 | 0.8 | 6.7 | 1.50 ± 0.82 |
| `mattcl-solver/aoc run 1 input-pting` | 1.4 ± 0.6 | 0.6 | 5.5 | 1.00 |
| `python pting/day01.py input-aspidites` | 36.4 ± 9.1 | 26.6 | 75.9 | 25.44 ± 12.28 |
| `python pting/day01.py input-kcen` | 37.4 ± 8.1 | 28.3 | 71.4 | 26.08 ± 12.18 |
| `python pting/day01.py input-lanjian` | 35.3 ± 7.7 | 26.1 | 60.7 | 24.62 ± 11.50 |
| `python pting/day01.py input-mattcl` | 33.6 ± 3.6 | 26.8 | 45.9 | 23.44 ± 10.00 |
| `python pting/day01.py input-pting` | 34.4 ± 6.3 | 25.7 | 56.0 | 24.02 ± 10.85 |
