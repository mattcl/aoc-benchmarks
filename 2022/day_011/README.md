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
| `mattcl-solver/aoc run 11 input-kcen` | 14.7 ± 0.2 | 14.4 | 16.7 | 1.00 ± 0.03 |
| `mattcl-solver/aoc run 11 input-mattcl` | 14.7 ± 0.5 | 14.4 | 20.6 | 1.00 |
| `mattcl-solver/aoc run 11 input-pting` | 21.4 ± 0.2 | 21.0 | 22.4 | 1.45 ± 0.05 |
| `python pting/day11/day11.py input-kcen` | 285.0 ± 2.5 | 282.0 | 290.1 | 19.39 ± 0.62 |
| `python pting/day11/day11.py input-mattcl` | 284.4 ± 4.8 | 279.3 | 292.8 | 19.35 ± 0.68 |
| `python pting/day11/day11.py input-pting` | 404.6 ± 4.6 | 398.7 | 411.8 | 27.54 ± 0.91 |

## input -> solutions mapping
|input|part 1|part 2|
|:---|:---|:---|
|input-mattcl|<pre>95472</pre>|<pre>17926061332</pre>|
|input-pting|<pre>110264</pre>|<pre>23612457316</pre>|
|input-kcen|<pre>95472</pre>|<pre>17926061332</pre>|
