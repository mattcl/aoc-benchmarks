# Day 11 benchmarks

[link to problem](http://adventofcode.com/2022/day/11)

The following benchmarks are auto-generated via [hyperfine](https://github.com/sharkdp/hyperfine) by a ci system running on shared hardware. Results may be inaccurate, particularly for execution times < 5ms, as per the hyperfine warnings.

[ci pipeline](http://ci.papercode.net:8080/teams/aoc2022/pipelines/aoc-compare-2022)

The "official" inputs were aggregated from repositories participating in the generation of these benchmarks. The "large" inputs (if any) were sourced from various places, including the subreddit.

## Repos (with solutions for day 11)


- [mattcl](https://github.com/mattcl/aoc2022)
- [pting](https://github.com/pting/aoc2022)

## Benchmarks with officially generated inputs
| Command | Mean [ms] | Min [ms] | Max [ms] | Relative |
|:---|---:|---:|---:|---:|
| `mattcl-solver/aoc run 11 input-mattcl` | 14.6 ± 0.3 | 14.4 | 18.4 | 1.00 |
| `mattcl-solver/aoc run 11 input-pting` | 21.5 ± 0.4 | 21.1 | 25.7 | 1.47 ± 0.04 |
| `python pting/day11/day11.py input-mattcl` | 285.4 ± 3.1 | 282.0 | 291.6 | 19.48 ± 0.44 |
| `python pting/day11/day11.py input-pting` | 403.7 ± 6.1 | 395.9 | 413.1 | 27.56 ± 0.69 |

## input -> solutions mapping
|input|part 1|part 2|
|:---|:---|:---|
|input-mattcl|<pre>95472</pre>|<pre>17926061332</pre>|
|input-pting|<pre>110264</pre>|<pre>23612457316</pre>|