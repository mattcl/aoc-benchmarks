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
| `lanjian/day_15 input-lanjian` | 0.7 ± 0.1 | 0.6 | 1.1 | 1.00 |
| `lanjian/day_15 input-mattcl` | 0.7 ± 0.1 | 0.6 | 1.2 | 1.06 ± 0.13 |
| `lanjian/day_15 input-pting` | 0.7 ± 0.1 | 0.6 | 1.0 | 1.01 ± 0.13 |
| `mattcl-solver/aoc run 15 input-lanjian` | 1.0 ± 0.1 | 0.9 | 1.4 | 1.44 ± 0.17 |
| `mattcl-solver/aoc run 15 input-mattcl` | 1.0 ± 0.1 | 0.9 | 1.5 | 1.46 ± 0.17 |
| `mattcl-solver/aoc run 15 input-pting` | 1.0 ± 0.1 | 0.9 | 1.4 | 1.44 ± 0.16 |
| `python pting/day15/day15.py input-lanjian` | 18975.5 ± 698.6 | 18557.1 | 19782.0 | 27558.51 ± 2665.76 |
| `python pting/day15/day15.py input-mattcl` | 31920.8 ± 1501.2 | 30213.9 | 33035.9 | 46359.27 ± 4685.05 |
| `python pting/day15/day15.py input-pting` | 30093.0 ± 1440.6 | 28499.8 | 31304.0 | 43704.73 ± 4434.08 |

## input -> solutions mapping
|input|part 1|part 2|
|:---|:---|:---|
|input-lanjian|<pre>4582667</pre>|<pre>10961118625406</pre>|
|input-mattcl|<pre>4873353</pre>|<pre>11600823139120</pre>|
|input-pting|<pre>4748135</pre>|<pre>13743542639657</pre>|
