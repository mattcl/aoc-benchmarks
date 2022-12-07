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
| `lanjian/day_07 input-lanjian` | 3.9 ± 2.0 | 1.2 | 22.4 | 1.28 ± 0.83 |
| `lanjian/day_07 input-mattcl` | 3.9 ± 1.6 | 1.3 | 13.2 | 1.29 ± 0.72 |
| `lanjian/day_07 input-pting` | 3.0 ± 1.2 | 1.3 | 11.3 | 1.00 |
| `mattcl-solver/aoc run 7 input-lanjian` | 3.8 ± 1.7 | 1.4 | 16.5 | 1.26 ± 0.73 |
| `mattcl-solver/aoc run 7 input-mattcl` | 3.3 ± 1.3 | 1.0 | 12.2 | 1.09 ± 0.60 |
| `mattcl-solver/aoc run 7 input-pting` | 3.6 ± 1.6 | 1.5 | 18.1 | 1.17 ± 0.69 |
| `python pting/day07.py input-lanjian` | 61.6 ± 8.7 | 46.8 | 86.3 | 20.22 ± 8.33 |
| `python pting/day07.py input-mattcl` | 61.7 ± 7.9 | 50.2 | 82.1 | 20.28 ± 8.27 |
| `python pting/day07.py input-pting` | 61.0 ± 7.7 | 51.4 | 79.7 | 20.02 ± 8.15 |

## input -> solutions mapping
|input|part 1|part 2|
|:---|:---|:---|
|input-lanjian|<pre>1391690</pre>|<pre>5469168</pre>|
|input-mattcl|<pre>1792222</pre>|<pre>1112963</pre>|
|input-pting|<pre>1555642</pre>|<pre>5974547</pre>|
