# Day 2 benchmarks

[link to problem](http://adventofcode.com/2022/day/2)

The following benchmarks are auto-generated via [hyperfine](https://github.com/sharkdp/hyperfine) by a ci system running on shared hardware. Results may be inaccurate, particularly for execution times < 5ms, as per the hyperfine warnings.

The "official" inputs were aggregated from repositories participating in the generation of these benchmarks. The "large" inputs (if any) were sourced from various places, including the subreddit.

## Benchmarks with officially generated inputs
| Command | Mean [ms] | Min [ms] | Max [ms] | Relative |
|:---|---:|---:|---:|---:|
| `mattcl-solver/aoc run 2 input-mattcl` | 2.5 ± 1.5 | 0.0 | 11.7 | 1.00 |
| `mattcl-solver/aoc run 2 input-pting` | 3.7 ± 2.9 | 0.4 | 30.4 | 1.44 ± 1.42 |
| `python pting/day02.py input-mattcl` | 40.6 ± 6.5 | 29.8 | 59.2 | 15.98 ± 9.84 |
| `python pting/day02.py input-pting` | 43.0 ± 6.5 | 32.6 | 61.3 | 16.91 ± 10.39 |
