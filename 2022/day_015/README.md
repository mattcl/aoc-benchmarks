# Day 15 benchmarks

[link to problem](http://adventofcode.com/2022/day/15)

The following benchmarks are auto-generated via [hyperfine](https://github.com/sharkdp/hyperfine) by a ci system running on shared hardware. Results may be inaccurate, particularly for execution times < 5ms, as per the hyperfine warnings.

[ci pipeline](http://ci.papercode.net:8080/teams/aoc2022/pipelines/aoc-compare-2022)

The "official" inputs were aggregated from repositories participating in the generation of these benchmarks. The "challenge" inputs (if any) were sourced from various places, including the subreddit.

## Repos (with solutions for day 15)


- [lanjian](https://github.com/LanJian/aoc-2022)
- [mattcl](https://github.com/mattcl/aoc2022)
- [pting](https://github.com/pting/aoc2022)

## Benchmarks with officially generated inputs
| Command | Mean [ms] | Min [ms] | Max [ms] | Relative |
|:---|---:|---:|---:|---:|
| `lanjian/day_15 input-lanjian` | 0.6 ± 0.1 | 0.5 | 1.5 | 1.00 |
| `lanjian/day_15 input-mattcl` | 0.7 ± 0.1 | 0.5 | 2.3 | 1.09 ± 0.17 |
| `lanjian/day_15 input-pting` | 0.6 ± 0.1 | 0.5 | 1.1 | 1.03 ± 0.16 |
| `mattcl-solver/aoc run 15 input-lanjian` | 0.8 ± 0.1 | 0.7 | 1.6 | 1.37 ± 0.20 |
| `mattcl-solver/aoc run 15 input-mattcl` | 0.9 ± 0.1 | 0.8 | 4.5 | 1.46 ± 0.25 |
| `mattcl-solver/aoc run 15 input-pting` | 0.9 ± 0.1 | 0.7 | 1.3 | 1.42 ± 0.19 |
| `python pting/day15/day15.py input-lanjian` | 18618.1 ± 1141.5 | 17831.2 | 19927.3 | 30618.43 ± 3976.68 |
| `python pting/day15/day15.py input-mattcl` | 31953.7 ± 384.0 | 31511.3 | 32200.0 | 52549.53 ± 6049.72 |
| `python pting/day15/day15.py input-pting` | 27930.2 ± 306.2 | 27640.3 | 28250.4 | 45932.67 ± 5283.13 |

## input -> solutions mapping
|input|part 1|part 2|
|:---|:---|:---|
|input-lanjian|<pre>4582667</pre>|<pre>10961118625406</pre>|
|input-mattcl|<pre>4873353</pre>|<pre>11600823139120</pre>|
|input-pting|<pre>4748135</pre>|<pre>13743542639657</pre>|
