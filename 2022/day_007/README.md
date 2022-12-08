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
| `lanjian/day_07 input-lanjian` | 3.2 ± 1.6 | 1.2 | 19.2 | 1.15 ± 0.70 |
| `lanjian/day_07 input-mattcl` | 3.5 ± 1.1 | 1.5 | 9.1 | 1.26 ± 0.59 |
| `lanjian/day_07 input-pting` | 2.8 ± 1.0 | 0.8 | 7.1 | 1.00 |
| `mattcl-solver/aoc run 7 input-lanjian` | 3.5 ± 1.5 | 1.5 | 14.7 | 1.25 ± 0.71 |
| `mattcl-solver/aoc run 7 input-mattcl` | 3.5 ± 1.7 | 1.3 | 15.5 | 1.24 ± 0.74 |
| `mattcl-solver/aoc run 7 input-pting` | 3.5 ± 1.5 | 1.4 | 19.7 | 1.25 ± 0.70 |
| `python pting/day07.py input-lanjian` | 249.3 ± 207.0 | 63.5 | 679.6 | 89.08 ± 80.52 |
| `python pting/day07.py input-mattcl` | 59.6 ± 8.3 | 42.8 | 81.1 | 21.30 ± 8.16 |
| `python pting/day07.py input-pting` | 59.1 ± 7.9 | 47.3 | 83.1 | 21.13 ± 8.06 |

## input -> solutions mapping
|input|part 1|part 2|
|:---|:---|:---|
|input-lanjian|<pre>1391690</pre>|<pre>5469168</pre>|
|input-mattcl|<pre>1792222</pre>|<pre>1112963</pre>|
|input-pting|<pre>1555642</pre>|<pre>5974547</pre>|
