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
| `lanjian/day_15 input-lanjian` | 0.6 ± 0.1 | 0.5 | 3.6 | 1.00 |
| `lanjian/day_15 input-mattcl` | 0.6 ± 0.1 | 0.5 | 1.7 | 1.12 ± 0.19 |
| `lanjian/day_15 input-pting` | 0.6 ± 0.1 | 0.5 | 1.1 | 1.02 ± 0.18 |
| `mattcl-solver/aoc run 15 input-lanjian` | 0.7 ± 0.1 | 0.6 | 3.1 | 1.19 ± 0.22 |
| `mattcl-solver/aoc run 15 input-mattcl` | 0.8 ± 0.1 | 0.6 | 5.6 | 1.34 ± 0.31 |
| `mattcl-solver/aoc run 15 input-pting` | 0.7 ± 0.1 | 0.6 | 3.5 | 1.29 ± 0.24 |
| `python pting/day15/day15.py input-lanjian` | 18367.8 ± 182.3 | 18218.9 | 18571.2 | 31691.91 ± 4509.31 |
| `python pting/day15/day15.py input-mattcl` | 30800.7 ± 382.7 | 30439.2 | 31201.6 | 53143.65 ± 7572.01 |
| `python pting/day15/day15.py input-pting` | 27105.6 ± 1053.0 | 25921.6 | 27937.5 | 46768.14 ± 6882.39 |

## input -> solutions mapping
|input|part 1|part 2|
|:---|:---|:---|
|input-lanjian|<pre>4582667</pre>|<pre>10961118625406</pre>|
|input-mattcl|<pre>4873353</pre>|<pre>11600823139120</pre>|
|input-pting|<pre>4748135</pre>|<pre>13743542639657</pre>|
