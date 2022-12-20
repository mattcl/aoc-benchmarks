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
| `lanjian/day_15 input-lanjian` | 0.6 ± 0.1 | 0.5 | 2.6 | 1.00 |
| `lanjian/day_15 input-mattcl` | 0.7 ± 0.1 | 0.5 | 1.0 | 1.09 ± 0.17 |
| `lanjian/day_15 input-pting` | 0.6 ± 0.1 | 0.5 | 1.0 | 1.05 ± 0.16 |
| `mattcl-solver/aoc run 15 input-lanjian` | 0.8 ± 0.1 | 0.7 | 2.8 | 1.35 ± 0.21 |
| `mattcl-solver/aoc run 15 input-mattcl` | 0.9 ± 0.1 | 0.7 | 1.4 | 1.44 ± 0.21 |
| `mattcl-solver/aoc run 15 input-pting` | 0.9 ± 0.1 | 0.7 | 1.4 | 1.45 ± 0.21 |
| `python pting/day15/day15.py input-lanjian` | 18746.4 ± 771.8 | 18069.1 | 19586.6 | 31211.96 ± 4113.04 |
| `python pting/day15/day15.py input-mattcl` | 30814.7 ± 738.8 | 29975.4 | 31366.8 | 51305.17 ± 6539.22 |
| `python pting/day15/day15.py input-pting` | 29143.4 ± 1428.7 | 27954.7 | 30728.5 | 48522.60 ± 6523.34 |

## input -> solutions mapping
|input|part 1|part 2|
|:---|:---|:---|
|input-lanjian|<pre>4582667</pre>|<pre>10961118625406</pre>|
|input-mattcl|<pre>4873353</pre>|<pre>11600823139120</pre>|
|input-pting|<pre>4748135</pre>|<pre>13743542639657</pre>|
