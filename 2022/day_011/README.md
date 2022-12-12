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
| `lanjian/day_11 input-kcen` | 14.3 ± 0.3 | 14.0 | 16.1 | 1.00 ± 0.03 |
| `lanjian/day_11 input-lanjian` | 19.9 ± 0.7 | 19.3 | 22.5 | 1.39 ± 0.05 |
| `lanjian/day_11 input-mattcl` | 14.3 ± 0.2 | 14.0 | 15.5 | 1.00 |
| `lanjian/day_11 input-pting` | 20.9 ± 0.5 | 20.5 | 23.5 | 1.46 ± 0.04 |
| `mattcl-solver/aoc run 11 input-kcen` | 14.7 ± 0.3 | 14.4 | 16.3 | 1.03 ± 0.03 |
| `mattcl-solver/aoc run 11 input-lanjian` | 20.1 ± 0.6 | 19.6 | 22.5 | 1.41 ± 0.05 |
| `mattcl-solver/aoc run 11 input-mattcl` | 14.7 ± 0.3 | 14.4 | 16.5 | 1.03 ± 0.03 |
| `mattcl-solver/aoc run 11 input-pting` | 21.6 ± 0.6 | 21.0 | 24.9 | 1.51 ± 0.05 |
| `python pting/day11/day11.py input-kcen` | 285.9 ± 6.5 | 279.5 | 303.0 | 19.98 ± 0.57 |
| `python pting/day11/day11.py input-lanjian` | 383.0 ± 7.8 | 377.1 | 402.6 | 26.77 ± 0.72 |
| `python pting/day11/day11.py input-mattcl` | 294.5 ± 13.6 | 282.5 | 320.1 | 20.58 ± 1.01 |
| `python pting/day11/day11.py input-pting` | 410.1 ± 7.7 | 402.2 | 424.9 | 28.66 ± 0.73 |

## input -> solutions mapping
|input|part 1|part 2|
|:---|:---|:---|
|input-lanjian|<pre>113220</pre>|<pre>30599555965</pre>|
|input-mattcl|<pre>95472</pre>|<pre>17926061332</pre>|
|input-pting|<pre>110264</pre>|<pre>23612457316</pre>|
|input-kcen|<pre>95472</pre>|<pre>17926061332</pre>|
