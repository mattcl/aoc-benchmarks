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
| `lanjian/day_07 input-lanjian` | 2.5 ± 1.3 | 0.9 | 20.5 | 1.16 ± 0.76 |
| `lanjian/day_07 input-mattcl` | 3.0 ± 1.2 | 1.0 | 14.0 | 1.37 ± 0.77 |
| `lanjian/day_07 input-pting` | 2.5 ± 1.0 | 0.9 | 7.4 | 1.16 ± 0.63 |
| `mattcl-solver/aoc run 7 input-lanjian` | 2.4 ± 1.1 | 0.8 | 7.3 | 1.11 ± 0.67 |
| `mattcl-solver/aoc run 7 input-mattcl` | 2.2 ± 0.8 | 0.8 | 5.9 | 1.00 |
| `mattcl-solver/aoc run 7 input-pting` | 2.6 ± 1.3 | 0.6 | 26.1 | 1.21 ± 0.78 |
| `python pting/day07.py input-lanjian` | 52.5 ± 7.0 | 43.0 | 80.1 | 24.36 ± 9.98 |
| `python pting/day07.py input-mattcl` | 53.0 ± 7.7 | 43.7 | 78.5 | 24.56 ± 10.17 |
| `python pting/day07.py input-pting` | 49.6 ± 6.4 | 40.3 | 68.8 | 22.98 ± 9.38 |

## input -> solutions mapping
|input|part 1|part 2|
|:---|:---|:---|
|input-lanjian|<pre>1391690</pre>|<pre>5469168</pre>|
|input-mattcl|<pre>1792222</pre>|<pre>1112963</pre>|
|input-pting|<pre>1555642</pre>|<pre>5974547</pre>|
