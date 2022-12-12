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
| `lanjian/day_11 input-kcen` | 14.5 ± 0.4 | 14.0 | 16.4 | 1.02 ± 0.03 |
| `lanjian/day_11 input-lanjian` | 19.7 ± 0.4 | 19.4 | 24.3 | 1.38 ± 0.03 |
| `lanjian/day_11 input-mattcl` | 14.3 ± 0.1 | 14.0 | 14.7 | 1.00 |
| `lanjian/day_11 input-pting` | 20.9 ± 0.2 | 20.5 | 21.6 | 1.47 ± 0.02 |
| `mattcl-solver/aoc run 11 input-kcen` | 14.9 ± 0.3 | 14.5 | 16.6 | 1.04 ± 0.03 |
| `mattcl-solver/aoc run 11 input-lanjian` | 20.1 ± 0.4 | 19.7 | 24.3 | 1.41 ± 0.03 |
| `mattcl-solver/aoc run 11 input-mattcl` | 14.8 ± 0.3 | 14.5 | 17.4 | 1.04 ± 0.02 |
| `mattcl-solver/aoc run 11 input-pting` | 21.6 ± 0.4 | 21.2 | 25.5 | 1.51 ± 0.03 |
| `python pting/day11/day11.py input-kcen` | 288.9 ± 9.4 | 281.7 | 310.3 | 20.28 ± 0.68 |
| `python pting/day11/day11.py input-lanjian` | 377.3 ± 4.0 | 373.9 | 386.6 | 26.48 ± 0.37 |
| `python pting/day11/day11.py input-mattcl` | 282.8 ± 1.5 | 280.1 | 284.7 | 19.84 ± 0.21 |
| `python pting/day11/day11.py input-pting` | 402.6 ± 5.6 | 396.3 | 414.7 | 28.25 ± 0.47 |

## input -> solutions mapping
|input|part 1|part 2|
|:---|:---|:---|
|input-lanjian|<pre>113220</pre>|<pre>30599555965</pre>|
|input-mattcl|<pre>95472</pre>|<pre>17926061332</pre>|
|input-pting|<pre>110264</pre>|<pre>23612457316</pre>|
|input-kcen|<pre>95472</pre>|<pre>17926061332</pre>|
