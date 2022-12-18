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
| `lanjian/day_15 input-mattcl` | 0.6 ± 0.1 | 0.5 | 1.8 | 1.00 ± 0.17 |
| `lanjian/day_15 input-pting` | 0.6 ± 0.1 | 0.5 | 2.8 | 1.03 ± 0.17 |
| `mattcl-solver/aoc run 15 input-lanjian` | 0.7 ± 0.1 | 0.6 | 1.3 | 1.22 ± 0.18 |
| `mattcl-solver/aoc run 15 input-mattcl` | 0.8 ± 0.1 | 0.6 | 3.4 | 1.27 ± 0.20 |
| `mattcl-solver/aoc run 15 input-pting` | 0.8 ± 0.1 | 0.6 | 3.9 | 1.30 ± 0.23 |
| `python pting/day15/day15.py input-lanjian` | 18422.7 ± 218.7 | 18172.2 | 18576.1 | 31074.21 ± 3476.80 |
| `python pting/day15/day15.py input-mattcl` | 31114.0 ± 1546.0 | 29982.4 | 32875.5 | 52480.91 ± 6394.62 |
| `python pting/day15/day15.py input-pting` | 27683.0 ± 1219.5 | 26383.1 | 28801.9 | 46693.75 ± 5587.32 |

## input -> solutions mapping
|input|part 1|part 2|
|:---|:---|:---|
|input-lanjian|<pre>4582667</pre>|<pre>10961118625406</pre>|
|input-mattcl|<pre>4873353</pre>|<pre>11600823139120</pre>|
|input-pting|<pre>4748135</pre>|<pre>13743542639657</pre>|
