# Day 6 benchmarks

[link to problem](http://adventofcode.com/2022/day/6)

The following benchmarks are auto-generated via [hyperfine](https://github.com/sharkdp/hyperfine) by a ci system running on shared hardware. Results may be inaccurate, particularly for execution times < 5ms, as per the hyperfine warnings.

[ci pipeline](http://ci.papercode.net:8080/teams/aoc2022/pipelines/aoc-compare-2022)

The "official" inputs were aggregated from repositories participating in the generation of these benchmarks. The "large" inputs (if any) were sourced from various places, including the subreddit.

## Repos (with solutions for day 6)


- [mattcl](https://github.com/mattcl/aoc2022)
- [pting](https://github.com/pting/aoc2022)

## Benchmarks with officially generated inputs
| Command | Mean [ms] | Min [ms] | Max [ms] | Relative |
|:---|---:|---:|---:|---:|
| `mattcl-solver/aoc run 6 input-mattcl` | 4.8 ± 2.2 | 1.9 | 16.2 | 1.00 |
| `mattcl-solver/aoc run 6 input-pting` | 4.9 ± 2.4 | 2.5 | 17.4 | 1.03 ± 0.70 |
| `python pting/day06.py input-mattcl` | 71.8 ± 17.3 | 56.0 | 117.7 | 15.02 ± 7.91 |
| `python pting/day06.py input-pting` | 58.3 ± 9.6 | 44.7 | 84.4 | 12.21 ± 6.05 |

## input -> solutions mapping
|input|part 1|part 2|
|:---|:---|:---|
|input-mattcl|<pre>1625</pre>|<pre>2250</pre>|
