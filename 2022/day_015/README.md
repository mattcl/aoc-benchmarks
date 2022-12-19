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
| `lanjian/day_15 input-lanjian` | 0.6 ± 0.1 | 0.5 | 2.5 | 1.00 |
| `lanjian/day_15 input-mattcl` | 0.7 ± 0.1 | 0.5 | 1.0 | 1.08 ± 0.15 |
| `lanjian/day_15 input-pting` | 0.6 ± 0.1 | 0.5 | 3.3 | 1.01 ± 0.17 |
| `mattcl-solver/aoc run 15 input-lanjian` | 0.7 ± 0.1 | 0.6 | 1.2 | 1.20 ± 0.16 |
| `mattcl-solver/aoc run 15 input-mattcl` | 0.8 ± 0.1 | 0.6 | 1.2 | 1.28 ± 0.17 |
| `mattcl-solver/aoc run 15 input-pting` | 0.8 ± 0.1 | 0.6 | 2.9 | 1.28 ± 0.22 |
| `python pting/day15/day15.py input-lanjian` | 18037.7 ± 173.3 | 17875.9 | 18220.6 | 29954.17 ± 3243.69 |
| `python pting/day15/day15.py input-mattcl` | 31652.0 ± 1094.9 | 30415.3 | 32497.9 | 52562.61 ± 5953.92 |
| `python pting/day15/day15.py input-pting` | 28237.8 ± 732.9 | 27469.2 | 28928.8 | 46892.83 ± 5202.28 |

## input -> solutions mapping
|input|part 1|part 2|
|:---|:---|:---|
|input-lanjian|<pre>4582667</pre>|<pre>10961118625406</pre>|
|input-mattcl|<pre>4873353</pre>|<pre>11600823139120</pre>|
|input-pting|<pre>4748135</pre>|<pre>13743542639657</pre>|
