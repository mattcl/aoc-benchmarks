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
| `lanjian/day_11 input-kcen` | 14.3 ± 0.2 | 14.1 | 15.5 | 1.01 ± 0.02 |
| `lanjian/day_11 input-lanjian` | 19.6 ± 0.3 | 19.3 | 21.0 | 1.38 ± 0.03 |
| `lanjian/day_11 input-mattcl` | 14.2 ± 0.2 | 13.9 | 16.4 | 1.00 |
| `lanjian/day_11 input-pting` | 20.9 ± 0.4 | 20.5 | 25.2 | 1.47 ± 0.04 |
| `mattcl-solver/aoc run 11 input-kcen` | 14.7 ± 0.2 | 14.5 | 16.8 | 1.04 ± 0.02 |
| `mattcl-solver/aoc run 11 input-lanjian` | 19.9 ± 0.4 | 19.5 | 23.9 | 1.40 ± 0.03 |
| `mattcl-solver/aoc run 11 input-mattcl` | 14.6 ± 0.1 | 14.4 | 15.1 | 1.03 ± 0.02 |
| `mattcl-solver/aoc run 11 input-pting` | 21.5 ± 0.6 | 21.1 | 24.7 | 1.52 ± 0.05 |
| `python pting/day11/day11.py input-kcen` | 285.3 ± 2.7 | 282.0 | 290.8 | 20.11 ± 0.34 |
| `python pting/day11/day11.py input-lanjian` | 388.1 ± 15.6 | 373.7 | 427.2 | 27.35 ± 1.16 |
| `python pting/day11/day11.py input-mattcl` | 282.5 ± 3.3 | 277.7 | 287.7 | 19.91 ± 0.36 |
| `python pting/day11/day11.py input-pting` | 397.9 ± 2.3 | 394.5 | 401.4 | 28.05 ± 0.42 |

## input -> solutions mapping
|input|part 1|part 2|
|:---|:---|:---|
|input-lanjian|<pre>113220</pre>|<pre>30599555965</pre>|
|input-mattcl|<pre>95472</pre>|<pre>17926061332</pre>|
|input-pting|<pre>110264</pre>|<pre>23612457316</pre>|
|input-kcen|<pre>95472</pre>|<pre>17926061332</pre>|
