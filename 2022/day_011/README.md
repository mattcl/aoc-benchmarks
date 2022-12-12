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
| `mattcl-solver/aoc run 11 input-kcen` | 14.7 ± 0.2 | 14.4 | 15.8 | 1.00 |
| `mattcl-solver/aoc run 11 input-lanjian` | 20.1 ± 0.4 | 19.7 | 22.8 | 1.37 ± 0.03 |
| `mattcl-solver/aoc run 11 input-mattcl` | 14.7 ± 0.2 | 14.4 | 16.6 | 1.00 ± 0.02 |
| `mattcl-solver/aoc run 11 input-pting` | 21.6 ± 0.4 | 21.2 | 23.7 | 1.47 ± 0.03 |
| `python pting/day11/day11.py input-kcen` | 287.9 ± 4.3 | 282.6 | 293.9 | 19.57 ± 0.39 |
| `python pting/day11/day11.py input-lanjian` | 381.4 ± 3.4 | 377.7 | 389.8 | 25.92 ± 0.41 |
| `python pting/day11/day11.py input-mattcl` | 288.2 ± 3.8 | 281.0 | 294.3 | 19.59 ± 0.36 |
| `python pting/day11/day11.py input-pting` | 404.0 ± 3.8 | 399.6 | 410.1 | 27.46 ± 0.45 |

## input -> solutions mapping
|input|part 1|part 2|
|:---|:---|:---|
|input-lanjian|<pre>113220</pre>|<pre>30599555965</pre>|
|input-mattcl|<pre>95472</pre>|<pre>17926061332</pre>|
|input-pting|<pre>110264</pre>|<pre>23612457316</pre>|
|input-kcen|<pre>95472</pre>|<pre>17926061332</pre>|
