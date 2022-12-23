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
| `lanjian/day_15 input-lanjian` | 0.5 ± 0.1 | 0.5 | 2.7 | 1.00 |
| `lanjian/day_15 input-mattcl` | 0.7 ± 0.1 | 0.5 | 2.5 | 1.20 ± 0.20 |
| `lanjian/day_15 input-pting` | 0.6 ± 0.1 | 0.5 | 1.4 | 1.14 ± 0.19 |
| `mattcl-solver/aoc run 15 input-lanjian` | 0.8 ± 0.2 | 0.7 | 7.2 | 1.45 ± 0.35 |
| `mattcl-solver/aoc run 15 input-mattcl` | 0.9 ± 0.1 | 0.8 | 1.4 | 1.62 ± 0.24 |
| `mattcl-solver/aoc run 15 input-pting` | 0.9 ± 0.1 | 0.7 | 1.3 | 1.59 ± 0.23 |
| `python pting/day15/day15.py input-lanjian` | 17398.8 ± 769.4 | 16521.1 | 17956.7 | 31680.70 ± 4283.41 |
| `python pting/day15/day15.py input-mattcl` | 30775.6 ± 368.1 | 30507.9 | 31195.3 | 56038.02 ± 7191.25 |
| `python pting/day15/day15.py input-pting` | 28009.1 ± 445.2 | 27499.4 | 28321.8 | 51000.66 ± 6566.57 |

## input -> solutions mapping
|input|part 1|part 2|
|:---|:---|:---|
|input-lanjian|<pre>4582667</pre>|<pre>10961118625406</pre>|
|input-mattcl|<pre>4873353</pre>|<pre>11600823139120</pre>|
|input-pting|<pre>4748135</pre>|<pre>13743542639657</pre>|
