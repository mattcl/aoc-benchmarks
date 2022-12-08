# Day 7 benchmarks

[link to problem](http://adventofcode.com/2022/day/7)

The following benchmarks are auto-generated via [hyperfine](https://github.com/sharkdp/hyperfine) by a ci system running on shared hardware. Results may be inaccurate, particularly for execution times < 5ms, as per the hyperfine warnings.

[ci pipeline](http://ci.papercode.net:8080/teams/aoc2022/pipelines/aoc-compare-2022)

The "official" inputs were aggregated from repositories participating in the generation of these benchmarks. The "large" inputs (if any) were sourced from various places, including the subreddit.

## Repos (with solutions for day 7)


- [lanjian](https://github.com/LanJian/aoc-2022)
- [mattcl](https://github.com/mattcl/aoc2022)
- [pting](https://github.com/pting/aoc2022)

## Benchmarks with officially generated inputs
| Command | Mean [ms] | Min [ms] | Max [ms] | Relative |
|:---|---:|---:|---:|---:|
| `lanjian/day_07 input-lanjian` | 2.9 ± 1.6 | 1.1 | 18.1 | 1.00 |
| `lanjian/day_07 input-mattcl` | 12.1 ± 7.5 | 3.7 | 39.1 | 4.17 ± 3.51 |
| `lanjian/day_07 input-pting` | 3.6 ± 1.6 | 1.4 | 20.7 | 1.24 ± 0.90 |
| `mattcl-solver/aoc run 7 input-lanjian` | 3.7 ± 1.0 | 1.7 | 9.0 | 1.29 ± 0.81 |
| `mattcl-solver/aoc run 7 input-mattcl` | 5.1 ± 5.6 | 1.4 | 53.4 | 1.77 ± 2.18 |
| `mattcl-solver/aoc run 7 input-pting` | 4.1 ± 1.9 | 1.8 | 21.7 | 1.41 ± 1.04 |
| `python pting/day07.py input-lanjian` | 59.6 ± 9.6 | 45.7 | 97.5 | 20.58 ± 12.10 |
| `python pting/day07.py input-mattcl` | 63.0 ± 10.7 | 44.5 | 89.5 | 21.75 ± 12.84 |
| `python pting/day07.py input-pting` | 58.8 ± 9.5 | 43.8 | 80.4 | 20.30 ± 11.94 |

## input -> solutions mapping
|input|part 1|part 2|
|:---|:---|:---|
|input-lanjian|<pre>1391690</pre>|<pre>5469168</pre>|
|input-mattcl|<pre>1792222</pre>|<pre>1112963</pre>|
|input-pting|<pre>1555642</pre>|<pre>5974547</pre>|
