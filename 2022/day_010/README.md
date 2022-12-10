# Day 10 benchmarks

[link to problem](http://adventofcode.com/2022/day/10)

The following benchmarks are auto-generated via [hyperfine](https://github.com/sharkdp/hyperfine) by a ci system running on shared hardware. Results may be inaccurate, particularly for execution times < 5ms, as per the hyperfine warnings.

[ci pipeline](http://ci.papercode.net:8080/teams/aoc2022/pipelines/aoc-compare-2022)

The "official" inputs were aggregated from repositories participating in the generation of these benchmarks. The "large" inputs (if any) were sourced from various places, including the subreddit.

## Repos (with solutions for day 10)


- [lanjian](https://github.com/LanJian/aoc-2022)
- [mattcl](https://github.com/mattcl/aoc2022)
- [pting](https://github.com/pting/aoc2022)

## Benchmarks with officially generated inputs
| Command | Mean [ms] | Min [ms] | Max [ms] | Relative |
|:---|---:|---:|---:|---:|
| `lanjian/day_10 input-lanjian` | 2.6 ± 1.5 | 0.8 | 16.4 | 1.29 ± 0.95 |
| `lanjian/day_10 input-mattcl` | 2.1 ± 0.9 | 0.8 | 11.1 | 1.00 |
| `lanjian/day_10 input-pting` | 2.2 ± 1.3 | 0.6 | 16.4 | 1.06 ± 0.78 |
| `mattcl-solver/aoc run 10 input-lanjian` | 2.4 ± 0.8 | 0.8 | 7.9 | 1.17 ± 0.67 |
| `mattcl-solver/aoc run 10 input-mattcl` | 2.5 ± 0.8 | 1.0 | 8.2 | 1.22 ± 0.69 |
| `mattcl-solver/aoc run 10 input-pting` | 2.5 ± 0.9 | 1.0 | 6.2 | 1.21 ± 0.69 |
| `python pting/day10.py input-lanjian` | 54.1 ± 7.6 | 43.1 | 77.5 | 26.36 ± 12.55 |
| `python pting/day10.py input-mattcl` | 51.2 ± 7.2 | 42.8 | 84.9 | 24.95 ± 11.89 |
| `python pting/day10.py input-pting` | 48.0 ± 5.9 | 39.4 | 61.3 | 23.39 ± 11.02 |
