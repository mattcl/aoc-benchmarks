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
| `aspidites-solver/aoc -i input-aspidites -d 2` | 12.3 ± 0.8 | 11.2 | 16.1 | 8.68 ± 4.44 |
| `aspidites-solver/aoc -i input-kcen -d 2` | 12.6 ± 0.6 | 11.5 | 15.8 | 8.93 ± 4.55 |
| `aspidites-solver/aoc -i input-lanjian -d 2` | 12.1 ± 0.6 | 11.3 | 14.3 | 8.52 ± 4.35 |
| `aspidites-solver/aoc -i input-mattcl -d 2` | 12.6 ± 1.0 | 11.0 | 15.5 | 8.90 ± 4.57 |
| `aspidites-solver/aoc -i input-pting -d 2` | 12.9 ± 1.2 | 11.7 | 25.3 | 9.11 ± 4.70 |
| `kcen/2022/02/solve input-aspidites` | 1.7 ± 0.6 | 0.9 | 6.3 | 1.20 ± 0.76 |
| `kcen/2022/02/solve input-kcen` | 1.9 ± 0.7 | 0.9 | 6.5 | 1.33 ± 0.84 |
| `kcen/2022/02/solve input-lanjian` | 1.8 ± 0.7 | 0.7 | 5.4 | 1.25 ± 0.80 |
| `kcen/2022/02/solve input-mattcl` | 1.4 ± 0.7 | 0.7 | 4.8 | 1.00 |
| `kcen/2022/02/solve input-pting` | 1.5 ± 0.8 | 0.6 | 14.3 | 1.07 ± 0.77 |
| `lanjian/day_02 input-aspidites` | 3.0 ± 1.5 | 1.2 | 17.6 | 2.12 ± 1.52 |
| `lanjian/day_02 input-kcen` | 2.3 ± 1.0 | 1.1 | 9.2 | 1.61 ± 1.08 |
| `lanjian/day_02 input-lanjian` | 1.8 ± 0.8 | 1.0 | 6.7 | 1.30 ± 0.85 |
| `lanjian/day_02 input-mattcl` | 1.9 ± 0.8 | 1.0 | 4.9 | 1.35 ± 0.87 |
| `lanjian/day_02 input-pting` | 2.0 ± 0.6 | 1.0 | 5.4 | 1.39 ± 0.82 |
| `mattcl-solver/aoc run 2 input-aspidites` | 1.7 ± 1.1 | 0.8 | 15.0 | 1.22 ± 0.98 |
| `mattcl-solver/aoc run 2 input-kcen` | 1.9 ± 0.8 | 0.8 | 7.4 | 1.32 ± 0.86 |
| `mattcl-solver/aoc run 2 input-lanjian` | 1.5 ± 0.6 | 0.8 | 4.2 | 1.07 ± 0.69 |
| `mattcl-solver/aoc run 2 input-mattcl` | 1.7 ± 0.6 | 0.9 | 6.8 | 1.23 ± 0.76 |
| `mattcl-solver/aoc run 2 input-pting` | 2.2 ± 0.7 | 1.0 | 5.4 | 1.58 ± 0.94 |
| `python pting/day02.py input-aspidites` | 36.0 ± 7.6 | 27.8 | 73.7 | 25.48 ± 14.01 |
| `python pting/day02.py input-kcen` | 34.6 ± 4.6 | 28.2 | 53.4 | 24.47 ± 12.84 |
| `python pting/day02.py input-lanjian` | 35.4 ± 6.3 | 28.8 | 78.3 | 25.04 ± 13.46 |
| `python pting/day02.py input-mattcl` | 38.6 ± 9.5 | 28.2 | 80.2 | 27.30 ± 15.38 |
| `python pting/day02.py input-pting` | 35.9 ± 4.9 | 28.8 | 55.4 | 25.40 ± 13.35 |
