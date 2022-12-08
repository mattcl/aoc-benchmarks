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
| `lanjian/day_07 input-lanjian` | 2.0 ± 1.1 | 0.2 | 13.2 | 1.34 ± 1.13 |
| `lanjian/day_07 input-mattcl` | 2.3 ± 1.4 | 0.0 | 12.3 | 1.54 ± 1.37 |
| `lanjian/day_07 input-pting` | 2.2 ± 1.7 | 0.1 | 14.6 | 1.46 ± 1.45 |
| `mattcl-solver/aoc run 7 input-lanjian` | 2.2 ± 1.2 | 0.1 | 9.6 | 1.46 ± 1.22 |
| `mattcl-solver/aoc run 7 input-mattcl` | 1.5 ± 0.9 | 0.0 | 7.9 | 1.00 |
| `mattcl-solver/aoc run 7 input-pting` | 2.0 ± 1.3 | 0.1 | 9.6 | 1.38 ± 1.24 |
| `python pting/day07.py input-lanjian` | 53.0 ± 7.5 | 42.1 | 76.0 | 35.68 ± 23.17 |
| `python pting/day07.py input-mattcl` | 57.6 ± 9.1 | 42.7 | 81.5 | 38.81 ± 25.36 |
| `python pting/day07.py input-pting` | 62.9 ± 11.4 | 45.2 | 102.0 | 42.34 ± 27.93 |

## input -> solutions mapping
|input|part 1|part 2|
|:---|:---|:---|
|input-lanjian|<pre>1391690</pre>|<pre>5469168</pre>|
|input-mattcl|<pre>1792222</pre>|<pre>1112963</pre>|
|input-pting|<pre>1555642</pre>|<pre>5974547</pre>|
