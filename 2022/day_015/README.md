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
| `lanjian/day_15 input-lanjian` | 0.6 ± 0.1 | 0.5 | 2.2 | 1.00 |
| `lanjian/day_15 input-mattcl` | 0.6 ± 0.1 | 0.5 | 2.2 | 1.11 ± 0.17 |
| `lanjian/day_15 input-pting` | 0.6 ± 0.1 | 0.5 | 1.1 | 1.04 ± 0.16 |
| `mattcl-solver/aoc run 15 input-lanjian` | 0.7 ± 0.1 | 0.6 | 2.5 | 1.21 ± 0.18 |
| `mattcl-solver/aoc run 15 input-mattcl` | 0.8 ± 0.1 | 0.6 | 1.5 | 1.32 ± 0.19 |
| `mattcl-solver/aoc run 15 input-pting` | 0.8 ± 0.1 | 0.6 | 2.4 | 1.30 ± 0.19 |
| `python pting/day15/day15.py input-lanjian` | 18233.7 ± 423.9 | 17863.7 | 18696.3 | 31324.25 ± 3659.49 |
| `python pting/day15/day15.py input-mattcl` | 31833.4 ± 909.4 | 31033.1 | 32822.4 | 54687.43 ± 6453.10 |
| `python pting/day15/day15.py input-pting` | 29187.6 ± 1418.9 | 28229.1 | 30817.6 | 50142.18 ± 6236.81 |

## input -> solutions mapping
|input|part 1|part 2|
|:---|:---|:---|
|input-lanjian|<pre>4582667</pre>|<pre>10961118625406</pre>|
|input-mattcl|<pre>4873353</pre>|<pre>11600823139120</pre>|
|input-pting|<pre>4748135</pre>|<pre>13743542639657</pre>|
