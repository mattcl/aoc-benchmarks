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
| `lanjian/day_07 input-lanjian` | 2.5 ± 0.9 | 0.8 | 6.1 | 1.06 ± 0.60 |
| `lanjian/day_07 input-mattcl` | 2.4 ± 1.1 | 0.8 | 12.0 | 1.00 |
| `lanjian/day_07 input-pting` | 2.6 ± 1.4 | 0.6 | 12.4 | 1.09 ± 0.76 |
| `mattcl-solver/aoc run 7 input-lanjian` | 2.6 ± 1.4 | 0.7 | 13.0 | 1.09 ± 0.74 |
| `mattcl-solver/aoc run 7 input-mattcl` | 3.1 ± 1.5 | 0.5 | 14.0 | 1.30 ± 0.85 |
| `mattcl-solver/aoc run 7 input-pting` | 2.6 ± 1.1 | 0.9 | 10.2 | 1.08 ± 0.66 |
| `python pting/day07.py input-lanjian` | 56.2 ± 8.0 | 45.8 | 89.3 | 23.40 ± 10.96 |
| `python pting/day07.py input-mattcl` | 52.9 ± 6.9 | 40.1 | 69.4 | 22.03 ± 10.24 |
| `python pting/day07.py input-pting` | 60.2 ± 8.4 | 43.5 | 84.1 | 25.09 ± 11.73 |

## input -> solutions mapping
|input|part 1|part 2|
|:---|:---|:---|
|input-lanjian|<pre>1391690</pre>|<pre>5469168</pre>|
|input-mattcl|<pre>1792222</pre>|<pre>1112963</pre>|
|input-pting|<pre>1555642</pre>|<pre>5974547</pre>|
