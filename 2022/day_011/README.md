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
| `lanjian/day_11 input-kcen` | 14.4 ± 0.5 | 14.0 | 19.1 | 1.00 ± 0.04 |
| `lanjian/day_11 input-lanjian` | 19.9 ± 0.8 | 19.4 | 22.9 | 1.39 ± 0.07 |
| `lanjian/day_11 input-mattcl` | 14.3 ± 0.4 | 14.0 | 19.9 | 1.00 |
| `lanjian/day_11 input-pting` | 20.9 ± 0.2 | 20.6 | 21.4 | 1.45 ± 0.05 |
| `mattcl-solver/aoc run 11 input-kcen` | 14.7 ± 0.3 | 14.4 | 16.6 | 1.03 ± 0.04 |
| `mattcl-solver/aoc run 11 input-lanjian` | 20.2 ± 0.5 | 19.7 | 22.2 | 1.40 ± 0.05 |
| `mattcl-solver/aoc run 11 input-mattcl` | 14.7 ± 0.2 | 14.4 | 15.6 | 1.03 ± 0.03 |
| `mattcl-solver/aoc run 11 input-pting` | 21.8 ± 0.9 | 21.1 | 24.8 | 1.52 ± 0.08 |
| `python pting/day11/day11.py input-kcen` | 286.8 ± 4.8 | 280.8 | 293.9 | 19.99 ± 0.68 |
| `python pting/day11/day11.py input-lanjian` | 391.0 ± 14.5 | 378.1 | 419.2 | 27.26 ± 1.30 |
| `python pting/day11/day11.py input-mattcl` | 288.3 ± 2.9 | 285.0 | 292.2 | 20.10 ± 0.63 |
| `python pting/day11/day11.py input-pting` | 404.9 ± 6.4 | 398.4 | 419.8 | 28.23 ± 0.95 |

## input -> solutions mapping
|input|part 1|part 2|
|:---|:---|:---|
|input-lanjian|<pre>113220</pre>|<pre>30599555965</pre>|
|input-mattcl|<pre>95472</pre>|<pre>17926061332</pre>|
|input-pting|<pre>110264</pre>|<pre>23612457316</pre>|
|input-kcen|<pre>95472</pre>|<pre>17926061332</pre>|
