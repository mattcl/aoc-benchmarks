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
| `aspidites-solver/aoc -i input-aspidites -d 2` | 12.2 ± 0.8 | 11.2 | 18.9 | 13.79 ± 4.97 |
| `aspidites-solver/aoc -i input-kcen -d 2` | 11.6 ± 0.5 | 10.8 | 13.5 | 13.11 ± 4.67 |
| `aspidites-solver/aoc -i input-lanjian -d 2` | 12.1 ± 0.8 | 11.1 | 15.1 | 13.69 ± 4.92 |
| `aspidites-solver/aoc -i input-mattcl -d 2` | 12.4 ± 0.8 | 11.3 | 16.3 | 13.99 ± 5.03 |
| `aspidites-solver/aoc -i input-pting -d 2` | 12.1 ± 1.1 | 10.8 | 21.3 | 13.71 ± 5.01 |
| `kcen/2022/02/solve input-aspidites` | 1.4 ± 1.0 | 0.6 | 25.6 | 1.57 ± 1.29 |
| `kcen/2022/02/solve input-kcen` | 1.0 ± 0.5 | 0.5 | 3.8 | 1.08 ± 0.65 |
| `kcen/2022/02/solve input-lanjian` | 1.4 ± 0.6 | 0.6 | 6.4 | 1.58 ± 0.92 |
| `kcen/2022/02/solve input-mattcl` | 1.5 ± 0.8 | 0.6 | 9.2 | 1.70 ± 1.06 |
| `kcen/2022/02/solve input-pting` | 1.5 ± 0.7 | 0.6 | 5.4 | 1.75 ± 1.01 |
| `lanjian/day_02 input-aspidites` | 1.4 ± 0.7 | 0.7 | 13.5 | 1.58 ± 0.97 |
| `lanjian/day_02 input-kcen` | 2.1 ± 1.0 | 0.9 | 8.9 | 2.33 ± 1.40 |
| `lanjian/day_02 input-lanjian` | 2.0 ± 0.9 | 0.8 | 7.2 | 2.24 ± 1.26 |
| `lanjian/day_02 input-mattcl` | 1.8 ± 0.9 | 0.8 | 14.0 | 1.98 ± 1.28 |
| `lanjian/day_02 input-pting` | 2.4 ± 1.1 | 0.8 | 11.8 | 2.74 ± 1.56 |
| `mattcl-solver/aoc run 2 input-aspidites` | 1.3 ± 0.5 | 0.6 | 6.7 | 1.50 ± 0.82 |
| `mattcl-solver/aoc run 2 input-kcen` | 2.1 ± 0.7 | 0.8 | 6.4 | 2.41 ± 1.19 |
| `mattcl-solver/aoc run 2 input-lanjian` | 1.6 ± 0.7 | 0.6 | 5.7 | 1.85 ± 0.98 |
| `mattcl-solver/aoc run 2 input-mattcl` | 0.9 ± 0.3 | 0.4 | 3.4 | 1.00 |
| `mattcl-solver/aoc run 2 input-pting` | 1.3 ± 0.6 | 0.4 | 5.8 | 1.52 ± 0.84 |
| `python pting/day02.py input-aspidites` | 38.4 ± 8.5 | 28.5 | 89.5 | 43.30 ± 18.05 |
| `python pting/day02.py input-kcen` | 34.0 ± 4.0 | 27.8 | 53.6 | 38.43 ± 14.32 |
| `python pting/day02.py input-lanjian` | 38.2 ± 8.0 | 29.1 | 62.8 | 43.11 ± 17.75 |
| `python pting/day02.py input-mattcl` | 40.7 ± 7.6 | 29.9 | 69.2 | 45.96 ± 18.41 |
| `python pting/day02.py input-pting` | 40.4 ± 11.1 | 28.8 | 86.4 | 45.57 ± 20.44 |
