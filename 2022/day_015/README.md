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
| `lanjian/day_15 input-lanjian` | 0.6 ± 0.1 | 0.5 | 1.1 | 1.02 ± 0.15 |
| `lanjian/day_15 input-mattcl` | 0.7 ± 0.1 | 0.5 | 0.9 | 1.11 ± 0.15 |
| `lanjian/day_15 input-pting` | 0.6 ± 0.1 | 0.5 | 1.5 | 1.00 |
| `mattcl-solver/aoc run 15 input-lanjian` | 0.7 ± 0.1 | 0.6 | 1.1 | 1.23 ± 0.17 |
| `mattcl-solver/aoc run 15 input-mattcl` | 0.8 ± 0.1 | 0.6 | 1.2 | 1.32 ± 0.18 |
| `mattcl-solver/aoc run 15 input-pting` | 0.8 ± 0.1 | 0.7 | 2.9 | 1.32 ± 0.20 |
| `python pting/day15/day15.py input-lanjian` | 18737.8 ± 1089.4 | 17746.5 | 19904.1 | 31634.82 ± 3932.73 |
| `python pting/day15/day15.py input-mattcl` | 31647.6 ± 503.5 | 31326.8 | 32227.8 | 53430.36 ± 5932.38 |
| `python pting/day15/day15.py input-pting` | 28949.6 ± 135.5 | 28806.2 | 29075.5 | 48875.42 ± 5375.52 |

## input -> solutions mapping
|input|part 1|part 2|
|:---|:---|:---|
|input-lanjian|<pre>4582667</pre>|<pre>10961118625406</pre>|
|input-mattcl|<pre>4873353</pre>|<pre>11600823139120</pre>|
|input-pting|<pre>4748135</pre>|<pre>13743542639657</pre>|
