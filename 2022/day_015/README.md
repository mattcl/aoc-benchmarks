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
| `lanjian/day_15 input-lanjian` | 0.5 ± 0.1 | 0.5 | 2.0 | 1.00 |
| `lanjian/day_15 input-mattcl` | 0.6 ± 0.1 | 0.5 | 2.2 | 1.17 ± 0.18 |
| `lanjian/day_15 input-pting` | 0.6 ± 0.1 | 0.5 | 3.4 | 1.12 ± 0.22 |
| `mattcl-solver/aoc run 15 input-lanjian` | 0.8 ± 0.1 | 0.7 | 1.2 | 1.45 ± 0.21 |
| `mattcl-solver/aoc run 15 input-mattcl` | 0.8 ± 0.1 | 0.7 | 1.3 | 1.60 ± 0.22 |
| `mattcl-solver/aoc run 15 input-pting` | 0.9 ± 0.1 | 0.7 | 5.5 | 1.63 ± 0.31 |
| `python pting/day15/day15.py input-lanjian` | 18918.8 ± 781.9 | 18393.8 | 19817.4 | 35823.89 ± 4412.03 |
| `python pting/day15/day15.py input-mattcl` | 31073.1 ± 544.9 | 30567.2 | 31650.0 | 58838.84 ± 6903.91 |
| `python pting/day15/day15.py input-pting` | 28034.1 ± 1539.7 | 26286.5 | 29191.4 | 53084.20 ± 6814.01 |

## input -> solutions mapping
|input|part 1|part 2|
|:---|:---|:---|
|input-lanjian|<pre>4582667</pre>|<pre>10961118625406</pre>|
|input-mattcl|<pre>4873353</pre>|<pre>11600823139120</pre>|
|input-pting|<pre>4748135</pre>|<pre>13743542639657</pre>|
