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
| `lanjian/day_11 input-kcen` | 14.3 ± 0.3 | 14.1 | 17.4 | 1.00 ± 0.02 |
| `lanjian/day_11 input-lanjian` | 19.7 ± 0.3 | 19.4 | 21.9 | 1.38 ± 0.03 |
| `lanjian/day_11 input-mattcl` | 14.3 ± 0.2 | 14.0 | 16.0 | 1.00 |
| `lanjian/day_11 input-pting` | 20.9 ± 0.2 | 20.6 | 21.5 | 1.46 ± 0.02 |
| `mattcl-solver/aoc run 11 input-kcen` | 14.7 ± 0.4 | 14.3 | 20.2 | 1.03 ± 0.03 |
| `mattcl-solver/aoc run 11 input-lanjian` | 20.0 ± 0.2 | 19.7 | 21.3 | 1.40 ± 0.02 |
| `mattcl-solver/aoc run 11 input-mattcl` | 14.6 ± 0.2 | 14.3 | 16.5 | 1.02 ± 0.02 |
| `mattcl-solver/aoc run 11 input-pting` | 21.2 ± 0.2 | 21.0 | 23.2 | 1.49 ± 0.03 |
| `python pting/day11/day11.py input-kcen` | 285.0 ± 5.2 | 278.6 | 294.5 | 19.97 ± 0.45 |
| `python pting/day11/day11.py input-lanjian` | 378.7 ± 4.1 | 373.2 | 386.9 | 26.54 ± 0.46 |
| `python pting/day11/day11.py input-mattcl` | 285.0 ± 3.8 | 281.8 | 293.7 | 19.97 ± 0.38 |
| `python pting/day11/day11.py input-pting` | 400.5 ± 4.3 | 394.1 | 405.8 | 28.07 ± 0.48 |

## input -> solutions mapping
|input|part 1|part 2|
|:---|:---|:---|
|input-lanjian|<pre>113220</pre>|<pre>30599555965</pre>|
|input-mattcl|<pre>95472</pre>|<pre>17926061332</pre>|
|input-pting|<pre>110264</pre>|<pre>23612457316</pre>|
|input-kcen|<pre>95472</pre>|<pre>17926061332</pre>|
