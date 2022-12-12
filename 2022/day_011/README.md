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
| `lanjian/day_11 input-kcen` | 14.4 ± 0.2 | 14.1 | 15.1 | 1.00 |
| `lanjian/day_11 input-lanjian` | 19.9 ± 0.2 | 19.6 | 21.2 | 1.38 ± 0.02 |
| `lanjian/day_11 input-mattcl` | 14.5 ± 0.3 | 14.2 | 17.6 | 1.01 ± 0.02 |
| `lanjian/day_11 input-pting` | 21.0 ± 0.2 | 20.7 | 21.7 | 1.46 ± 0.02 |
| `mattcl-solver/aoc run 11 input-kcen` | 14.8 ± 0.3 | 14.5 | 19.0 | 1.03 ± 0.03 |
| `mattcl-solver/aoc run 11 input-lanjian` | 20.2 ± 0.2 | 19.8 | 21.5 | 1.41 ± 0.02 |
| `mattcl-solver/aoc run 11 input-mattcl` | 14.8 ± 0.2 | 14.5 | 15.5 | 1.03 ± 0.02 |
| `mattcl-solver/aoc run 11 input-pting` | 21.5 ± 0.2 | 21.2 | 22.6 | 1.50 ± 0.02 |
| `python pting/day11/day11.py input-kcen` | 286.8 ± 3.0 | 283.4 | 290.8 | 19.94 ± 0.30 |
| `python pting/day11/day11.py input-lanjian` | 383.4 ± 2.5 | 379.6 | 386.9 | 26.65 ± 0.35 |
| `python pting/day11/day11.py input-mattcl` | 289.0 ± 5.5 | 284.2 | 303.2 | 20.09 ± 0.44 |
| `python pting/day11/day11.py input-pting` | 408.4 ± 5.8 | 400.7 | 419.0 | 28.39 ± 0.51 |

## input -> solutions mapping
|input|part 1|part 2|
|:---|:---|:---|
|input-lanjian|<pre>113220</pre>|<pre>30599555965</pre>|
|input-mattcl|<pre>95472</pre>|<pre>17926061332</pre>|
|input-pting|<pre>110264</pre>|<pre>23612457316</pre>|
|input-kcen|<pre>95472</pre>|<pre>17926061332</pre>|
