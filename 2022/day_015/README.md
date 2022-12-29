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
| `lanjian/day_15 input-lanjian` | 0.6 ± 0.1 | 0.5 | 2.8 | 1.00 |
| `lanjian/day_15 input-mattcl` | 0.6 ± 0.1 | 0.5 | 2.6 | 1.11 ± 0.22 |
| `lanjian/day_15 input-pting` | 0.6 ± 0.1 | 0.5 | 2.5 | 1.01 ± 0.21 |
| `mattcl-solver/aoc run 15 input-lanjian` | 0.8 ± 0.1 | 0.7 | 3.2 | 1.43 ± 0.28 |
| `mattcl-solver/aoc run 15 input-mattcl` | 0.9 ± 0.1 | 0.7 | 1.3 | 1.50 ± 0.27 |
| `mattcl-solver/aoc run 15 input-pting` | 0.8 ± 0.1 | 0.7 | 2.8 | 1.44 ± 0.27 |
| `python pting/day15/day15.py input-lanjian` | 18427.9 ± 716.8 | 17779.6 | 19197.7 | 32023.03 ± 5373.90 |
| `python pting/day15/day15.py input-mattcl` | 32072.6 ± 545.1 | 31497.9 | 32582.3 | 55734.12 ± 9147.39 |
| `python pting/day15/day15.py input-pting` | 28403.8 ± 254.6 | 28152.5 | 28661.6 | 49358.69 ± 8069.60 |

## input -> solutions mapping
|input|part 1|part 2|
|:---|:---|:---|
|input-lanjian|<pre>4582667</pre>|<pre>10961118625406</pre>|
|input-mattcl|<pre>4873353</pre>|<pre>11600823139120</pre>|
|input-pting|<pre>4748135</pre>|<pre>13743542639657</pre>|
