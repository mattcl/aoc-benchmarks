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
| `mattcl-solver/aoc run 6 input-mattcl` | 4.1 ± 1.1 | 1.9 | 10.0 | 1.10 ± 0.46 |
| `mattcl-solver/aoc run 6 input-pting` | 3.7 ± 1.2 | 1.7 | 10.7 | 1.00 |
| `python pting/day06.py input-mattcl` | 60.8 ± 8.0 | 48.2 | 83.1 | 16.49 ± 5.80 |
| `python pting/day06.py input-pting` | 64.9 ± 9.4 | 44.4 | 87.4 | 17.61 ± 6.28 |

## input -> solutions mapping
|input|part 1|part 2|
|:---|:---|:---|
|input-mattcl|<pre>1625</pre>|<pre>2250</pre>|
|input-pting|<pre>1802</pre>|<pre>3551</pre>|
