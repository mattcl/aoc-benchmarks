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
| `lanjian/day_11 input-kcen` | 14.3 ± 0.3 | 14.1 | 17.1 | 1.00 |
| `lanjian/day_11 input-lanjian` | 19.7 ± 0.2 | 19.4 | 20.5 | 1.38 ± 0.03 |
| `lanjian/day_11 input-mattcl` | 14.4 ± 0.2 | 14.1 | 16.2 | 1.00 ± 0.02 |
| `lanjian/day_11 input-pting` | 20.8 ± 0.2 | 20.6 | 22.7 | 1.45 ± 0.03 |
| `mattcl-solver/aoc run 11 input-kcen` | 14.8 ± 0.2 | 14.5 | 16.8 | 1.03 ± 0.02 |
| `mattcl-solver/aoc run 11 input-lanjian` | 20.0 ± 0.3 | 19.6 | 22.9 | 1.40 ± 0.03 |
| `mattcl-solver/aoc run 11 input-mattcl` | 14.7 ± 0.2 | 14.4 | 16.5 | 1.02 ± 0.02 |
| `mattcl-solver/aoc run 11 input-pting` | 21.4 ± 0.3 | 21.1 | 23.2 | 1.49 ± 0.03 |
| `python pting/day11/day11.py input-kcen` | 284.4 ± 3.3 | 281.4 | 292.0 | 19.83 ± 0.42 |
| `python pting/day11/day11.py input-lanjian` | 381.1 ± 4.4 | 375.8 | 390.3 | 26.58 ± 0.57 |
| `python pting/day11/day11.py input-mattcl` | 284.7 ± 2.9 | 281.0 | 289.1 | 19.86 ± 0.41 |
| `python pting/day11/day11.py input-pting` | 404.7 ± 11.8 | 394.3 | 433.4 | 28.22 ± 0.97 |

## input -> solutions mapping
|input|part 1|part 2|
|:---|:---|:---|
|input-lanjian|<pre>113220</pre>|<pre>30599555965</pre>|
|input-mattcl|<pre>95472</pre>|<pre>17926061332</pre>|
|input-pting|<pre>110264</pre>|<pre>23612457316</pre>|
|input-kcen|<pre>95472</pre>|<pre>17926061332</pre>|
