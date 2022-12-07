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
| `lanjian/day_07 input-lanjian` | 2.9 ± 1.7 | 0.4 | 16.4 | 1.00 |
| `lanjian/day_07 input-mattcl` | 3.0 ± 1.7 | 0.9 | 15.2 | 1.04 ± 0.85 |
| `lanjian/day_07 input-pting` | 2.9 ± 1.3 | 0.7 | 10.8 | 1.00 ± 0.75 |
| `mattcl-solver/aoc run 7 input-lanjian` | 3.2 ± 1.8 | 0.3 | 14.8 | 1.11 ± 0.91 |
| `mattcl-solver/aoc run 7 input-mattcl` | 3.4 ± 2.1 | 0.6 | 18.6 | 1.19 ± 1.01 |
| `mattcl-solver/aoc run 7 input-pting` | 3.2 ± 2.0 | 0.4 | 18.6 | 1.12 ± 0.95 |
| `python pting/day07.py input-lanjian` | 64.0 ± 8.3 | 49.4 | 81.4 | 22.13 ± 13.36 |
| `python pting/day07.py input-mattcl` | 68.2 ± 13.4 | 49.3 | 104.1 | 23.60 ± 14.66 |
| `python pting/day07.py input-pting` | 108.5 ± 56.4 | 52.6 | 293.9 | 37.55 ± 29.51 |

## input -> solutions mapping
|input|part 1|part 2|
|:---|:---|:---|
|input-lanjian|<pre>1391690</pre>|<pre>5469168</pre>|
|input-mattcl|<pre>1792222</pre>|<pre>1112963</pre>|
|input-pting|<pre>1555642</pre>|<pre>5974547</pre>|
