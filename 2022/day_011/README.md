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
| `mattcl-solver/aoc run 11 input-kcen` | 14.7 ± 0.1 | 14.4 | 15.2 | 1.00 ± 0.02 |
| `mattcl-solver/aoc run 11 input-lanjian` | 20.0 ± 0.3 | 19.7 | 21.8 | 1.37 ± 0.02 |
| `mattcl-solver/aoc run 11 input-mattcl` | 14.6 ± 0.2 | 14.4 | 16.2 | 1.00 |
| `mattcl-solver/aoc run 11 input-pting` | 21.4 ± 0.2 | 21.0 | 22.2 | 1.46 ± 0.02 |
| `python pting/day11/day11.py input-kcen` | 286.4 ± 3.1 | 282.5 | 292.1 | 19.56 ± 0.32 |
| `python pting/day11/day11.py input-lanjian` | 382.0 ± 2.4 | 377.9 | 385.4 | 26.09 ± 0.36 |
| `python pting/day11/day11.py input-mattcl` | 290.1 ± 4.5 | 282.8 | 298.2 | 19.82 ± 0.39 |
| `python pting/day11/day11.py input-pting` | 401.3 ± 3.8 | 397.9 | 408.5 | 27.41 ± 0.42 |

## input -> solutions mapping
|input|part 1|part 2|
|:---|:---|:---|
|input-lanjian|<pre>113220</pre>|<pre>30599555965</pre>|
|input-mattcl|<pre>95472</pre>|<pre>17926061332</pre>|
|input-pting|<pre>110264</pre>|<pre>23612457316</pre>|
|input-kcen|<pre>95472</pre>|<pre>17926061332</pre>|
