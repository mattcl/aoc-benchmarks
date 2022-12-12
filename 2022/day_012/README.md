# Day 12 benchmarks

[link to problem](http://adventofcode.com/2022/day/12)

The following benchmarks are auto-generated via [hyperfine](https://github.com/sharkdp/hyperfine) by a ci system running on shared hardware. Results may be inaccurate, particularly for execution times < 5ms, as per the hyperfine warnings.

[ci pipeline](http://ci.papercode.net:8080/teams/aoc2022/pipelines/aoc-compare-2022)

The "official" inputs were aggregated from repositories participating in the generation of these benchmarks. The "large" inputs (if any) were sourced from various places, including the subreddit.

## Repos (with solutions for day 12)


- [lanjian](https://github.com/LanJian/aoc-2022)
- [pting](https://github.com/pting/aoc2022)

## Benchmarks with officially generated inputs
| Command | Mean [ms] | Min [ms] | Max [ms] | Relative |
|:---|---:|---:|---:|---:|
| `lanjian/day_12 input-lanjian` | 2.3 ± 0.1 | 2.2 | 4.9 | 1.00 |
| `lanjian/day_12 input-pting` | 2.6 ± 0.2 | 2.5 | 6.3 | 1.13 ± 0.09 |
| `python pting/day12/day12.py input-lanjian` | 470.4 ± 5.0 | 466.3 | 483.3 | 202.48 ± 10.72 |
| `python pting/day12/day12.py input-pting` | 333.1 ± 3.8 | 329.5 | 341.0 | 143.37 ± 7.62 |
