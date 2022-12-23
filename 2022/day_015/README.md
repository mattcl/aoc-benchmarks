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
| `lanjian/day_15 input-lanjian` | 0.6 ± 0.1 | 0.5 | 2.4 | 1.00 |
| `lanjian/day_15 input-mattcl` | 0.7 ± 0.1 | 0.5 | 1.3 | 1.09 ± 0.18 |
| `lanjian/day_15 input-pting` | 0.6 ± 0.1 | 0.5 | 1.6 | 1.05 ± 0.19 |
| `mattcl-solver/aoc run 15 input-lanjian` | 0.8 ± 0.1 | 0.7 | 2.7 | 1.37 ± 0.23 |
| `mattcl-solver/aoc run 15 input-mattcl` | 0.9 ± 0.1 | 0.8 | 1.3 | 1.47 ± 0.23 |
| `mattcl-solver/aoc run 15 input-pting` | 0.9 ± 0.1 | 0.8 | 2.6 | 1.47 ± 0.24 |
| `python pting/day15/day15.py input-lanjian` | 18440.8 ± 493.8 | 17903.8 | 18875.3 | 30055.98 ± 4239.33 |
| `python pting/day15/day15.py input-mattcl` | 31064.8 ± 662.4 | 30650.9 | 31828.8 | 50631.32 ± 7094.19 |
| `python pting/day15/day15.py input-pting` | 28320.3 ± 908.7 | 27273.2 | 28902.7 | 46158.21 ± 6561.46 |

## input -> solutions mapping
|input|part 1|part 2|
|:---|:---|:---|
|input-lanjian|<pre>4582667</pre>|<pre>10961118625406</pre>|
|input-mattcl|<pre>4873353</pre>|<pre>11600823139120</pre>|
|input-pting|<pre>4748135</pre>|<pre>13743542639657</pre>|
