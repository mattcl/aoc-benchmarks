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
| `lanjian/day_07 input-lanjian` | 2.6 ± 1.0 | 0.9 | 9.7 | 1.00 |
| `lanjian/day_07 input-mattcl` | 3.2 ± 1.7 | 0.9 | 14.9 | 1.23 ± 0.81 |
| `lanjian/day_07 input-pting` | 2.8 ± 1.2 | 0.9 | 11.4 | 1.08 ± 0.62 |
| `mattcl-solver/aoc run 7 input-lanjian` | 3.3 ± 1.2 | 1.3 | 14.9 | 1.24 ± 0.65 |
| `mattcl-solver/aoc run 7 input-mattcl` | 3.7 ± 2.2 | 0.8 | 22.8 | 1.41 ± 1.00 |
| `mattcl-solver/aoc run 7 input-pting` | 3.1 ± 1.5 | 0.8 | 20.9 | 1.17 ± 0.72 |
| `python pting/day07.py input-lanjian` | 58.8 ± 10.7 | 43.5 | 97.6 | 22.33 ± 9.52 |
| `python pting/day07.py input-mattcl` | 56.7 ± 7.7 | 45.2 | 81.5 | 21.54 ± 8.79 |
| `python pting/day07.py input-pting` | 56.2 ± 9.2 | 44.4 | 79.9 | 21.34 ± 8.93 |

## input -> solutions mapping
|input|part 1|part 2|
|:---|:---|:---|
|input-lanjian|<pre>1391690</pre>|<pre>5469168</pre>|
|input-mattcl|<pre>1792222</pre>|<pre>1112963</pre>|
|input-pting|<pre>1555642</pre>|<pre>5974547</pre>|
