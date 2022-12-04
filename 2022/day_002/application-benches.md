# Day 2 benchmarks

[link to problem](http://adventofcode.com/2022/day/2)

The following benchmarks are auto-generated via [hyperfine](https://github.com/sharkdp/hyperfine) by a ci system running on shared hardware. Results may be inaccurate, particularly for execution times < 5ms, as per the hyperfine warnings.

[ci pipeline](http://ci.papercode.net:8080/teams/aoc2022/pipelines/aoc-compare-2022)

The "official" inputs were aggregated from repositories participating in the generation of these benchmarks. The "large" inputs (if any) were sourced from various places, including the subreddit.

## Repos (with solutions for day 2)

- [aspidites](https://github.com/aspidites/aoc2022)
- [aspidites](https://github.com/aspidites/aoc2022)
- [kcen](https://github.com/kcen/AdventOfCode)
- [kcen](https://github.com/kcen/AdventOfCode)
- [lanjian](https://github.com/LanJian/aoc-2022)
- [lanjian](https://github.com/LanJian/aoc-2022)
- [mattcl](https://github.com/mattcl/aoc2022)
- [mattcl](https://github.com/mattcl/aoc2022)
- [pting](https://github.com/pting/aoc2022)
- [pting](https://github.com/pting/aoc2022)

## Benchmarks with officially generated inputs
| Command | Mean [ms] | Min [ms] | Max [ms] | Relative |
|:---|---:|---:|---:|---:|
| `aspidites-solver/aoc -i input-aspidites -d 2` | 13.3 ± 0.9 | 11.6 | 16.9 | 7.72 ± 3.15 |
| `aspidites-solver/aoc -i input-kcen -d 2` | 12.7 ± 0.8 | 11.3 | 15.6 | 7.39 ± 3.00 |
| `aspidites-solver/aoc -i input-lanjian -d 2` | 12.9 ± 1.1 | 11.3 | 24.7 | 7.48 ± 3.06 |
| `aspidites-solver/aoc -i input-mattcl -d 2` | 13.1 ± 1.2 | 11.4 | 24.0 | 7.59 ± 3.13 |
| `aspidites-solver/aoc -i input-pting -d 2` | 13.0 ± 1.3 | 11.8 | 23.8 | 7.53 ± 3.12 |
| `kcen/2022/02/solve input-aspidites` | 2.3 ± 1.0 | 0.7 | 10.1 | 1.32 ± 0.78 |
| `kcen/2022/02/solve input-kcen` | 1.7 ± 0.7 | 0.9 | 9.4 | 1.00 |
| `kcen/2022/02/solve input-lanjian` | 1.9 ± 0.7 | 0.8 | 5.4 | 1.10 ± 0.59 |
| `kcen/2022/02/solve input-mattcl` | 2.0 ± 0.8 | 0.8 | 7.2 | 1.16 ± 0.64 |
| `kcen/2022/02/solve input-pting` | 2.6 ± 1.4 | 1.0 | 25.5 | 1.51 ± 1.02 |
| `lanjian/day_02 input-aspidites` | 2.2 ± 1.2 | 1.1 | 21.1 | 1.26 ± 0.86 |
| `lanjian/day_02 input-kcen` | 1.8 ± 0.6 | 1.1 | 7.6 | 1.05 ± 0.56 |
| `lanjian/day_02 input-lanjian` | 2.7 ± 1.0 | 1.1 | 9.0 | 1.57 ± 0.84 |
| `lanjian/day_02 input-mattcl` | 2.5 ± 0.8 | 1.2 | 12.5 | 1.48 ± 0.75 |
| `lanjian/day_02 input-pting` | 2.5 ± 0.9 | 1.1 | 7.0 | 1.45 ± 0.79 |
| `mattcl-solver/aoc run 2 input-aspidites` | 1.8 ± 0.7 | 0.9 | 8.7 | 1.03 ± 0.60 |
| `mattcl-solver/aoc run 2 input-kcen` | 2.1 ± 0.9 | 0.9 | 7.2 | 1.21 ± 0.70 |
| `mattcl-solver/aoc run 2 input-lanjian` | 2.8 ± 1.7 | 0.9 | 17.8 | 1.62 ± 1.16 |
| `mattcl-solver/aoc run 2 input-mattcl` | 2.2 ± 0.8 | 0.8 | 13.2 | 1.25 ± 0.70 |
| `mattcl-solver/aoc run 2 input-pting` | 2.2 ± 0.8 | 1.0 | 6.7 | 1.27 ± 0.67 |
| `python pting/day02.py input-aspidites` | 44.4 ± 11.2 | 32.5 | 86.4 | 25.73 ± 12.19 |
| `python pting/day02.py input-kcen` | 33.7 ± 3.0 | 29.5 | 42.7 | 19.53 ± 8.03 |
| `python pting/day02.py input-lanjian` | 40.3 ± 8.0 | 29.6 | 66.5 | 23.35 ± 10.47 |
| `python pting/day02.py input-mattcl` | 36.3 ± 6.3 | 28.3 | 57.7 | 21.09 ± 9.23 |
| `python pting/day02.py input-pting` | 41.5 ± 15.9 | 27.7 | 98.6 | 24.09 ± 13.38 |
