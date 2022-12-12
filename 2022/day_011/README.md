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
| `lanjian/day_11 input-kcen` | 14.5 ± 0.3 | 14.1 | 18.2 | 1.00 ± 0.03 |
| `lanjian/day_11 input-lanjian` | 19.9 ± 0.5 | 19.5 | 24.2 | 1.38 ± 0.04 |
| `lanjian/day_11 input-mattcl` | 14.4 ± 0.3 | 14.1 | 17.7 | 1.00 |
| `lanjian/day_11 input-pting` | 21.1 ± 0.3 | 20.7 | 23.1 | 1.46 ± 0.04 |
| `mattcl-solver/aoc run 11 input-kcen` | 14.8 ± 0.2 | 14.6 | 15.4 | 1.03 ± 0.02 |
| `mattcl-solver/aoc run 11 input-lanjian` | 20.2 ± 0.2 | 19.8 | 20.9 | 1.40 ± 0.03 |
| `mattcl-solver/aoc run 11 input-mattcl` | 14.8 ± 0.2 | 14.5 | 17.2 | 1.02 ± 0.03 |
| `mattcl-solver/aoc run 11 input-pting` | 21.7 ± 0.3 | 21.4 | 22.6 | 1.51 ± 0.03 |
| `python pting/day11/day11.py input-kcen` | 286.9 ± 4.9 | 281.7 | 295.9 | 19.90 ± 0.52 |
| `python pting/day11/day11.py input-lanjian` | 390.5 ± 7.3 | 382.9 | 404.4 | 27.09 ± 0.74 |
| `python pting/day11/day11.py input-mattcl` | 291.9 ± 3.2 | 287.8 | 298.7 | 20.25 ± 0.46 |
| `python pting/day11/day11.py input-pting` | 405.0 ± 2.8 | 399.7 | 408.6 | 28.10 ± 0.59 |

## input -> solutions mapping
|input|part 1|part 2|
|:---|:---|:---|
|input-lanjian|<pre>113220</pre>|<pre>30599555965</pre>|
|input-mattcl|<pre>95472</pre>|<pre>17926061332</pre>|
|input-pting|<pre>110264</pre>|<pre>23612457316</pre>|
|input-kcen|<pre>95472</pre>|<pre>17926061332</pre>|
