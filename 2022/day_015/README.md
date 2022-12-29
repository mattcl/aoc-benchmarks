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
| `lanjian/day_15 input-mattcl` | 0.6 ± 0.1 | 0.5 | 2.3 | 1.06 ± 0.24 |
| `lanjian/day_15 input-pting` | 0.6 ± 0.1 | 0.5 | 3.1 | 1.00 ± 0.26 |
| `mattcl-solver/aoc run 15 input-lanjian` | 0.8 ± 0.1 | 0.7 | 2.6 | 1.41 ± 0.32 |
| `mattcl-solver/aoc run 15 input-mattcl` | 0.9 ± 0.1 | 0.7 | 1.6 | 1.47 ± 0.32 |
| `mattcl-solver/aoc run 15 input-pting` | 0.9 ± 0.1 | 0.7 | 1.5 | 1.43 ± 0.31 |
| `python pting/day15/day15.py input-lanjian` | 17583.3 ± 584.0 | 16923.9 | 18035.3 | 29541.58 ± 6014.77 |
| `python pting/day15/day15.py input-mattcl` | 32028.5 ± 368.1 | 31753.0 | 32446.6 | 53811.04 ± 10827.05 |
| `python pting/day15/day15.py input-pting` | 28761.5 ± 894.9 | 27971.8 | 29733.5 | 48322.06 ± 9822.51 |

## input -> solutions mapping
|input|part 1|part 2|
|:---|:---|:---|
|input-lanjian|<pre>4582667</pre>|<pre>10961118625406</pre>|
|input-mattcl|<pre>4873353</pre>|<pre>11600823139120</pre>|
|input-pting|<pre>4748135</pre>|<pre>13743542639657</pre>|
