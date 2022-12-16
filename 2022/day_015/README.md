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
| `lanjian/day_15 input-lanjian` | 0.6 ± 0.1 | 0.5 | 3.1 | 1.00 |
| `lanjian/day_15 input-mattcl` | 0.7 ± 0.1 | 0.5 | 2.2 | 1.05 ± 0.19 |
| `lanjian/day_15 input-pting` | 0.6 ± 0.1 | 0.5 | 2.6 | 1.02 ± 0.18 |
| `mattcl-solver/aoc run 15 input-lanjian` | 0.7 ± 0.1 | 0.6 | 3.6 | 1.16 ± 0.21 |
| `mattcl-solver/aoc run 15 input-mattcl` | 0.8 ± 0.1 | 0.6 | 2.4 | 1.24 ± 0.21 |
| `mattcl-solver/aoc run 15 input-pting` | 0.8 ± 0.1 | 0.7 | 3.6 | 1.26 ± 0.23 |
| `python pting/day15/day15.py input-lanjian` | 18210.0 ± 694.6 | 17782.9 | 19011.4 | 29434.83 ± 4243.28 |
| `python pting/day15/day15.py input-mattcl` | 31974.8 ± 472.9 | 31458.1 | 32386.1 | 51684.37 ± 7225.76 |
| `python pting/day15/day15.py input-pting` | 28143.9 ± 740.3 | 27563.1 | 28977.4 | 45492.10 ± 6436.55 |

## input -> solutions mapping
|input|part 1|part 2|
|:---|:---|:---|
|input-lanjian|<pre>4582667</pre>|<pre>10961118625406</pre>|
|input-mattcl|<pre>4873353</pre>|<pre>11600823139120</pre>|
|input-pting|<pre>4748135</pre>|<pre>13743542639657</pre>|
