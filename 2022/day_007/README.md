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
| `lanjian/day_07 input-lanjian` | 2.2 ± 1.2 | 0.9 | 13.8 | 1.27 ± 0.93 |
| `lanjian/day_07 input-mattcl` | 2.3 ± 0.9 | 0.9 | 6.8 | 1.28 ± 0.85 |
| `lanjian/day_07 input-pting` | 2.1 ± 0.9 | 0.8 | 7.9 | 1.20 ± 0.79 |
| `mattcl-solver/aoc run 7 input-lanjian` | 2.5 ± 1.0 | 0.9 | 10.0 | 1.40 ± 0.91 |
| `mattcl-solver/aoc run 7 input-mattcl` | 2.1 ± 0.9 | 0.8 | 9.9 | 1.19 ± 0.81 |
| `mattcl-solver/aoc run 7 input-pting` | 1.8 ± 0.9 | 0.6 | 11.8 | 1.00 |
| `python pting/day07.py input-lanjian` | 44.1 ± 4.8 | 37.1 | 56.9 | 24.89 ± 13.22 |
| `python pting/day07.py input-mattcl` | 42.0 ± 3.9 | 36.7 | 57.6 | 23.71 ± 12.52 |
| `python pting/day07.py input-pting` | 68.0 ± 48.0 | 36.7 | 276.2 | 38.33 ± 33.62 |

## input -> solutions mapping
|input|part 1|part 2|
|:---|:---|:---|
|input-lanjian|<pre>1391690</pre>|<pre>5469168</pre>|
|input-mattcl|<pre>1792222</pre>|<pre>1112963</pre>|
|input-pting|<pre>1555642</pre>|<pre>5974547</pre>|
