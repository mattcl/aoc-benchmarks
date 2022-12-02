# Day 2 benchmarks

[link to problem](http://adventofcode.com/2022/day/2)

The following benchmarks are auto-generated via [hyperfine](https://github.com/sharkdp/hyperfine) by a ci system running on shared hardware. Results may be inaccurate, particularly for execution times < 5ms, as per the hyperfine warnings.

The "official" inputs were aggregated from repositories participating in the generation of these benchmarks. The "large" inputs (if any) were sourced from various places, including the subreddit.

## Benchmarks with officially generated inputs
| Command | Mean [ms] | Min [ms] | Max [ms] | Relative |
|:---|---:|---:|---:|---:|
| `mattcl-solver/aoc run 2 input-mattcl` | 3.5 ± 1.9 | 0.6 | 10.0 | 1.06 ± 0.85 |
| `mattcl-solver/aoc run 2 input-pting` | 3.3 ± 2.0 | 0.6 | 23.6 | 1.00 |
| `python pting/day02.py input-mattcl` | 53.0 ± 23.6 | 27.8 | 132.4 | 16.00 ± 11.92 |
| `python pting/day02.py input-pting` | 50.7 ± 16.7 | 32.1 | 95.0 | 15.33 ± 10.46 |
