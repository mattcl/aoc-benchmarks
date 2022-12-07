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
| `lanjian/day_07 input-lanjian` | 4.5 ± 2.1 | 1.4 | 19.6 | 1.29 ± 0.84 |
| `lanjian/day_07 input-mattcl` | 4.5 ± 2.3 | 1.4 | 20.4 | 1.30 ± 0.90 |
| `lanjian/day_07 input-pting` | 4.8 ± 2.5 | 1.3 | 14.9 | 1.36 ± 0.95 |
| `mattcl-solver/aoc run 7 input-lanjian` | 3.5 ± 1.8 | 0.7 | 20.5 | 1.01 ± 0.69 |
| `mattcl-solver/aoc run 7 input-mattcl` | 3.5 ± 1.6 | 1.0 | 19.1 | 1.00 |
| `mattcl-solver/aoc run 7 input-pting` | 9.9 ± 9.4 | 1.8 | 70.2 | 2.83 ± 2.98 |
| `python pting/day07.py input-lanjian` | 68.8 ± 14.5 | 47.6 | 96.2 | 19.68 ± 9.99 |
| `python pting/day07.py input-mattcl` | 69.5 ± 12.6 | 46.9 | 102.0 | 19.87 ± 9.86 |
| `python pting/day07.py input-pting` | 69.9 ± 12.1 | 51.4 | 97.9 | 20.00 ± 9.86 |

## input -> solutions mapping
|input|part 1|part 2|
|:---|:---|:---|
|input-lanjian|<pre>1391690</pre>|<pre>5469168</pre>|
|input-mattcl|<pre>1792222</pre>|<pre>1112963</pre>|
|input-pting|<pre>1555642</pre>|<pre>5974547</pre>|
