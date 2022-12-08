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
| `lanjian/day_07 input-lanjian` | 3.4 ± 1.4 | 1.3 | 15.0 | 1.17 ± 0.72 |
| `lanjian/day_07 input-mattcl` | 4.2 ± 2.0 | 1.5 | 21.4 | 1.42 ± 0.93 |
| `lanjian/day_07 input-pting` | 2.9 ± 1.3 | 1.2 | 15.3 | 1.00 |
| `mattcl-solver/aoc run 7 input-lanjian` | 3.9 ± 1.8 | 1.3 | 15.8 | 1.33 ± 0.87 |
| `mattcl-solver/aoc run 7 input-mattcl` | 3.6 ± 1.4 | 1.2 | 10.6 | 1.22 ± 0.74 |
| `mattcl-solver/aoc run 7 input-pting` | 3.9 ± 1.7 | 1.6 | 21.9 | 1.34 ± 0.83 |
| `python pting/day07.py input-lanjian` | 65.6 ± 10.2 | 49.6 | 97.4 | 22.39 ± 10.69 |
| `python pting/day07.py input-mattcl` | 66.9 ± 8.5 | 50.1 | 90.8 | 22.84 ± 10.71 |
| `python pting/day07.py input-pting` | 60.1 ± 10.0 | 46.5 | 103.5 | 20.51 ± 9.87 |

## input -> solutions mapping
|input|part 1|part 2|
|:---|:---|:---|
|input-lanjian|<pre>1391690</pre>|<pre>5469168</pre>|
|input-mattcl|<pre>1792222</pre>|<pre>1112963</pre>|
|input-pting|<pre>1555642</pre>|<pre>5974547</pre>|
