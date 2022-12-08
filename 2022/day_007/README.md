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
| `lanjian/day_07 input-lanjian` | 2.9 ± 1.9 | 0.5 | 16.7 | 1.03 ± 0.82 |
| `lanjian/day_07 input-mattcl` | 3.0 ± 1.7 | 0.6 | 27.5 | 1.04 ± 0.77 |
| `lanjian/day_07 input-pting` | 2.9 ± 1.8 | 0.4 | 27.6 | 1.03 ± 0.80 |
| `mattcl-solver/aoc run 7 input-lanjian` | 3.1 ± 1.1 | 0.9 | 9.0 | 1.10 ± 0.64 |
| `mattcl-solver/aoc run 7 input-mattcl` | 3.0 ± 1.2 | 0.7 | 9.4 | 1.07 ± 0.65 |
| `mattcl-solver/aoc run 7 input-pting` | 2.8 ± 1.3 | 0.4 | 12.4 | 1.00 |
| `python pting/day07.py input-lanjian` | 52.6 ± 10.3 | 39.3 | 82.3 | 18.50 ± 9.10 |
| `python pting/day07.py input-mattcl` | 55.6 ± 8.4 | 42.1 | 71.8 | 19.54 ± 9.30 |
| `python pting/day07.py input-pting` | 61.5 ± 9.2 | 46.6 | 79.7 | 21.63 ± 10.28 |

## input -> solutions mapping
|input|part 1|part 2|
|:---|:---|:---|
|input-lanjian|<pre>1391690</pre>|<pre>5469168</pre>|
|input-mattcl|<pre>1792222</pre>|<pre>1112963</pre>|
|input-pting|<pre>1555642</pre>|<pre>5974547</pre>|
