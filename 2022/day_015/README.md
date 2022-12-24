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
| `lanjian/day_15 input-lanjian` | 0.6 ± 0.1 | 0.5 | 2.6 | 1.02 ± 0.18 |
| `lanjian/day_15 input-mattcl` | 0.7 ± 0.1 | 0.6 | 2.4 | 1.09 ± 0.18 |
| `lanjian/day_15 input-pting` | 0.6 ± 0.1 | 0.5 | 3.1 | 1.00 |
| `mattcl-solver/aoc run 15 input-lanjian` | 0.8 ± 0.1 | 0.7 | 2.8 | 1.38 ± 0.23 |
| `mattcl-solver/aoc run 15 input-mattcl` | 1.0 ± 0.2 | 0.8 | 5.6 | 1.58 ± 0.40 |
| `mattcl-solver/aoc run 15 input-pting` | 0.9 ± 0.1 | 0.8 | 3.0 | 1.44 ± 0.23 |
| `python pting/day15/day15.py input-lanjian` | 17460.1 ± 1084.9 | 16260.4 | 18372.2 | 28495.72 ± 4110.00 |
| `python pting/day15/day15.py input-mattcl` | 31671.9 ± 848.4 | 30825.2 | 32522.1 | 51690.06 ± 6869.12 |
| `python pting/day15/day15.py input-pting` | 28155.2 ± 741.5 | 27573.4 | 28990.1 | 45950.53 ± 6102.25 |

## input -> solutions mapping
|input|part 1|part 2|
|:---|:---|:---|
|input-lanjian|<pre>4582667</pre>|<pre>10961118625406</pre>|
|input-mattcl|<pre>4873353</pre>|<pre>11600823139120</pre>|
|input-pting|<pre>4748135</pre>|<pre>13743542639657</pre>|
