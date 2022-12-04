# Day 2 benchmarks

[link to problem](http://adventofcode.com/2022/day/2)

The following benchmarks are auto-generated via [hyperfine](https://github.com/sharkdp/hyperfine) by a ci system running on shared hardware. Results may be inaccurate, particularly for execution times < 5ms, as per the hyperfine warnings.

[ci pipeline](http://ci.papercode.net:8080/teams/aoc2022/pipelines/aoc-compare-2022)

The "official" inputs were aggregated from repositories participating in the generation of these benchmarks. The "large" inputs (if any) were sourced from various places, including the subreddit.

## Repos (with solutions for day 2)


- [aspidites](https://github.com/aspidites/aoc2022)
- [kcen](https://github.com/kcen/AdventOfCode)
- [lanjian](https://github.com/LanJian/aoc-2022)
- [mattcl](https://github.com/mattcl/aoc2022)
- [pting](https://github.com/pting/aoc2022)

## Benchmarks with officially generated inputs
| Command | Mean [ms] | Min [ms] | Max [ms] | Relative |
|:---|---:|---:|---:|---:|
| `aspidites-solver/aoc -i input-aspidites -d 2` | 12.7 ± 1.5 | 11.1 | 22.4 | 10.46 ± 4.08 |
| `aspidites-solver/aoc -i input-kcen -d 2` | 12.1 ± 0.8 | 11.1 | 18.9 | 9.94 ± 3.76 |
| `aspidites-solver/aoc -i input-lanjian -d 2` | 12.6 ± 0.9 | 11.3 | 20.1 | 10.39 ± 3.94 |
| `aspidites-solver/aoc -i input-mattcl -d 2` | 12.0 ± 0.7 | 11.1 | 15.7 | 9.88 ± 3.71 |
| `aspidites-solver/aoc -i input-pting -d 2` | 12.8 ± 1.6 | 11.3 | 24.6 | 10.54 ± 4.14 |
| `kcen/2022/02/solve input-aspidites` | 1.4 ± 0.7 | 0.7 | 6.2 | 1.19 ± 0.72 |
| `kcen/2022/02/solve input-kcen` | 1.6 ± 0.9 | 0.6 | 10.5 | 1.31 ± 0.91 |
| `kcen/2022/02/solve input-lanjian` | 1.8 ± 0.8 | 0.5 | 5.0 | 1.52 ± 0.87 |
| `kcen/2022/02/solve input-mattcl` | 1.7 ± 0.9 | 0.7 | 10.4 | 1.37 ± 0.92 |
| `kcen/2022/02/solve input-pting` | 1.7 ± 0.7 | 0.7 | 5.7 | 1.40 ± 0.77 |
| `lanjian/day_02 input-aspidites` | 2.1 ± 1.2 | 1.1 | 12.2 | 1.74 ± 1.17 |
| `lanjian/day_02 input-kcen` | 2.0 ± 0.9 | 0.9 | 6.5 | 1.68 ± 0.97 |
| `lanjian/day_02 input-lanjian` | 1.5 ± 0.6 | 0.9 | 5.4 | 1.23 ± 0.70 |
| `lanjian/day_02 input-mattcl` | 2.3 ± 1.2 | 0.9 | 8.2 | 1.93 ± 1.22 |
| `lanjian/day_02 input-pting` | 2.7 ± 1.3 | 1.0 | 8.5 | 2.23 ± 1.34 |
| `mattcl-solver/aoc run 2 input-aspidites` | 1.2 ± 0.5 | 0.8 | 5.7 | 1.00 |
| `mattcl-solver/aoc run 2 input-kcen` | 2.4 ± 0.8 | 0.8 | 7.3 | 1.94 ± 0.99 |
| `mattcl-solver/aoc run 2 input-lanjian` | 1.2 ± 0.5 | 0.8 | 5.2 | 1.03 ± 0.53 |
| `mattcl-solver/aoc run 2 input-mattcl` | 1.8 ± 0.8 | 0.7 | 5.7 | 1.47 ± 0.83 |
| `mattcl-solver/aoc run 2 input-pting` | 1.5 ± 0.8 | 0.7 | 7.0 | 1.24 ± 0.84 |
| `python pting/day02.py input-aspidites` | 36.0 ± 6.0 | 30.7 | 59.6 | 29.73 ± 12.10 |
| `python pting/day02.py input-kcen` | 37.7 ± 7.4 | 29.4 | 72.4 | 31.11 ± 13.08 |
| `python pting/day02.py input-lanjian` | 31.7 ± 2.8 | 28.1 | 46.6 | 26.14 ± 9.99 |
| `python pting/day02.py input-mattcl` | 40.7 ± 10.3 | 27.7 | 79.4 | 33.59 ± 15.12 |
| `python pting/day02.py input-pting` | 38.3 ± 6.8 | 28.9 | 68.3 | 31.64 ± 13.03 |
