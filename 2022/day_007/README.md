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
| `lanjian/day_07 input-lanjian` | 2.2 ± 1.1 | 0.6 | 8.0 | 1.01 ± 0.68 |
| `lanjian/day_07 input-mattcl` | 2.1 ± 1.0 | 0.4 | 7.7 | 1.00 |
| `lanjian/day_07 input-pting` | 3.4 ± 1.9 | 0.6 | 18.7 | 1.59 ± 1.13 |
| `mattcl-solver/aoc run 7 input-lanjian` | 2.6 ± 1.3 | 0.9 | 15.0 | 1.20 ± 0.82 |
| `mattcl-solver/aoc run 7 input-mattcl` | 2.4 ± 1.1 | 0.7 | 13.9 | 1.10 ± 0.71 |
| `mattcl-solver/aoc run 7 input-pting` | 7.2 ± 6.9 | 0.8 | 39.8 | 3.37 ± 3.56 |
| `python pting/day07.py input-lanjian` | 52.6 ± 8.9 | 41.2 | 84.6 | 24.48 ± 11.69 |
| `python pting/day07.py input-mattcl` | 52.5 ± 7.8 | 41.0 | 76.6 | 24.45 ± 11.50 |
| `python pting/day07.py input-pting` | 50.2 ± 6.0 | 40.6 | 69.5 | 23.37 ± 10.79 |

## input -> solutions mapping
|input|part 1|part 2|
|:---|:---|:---|
|input-lanjian|<pre>1391690</pre>|<pre>5469168</pre>|
|input-mattcl|<pre>1792222</pre>|<pre>1112963</pre>|
|input-pting|<pre>1555642</pre>|<pre>5974547</pre>|
