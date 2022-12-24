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
| `lanjian/day_15 input-lanjian` | 0.6 ± 0.1 | 0.5 | 3.4 | 1.00 |
| `lanjian/day_15 input-mattcl` | 0.7 ± 0.1 | 0.6 | 3.3 | 1.11 ± 0.22 |
| `lanjian/day_15 input-pting` | 0.6 ± 0.1 | 0.5 | 2.3 | 1.00 ± 0.19 |
| `mattcl-solver/aoc run 15 input-lanjian` | 0.9 ± 0.2 | 0.7 | 5.7 | 1.39 ± 0.32 |
| `mattcl-solver/aoc run 15 input-mattcl` | 0.9 ± 0.1 | 0.8 | 2.7 | 1.47 ± 0.27 |
| `mattcl-solver/aoc run 15 input-pting` | 0.9 ± 0.1 | 0.8 | 1.3 | 1.42 ± 0.25 |
| `python pting/day15/day15.py input-lanjian` | 18044.7 ± 709.4 | 17403.3 | 18806.5 | 28626.52 ± 4647.69 |
| `python pting/day15/day15.py input-mattcl` | 31841.4 ± 1113.7 | 30575.0 | 32667.8 | 50514.06 ± 8151.02 |
| `python pting/day15/day15.py input-pting` | 28705.8 ± 1011.3 | 27617.6 | 29616.9 | 45539.63 ± 7350.86 |

## input -> solutions mapping
|input|part 1|part 2|
|:---|:---|:---|
|input-lanjian|<pre>4582667</pre>|<pre>10961118625406</pre>|
|input-mattcl|<pre>4873353</pre>|<pre>11600823139120</pre>|
|input-pting|<pre>4748135</pre>|<pre>13743542639657</pre>|
