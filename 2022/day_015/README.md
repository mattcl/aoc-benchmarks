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
| `lanjian/day_15 input-lanjian` | 0.6 ± 0.1 | 0.5 | 4.6 | 1.00 |
| `lanjian/day_15 input-mattcl` | 0.7 ± 0.1 | 0.5 | 1.1 | 1.06 ± 0.22 |
| `lanjian/day_15 input-pting` | 0.6 ± 0.1 | 0.5 | 1.0 | 1.03 ± 0.21 |
| `mattcl-solver/aoc run 15 input-lanjian` | 0.8 ± 0.1 | 0.7 | 2.5 | 1.37 ± 0.29 |
| `mattcl-solver/aoc run 15 input-mattcl` | 0.9 ± 0.1 | 0.8 | 1.3 | 1.42 ± 0.28 |
| `mattcl-solver/aoc run 15 input-pting` | 0.9 ± 0.1 | 0.8 | 1.4 | 1.45 ± 0.29 |
| `python pting/day15/day15.py input-lanjian` | 17965.4 ± 878.9 | 17025.9 | 18767.6 | 29062.54 ± 5543.96 |
| `python pting/day15/day15.py input-mattcl` | 31792.1 ± 388.5 | 31449.3 | 32214.1 | 51429.93 ± 9503.44 |
| `python pting/day15/day15.py input-pting` | 26907.2 ± 1474.0 | 25211.4 | 27881.4 | 43527.66 ± 8372.37 |

## input -> solutions mapping
|input|part 1|part 2|
|:---|:---|:---|
|input-lanjian|<pre>4582667</pre>|<pre>10961118625406</pre>|
|input-mattcl|<pre>4873353</pre>|<pre>11600823139120</pre>|
|input-pting|<pre>4748135</pre>|<pre>13743542639657</pre>|
