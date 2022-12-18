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
| `lanjian/day_15 input-lanjian` | 0.6 ± 0.1 | 0.5 | 4.1 | 1.00 |
| `lanjian/day_15 input-mattcl` | 0.7 ± 0.1 | 0.6 | 4.9 | 1.08 ± 0.25 |
| `lanjian/day_15 input-pting` | 0.7 ± 0.1 | 0.5 | 3.4 | 1.03 ± 0.21 |
| `mattcl-solver/aoc run 15 input-lanjian` | 0.7 ± 0.1 | 0.6 | 1.2 | 1.17 ± 0.18 |
| `mattcl-solver/aoc run 15 input-mattcl` | 0.8 ± 0.1 | 0.7 | 2.0 | 1.26 ± 0.20 |
| `mattcl-solver/aoc run 15 input-pting` | 0.8 ± 0.1 | 0.7 | 3.4 | 1.25 ± 0.23 |
| `python pting/day15/day15.py input-lanjian` | 17735.8 ± 479.9 | 17195.6 | 18112.9 | 27837.78 ± 3817.00 |
| `python pting/day15/day15.py input-mattcl` | 32230.2 ± 554.0 | 31872.9 | 32868.4 | 50587.94 ± 6855.37 |
| `python pting/day15/day15.py input-pting` | 28389.7 ± 697.0 | 27886.9 | 29185.4 | 44559.95 ± 6088.81 |

## input -> solutions mapping
|input|part 1|part 2|
|:---|:---|:---|
|input-lanjian|<pre>4582667</pre>|<pre>10961118625406</pre>|
|input-mattcl|<pre>4873353</pre>|<pre>11600823139120</pre>|
|input-pting|<pre>4748135</pre>|<pre>13743542639657</pre>|
