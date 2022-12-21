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
| `lanjian/day_15 input-lanjian` | 0.6 ± 0.1 | 0.5 | 5.0 | 1.00 |
| `lanjian/day_15 input-mattcl` | 0.7 ± 0.1 | 0.6 | 1.7 | 1.08 ± 0.21 |
| `lanjian/day_15 input-pting` | 0.6 ± 0.1 | 0.5 | 4.3 | 1.03 ± 0.25 |
| `mattcl-solver/aoc run 15 input-lanjian` | 0.8 ± 0.1 | 0.7 | 2.8 | 1.36 ± 0.26 |
| `mattcl-solver/aoc run 15 input-mattcl` | 0.9 ± 0.1 | 0.8 | 4.3 | 1.44 ± 0.30 |
| `mattcl-solver/aoc run 15 input-pting` | 0.9 ± 0.1 | 0.8 | 1.6 | 1.45 ± 0.27 |
| `python pting/day15/day15.py input-lanjian` | 18749.0 ± 584.5 | 18219.7 | 19376.4 | 30045.96 ± 5080.94 |
| `python pting/day15/day15.py input-mattcl` | 31095.6 ± 511.6 | 30508.0 | 31442.0 | 49831.72 ± 8322.86 |
| `python pting/day15/day15.py input-pting` | 28279.5 ± 607.7 | 27842.6 | 28973.5 | 45318.88 ± 7595.01 |

## input -> solutions mapping
|input|part 1|part 2|
|:---|:---|:---|
|input-lanjian|<pre>4582667</pre>|<pre>10961118625406</pre>|
|input-mattcl|<pre>4873353</pre>|<pre>11600823139120</pre>|
|input-pting|<pre>4748135</pre>|<pre>13743542639657</pre>|
