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
| `aspidites-solver/aoc -i input-aspidites -d 3` | 15.5 ± 4.6 | 11.9 | 27.4 | 12.92 ± 6.65 |
| `aspidites-solver/aoc -i input-kcen -d 3` | 14.2 ± 3.3 | 11.9 | 27.4 | 11.88 ± 5.68 |
| `aspidites-solver/aoc -i input-lanjian -d 3` | 16.9 ± 5.6 | 11.6 | 30.9 | 14.12 ± 7.54 |
| `aspidites-solver/aoc -i input-mattcl -d 3` | 13.2 ± 3.0 | 11.6 | 25.4 | 11.01 ± 5.27 |
| `aspidites-solver/aoc -i input-pting -d 3` | 13.9 ± 3.6 | 11.6 | 27.7 | 11.66 ± 5.76 |
| `kcen/2022/03/solve input-aspidites` | 279.7 ± 20.3 | 256.7 | 315.2 | 233.94 ± 99.73 |
| `kcen/2022/03/solve input-kcen` | 262.3 ± 31.0 | 214.3 | 337.0 | 219.32 ± 95.71 |
| `kcen/2022/03/solve input-lanjian` | 241.3 ± 33.2 | 206.3 | 313.3 | 201.83 ± 89.21 |
| `kcen/2022/03/solve input-mattcl` | 242.3 ± 19.5 | 219.5 | 287.8 | 202.63 ± 86.67 |
| `kcen/2022/03/solve input-pting` | 241.4 ± 19.1 | 202.1 | 267.3 | 201.87 ± 86.30 |
| `lanjian/day_03 input-aspidites` | 1.3 ± 0.5 | 0.8 | 5.8 | 1.05 ± 0.58 |
| `lanjian/day_03 input-kcen` | 1.9 ± 0.9 | 0.7 | 10.5 | 1.55 ± 0.97 |
| `lanjian/day_03 input-lanjian` | 1.5 ± 0.6 | 0.5 | 4.5 | 1.29 ± 0.75 |
| `lanjian/day_03 input-mattcl` | 1.6 ± 0.6 | 0.6 | 5.8 | 1.31 ± 0.77 |
| `lanjian/day_03 input-pting` | 1.3 ± 0.7 | 0.7 | 8.3 | 1.11 ± 0.76 |
| `mattcl-solver/aoc run 3 input-aspidites` | 1.2 ± 0.5 | 0.7 | 7.9 | 1.00 |
| `mattcl-solver/aoc run 3 input-kcen` | 2.1 ± 0.7 | 0.8 | 6.0 | 1.72 ± 0.92 |
| `mattcl-solver/aoc run 3 input-lanjian` | 1.7 ± 0.6 | 0.7 | 5.5 | 1.40 ± 0.79 |
| `mattcl-solver/aoc run 3 input-mattcl` | 1.4 ± 0.7 | 0.5 | 7.4 | 1.18 ± 0.74 |
| `mattcl-solver/aoc run 3 input-pting` | 2.0 ± 1.3 | 0.7 | 16.1 | 1.66 ± 1.27 |
| `python pting/day03.py input-aspidites` | 34.4 ± 5.2 | 28.1 | 54.8 | 28.75 ± 12.84 |
| `python pting/day03.py input-kcen` | 41.8 ± 11.7 | 26.7 | 73.2 | 34.99 ± 17.65 |
| `python pting/day03.py input-lanjian` | 38.5 ± 9.5 | 27.0 | 87.3 | 32.20 ± 15.67 |
| `python pting/day03.py input-mattcl` | 37.7 ± 9.5 | 27.3 | 72.6 | 31.51 ± 15.44 |
| `python pting/day03.py input-pting` | 37.4 ± 7.0 | 27.2 | 64.2 | 31.24 ± 14.35 |
