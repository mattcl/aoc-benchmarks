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
| `lanjian/day_07 input-lanjian` | 2.6 ± 1.1 | 1.0 | 15.3 | 1.00 |
| `lanjian/day_07 input-mattcl` | 2.7 ± 1.1 | 1.1 | 11.7 | 1.06 ± 0.61 |
| `lanjian/day_07 input-pting` | 6.0 ± 6.1 | 1.7 | 55.5 | 2.32 ± 2.54 |
| `mattcl-solver/aoc run 7 input-lanjian` | 2.7 ± 1.0 | 0.9 | 12.9 | 1.04 ± 0.58 |
| `mattcl-solver/aoc run 7 input-mattcl` | 2.9 ± 1.4 | 1.1 | 18.3 | 1.12 ± 0.72 |
| `mattcl-solver/aoc run 7 input-pting` | 2.8 ± 1.0 | 1.0 | 11.4 | 1.08 ± 0.60 |
| `python pting/day07.py input-lanjian` | 53.7 ± 7.9 | 41.0 | 78.0 | 20.81 ± 9.10 |
| `python pting/day07.py input-mattcl` | 50.0 ± 6.3 | 39.5 | 67.9 | 19.38 ± 8.34 |
| `python pting/day07.py input-pting` | 51.1 ± 7.6 | 40.1 | 78.2 | 19.80 ± 8.67 |

## input -> solutions mapping
|input|part 1|part 2|
|:---|:---|:---|
|input-lanjian|<pre>1391690</pre>|<pre>5469168</pre>|
|input-mattcl|<pre>1792222</pre>|<pre>1112963</pre>|
|input-pting|<pre>1555642</pre>|<pre>5974547</pre>|
