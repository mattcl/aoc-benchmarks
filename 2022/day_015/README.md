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
| `lanjian/day_15 input-lanjian` | 0.6 ± 0.1 | 0.5 | 2.3 | 1.00 |
| `lanjian/day_15 input-mattcl` | 0.7 ± 0.1 | 0.5 | 2.4 | 1.19 ± 0.18 |
| `lanjian/day_15 input-pting` | 0.6 ± 0.1 | 0.5 | 1.0 | 1.11 ± 0.17 |
| `mattcl-solver/aoc run 15 input-lanjian` | 0.7 ± 0.1 | 0.6 | 5.8 | 1.23 ± 0.26 |
| `mattcl-solver/aoc run 15 input-mattcl` | 0.8 ± 0.1 | 0.7 | 1.3 | 1.40 ± 0.19 |
| `mattcl-solver/aoc run 15 input-pting` | 0.8 ± 0.1 | 0.7 | 2.7 | 1.39 ± 0.21 |
| `python pting/day15/day15.py input-lanjian` | 18340.5 ± 648.5 | 17637.3 | 18914.9 | 32357.81 ± 3884.44 |
| `python pting/day15/day15.py input-mattcl` | 31619.3 ± 381.9 | 31183.0 | 31892.5 | 55785.41 ± 6435.14 |
| `python pting/day15/day15.py input-pting` | 28255.9 ± 709.9 | 27695.9 | 29054.4 | 49851.41 ± 5854.58 |

## input -> solutions mapping
|input|part 1|part 2|
|:---|:---|:---|
|input-lanjian|<pre>4582667</pre>|<pre>10961118625406</pre>|
|input-mattcl|<pre>4873353</pre>|<pre>11600823139120</pre>|
|input-pting|<pre>4748135</pre>|<pre>13743542639657</pre>|
