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
| `lanjian/day_11 input-kcen` | 14.3 ± 0.2 | 14.0 | 15.0 | 1.00 ± 0.02 |
| `lanjian/day_11 input-lanjian` | 19.7 ± 0.3 | 19.4 | 21.5 | 1.38 ± 0.03 |
| `lanjian/day_11 input-mattcl` | 14.3 ± 0.2 | 14.0 | 16.1 | 1.00 |
| `lanjian/day_11 input-pting` | 21.0 ± 0.3 | 20.7 | 22.6 | 1.47 ± 0.03 |
| `mattcl-solver/aoc run 11 input-kcen` | 14.7 ± 0.3 | 14.4 | 16.3 | 1.03 ± 0.02 |
| `mattcl-solver/aoc run 11 input-lanjian` | 20.0 ± 0.4 | 19.6 | 22.8 | 1.40 ± 0.03 |
| `mattcl-solver/aoc run 11 input-mattcl` | 14.6 ± 0.1 | 14.4 | 15.2 | 1.03 ± 0.02 |
| `mattcl-solver/aoc run 11 input-pting` | 21.4 ± 0.3 | 21.0 | 23.1 | 1.50 ± 0.03 |
| `python pting/day11/day11.py input-kcen` | 284.6 ± 1.5 | 282.7 | 287.0 | 19.97 ± 0.30 |
| `python pting/day11/day11.py input-lanjian` | 380.0 ± 5.8 | 371.4 | 387.4 | 26.66 ± 0.55 |
| `python pting/day11/day11.py input-mattcl` | 282.2 ± 1.5 | 279.6 | 284.6 | 19.80 ± 0.30 |
| `python pting/day11/day11.py input-pting` | 402.6 ± 7.6 | 394.3 | 415.8 | 28.25 ± 0.66 |

## input -> solutions mapping
|input|part 1|part 2|
|:---|:---|:---|
|input-lanjian|<pre>113220</pre>|<pre>30599555965</pre>|
|input-mattcl|<pre>95472</pre>|<pre>17926061332</pre>|
|input-pting|<pre>110264</pre>|<pre>23612457316</pre>|
|input-kcen|<pre>95472</pre>|<pre>17926061332</pre>|
