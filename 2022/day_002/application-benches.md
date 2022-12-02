# Day 2 benchmarks

[link to problem](http://adventofcode.com/2022/day/2)

The following benchmarks are auto-generated via [hyperfine](https://github.com/sharkdp/hyperfine) by a ci system running on shared hardware. Results may be inaccurate, particularly for execution times < 5ms, as per the hyperfine warnings.

The "official" inputs were aggregated from repositories participating in the generation of these benchmarks. The "large" inputs (if any) were sourced from various places, including the subreddit.

## Benchmarks with officially generated inputs
| Command | Mean [ms] | Min [ms] | Max [ms] | Relative |
|:---|---:|---:|---:|---:|
| `mattcl-solver/aoc run 2 input-mattcl` | 4.7 ± 3.5 | 1.0 | 29.7 | 1.00 |
| `mattcl-solver/aoc run 2 input-pting` | 7.2 ± 6.4 | 1.3 | 58.3 | 1.53 ± 1.77 |
| `python pting/day02.py input-mattcl` | 60.9 ± 27.6 | 34.1 | 161.3 | 12.90 ± 11.24 |
| `python pting/day02.py input-pting` | 52.4 ± 22.3 | 31.7 | 139.4 | 11.11 ± 9.52 |
