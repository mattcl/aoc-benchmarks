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
| `mattcl-solver/aoc run 6 input-mattcl` | 4.3 ± 1.2 | 2.1 | 10.4 | 1.00 ± 0.40 |
| `mattcl-solver/aoc run 6 input-pting` | 4.3 ± 1.2 | 1.8 | 11.6 | 1.00 |
| `python pting/day06.py input-mattcl` | 62.2 ± 8.2 | 51.1 | 99.5 | 14.37 ± 4.42 |
| `python pting/day06.py input-pting` | 62.0 ± 6.3 | 48.8 | 77.3 | 14.32 ± 4.25 |

## input -> solutions mapping
|input|part 1|part 2|
|:---|:---|:---|
|input-mattcl|<pre>1625</pre>|<pre>2250</pre>|
|input-pting|<pre>1802</pre>|<pre>3551</pre>|
