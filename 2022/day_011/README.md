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
| `lanjian/day_11 input-kcen` | 14.4 ± 0.4 | 14.0 | 16.7 | 1.00 |
| `lanjian/day_11 input-lanjian` | 19.9 ± 0.6 | 19.4 | 22.4 | 1.39 ± 0.06 |
| `lanjian/day_11 input-mattcl` | 14.4 ± 0.4 | 14.0 | 16.3 | 1.01 ± 0.04 |
| `lanjian/day_11 input-pting` | 21.0 ± 0.4 | 20.5 | 22.6 | 1.46 ± 0.05 |
| `mattcl-solver/aoc run 11 input-kcen` | 14.7 ± 0.3 | 14.4 | 16.3 | 1.03 ± 0.04 |
| `mattcl-solver/aoc run 11 input-lanjian` | 20.3 ± 0.6 | 19.8 | 23.1 | 1.42 ± 0.06 |
| `mattcl-solver/aoc run 11 input-mattcl` | 14.9 ± 0.5 | 14.5 | 17.1 | 1.04 ± 0.05 |
| `mattcl-solver/aoc run 11 input-pting` | 21.5 ± 0.5 | 21.0 | 23.6 | 1.50 ± 0.06 |
| `python pting/day11/day11.py input-kcen` | 287.2 ± 7.1 | 280.4 | 300.1 | 20.01 ± 0.77 |
| `python pting/day11/day11.py input-lanjian` | 381.1 ± 4.3 | 375.8 | 389.4 | 26.55 ± 0.84 |
| `python pting/day11/day11.py input-mattcl` | 291.3 ± 5.5 | 283.2 | 300.6 | 20.29 ± 0.71 |
| `python pting/day11/day11.py input-pting` | 411.3 ± 14.1 | 397.5 | 439.3 | 28.65 ± 1.30 |

## input -> solutions mapping
|input|part 1|part 2|
|:---|:---|:---|
|input-lanjian|<pre>113220</pre>|<pre>30599555965</pre>|
|input-mattcl|<pre>95472</pre>|<pre>17926061332</pre>|
|input-pting|<pre>110264</pre>|<pre>23612457316</pre>|
|input-kcen|<pre>95472</pre>|<pre>17926061332</pre>|
