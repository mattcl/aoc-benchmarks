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
| `lanjian/day_11 input-kcen` | 14.3 ± 0.5 | 14.0 | 19.8 | 1.00 ± 0.04 |
| `lanjian/day_11 input-lanjian` | 19.9 ± 0.8 | 19.4 | 27.4 | 1.39 ± 0.06 |
| `lanjian/day_11 input-mattcl` | 14.3 ± 0.3 | 14.0 | 17.8 | 1.00 |
| `lanjian/day_11 input-pting` | 20.8 ± 0.1 | 20.6 | 21.6 | 1.46 ± 0.03 |
| `mattcl-solver/aoc run 11 input-kcen` | 14.7 ± 0.3 | 14.4 | 16.8 | 1.03 ± 0.03 |
| `mattcl-solver/aoc run 11 input-lanjian` | 20.0 ± 0.3 | 19.7 | 21.3 | 1.40 ± 0.04 |
| `mattcl-solver/aoc run 11 input-mattcl` | 14.7 ± 0.2 | 14.4 | 15.7 | 1.03 ± 0.03 |
| `mattcl-solver/aoc run 11 input-pting` | 21.3 ± 0.4 | 21.0 | 25.8 | 1.49 ± 0.04 |
| `python pting/day11/day11.py input-kcen` | 289.4 ± 6.6 | 283.2 | 301.6 | 20.28 ± 0.63 |
| `python pting/day11/day11.py input-lanjian` | 380.5 ± 1.9 | 376.9 | 383.9 | 26.66 ± 0.58 |
| `python pting/day11/day11.py input-mattcl` | 285.2 ± 2.9 | 281.8 | 291.4 | 19.98 ± 0.47 |
| `python pting/day11/day11.py input-pting` | 403.0 ± 4.3 | 398.1 | 410.9 | 28.23 ± 0.67 |

## input -> solutions mapping
|input|part 1|part 2|
|:---|:---|:---|
|input-lanjian|<pre>113220</pre>|<pre>30599555965</pre>|
|input-mattcl|<pre>95472</pre>|<pre>17926061332</pre>|
|input-pting|<pre>110264</pre>|<pre>23612457316</pre>|
|input-kcen|<pre>95472</pre>|<pre>17926061332</pre>|
