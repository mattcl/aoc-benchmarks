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
| `lanjian/day_07 input-lanjian` | 3.5 ± 1.7 | 1.4 | 13.1 | 1.07 ± 0.74 |
| `lanjian/day_07 input-mattcl` | 3.8 ± 1.5 | 1.6 | 13.8 | 1.17 ± 0.72 |
| `lanjian/day_07 input-pting` | 3.9 ± 1.4 | 1.5 | 10.9 | 1.18 ± 0.70 |
| `mattcl-solver/aoc run 7 input-lanjian` | 3.7 ± 1.7 | 1.4 | 15.4 | 1.13 ± 0.75 |
| `mattcl-solver/aoc run 7 input-mattcl` | 3.3 ± 1.6 | 1.1 | 17.0 | 1.00 |
| `mattcl-solver/aoc run 7 input-pting` | 3.9 ± 1.9 | 1.8 | 21.8 | 1.20 ± 0.82 |
| `python pting/day07.py input-lanjian` | 65.3 ± 17.6 | 47.6 | 132.7 | 19.98 ± 10.98 |
| `python pting/day07.py input-mattcl` | 69.9 ± 26.2 | 48.4 | 184.6 | 21.37 ± 13.01 |
| `python pting/day07.py input-pting` | 61.8 ± 15.1 | 48.4 | 125.7 | 18.89 ± 10.17 |

## input -> solutions mapping
|input|part 1|part 2|
|:---|:---|:---|
|input-lanjian|<pre>1391690</pre>|<pre>5469168</pre>|
|input-mattcl|<pre>1792222</pre>|<pre>1112963</pre>|
|input-pting|<pre>1555642</pre>|<pre>5974547</pre>|
