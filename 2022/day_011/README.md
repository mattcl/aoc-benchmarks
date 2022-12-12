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
| `lanjian/day_11 input-kcen` | 14.4 ± 0.4 | 14.0 | 16.5 | 1.00 ± 0.05 |
| `lanjian/day_11 input-lanjian` | 19.9 ± 0.7 | 19.3 | 23.0 | 1.39 ± 0.08 |
| `lanjian/day_11 input-mattcl` | 14.3 ± 0.6 | 14.0 | 20.3 | 1.00 |
| `lanjian/day_11 input-pting` | 20.8 ± 0.1 | 20.5 | 21.3 | 1.45 ± 0.06 |
| `mattcl-solver/aoc run 11 input-kcen` | 14.7 ± 0.2 | 14.5 | 16.5 | 1.03 ± 0.05 |
| `mattcl-solver/aoc run 11 input-lanjian` | 20.3 ± 0.7 | 19.7 | 23.8 | 1.42 ± 0.08 |
| `mattcl-solver/aoc run 11 input-mattcl` | 14.6 ± 0.2 | 14.4 | 16.2 | 1.02 ± 0.04 |
| `mattcl-solver/aoc run 11 input-pting` | 21.5 ± 0.3 | 21.1 | 22.8 | 1.50 ± 0.07 |
| `python pting/day11/day11.py input-kcen` | 287.0 ± 3.3 | 281.6 | 289.8 | 20.04 ± 0.86 |
| `python pting/day11/day11.py input-lanjian` | 380.7 ± 2.9 | 375.9 | 386.7 | 26.58 ± 1.12 |
| `python pting/day11/day11.py input-mattcl` | 285.6 ± 4.1 | 278.8 | 291.7 | 19.95 ± 0.87 |
| `python pting/day11/day11.py input-pting` | 398.1 ± 3.1 | 394.4 | 403.5 | 27.80 ± 1.17 |

## input -> solutions mapping
|input|part 1|part 2|
|:---|:---|:---|
|input-lanjian|<pre>113220</pre>|<pre>30599555965</pre>|
|input-mattcl|<pre>95472</pre>|<pre>17926061332</pre>|
|input-pting|<pre>110264</pre>|<pre>23612457316</pre>|
|input-kcen|<pre>95472</pre>|<pre>17926061332</pre>|
