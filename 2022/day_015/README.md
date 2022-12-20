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
| `lanjian/day_15 input-lanjian` | 0.6 ± 0.1 | 0.5 | 1.0 | 1.00 |
| `lanjian/day_15 input-mattcl` | 0.6 ± 0.1 | 0.5 | 2.0 | 1.08 ± 0.16 |
| `lanjian/day_15 input-pting` | 0.6 ± 0.1 | 0.5 | 2.5 | 1.00 ± 0.16 |
| `mattcl-solver/aoc run 15 input-lanjian` | 0.8 ± 0.1 | 0.7 | 7.2 | 1.37 ± 0.29 |
| `mattcl-solver/aoc run 15 input-mattcl` | 0.8 ± 0.1 | 0.7 | 3.1 | 1.44 ± 0.21 |
| `mattcl-solver/aoc run 15 input-pting` | 0.8 ± 0.1 | 0.7 | 1.2 | 1.43 ± 0.19 |
| `python pting/day15/day15.py input-lanjian` | 18223.9 ± 449.2 | 17759.6 | 18656.3 | 31494.04 ± 3402.36 |
| `python pting/day15/day15.py input-mattcl` | 32329.6 ± 1884.6 | 30875.9 | 34458.8 | 55871.29 ± 6718.80 |
| `python pting/day15/day15.py input-pting` | 28148.9 ± 759.7 | 27491.0 | 28980.3 | 48646.22 ± 5282.45 |

## input -> solutions mapping
|input|part 1|part 2|
|:---|:---|:---|
|input-lanjian|<pre>4582667</pre>|<pre>10961118625406</pre>|
|input-mattcl|<pre>4873353</pre>|<pre>11600823139120</pre>|
|input-pting|<pre>4748135</pre>|<pre>13743542639657</pre>|
