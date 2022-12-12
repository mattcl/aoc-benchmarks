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
| `lanjian/day_11 input-kcen` | 14.4 ± 0.3 | 14.2 | 16.7 | 1.01 ± 0.03 |
| `lanjian/day_11 input-lanjian` | 19.6 ± 0.4 | 19.3 | 23.5 | 1.37 ± 0.04 |
| `lanjian/day_11 input-mattcl` | 14.3 ± 0.3 | 14.1 | 18.3 | 1.00 |
| `lanjian/day_11 input-pting` | 20.8 ± 0.2 | 20.5 | 22.7 | 1.46 ± 0.04 |
| `mattcl-solver/aoc run 11 input-kcen` | 14.7 ± 0.2 | 14.5 | 16.0 | 1.03 ± 0.03 |
| `mattcl-solver/aoc run 11 input-lanjian` | 19.9 ± 0.2 | 19.6 | 20.6 | 1.39 ± 0.03 |
| `mattcl-solver/aoc run 11 input-mattcl` | 14.6 ± 0.1 | 14.4 | 15.1 | 1.02 ± 0.03 |
| `mattcl-solver/aoc run 11 input-pting` | 21.3 ± 0.2 | 21.1 | 22.6 | 1.49 ± 0.04 |
| `python pting/day11/day11.py input-kcen` | 286.3 ± 4.2 | 280.1 | 293.8 | 20.03 ± 0.56 |
| `python pting/day11/day11.py input-lanjian` | 385.4 ± 8.7 | 375.0 | 400.8 | 26.96 ± 0.88 |
| `python pting/day11/day11.py input-mattcl` | 283.1 ± 2.6 | 280.4 | 289.8 | 19.80 ± 0.50 |
| `python pting/day11/day11.py input-pting` | 400.3 ± 3.8 | 395.9 | 408.9 | 28.00 ± 0.71 |

## input -> solutions mapping
|input|part 1|part 2|
|:---|:---|:---|
|input-lanjian|<pre>113220</pre>|<pre>30599555965</pre>|
|input-mattcl|<pre>95472</pre>|<pre>17926061332</pre>|
|input-pting|<pre>110264</pre>|<pre>23612457316</pre>|
|input-kcen|<pre>95472</pre>|<pre>17926061332</pre>|
