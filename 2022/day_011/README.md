# Day 11 benchmarks

[link to problem](http://adventofcode.com/2022/day/11)

The following benchmarks are auto-generated via [hyperfine](https://github.com/sharkdp/hyperfine) by a ci system running on shared hardware. Results may be inaccurate, particularly for execution times < 5ms, as per the hyperfine warnings.

[ci pipeline](http://ci.papercode.net:8080/teams/aoc2022/pipelines/aoc-compare-2022)

The "official" inputs were aggregated from repositories participating in the generation of these benchmarks. The "large" inputs (if any) were sourced from various places, including the subreddit.

## Repos (with solutions for day 11)


- [lanjian](https://github.com/LanJian/aoc-2022)
- [mattcl](https://github.com/mattcl/aoc2022)
- [pting](https://github.com/pting/aoc2022)

## Benchmarks with officially generated inputs
| Command | Mean [ms] | Min [ms] | Max [ms] | Relative |
|:---|---:|---:|---:|---:|
| `lanjian/day_11 input-kcen` | 14.4 ± 0.2 | 14.1 | 15.5 | 1.00 ± 0.02 |
| `lanjian/day_11 input-lanjian` | 19.6 ± 0.2 | 19.4 | 22.0 | 1.37 ± 0.03 |
| `lanjian/day_11 input-mattcl` | 14.3 ± 0.3 | 14.0 | 15.7 | 1.00 |
| `lanjian/day_11 input-pting` | 21.0 ± 0.4 | 20.7 | 22.7 | 1.47 ± 0.04 |
| `mattcl-solver/aoc run 11 input-kcen` | 14.7 ± 0.1 | 14.4 | 15.8 | 1.02 ± 0.02 |
| `mattcl-solver/aoc run 11 input-lanjian` | 19.9 ± 0.1 | 19.7 | 20.4 | 1.39 ± 0.03 |
| `mattcl-solver/aoc run 11 input-mattcl` | 14.8 ± 0.5 | 14.4 | 16.9 | 1.04 ± 0.04 |
| `mattcl-solver/aoc run 11 input-pting` | 21.4 ± 0.3 | 21.0 | 22.6 | 1.49 ± 0.04 |
| `python pting/day11/day11.py input-kcen` | 285.7 ± 2.6 | 282.6 | 289.8 | 19.95 ± 0.44 |
| `python pting/day11/day11.py input-lanjian` | 382.1 ± 8.8 | 375.2 | 405.6 | 26.68 ± 0.81 |
| `python pting/day11/day11.py input-mattcl` | 282.6 ± 2.9 | 279.8 | 289.9 | 19.73 ± 0.44 |
| `python pting/day11/day11.py input-pting` | 403.6 ± 4.2 | 399.2 | 409.8 | 28.18 ± 0.63 |

## input -> solutions mapping
|input|part 1|part 2|
|:---|:---|:---|
|input-lanjian|<pre>113220</pre>|<pre>30599555965</pre>|
|input-mattcl|<pre>95472</pre>|<pre>17926061332</pre>|
|input-pting|<pre>110264</pre>|<pre>23612457316</pre>|
|input-kcen|<pre>95472</pre>|<pre>17926061332</pre>|
