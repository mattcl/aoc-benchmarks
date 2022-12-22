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
| `lanjian/day_15 input-lanjian` | 0.5 ± 0.1 | 0.5 | 2.8 | 1.00 |
| `lanjian/day_15 input-mattcl` | 0.6 ± 0.1 | 0.5 | 1.1 | 1.18 ± 0.19 |
| `lanjian/day_15 input-pting` | 0.6 ± 0.1 | 0.5 | 1.4 | 1.12 ± 0.19 |
| `mattcl-solver/aoc run 15 input-lanjian` | 0.8 ± 0.1 | 0.7 | 1.8 | 1.41 ± 0.22 |
| `mattcl-solver/aoc run 15 input-mattcl` | 0.9 ± 0.1 | 0.7 | 1.6 | 1.57 ± 0.24 |
| `mattcl-solver/aoc run 15 input-pting` | 0.8 ± 0.1 | 0.7 | 1.3 | 1.56 ± 0.24 |
| `python pting/day15/day15.py input-lanjian` | 18125.3 ± 446.3 | 17727.8 | 18608.1 | 33438.26 ± 4433.90 |
| `python pting/day15/day15.py input-mattcl` | 31682.1 ± 1171.5 | 30400.6 | 32698.2 | 58448.55 ± 7916.20 |
| `python pting/day15/day15.py input-pting` | 28286.2 ± 2011.2 | 26250.2 | 30271.7 | 52183.69 ± 7745.70 |

## input -> solutions mapping
|input|part 1|part 2|
|:---|:---|:---|
|input-lanjian|<pre>4582667</pre>|<pre>10961118625406</pre>|
|input-mattcl|<pre>4873353</pre>|<pre>11600823139120</pre>|
|input-pting|<pre>4748135</pre>|<pre>13743542639657</pre>|
