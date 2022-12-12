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
| `lanjian/day_11 input-kcen` | 14.4 ± 0.3 | 14.1 | 15.9 | 1.01 ± 0.03 |
| `lanjian/day_11 input-lanjian` | 19.9 ± 0.6 | 19.4 | 23.3 | 1.40 ± 0.04 |
| `lanjian/day_11 input-mattcl` | 14.2 ± 0.2 | 14.0 | 16.4 | 1.00 |
| `lanjian/day_11 input-pting` | 20.9 ± 0.4 | 20.6 | 24.1 | 1.47 ± 0.03 |
| `mattcl-solver/aoc run 11 input-kcen` | 14.8 ± 0.4 | 14.5 | 17.3 | 1.04 ± 0.03 |
| `mattcl-solver/aoc run 11 input-lanjian` | 20.1 ± 0.4 | 19.8 | 21.8 | 1.42 ± 0.03 |
| `mattcl-solver/aoc run 11 input-mattcl` | 14.7 ± 0.2 | 14.5 | 16.3 | 1.03 ± 0.02 |
| `mattcl-solver/aoc run 11 input-pting` | 21.8 ± 0.7 | 21.3 | 25.1 | 1.53 ± 0.05 |
| `python pting/day11/day11.py input-kcen` | 285.1 ± 4.1 | 280.4 | 294.5 | 20.03 ± 0.41 |
| `python pting/day11/day11.py input-lanjian` | 380.9 ± 4.3 | 374.3 | 386.7 | 26.76 ± 0.49 |
| `python pting/day11/day11.py input-mattcl` | 284.8 ± 4.9 | 279.1 | 296.1 | 20.01 ± 0.45 |
| `python pting/day11/day11.py input-pting` | 402.1 ± 4.5 | 396.7 | 411.5 | 28.25 ± 0.51 |

## input -> solutions mapping
|input|part 1|part 2|
|:---|:---|:---|
|input-lanjian|<pre>113220</pre>|<pre>30599555965</pre>|
|input-mattcl|<pre>95472</pre>|<pre>17926061332</pre>|
|input-pting|<pre>110264</pre>|<pre>23612457316</pre>|
|input-kcen|<pre>95472</pre>|<pre>17926061332</pre>|
