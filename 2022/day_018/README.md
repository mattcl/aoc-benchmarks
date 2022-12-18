# Day 18 benchmarks

[link to problem](http://adventofcode.com/2022/day/18)

The following benchmarks are auto-generated via [hyperfine](https://github.com/sharkdp/hyperfine) by a ci system running on shared hardware. Results may be inaccurate, particularly for execution times < 5ms, as per the hyperfine warnings.

[ci pipeline](http://ci.papercode.net:8080/teams/aoc2022/pipelines/aoc-compare-2022)

The "official" inputs were aggregated from repositories participating in the generation of these benchmarks. The "challenge" inputs (if any) were sourced from various places, including the subreddit.

## Repos (with solutions for day 18)


- [mattcl](https://github.com/mattcl/aoc2022)
- [pting](https://github.com/pting/aoc2022)

## Benchmarks with officially generated inputs
| Command | Mean [ms] | Min [ms] | Max [ms] | Relative |
|:---|---:|---:|---:|---:|
| `mattcl-solver/aoc run 18 input-mattcl` | 42.5 ± 0.4 | 42.0 | 44.3 | 1.86 ± 0.05 |
| `mattcl-solver/aoc run 18 input-pting` | 22.8 ± 0.5 | 22.4 | 27.4 | 1.00 |
| `python pting/day18/day18.py input-mattcl` | 89.7 ± 1.5 | 87.4 | 94.2 | 3.93 ± 0.11 |
| `python pting/day18/day18.py input-pting` | 71.5 ± 1.6 | 69.8 | 79.5 | 3.13 ± 0.10 |

## input -> solutions mapping
|input|part 1|part 2|
|:---|:---|:---|
|input-mattcl|<pre>4536</pre>|<pre>2606</pre>|
|input-pting|<pre>3454</pre>|<pre>2014</pre>|
